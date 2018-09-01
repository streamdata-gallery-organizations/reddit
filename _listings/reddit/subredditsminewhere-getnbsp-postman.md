{
  "info": {
    "name": "Reddit Get Subreddits Mine Where",
    "_postman_id": "763c2b25-935e-4241-af33-225d3c8e330d",
    "description": "Get subreddits the user has a relationship with.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Best",
      "item": [
        {
          "id": "280d1257-5a3f-4394-94ec-9426658fa14a",
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
              "id": "3b5f75ef-2784-485c-b881-699caba2b924"
            }
          ]
        }
      ]
    },
    {
      "name": "Names",
      "item": [
        {
          "id": "bcaba476-95ae-4743-a849-12659390ae7a",
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
              "id": "db8af0fb-4849-4d7c-9f57-6a036705b12f"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddit",
      "item": [
        {
          "id": "0db5d79e-4e27-4840-968b-b5a3752d7c9b",
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
              "id": "0581747c-94c0-438c-8782-937b8933e18a"
            }
          ]
        },
        {
          "id": "a51e457a-47bf-4796-b92d-80f68fafa0a9",
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
              "id": "a1ffae43-1f51-4002-ad11-7f1b75b189be"
            }
          ]
        },
        {
          "id": "a70a39d2-09c9-4843-92f7-48ee15a0b874",
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
              "id": "f192d1eb-4ac9-4b63-8ec1-138d43717125"
            }
          ]
        },
        {
          "id": "0ebf1197-62d7-4b33-ae73-05b9457959e8",
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
              "id": "8ac4edc0-3c73-49f5-8557-82c5319df0c2"
            }
          ]
        },
        {
          "id": "dc716afa-7a44-45f1-af3a-fcc1bd49ddc4",
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
              "id": "f5b4a459-f65a-4289-939b-10ea8369c6d9"
            }
          ]
        },
        {
          "id": "828830c9-756d-402f-b8af-67f0b246c1dc",
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
              "id": "172faa5e-8127-44a4-934a-61cbee7d8bd3"
            }
          ]
        },
        {
          "id": "b4d7c870-5a76-4a6e-ac01-b306187b8336",
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
              "id": "abf5c6bd-462a-4138-9e15-0b10b0569fd6"
            }
          ]
        },
        {
          "id": "253ff6d6-8b3e-46c8-aa6d-337f734f3e80",
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
              "id": "b6a71677-c61b-429a-bd2f-2f8c13385ac4"
            }
          ]
        },
        {
          "id": "9a0fb75b-978d-4825-a700-d8c4642ecb63",
          "name": "get&nbsp;RSubredditSticky",
          "request": {
            "url": "http://www.reddit.com/{/r/subreddit}/sticky?num=num",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Redirect to one of the posts stickied in the current subreddit"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66594f24-e0dd-4254-931f-5bee5a43351c"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "e754e256-8817-4ceb-8e8c-e764db3c17dd",
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
              "id": "329cf7c8-9cc8-4281-9b6f-316843921d91"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddits",
      "item": [
        {
          "id": "a0972d40-5158-47a0-a435-519fbb65d1b7",
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
              "id": "e92d29c2-f3c7-486f-b4a5-998627705a26"
            }
          ]
        }
      ]
    }
  ]
}