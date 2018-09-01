{
  "info": {
    "name": "Reddit Get Subreddit Sticky",
    "_postman_id": "5948d283-c5f0-4848-993a-d6c6fcf59f09",
    "description": "Redirect to one of the posts stickied in the current subreddit",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Best",
      "item": [
        {
          "id": "c1b6ab7f-22d7-4492-bd04-2294888b1d7a",
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
              "id": "58f9ad9f-4055-4622-b27f-757c796d75d9"
            }
          ]
        }
      ]
    },
    {
      "name": "Names",
      "item": [
        {
          "id": "115c54ee-b401-4373-9a8c-bd5bdd445a78",
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
              "id": "39a1ef46-439c-4f97-9ce8-f357021fec38"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddit",
      "item": [
        {
          "id": "bc542906-ce16-4a1d-9f2d-70516969788e",
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
              "id": "6c7b968b-7f7b-4e13-8784-c7f83d04878a"
            }
          ]
        },
        {
          "id": "3af54558-bd79-478a-b9bd-6e6ba1cbc6a2",
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
              "id": "fb2429df-a6d6-4567-bf44-0e9b26164091"
            }
          ]
        },
        {
          "id": "109b91f4-ea8f-4297-bdaf-da7818e43ee9",
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
              "id": "a1cef521-fcfa-4928-a948-d4b6f229187f"
            }
          ]
        },
        {
          "id": "aa7c2dbb-83fe-47d4-978a-08859f2094d6",
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
              "id": "2845cc01-9abe-40a6-95e1-532ede16c2ed"
            }
          ]
        },
        {
          "id": "f6df84fe-8bab-45a7-a70b-b2efcf34f61d",
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
              "id": "7220c2a3-a909-4a29-b86d-39eed265ea6d"
            }
          ]
        },
        {
          "id": "371ef4aa-7724-4516-88c8-79bd5c2a648a",
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
              "id": "be5a9c57-9a1f-4890-99c3-da29574b7422"
            }
          ]
        },
        {
          "id": "33fdbcfc-1f52-469e-b030-05f4012b34b6",
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
              "id": "bb98cc8f-e1e6-4271-ba3c-1de6ec100f41"
            }
          ]
        },
        {
          "id": "857dab03-bf89-4fbc-aade-31f97ccd4c82",
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
              "id": "582a8e9b-4b52-4d19-bf1e-d0809e5d1bff"
            }
          ]
        },
        {
          "id": "6f140526-b4e8-499a-9e92-2f5a60ce2d5e",
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
              "id": "9d447077-6ea4-4f7a-babd-f6315dc7e630"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "5479487d-4ff5-4ebc-88b1-bf9656df8f53",
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
              "id": "624c23d6-f147-495c-9422-2df665e67a4d"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddits",
      "item": [
        {
          "id": "0e7758ae-a7cf-44c8-a921-f6153fdb8a2c",
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
              "id": "41b9c4e9-2d19-4e0a-b667-113eb8e16d18"
            }
          ]
        }
      ]
    }
  ]
}