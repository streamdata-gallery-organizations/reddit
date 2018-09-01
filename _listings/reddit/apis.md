---
name: Reddit
x-slug: reddit
description: Reddit is a community of millions of users engaging in the creation of
  content and the sharing of conversation across tens of thousands of topics.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
x-kinRank: "9"
x-alexaRank: "6"
tags: Reddit
created: "2018-08-31"
modified: "2018-08-31"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/apis.md
specificationVersion: "0.14"
apis:
- name: Reddit - Get Me
  x-api-slug: v1me-getnbsp
  description: Returns the identity of the user currently authenticated via OAuth.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1me-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1me-getnbsp-openapi.md
- name: Reddit - Get Me Karma
  x-api-slug: v1mekarma-getnbsp
  description: Return a breakdown of subreddit karma.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1mekarma-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1mekarma-getnbsp-openapi.md
- name: Reddit - Get Me Prefs
  x-api-slug: v1meprefs-getnbsp
  description: Return the preference settings of the logged in user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1meprefs-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1meprefs-getnbsp-openapi.md
- name: Reddit - Patch Me Prefs
  x-api-slug: v1meprefs-patchnbsp
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1meprefs-patchnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1meprefs-patchnbsp-openapi.md
- name: Reddit - Get Me Trophies
  x-api-slug: v1metrophies-getnbsp
  description: Return a list of trophies for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1metrophies-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1metrophies-getnbsp-openapi.md
- name: Reddit - Get Prefs Where
  x-api-slug: prefswhere-getnbsp
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/prefswhere-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/prefswhere-getnbsp-openapi.md
- name: Reddit - Add Subreddit Emoji.json
  x-api-slug: v1subredditemoji-json-postnbsp
  description: |-
    Add an emoji to the DB by posting a message on emoji_upload_q.
    A job processor that listens on a queue, uses the s3_key provided
    in the request to locate the image in S3 Temp Bucket and moves it
    to the PERM bucket. It also adds it to the DB using name as the column
    and sr_fullname as the key and sends the status on the websocket URL
    that is provided as part of this response.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1subredditemoji-json-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1subredditemoji-json-postnbsp-openapi.md
- name: Reddit - Delete Subreddit Emoji Emoji Name
  x-api-slug: v1subredditemojiemoji-name-deletenbsp
  description: |-
    Delete a Subreddit emoji.
    Remove the emoji from Cassandra and purge the assets from S3
    and the image resizing provider.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1subredditemojiemoji-name-deletenbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1subredditemojiemoji-name-deletenbsp-openapi.md
- name: Reddit - Add Subreddit Emoji Asset Upload S3.json
  x-api-slug: v1subredditemoji-asset-upload-s3-json-postnbsp
  description: |-
    Acquire and return an upload lease to s3 temp bucket. The return value
    of this function is a json object containing credentials for uploading
    assets to S3 bucket, S3 url for upload request and the key to use for
    uploading. Using this lease the client will upload the emoji image to
    S3 temp bucket (included as part of the S3 URL).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1subredditemoji-asset-upload-s3-json-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1subredditemoji-asset-upload-s3-json-postnbsp-openapi.md
- name: Reddit - Get Subreddit Emojis All
  x-api-slug: v1subredditemojisall-getnbsp
  description: |-
    Get all emojis for a SR. The response inclueds reddit emojis
    as well as emojis for the SR specified in the request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1subredditemojisall-getnbsp-openapi.md
- name: Reddit - Add Gold Gild Fullname
  x-api-slug: v1goldgildfullname-postnbsp
  description: fullname of a thing
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1goldgildfullname-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1goldgildfullname-postnbsp-openapi.md
- name: Reddit - Add Gold Give Username
  x-api-slug: v1goldgiveusername-postnbsp
  description: an integer between 1 and 36
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1goldgiveusername-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/v1goldgiveusername-postnbsp-openapi.md
- name: Reddit - Get Best
  x-api-slug: best-json-get
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/best-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/best-json-get-openapi.md
- name: Reddit - Get By Names
  x-api-slug: by-idnames-get
  description: Get a listing of links by fullname.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/by-idnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/by-idnames-get-openapi.md
- name: Reddit - Get Subreddit Comments Article
  x-api-slug: rsubredditcommentsarticle-getnbsp
  description: Get the comment tree for a given Link article.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditcommentsarticle-getnbsp-openapi.md
