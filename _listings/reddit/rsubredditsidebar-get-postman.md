{
  "info": {
    "name": "Reddit Get Subreddit Sebar",
    "_postman_id": "61fc1699-a558-43ed-bb71-b8fda33fc8ae",
    "description": "Get the sidebar for the current subreddit",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Best",
      "item": [
        {
          "id": "17a77cd1-2f2a-41a7-a819-7a9a2f1ae2c1",
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
              "id": "b2f3c691-87a6-4d11-9c2f-3ff52c3a3c36"
            }
          ]
        }
      ]
    },
    {
      "name": "Names",
      "item": [
        {
          "id": "8d673cf7-2161-4216-9fa4-69c1bf3962cd",
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
              "id": "2bd54e56-dc1b-4c41-b905-9334d73ed563"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddit",
      "item": [
        {
          "id": "6ca9ad25-bf5f-432e-88d0-76a76d4ecee0",
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
              "id": "565b94b9-145c-481d-99c4-15b22732502f"
            }
          ]
        },
        {
          "id": "0f8e7dcf-523b-4b8e-af3c-d620549e20e5",
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
              "id": "13290a71-f7d2-4096-b20c-a7c71d8f2ffb"
            }
          ]
        },
        {
          "id": "75188d16-44d6-4adc-ae04-57e7b99fb7a2",
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
              "id": "e0fa0d97-53f0-4ecb-8751-1c71e02e3a3b"
            }
          ]
        },
        {
          "id": "a9c21efe-a35b-43fa-b27e-853f7c08f8f4",
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
              "id": "5aa63258-8d76-4199-93c0-3ccd723dec05"
            }
          ]
        },
        {
          "id": "4eade66a-8121-47e5-8254-3d547f1e1293",
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
              "id": "f872f659-769a-4bbb-a728-0d59e57cf63c"
            }
          ]
        },
        {
          "id": "f247db77-5482-4baf-ad68-fb9d06519631",
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
              "id": "36bf2d57-5407-4e99-9767-f5f65919f482"
            }
          ]
        },
        {
          "id": "06aac597-574b-4d97-877b-3096ba10f7b8",
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
              "id": "fb5bd738-ba8a-4c04-8188-583a60f6a2b2"
            }
          ]
        },
        {
          "id": "3feca5e2-4373-4ed8-896a-7e59f3eb67a6",
          "name": "get&nbsp;RSubredditSebar",
          "request": {
            "url": "http://www.reddit.com/{/r/subreddit}/sidebar",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the sidebar for the current subreddit"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2037f176-fded-45d4-9bc2-780ae2a9a012"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "99631054-eca5-4a6f-98cd-333b72054069",
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
              "id": "2a5f45a6-c339-4611-922a-75fcebd27536"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddits",
      "item": [
        {
          "id": "5d7878c4-f2fb-489c-afd9-c624428ce122",
          "name": "getNewSubreddit",
          "request": {
            "url": "http://www.reddit.com/subreddits/new.json?query=query",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns new subreddits."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dea86dc2-f75b-40c4-9e69-6da016da2981"
            }
          ]
        }
      ]
    }
  ]
}