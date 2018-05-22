{
  "info": {
    "name": "Reddit Add Subreddit Subreddit Stylesheet",
    "_postman_id": "4274a16e-4446-4076-819c-adccb4c7e112",
    "description": "Update a subreddit&#39;s stylesheet.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Best",
      "item": [
        {
          "id": "cbaa66ef-5666-41ec-9120-67e8b5176f0c",
          "name": "get&nbsp;Best",
          "request": {
            "url": "http://www.reddit.com/best.json?after=after&before=before&count=count&limit=limit&show=show&sr_detail=sr_detail",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint is a listing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f33a8dd-28dd-4f8e-8b6d-bdbfa5c8c7da"
            }
          ]
        }
      ]
    },
    {
      "name": "Names",
      "item": [
        {
          "id": "3cf91e3f-47eb-4f5b-8f3f-0e0630d7266a",
          "name": "get&nbsp;ByNames",
          "request": {
            "url": "http://www.reddit.com/by_id/names?names=names",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a listing of links by fullname."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b06dcbe4-6940-469d-bc7b-76a2d502518f"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddit",
      "item": [
        {
          "id": "d47d262c-72c8-4bc1-b385-c9f9dedafd83",
          "name": "get&nbsp;RSubredditHot",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.reddit.com",
              "path": [
                ":/r/subreddit/hot.json"
              ],
              "query": [
                {
                  "key": "after",
                  "value": "after",
                  "disabled": false
                },
                {
                  "key": "before",
                  "value": "before",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "count",
                  "disabled": false
                },
                {
                  "key": "g",
                  "value": "g",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "show",
                  "value": "show",
                  "disabled": false
                },
                {
                  "key": "sr_detail",
                  "value": "sr_detail",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "/r/subreddit",
                  "value": "/r/subreddit",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint is a listing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8ff492c-2eed-433d-9dcd-e0d5633352b7"
            }
          ]
        },
        {
          "id": "edfca8f1-d094-4217-8522-97deb1ed42b6",
          "name": "get&nbsp;RSubredditNew",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.reddit.com",
              "path": [
                ":/r/subreddit/new.json"
              ],
              "query": [
                {
                  "key": "after",
                  "value": "after",
                  "disabled": false
                },
                {
                  "key": "before",
                  "value": "before",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "count",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "show",
                  "value": "show",
                  "disabled": false
                },
                {
                  "key": "sr_detail",
                  "value": "sr_detail",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "/r/subreddit",
                  "value": "/r/subreddit",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint is a listing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "605e9b15-81a3-4fb3-a155-9583ac05e461"
            }
          ]
        },
        {
          "id": "a515796b-420c-4fdf-b3f0-b874ab17e23d",
          "name": "get&nbsp;RSubredditRandom",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.reddit.com",
              "path": [
                ":/r/subreddit/random.json"
              ],
              "variable": [
                {
                  "id": "/r/subreddit",
                  "value": "/r/subreddit",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The Serendipity button"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03492d93-d6af-4668-b5f6-202adf980482"
            }
          ]
        },
        {
          "id": "e015ee7a-6fee-451a-b44f-24aee2e18899",
          "name": "get&nbsp;RSubredditRising",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.reddit.com",
              "path": [
                ":/r/subreddit/rising.json"
              ],
              "query": [
                {
                  "key": "after",
                  "value": "after",
                  "disabled": false
                },
                {
                  "key": "before",
                  "value": "before",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "count",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "show",
                  "value": "show",
                  "disabled": false
                },
                {
                  "key": "sr_detail",
                  "value": "sr_detail",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "/r/subreddit",
                  "value": "/r/subreddit",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint is a listing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea5e5064-2d1f-45b4-82c9-f466baa209c9"
            }
          ]
        },
        {
          "id": "984543aa-827a-41b2-94de-359f160e83aa",
          "name": "get&nbsp;RSubredditSort",
          "request": {
            "url": "http://www.reddit.com/{/r/subreddit}/sort?after=after&before=before&count=count&limit=limit&show=show&sr_detail=sr_detail&t=t",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint is a listing."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c26c0597-3783-4ebc-90a1-9ec712634603"
            }
          ]
        },
        {
          "id": "5b5626c1-b89e-4eab-befd-52317d9f0623",
          "name": "get&nbsp;RSubredditStylesheet",
          "request": {
            "url": "http://www.reddit.com/{/r/subreddit}/stylesheet",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Redirect to the subreddit&#39;s stylesheet if one exists."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fdfdcfa8-bbbe-4c22-bb20-63875e1e2a83"
            }
          ]
        },
        {
          "id": "24b39d74-fe3e-419e-8fa7-92d61e11bfcd",
          "name": "get&nbsp;RSubredditSubmitText",
          "request": {
            "url": "http://www.reddit.com/{/r/subreddit}/submit_text",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the submission text for the subreddit."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4abf195e-16a7-413e-8d52-c2e6c626c75f"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "29cc3ac6-f3b4-4335-894e-794b428fddf8",
          "name": "get&nbsp;SearchRedditNames",
          "request": {
            "url": "http://www.reddit.com/api/search_reddit_names.json?exact=exact&include_over_18=include_over_18&include_unadvertisable=include_unadvertisable&query=query",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List subreddit names that begin with a query string."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca797d45-dd44-4a7d-97b0-a09e5805fa55"
            }
          ]
        }
      ]
    }
  ]
}