- name: Reddit - Get Duplicates Article
  x-api-slug: duplicatesarticle-getnbsp
  description: Return a list of other submissions of the same URL
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/duplicatesarticle-getnbsp-openapi.md
- name: Reddit - Get Subreddit Hot
  x-api-slug: rsubreddithot-json-get
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubreddithot-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubreddithot-json-get-openapi.md
- name: Reddit - Get Subreddit New
  x-api-slug: rsubredditnew-json-get
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditnew-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditnew-json-get-openapi.md
- name: Reddit - Get Subreddit Random
  x-api-slug: rsubredditrandom-json-get
  description: The Serendipity button
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditrandom-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditrandom-json-get-openapi.md
- name: Reddit - Get Subreddit Rising
  x-api-slug: rsubredditrising-json-get
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditrising-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditrising-json-get-openapi.md
- name: Reddit - Get Subreddit Sort
  x-api-slug: rsubredditsort-get
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsort-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsort-get-openapi.md
- name: Reddit - Add Block
  x-api-slug: block-postnbsp
  description: For blocking the author of a thing via inbox.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/block-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/block-postnbsp-openapi.md
- name: Reddit - Add Collapse Message
  x-api-slug: collapse-message-postnbsp
  description: Collapse a message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/collapse-message-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/collapse-message-postnbsp-openapi.md
- name: Reddit - Add Compose
  x-api-slug: compose-postnbsp
  description: Handles message composition under /message/compose.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/compose-postnbsp-openapi.md
- name: Reddit - Add Del Msg
  x-api-slug: del-msg-postnbsp
  description: Delete messages from the recipient&#39;s view of their inbox.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/del-msg-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/del-msg-postnbsp-openapi.md
- name: Reddit - Add Read All Messages
  x-api-slug: read-all-messages-postnbsp
  description: Queue up marking all messages for a user as read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/read-all-messages-postnbsp-openapi.md
- name: Reddit - Add Read Message
  x-api-slug: read-message-postnbsp
  description: A comma-separated list of thing fullnames
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/read-message-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/read-message-postnbsp-openapi.md
- name: Reddit - Add Unblock Subreddit
  x-api-slug: unblock-subreddit-postnbsp
  description: fullname of a thing
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/unblock-subreddit-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/unblock-subreddit-postnbsp-openapi.md
- name: Reddit - Add Uncollapse Message
  x-api-slug: uncollapse-message-postnbsp
  description: Uncollapse a message
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/uncollapse-message-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/uncollapse-message-postnbsp-openapi.md
- name: Reddit - Add Unread Message
  x-api-slug: unread-message-postnbsp
  description: A comma-separated list of thing fullnames
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/unread-message-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/unread-message-postnbsp-openapi.md
- name: Reddit - Get Message Where
  x-api-slug: messagewhere-getnbsp
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/messagewhere-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/messagewhere-getnbsp-openapi.md
- name: Reddit - Get Subreddit About Log
  x-api-slug: rsubredditaboutlog-getnbsp
  description: Get a list of recent moderation actions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutlog-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutlog-getnbsp-openapi.md
- name: Reddit - Get Subreddit About Location
  x-api-slug: rsubredditaboutlocation-getnbsp
  description: Return a listing of posts relevant to moderators.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutlocation-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutlocation-getnbsp-openapi.md
- name: Reddit - Add Subreddit Accept Moderator Invite
  x-api-slug: rsubredditaccept-moderator-invite-postnbsp
  description: Accept an invite to moderate the specified subreddit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaccept-moderator-invite-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaccept-moderator-invite-postnbsp-openapi.md
- name: Reddit - Add Approve
  x-api-slug: approve-postnbsp
  description: Approve a link or comment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/approve-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/approve-postnbsp-openapi.md
- name: Reddit - Add Distinguish
  x-api-slug: distinguish-postnbsp
  description: Distinguish a thing&#39;s author with a sigil.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/distinguish-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/distinguish-postnbsp-openapi.md
- name: Reddit - Add Ignore Reports
  x-api-slug: ignore-reports-postnbsp
  description: Prevent future reports on a thing from causing notifications.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/ignore-reports-postnbsp-openapi.md
- name: Reddit - Add Leavecontributor
  x-api-slug: leavecontributor-postnbsp
  description: Abdicate approved submitter status in a subreddit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/leavecontributor-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/leavecontributor-postnbsp-openapi.md
- name: Reddit - Add Leavemoderator
  x-api-slug: leavemoderator-postnbsp
  description: Abdicate moderator status in a subreddit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/leavemoderator-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/leavemoderator-postnbsp-openapi.md
- name: Reddit - Add Mute Message Author
  x-api-slug: mute-message-author-postnbsp
  description: For muting user via modmail.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/mute-message-author-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/mute-message-author-postnbsp-openapi.md
