---
swagger: "2.0"
info:
  title: Reddit
  description: The Reddit API allows you to access the user submitted and rated stories
    on reddit.com. It also provides advanced functionality, including user account
    information and sub-reddit moderation.
  version: 1.0.0
host: www.reddit.com
basePath: api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /distinguish:
    post:
      summary: Add Distinguish
      description: Distinguish a thing&#39;s author with a sigil
      operationId: post&nbsp;Distinguish
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: how
        description: one of (yes, no, admin, special)
        type: string
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: sticky
        description: boolean value
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - distinguish
definitions: []
x-collection-name: Reddit
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