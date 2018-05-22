{
  "info": {
    "name": "Reddit Add Subreddit Delete Sr Banner",
    "_postman_id": "8b51d6bb-235e-4138-96e8-cf28e5e6bae0",
    "description": "Remove the subreddit&#39;s custom mobile banner.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Best",
      "item": [
        {
          "id": "ee9aa1b2-ca1a-4977-8eaf-bac691d64bea",
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
              "id": "c9f6e5ad-a34d-423e-b706-e55ff9c6db01"
            }
          ]
        }
      ]
    },
    {
      "name": "Names",
      "item": [
        {
          "id": "d7003d0f-b367-4f5f-ab44-fc40f10ac62c",
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
              "id": "3a203e45-3301-4124-bc6d-31100f6545d8"
            }
          ]
        }
      ]
    },
    {
      "name": "Subreddit",
      "item": [
        {
          "id": "000ceea3-3c5a-4668-be7e-2a852bab99a2",
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
              "id": "757644d4-6749-4397-8f25-67ae1a9716c9"
            }
          ]
        },
        {
          "id": "5af9ed60-11a1-4ff6-939f-884f6eb70d1e",
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
              "id": "ffe74c49-a74f-40f8-bcdf-136da88d399f"
            }
          ]
        },
        {
          "id": "fd0aca02-d60f-4fd5-a937-b4c277d6e8b0",
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
              "id": "aba070c2-f6ea-49ac-a9fe-8f0df42773f1"
            }
          ]
        },
        {
          "id": "df361e50-611b-4e21-b58b-eea5ffe04a2d",
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
              "id": "d102cc02-cadc-42c0-bc5e-76f8197a9962"
            }
          ]
        },
        {
          "id": "b84958d7-0714-4f65-ad0a-359ae139714c",
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
              "id": "505d0bc5-f68c-43f3-be43-e4a354b3e5a1"
            }
          ]
        },
        {
          "id": "e50385af-4b99-4871-92c4-651035068780",
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
              "id": "d0331857-60a0-4514-ae27-8ce12513b159"
            }
          ]
        }
      ]
    }
  ]
}