- name: Reddit - Add Remove
  x-api-slug: remove-postnbsp
  description: Remove a link, comment, or modmail message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/remove-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/remove-postnbsp-openapi.md
- name: Reddit - Add Unignore Reports
  x-api-slug: unignore-reports-postnbsp
  description: Allow future reports on a thing to cause notifications.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/unignore-reports-postnbsp-openapi.md
- name: Reddit - Add Unmute Message Author
  x-api-slug: unmute-message-author-postnbsp
  description: For unmuting user via modmail.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/unmute-message-author-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/unmute-message-author-postnbsp-openapi.md
- name: Reddit - Get Subreddit Stylesheet
  x-api-slug: rsubredditstylesheet-get
  description: Redirect to the subreddit&#39;s stylesheet if one exists.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditstylesheet-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditstylesheet-get-openapi.md
- name: Reddit - Add Multi Copy
  x-api-slug: multicopy-postnbsp
  description: Copy a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multicopy-postnbsp-openapi.md
- name: Reddit - Get Multi Mine
  x-api-slug: multimine-getnbsp
  description: Fetch a list of multis belonging to the current user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimine-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimine-getnbsp-openapi.md
- name: Reddit - Add Multi Rename
  x-api-slug: multirename-postnbsp
  description: Rename a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multirename-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multirename-postnbsp-openapi.md
- name: Reddit - Get Multi User Username
  x-api-slug: multiuserusername-getnbsp
  description: Fetch a list of public multis belonging to username
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multiuserusername-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multiuserusername-getnbsp-openapi.md
- name: Reddit - Delete Multi Multipath
  x-api-slug: multimultipath-deletenbsp
  description: Delete a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipath-deletenbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipath-deletenbsp-openapi.md
- name: Reddit - Get Multi Multipath
  x-api-slug: multimultipath-getnbsp
  description: Fetch a multi&#39;s data and subreddit list by name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipath-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipath-getnbsp-openapi.md
- name: Reddit - Add Multi Multipath
  x-api-slug: multimultipath-postnbsp
  description: Create a multi. Responds with 409 Conflict if it already exists.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipath-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipath-postnbsp-openapi.md
- name: Reddit - Put Multi Multipath
  x-api-slug: multimultipath-putnbsp
  description: Create or update a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipath-putnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipath-putnbsp-openapi.md
- name: Reddit - Get Multi Multipath Description
  x-api-slug: multimultipathdescription-getnbsp
  description: Get a multi&#39;s description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathdescription-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathdescription-getnbsp-openapi.md
- name: Reddit - Put Multi Multipath Description
  x-api-slug: multimultipathdescription-putnbsp
  description: Change a multi&#39;s markdown description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathdescription-putnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathdescription-putnbsp-openapi.md
- name: Reddit - Delete Multi Multipath Srname
  x-api-slug: multimultipathrsrname-deletenbsp
  description: Remove a subreddit from a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathrsrname-deletenbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathrsrname-deletenbsp-openapi.md
- name: Reddit - Get Multi Multipath Srname
  x-api-slug: multimultipathrsrname-getnbsp
  description: Get data about a subreddit in a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathrsrname-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathrsrname-getnbsp-openapi.md
- name: Reddit - Put Multi Multipath Srname
  x-api-slug: multimultipathrsrname-putnbsp
  description: Add a subreddit to a multi.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathrsrname-putnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/multimultipathrsrname-putnbsp-openapi.md
- name: Reddit - Get Subreddit About Where
  x-api-slug: rsubredditaboutwhere-getnbsp
  description: This endpoint is a listing.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutwhere-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutwhere-getnbsp-openapi.md
- name: Reddit - Add Subreddit Delete Sr Banner
  x-api-slug: rsubredditdelete-sr-banner-postnbsp
  description: Remove the subreddit&#39;s custom mobile banner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditdelete-sr-banner-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditdelete-sr-banner-postnbsp-openapi.md
- name: Reddit - Add Subreddit Delete Sr Header
  x-api-slug: rsubredditdelete-sr-header-postnbsp
  description: Remove the subreddit&#39;s custom header image.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditdelete-sr-header-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditdelete-sr-header-postnbsp-openapi.md
- name: Reddit - Add Subreddit Delete Sr Icon
  x-api-slug: rsubredditdelete-sr-icon-postnbsp
  description: Remove the subreddit&#39;s custom mobile icon.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditdelete-sr-icon-postnbsp-openapi.md
- name: Reddit - Add Subreddit Delete Sr Img
  x-api-slug: rsubredditdelete-sr-img-postnbsp
  description: Remove an image from the subreddit&#39;s custom image set.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditdelete-sr-img-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditdelete-sr-img-postnbsp-openapi.md
