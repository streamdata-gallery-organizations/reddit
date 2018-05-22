{
  "info": {
    "name": "Reddit Add Subscribe",
    "_postman_id": "3d50a4d6-cb7d-4133-8338-7747d4db6764",
    "description": "Subscribe to or unsubscribe from a subreddit.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Best",
      "item": [
        {
          "id": "f89807ce-6f25-482e-a8d2-4e0b0275d00f",
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
              "id": "1c542ce9-c545-409d-b815-ac5604bfd005"
            }
          ]
        }
      ]
    },
    {
      "name": "Names",
      "item": [
        {
          "id": "9d839f39-45f9-4317-a438-dfe9d1f6ed22",
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
              "id": "eff0e974-3adb-42df-9395-a7770c0f7254"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddit",
      "item": [
        {
          "id": "75b75204-596d-4177-94b7-55f991624b06",
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
              "id": "3f436abc-1259-41cc-b944-d1c55ea7da82"
            }
          ]
        },
        {
          "id": "c0b13f57-b264-4992-9698-d77126c5773a",
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
              "id": "7607c543-b112-4b7e-99be-c75063ac4ef5"
            }
          ]
        },
        {
          "id": "4965aad0-1d80-41dc-a351-6463f4968f9c",
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
              "id": "6d51adad-c5cf-430a-bba8-239b5e5018e3"
            }
          ]
        },
        {
          "id": "e9ff043f-9a89-44be-acf2-a6a67dbc3931",
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
              "id": "9afddbd3-c2f9-47c9-8255-871326318242"
            }
          ]
        },
        {
          "id": "2f5dd9e2-61db-4fce-835b-bbb0d90b52da",
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
              "id": "3e97fc02-c3c7-49f3-bc20-ef4fc8c5a83e"
            }
          ]
        },
        {
          "id": "757172a9-29fa-42a0-ba10-7268a3bfd92b",
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
              "id": "eb9265f8-a5a3-4740-b952-1e1d9d5006a4"
            }
          ]
        },
        {
          "id": "276a5aed-41e7-4343-95e3-b9bef85403ab",
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
              "id": "d2ef3470-862c-438d-a494-ccdd4cebe703"
            }
          ]
        }
      ]
    },
    {
      "name": "Search",
      "item": [
        {
          "id": "d75bbd6d-b456-4cef-93a1-83a2c2846d67",
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
              "id": "7f8296f3-c133-426a-af72-76b7fe3c0ea2"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddits",
      "item": [
        {
          "id": "bdbb4277-f26a-47ad-906f-e1205ded1479",
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
              "id": "0f85c417-d31d-4b69-8472-948c37c1055f"
            }
          ]
        }
      ]
    }
  ]
}