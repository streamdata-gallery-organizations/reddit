---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Get Me Karma
  description: Return a breakdown of subreddit karma.
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/me:
    get&nbsp;:
      summary: Get Me
      description: Returns the identity of the user currently authenticated via OAuth.
      operationId: get&nbsp;V1Me
      x-api-path-slug: v1me-getnbsp
      responses:
        200:
          description: OK
      tags:
      - Me
  /v1/me/karma:
    get&nbsp;:
      summary: Get Me Karma
      description: Return a breakdown of subreddit karma.
      operationId: get&nbsp;V1MeKarma
      x-api-path-slug: v1mekarma-getnbsp
      responses:
        200:
          description: OK
      tags:
      - Me
      - Karma
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---