- name: Reddit - Get Recommend Sr Srnames
  x-api-slug: recommendsrsrnames-getnbsp
  description: Return subreddits recommended for the given subreddit(s).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/recommendsrsrnames-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/recommendsrsrnames-getnbsp-openapi.md
- name: Reddit - Get Search Reddit Names
  x-api-slug: apisearch-reddit-names-json-get
  description: List subreddit names that begin with a query string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/apisearch-reddit-names-json-get-openapi.md
- name: Reddit - Add Search Reddit Names
  x-api-slug: search-reddit-names-postnbsp
  description: List subreddit names that begin with a query string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/search-reddit-names-postnbsp-openapi.md
- name: Reddit - Add Search Subreddits
  x-api-slug: search-subreddits-postnbsp
  description: List subreddits that begin with a query string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/search-subreddits-postnbsp-openapi.md
- name: Reddit - Add Site Admin
  x-api-slug: site-admin-postnbsp
  description: Create or configure a subreddit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/site-admin-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/site-admin-postnbsp-openapi.md
- name: Reddit - Get Subreddit Submit Text
  x-api-slug: rsubredditsubmit-text-get
  description: Get the submission text for the subreddit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsubmit-text-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsubmit-text-get-openapi.md
- name: Reddit - Get Subreddit Autocomplete
  x-api-slug: subreddit-autocomplete-getnbsp
  description: |-
    Return a list of subreddits and data for subreddits whose names start
    with &#39;query&#39;.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subreddit-autocomplete-getnbsp-openapi.md
- name: Reddit - Get Subreddit Autocomplete V2
  x-api-slug: subreddit-autocomplete-v2-getnbsp
  description: boolean value
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subreddit-autocomplete-v2-getnbsp-openapi.md
- name: Reddit - Add Subreddit Subreddit Stylesheet
  x-api-slug: rsubredditsubreddit-stylesheet-postnbsp
  description: Update a subreddit&#39;s stylesheet.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsubreddit-stylesheet-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsubreddit-stylesheet-postnbsp-openapi.md
- name: Reddit - Get New Subreddits
  x-api-slug: subredditsnew-json-get
  description: Returns new subreddits.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subredditsnew-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subredditsnew-json-get-openapi.md
- name: Reddit - Add Subscribe
  x-api-slug: subscribe-postnbsp
  description: Subscribe to or unsubscribe from a subreddit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subscribe-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subscribe-postnbsp-openapi.md
- name: Reddit - Add Subreddit Upload Sr Img
  x-api-slug: rsubredditupload-sr-img-postnbsp
  description: |-
    Add or replace a subreddit image, custom header logo, custom mobile
    icon, or custom mobile banner.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditupload-sr-img-postnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditupload-sr-img-postnbsp-openapi.md
- name: Reddit - Get Subreddit About
  x-api-slug: rsubredditabout-getnbsp
  description: Return information about the subreddit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditabout-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditabout-getnbsp-openapi.md
- name: Reddit - Get Subreddit About Edit
  x-api-slug: rsubredditaboutedit-getnbsp
  description: Get the current settings of a subreddit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutedit-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutedit-getnbsp-openapi.md
- name: Reddit - Get Subreddit About Rules
  x-api-slug: rsubredditaboutrules-getnbsp
  description: Get the rules for the current subreddit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditaboutrules-getnbsp-openapi.md
- name: Reddit - Get Subreddit About Traffic
  x-api-slug: rsubredditabouttraffic-getnbsp
  description: Get the traffic for the current subreddit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditabouttraffic-getnbsp-openapi.md
- name: Reddit - Get Subreddit Sebar
  x-api-slug: rsubredditsidebar-get
  description: Get the sidebar for the current subreddit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsidebar-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsidebar-get-openapi.md
- name: Reddit - Get Subreddit Sticky
  x-api-slug: rsubredditsticky-get
  description: Redirect to one of the posts stickied in the current subreddit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsticky-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditsticky-get-openapi.md
- name: Reddit - Get Subreddits Mine Where
  x-api-slug: subredditsminewhere-getnbsp
  description: Get subreddits the user has a relationship with.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subredditsminewhere-getnbsp-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subredditsminewhere-getnbsp-openapi.md
- name: Reddit - Get Subreddits Search
  x-api-slug: subredditssearch-json-get
  description: Search subreddits by title and description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subredditssearch-json-get-openapi.md
- name: Reddit - Get Subreddits Where
  x-api-slug: subredditspopular-json-get
  description: Get all subreddits.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subredditspopular-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/subredditspopular-json-get-openapi.md
- name: Reddit - Get Users Where
  x-api-slug: userswhere-getnbsp
  description: Get all user subreddits.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/userswhere-getnbsp-openapi.md
- name: Reddit - Add Subreddit Wiki Alloweditor Act
  x-api-slug: rsubredditwikialloweditoract-postnbsp
  description: Allow/deny username to edit this wiki page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikialloweditoract-postnbsp-openapi.md
- name: Reddit - Subreddit Wiki Edit
  x-api-slug: rsubredditwikiedit-postnbsp
  description: Edit a wiki page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikiedit-postnbsp-openapi.md
- name: Reddit - Add Subreddit Wiki
  x-api-slug: rsubredditwikihide-postnbsp
  description: Toggle the public visibility of a wiki page revision
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikihide-postnbsp-openapi.md
- name: Reddit - Add Subreddit Wiki Revert
  x-api-slug: rsubredditwikirevert-postnbsp
  description: Revert a wiki page to revision
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikirevert-postnbsp-openapi.md
- name: Reddit - Get Subreddit Wiki Discussions Page
  x-api-slug: rsubredditwikidiscussionspage-getnbsp
  description: Retrieve a list of discussions about this wiki page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikidiscussionspage-getnbsp-openapi.md
- name: Reddit - Get Subreddit Wiki Pages
  x-api-slug: rsubredditwikipages-getnbsp
  description: Retrieve a list of wiki pages in this subreddit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikipages-getnbsp-openapi.md
- name: Reddit - Get Subreddit Wiki Revisions
  x-api-slug: rsubredditwikirevisions-getnbsp
  description: Retrieve a list of recently changed wiki pages in this subreddit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikirevisions-getnbsp-openapi.md
- name: Reddit - Get Subreddit Wiki Revisions Page
  x-api-slug: rsubredditwikirevisionspage-getnbsp
  description: Retrieve a list of revisions of this wiki page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikirevisionspage-getnbsp-openapi.md
- name: Reddit - Get Subreddit Wiki Settings Page
  x-api-slug: rsubredditwikisettingspage-getnbsp
  description: Retrieve the current permission settings for page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikisettingspage-getnbsp-openapi.md
- name: Reddit - Add Subreddit Wiki Settings Page
  x-api-slug: rsubredditwikisettingspage-postnbsp
  description: Update the permissions and visibility of wiki page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikisettingspage-postnbsp-openapi.md
- name: Reddit - Get Subreddit Wiki Page
  x-api-slug: rsubredditwikipage-getnbsp
  description: Return the content of a wiki page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3516-reddit.jpg
  humanURL: http://www.reddit.com
  baseURL: https://www.reddit.com//
  tags: Social, Social, My API Stack, Links, Stack Network, Stack, Media, internet,
    Mobile, Technology, SDIO Syndication, General Data, Pedestal, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/reddit/master/_listings/reddit/rsubredditwikipage-getnbsp-openapi.md
x-common:
- type: x-api-gallery
  url: http://rebilly.api.gallery.streamdata.io
- type: x-api-stack
  url: http://reddit.stack.network
- type: x-authentication
  url: https://github.com/reddit/reddit/wiki/OAuth2
- type: x-base
  url: https://www.reddit.com/
- type: x-best-practices
  url: https://github.com/reddit/reddit/wiki/API
- type: x-blog
  url: http://www.redditblog.com/
- type: x-blog-rss
  url: https://www.reddit.com/r/datasets/.rss
- type: x-blog-rss
  url: http://www.redditblog.com/feeds/posts/default?alt=rss
- type: x-code-libraries
  url: https://github.com/reddit/reddit/wiki/API-Wrappers
- type: x-console
  url: https://apigee.com/console/reddit
- type: x-crunchbase
  url: https://crunchbase.com/organization/reddit
- type: x-developer
  url: http://www.reddit.com/dev/api
- type: x-email
  url: legal@reddit.com
- type: x-github
  url: https://github.com/reddit
- type: x-linkedin
  url: https://www.linkedin.com/company/product-hunt/
- type: x-privacy
  url: https://www.reddit.com/help/privacypolicy
- type: x-security
  url: https://www.reddit.com/help/privacypolicy#section_security
- type: x-support
  url: https://www.reddit.com/contact/
- type: x-terms-of-service
  url: http://www.reddit.com/help/useragreement
- type: x-transparency-report
  url: https://www.reddit.com/wiki/transparency
- type: x-twitter
  url: https://twitter.com/reddit
- type: x-website
  url: http://www.reddit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---