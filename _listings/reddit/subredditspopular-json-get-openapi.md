---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Get Subreddits Where
  description: Get all subreddits.
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
  /v1/me/prefs:
    get&nbsp;:
      summary: Get Me Prefs
      description: Return the preference settings of the logged in user
      operationId: get&nbsp;V1MePrefs
      x-api-path-slug: v1meprefs-getnbsp
      parameters:
      - in: query
        name: fields
        description: A comma-separated list of items from this set:default_theme_srthreaded_messageshide_downsemail_messagesprofile_opt_outshow_link_flaircreddit_autorenewshow_trendingprivate_feedsmonitor_mentionsresearchignore_suggested_sortemail_digestsmediaclickgadgetuse_global_defaultslabel_nsfwdomain_detailsshow_stylesheetslive_orangeredshighlight_controversialno_profanityemail_unsubscribe_alllanghide_upsallow_clicktrackinghide_from_robotscompressstore_visitsthreaded_modmaildesign_betabetaother_thememedia_previewover_18enable_default_themesgeopopularshow_promotemin_comment_scorepublic_votesno_video_autoplayorganiccollapse_read_messagesshow_flairmark_messages_readsearch_include_over_18hide_adsmin_link_scoretop_karma_subredditsnewwindownumsiteslegacy_searchnum_commentsshow_gold_expirationhighlight_new_commentsdefault_comment_sorthide_locationbar
        type: string
      responses:
        200:
          description: OK
      tags:
      - Me
      - Prefs
    patch&nbsp;:
      summary: Patch Me Prefs
      description: ""
      operationId: patch&nbsp;V1MePrefs
      x-api-path-slug: v1meprefs-patchnbsp
      parameters:
      - in: query
        name: This endpoint expects JSON data of this format
        description: '{  &quot;allow_clicktracking&quot;: boolean value,  &quot;beta&quot;:
          boolean value,  &quot;clickgadget&quot;: boolean value,  &quot;collapse_read_messages&quot;:
          boolean value,  &quot;compress&quot;: boolean value,  &quot;creddit_autorenew&quot;:
          boolean value,  &quot;default_comment_sort&quot;: one of (`confidence`,
          `top`, `new`, `controversial`, `old`, `random`, `qa`, `live`),  &quot;domain_details&quot;:
          boolean value,  &quot;email_digests&quot;: boolean value,  &quot;email_messages&quot;:
          boolean value,  &quot;email_unsubscribe_all&quot;: boolean value,  &quot;enable_default_themes&quot;:
          boolean value,  &quot;g&quot;: one of (`GLOBAL`, `US`, `AR`, `AU`, `BG`,
          `CA`, `CL`, `CO`, `HR`, `CZ`, `FI`, `GR`, `HU`, `IS`, `IN`, `IE`, `JP`,
          `MY`, `MX`, `NZ`, `PH`, `PL`, `PT`, `PR`, `RO`, `RS`, `SG`, `SE`, `TW`,
          `TH`, `TR`, `GB`, `US_WA`, `US_DE`, `US_DC`, `US_WI`, `US_WV`, `US_HI`,
          `US_FL`, `US_WY`, `US_NH`, `US_NJ`, `US_NM`, `US_TX`, `US_LA`, `US_NC`,
          `US_ND`, `US_NE`, `US_TN`, `US_NY`, `US_PA`, `US_CA`, `US_NV`, `US_VA`,
          `US_CO`, `US_AK`, `US_AL`, `US_AR`, `US_VT`, `US_IL`, `US_GA`, `US_IN`,
          `US_IA`, `US_OK`, `US_AZ`, `US_ID`, `US_CT`, `US_ME`, `US_MD`, `US_MA`,
          `US_OH`, `US_UT`, `US_MO`, `US_MN`, `US_MI`, `US_RI`, `US_KS`, `US_MT`,
          `US_MS`, `US_SC`, `US_KY`, `US_OR`, `US_SD`),  &quot;hide_ads&quot;: boolean
          value,  &quot;hide_downs&quot;: boolean value,  &quot;hide_from_robots&quot;:
          boolean value,  &quot;hide_locationbar&quot;: boolean value,  &quot;hide_ups&quot;:
          boolean value,  &quot;highlight_controversial&quot;: boolean value,  &quot;highlight_new_comments&quot;:
          boolean value,  &quot;ignore_suggested_sort&quot;: boolean value,  &quot;in_redesign_beta&quot;:
          boolean value,  &quot;label_nsfw&quot;: boolean value,  &quot;lang&quot;:
          a valid IETF language tag (underscore separated),  &quot;legacy_search&quot;:
          boolean value,  &quot;live_orangereds&quot;: boolean value,  &quot;mark_messages_read&quot;:
          boolean value,  &quot;media&quot;: one of (`on`, `off`, `subreddit`),  &quot;media_preview&quot;:
          one of (`on`, `off`, `subreddit`),  &quot;min_comment_score&quot;: an integer
          between -100 and 100,  &quot;min_link_score&quot;: an integer between -100
          and 100,  &quot;monitor_mentions&quot;: boolean value,  &quot;newwindow&quot;:
          boolean value,  &quot;no_profanity&quot;: boolean value,  &quot;no_video_autoplay&quot;:
          boolean value,  &quot;num_comments&quot;: an integer between 1 and 500,  &quot;numsites&quot;:
          an integer between 1 and 100,  &quot;organic&quot;: boolean value,  &quot;other_theme&quot;:
          subreddit name,  &quot;over_18&quot;: boolean value,  &quot;private_feeds&quot;:
          boolean value,  &quot;profile_opt_out&quot;: boolean value,  &quot;public_votes&quot;:
          boolean value,  &quot;research&quot;: boolean value,  &quot;search_include_over_18&quot;:
          boolean value,  &quot;show_flair&quot;: boolean value,  &quot;show_gold_expiration&quot;:
          boolean value,  &quot;show_link_flair&quot;: boolean value,  &quot;show_promote&quot;:
          boolean value,  &quot;show_stylesheets&quot;: boolean value,  &quot;show_trending&quot;:
          boolean value,  &quot;store_visits&quot;: boolean value,  &quot;theme_selector&quot;:
          subreddit name,  &quot;threaded_messages&quot;: boolean value,  &quot;threaded_modmail&quot;:
          boolean value,  &quot;top_karma_subreddits&quot;: boolean value,  &quot;use_global_defaults&quot;:
          boolean value,}'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Me
      - Prefs
  /v1/me/trophies:
    get&nbsp;:
      summary: Get Me Trophies
      description: Return a list of trophies for the current user.
      operationId: get&nbsp;V1MeTrophies
      x-api-path-slug: v1metrophies-getnbsp
      responses:
        200:
          description: OK
      tags:
      - Me
      - Trophies
  /prefs/where:
    get&nbsp;:
      summary: Get Prefs Where
      description: This endpoint is a listing.
      operationId: get&nbsp;PrefsWhere
      x-api-path-slug: prefswhere-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Prefs
      - Where
  /v1/subreddit/emoji.json:
    post&nbsp;:
      summary: Add Subreddit Emoji.json
      description: |-
        Add an emoji to the DB by posting a message on emoji_upload_q.
        A job processor that listens on a queue, uses the s3_key provided
        in the request to locate the image in S3 Temp Bucket and moves it
        to the PERM bucket. It also adds it to the DB using name as the column
        and sr_fullname as the key and sends the status on the websocket URL
        that is provided as part of this response.
      operationId: post&nbsp;V1SubredditEmoji.json
      x-api-path-slug: v1subredditemoji-json-postnbsp
      parameters:
      - in: query
        name: name
        description: Name of the emoji to be created
        type: string
      - in: query
        name: s3_key
        description: S3 key of the uploaded image which can be obtained from the S3
          url
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Emoji.json
  /v1/subreddit/emoji/emoji_name:
    delete&nbsp;:
      summary: Delete Subreddit Emoji Emoji Name
      description: |-
        Delete a Subreddit emoji.
        Remove the emoji from Cassandra and purge the assets from S3
        and the image resizing provider.
      operationId: delete&nbsp;V1SubredditEmojiEmojiName
      x-api-path-slug: v1subredditemojiemoji-name-deletenbsp
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Emoji
      - Emoji
      - Name
  /v1/subreddit/emoji_asset_upload_s3.json:
    post&nbsp;:
      summary: Add Subreddit Emoji Asset Upload S3.json
      description: |-
        Acquire and return an upload lease to s3 temp bucket. The return value
        of this function is a json object containing credentials for uploading
        assets to S3 bucket, S3 url for upload request and the key to use for
        uploading. Using this lease the client will upload the emoji image to
        S3 temp bucket (included as part of the S3 URL).
      operationId: post&nbsp;V1SubredditEmojiAssetUploadS3.json
      x-api-path-slug: v1subredditemoji-asset-upload-s3-json-postnbsp
      parameters:
      - in: query
        name: filepath
        description: name and extension of the image file e
        type: string
      - in: query
        name: mimetype
        description: mime type of the image e
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Emoji
      - Asset
      - Upload
      - S3.json
  /v1/subreddit/emojis/all:
    get&nbsp;:
      summary: Get Subreddit Emojis All
      description: |-
        Get all emojis for a SR. The response inclueds reddit emojis
        as well as emojis for the SR specified in the request.
      operationId: get&nbsp;V1SubredditEmojisAll
      x-api-path-slug: v1subredditemojisall-getnbsp
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Emojis
  /v1/gold/gild/fullname:
    post&nbsp;:
      summary: Add Gold Gild Fullname
      description: fullname of a thing
      operationId: post&nbsp;V1GoldGildFullname
      x-api-path-slug: v1goldgildfullname-postnbsp
      parameters:
      - in: query
        name: fullname
        description: fullname of a thing
        type: string
      responses:
        200:
          description: OK
      tags:
      - Gold
      - Gild
      - Fullname
  /v1/gold/give/username:
    post&nbsp;:
      summary: Add Gold Give Username
      description: an integer between 1 and 36
      operationId: post&nbsp;V1GoldGiveUsername
      x-api-path-slug: v1goldgiveusername-postnbsp
      parameters:
      - in: query
        name: months
        description: an integer between 1 and 36
        type: string
      - in: query
        name: username
        description: A valid, existing reddit username
        type: string
      responses:
        200:
          description: OK
      tags:
      - Gold
      - Give
      - Username
  /best.json:
    get:
      summary: Get Best
      description: This endpoint is a listing.
      operationId: get&nbsp;Best
      x-api-path-slug: best-json-get
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Best
  /by_id/names:
    get:
      summary: Get By Names
      description: Get a listing of links by fullname.
      operationId: get&nbsp;ByNames
      x-api-path-slug: by-idnames-get
      parameters:
      - in: query
        name: names
        description: A comma-separated list of link fullnames
        type: string
      responses:
        200:
          description: OK
      tags:
      - Names
  '{/r/subreddit}/comments/article':
    get&nbsp;:
      summary: Get Subreddit Comments Article
      description: Get the comment tree for a given Link article.
      operationId: get&nbsp;RSubredditCommentsArticle
      x-api-path-slug: rsubredditcommentsarticle-getnbsp
      parameters:
      - in: query
        name: article
        description: ID36 of a link
        type: string
      - in: query
        name: comment
        description: (optional) ID36 of a comment
        type: string
      - in: query
        name: context
        description: an integer between 0 and 8
        type: string
      - in: query
        name: depth
        description: (optional) an integer
        type: string
      - in: query
        name: limit
        description: (optional) an integer
        type: string
      - in: query
        name: showedits
        description: boolean value
        type: string
      - in: query
        name: showmore
        description: boolean value
        type: string
      - in: query
        name: sort
        description: one of (confidence, top, new, controversial, old, random, qa,
          live)
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      - in: query
        name: threaded
        description: boolean value
        type: string
      - in: query
        name: truncate
        description: an integer between 0 and 50
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Comments
      - Article
  /duplicates/article:
    get&nbsp;:
      summary: Get Duplicates Article
      description: Return a list of other submissions of the same URL
      operationId: get&nbsp;DuplicatesArticle
      x-api-path-slug: duplicatesarticle-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: article
        description: The base 36 ID of a Link
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Duplicates
      - Article
  '{/r/subreddit}/hot.json':
    get:
      summary: Get Subreddit Hot
      description: This endpoint is a listing.
      operationId: get&nbsp;RSubredditHot
      x-api-path-slug: rsubreddithot-json-get
      parameters:
      - in: path
        name: /r/subreddit
        description: The subreddit
        type: string
        format: string
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: g
        description: one of (GLOBAL, US, AR, AU, BG, CA, CL, CO, HR, CZ, FI, GR, HU,
          IS, IN, IE, JP, MY, MX, NZ, PH, PL, PT, PR, RO, RS, SG, SE, TW, TH, TR,
          GB, US_WA, US_DE, US_DC, US_WI, US_WV, US_HI, US_FL, US_WY, US_NH, US_NJ,
          US_NM, US_TX, US_LA, US_NC, US_ND, US_NE, US_TN, US_NY, US_PA, US_CA, US_NV,
          US_VA, US_CO, US_AK, US_AL, US_AR, US_VT, US_IL, US_GA, US_IN, US_IA, US_OK,
          US_AZ, US_ID, US_CT, US_ME, US_MD, US_MA, US_OH, US_UT, US_MO, US_MN, US_MI,
          US_RI, US_KS, US_MT, US_MS, US_SC, US_KY, US_OR, US_SD)
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Hot
  '{/r/subreddit}/new.json':
    get:
      summary: Get Subreddit New
      description: This endpoint is a listing.
      operationId: get&nbsp;RSubredditNew
      x-api-path-slug: rsubredditnew-json-get
      parameters:
      - in: path
        name: /r/subreddit
        description: the subreddit
        type: string
        format: string
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - New
  '{/r/subreddit}/random.json':
    get:
      summary: Get Subreddit Random
      description: The Serendipity button
      operationId: get&nbsp;RSubredditRandom
      x-api-path-slug: rsubredditrandom-json-get
      parameters:
      - in: path
        name: /r/subreddit
        description: The subreddit
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Random
  '{/r/subreddit}/rising.json':
    get:
      summary: Get Subreddit Rising
      description: This endpoint is a listing.
      operationId: get&nbsp;RSubredditRising
      x-api-path-slug: rsubredditrising-json-get
      parameters:
      - in: path
        name: /r/subreddit
        description: The subreddit
        type: string
        format: string
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Rising
  '{/r/subreddit}/sort':
    get:
      summary: Get Subreddit Sort
      description: This endpoint is a listing.
      operationId: get&nbsp;RSubredditSort
      x-api-path-slug: rsubredditsort-get
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      - in: query
        name: t
        description: one of (hour, day, week, month, year, all)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Sort
  /block:
    post&nbsp;:
      summary: Add Block
      description: For blocking the author of a thing via inbox.
      operationId: post&nbsp;Block
      x-api-path-slug: block-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Block
  /collapse_message:
    post&nbsp;:
      summary: Add Collapse Message
      description: Collapse a message
      operationId: post&nbsp;CollapseMessage
      x-api-path-slug: collapse-message-postnbsp
      parameters:
      - in: query
        name: id
        description: A comma-separated list of thing fullnames
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Collapse
      - Message
  /compose:
    post&nbsp;:
      summary: Add Compose
      description: Handles message composition under /message/compose.
      operationId: post&nbsp;Compose
      x-api-path-slug: compose-postnbsp
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: from_sr
        description: subreddit name
        type: string
      - in: query
        name: g-recaptcha-response
        type: string
      - in: query
        name: subject
        description: a string no longer than 100 characters
        type: string
      - in: query
        name: text
        description: raw markdown text
        type: string
      - in: query
        name: to
        description: the name of an existing user
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Compose
  /del_msg:
    post&nbsp;:
      summary: Add Del Msg
      description: Delete messages from the recipient&#39;s view of their inbox.
      operationId: post&nbsp;DelMsg
      x-api-path-slug: del-msg-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Del
      - Msg
  /read_all_messages:
    post&nbsp;:
      summary: Add Read All Messages
      description: Queue up marking all messages for a user as read.
      operationId: post&nbsp;ReadAllMessages
      x-api-path-slug: read-all-messages-postnbsp
      parameters:
      - in: query
        name: filter_types
        description: A comma-separated list of items
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Read
      - Messages
  /read_message:
    post&nbsp;:
      summary: Add Read Message
      description: A comma-separated list of thing fullnames
      operationId: post&nbsp;ReadMessage
      x-api-path-slug: read-message-postnbsp
      parameters:
      - in: query
        name: id
        description: A comma-separated list of thing fullnames
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Read
      - Message
  /unblock_subreddit:
    post&nbsp;:
      summary: Add Unblock Subreddit
      description: fullname of a thing
      operationId: post&nbsp;UnblockSubreddit
      x-api-path-slug: unblock-subreddit-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Unblock
      - Subreddit
  /uncollapse_message:
    post&nbsp;:
      summary: Add Uncollapse Message
      description: Uncollapse a message
      operationId: post&nbsp;UncollapseMessage
      x-api-path-slug: uncollapse-message-postnbsp
      parameters:
      - in: query
        name: id
        description: A comma-separated list of thing fullnames
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Uncollapse
      - Message
  /unread_message:
    post&nbsp;:
      summary: Add Unread Message
      description: A comma-separated list of thing fullnames
      operationId: post&nbsp;UnreadMessage
      x-api-path-slug: unread-message-postnbsp
      parameters:
      - in: query
        name: id
        description: A comma-separated list of thing fullnames
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Unread
      - Message
  /message/where:
    get&nbsp;:
      summary: Get Message Where
      description: This endpoint is a listing.
      operationId: get&nbsp;MessageWhere
      x-api-path-slug: messagewhere-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: mark
        description: one of (true, false)
        type: string
      - in: query
        name: mid
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Message
      - Where
  '{/r/subreddit}/about/log':
    get&nbsp;:
      summary: Get Subreddit About Log
      description: Get a list of recent moderation actions.
      operationId: get&nbsp;RSubredditAboutLog
      x-api-path-slug: rsubredditaboutlog-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 500)'
        type: string
      - in: query
        name: mod
        description: (optional) a moderator filter
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      - in: query
        name: type
        description: one of (banuser, unbanuser, spamlink, removelink, approvelink,
          spamcomment, removecomment, approvecomment, addmoderator, invitemoderator,
          uninvitemoderator, acceptmoderatorinvite, removemoderator, addcontributor,
          removecontributor, editsettings, editflair, distinguish, marknsfw, wikibanned,
          wikicontributor, wikiunbanned, wikipagelisted, removewikicontributor, wikirevise,
          wikipermlevel, ignorereports, unignorereports, setpermissions, setsuggestedsort,
          sticky, unsticky, setcontestmode, unsetcontestmode, lock, unlock, muteuser,
          unmuteuser, createrule, editrule, deleterule, spoiler, unspoiler, modmail_enrollment,
          community_styling, community_widgets)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - About
      - Log
  '{/r/subreddit}/about/location':
    get&nbsp;:
      summary: Get Subreddit About Location
      description: Return a listing of posts relevant to moderators.
      operationId: get&nbsp;RSubredditAboutLocation
      x-api-path-slug: rsubredditaboutlocation-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: location
        type: string
      - in: query
        name: only
        description: one of (links, comments)
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - About
      - Location
  '{/r/subreddit}/accept_moderator_invite':
    post&nbsp;:
      summary: Add Subreddit Accept Moderator Invite
      description: Accept an invite to moderate the specified subreddit.
      operationId: post&nbsp;RSubredditAcceptModeratorInvite
      x-api-path-slug: rsubredditaccept-moderator-invite-postnbsp
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Accept
      - Moderator
      - Invite
  /approve:
    post&nbsp;:
      summary: Add Approve
      description: Approve a link or comment.
      operationId: post&nbsp;Approve
      x-api-path-slug: approve-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Approve
  /distinguish:
    post&nbsp;:
      summary: Add Distinguish
      description: Distinguish a thing&#39;s author with a sigil.
      operationId: post&nbsp;Distinguish
      x-api-path-slug: distinguish-postnbsp
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
      - Distinguish
  /ignore_reports:
    post&nbsp;:
      summary: Add Ignore Reports
      description: Prevent future reports on a thing from causing notifications.
      operationId: post&nbsp;IgnoreReports
      x-api-path-slug: ignore-reports-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Ignore
      - Reports
  /leavecontributor:
    post&nbsp;:
      summary: Add Leavecontributor
      description: Abdicate approved submitter status in a subreddit.
      operationId: post&nbsp;Leavecontributor
      x-api-path-slug: leavecontributor-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Leavecontributor
  /leavemoderator:
    post&nbsp;:
      summary: Add Leavemoderator
      description: Abdicate moderator status in a subreddit.
      operationId: post&nbsp;Leavemoderator
      x-api-path-slug: leavemoderator-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Leavemoderator
  /mute_message_author:
    post&nbsp;:
      summary: Add Mute Message Author
      description: For muting user via modmail.
      operationId: post&nbsp;MuteMessageAuthor
      x-api-path-slug: mute-message-author-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Mute
      - Message
      - Author
  /remove:
    post&nbsp;:
      summary: Add Remove
      description: Remove a link, comment, or modmail message.
      operationId: post&nbsp;Remove
      x-api-path-slug: remove-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: spam
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
      - Remove
  /unignore_reports:
    post&nbsp;:
      summary: Add Unignore Reports
      description: Allow future reports on a thing to cause notifications.
      operationId: post&nbsp;UnignoreReports
      x-api-path-slug: unignore-reports-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Unignore
      - Reports
  /unmute_message_author:
    post&nbsp;:
      summary: Add Unmute Message Author
      description: For unmuting user via modmail.
      operationId: post&nbsp;UnmuteMessageAuthor
      x-api-path-slug: unmute-message-author-postnbsp
      parameters:
      - in: query
        name: id
        description: fullname of a thing
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Unmute
      - Message
      - Author
  '{/r/subreddit}/stylesheet':
    get:
      summary: Get Subreddit Stylesheet
      description: Redirect to the subreddit&#39;s stylesheet if one exists.
      operationId: get&nbsp;RSubredditStylesheet
      x-api-path-slug: rsubredditstylesheet-get
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Stylesheet
  /multi/copy:
    post&nbsp;:
      summary: Add Multi Copy
      description: Copy a multi.
      operationId: post&nbsp;MultiCopy
      x-api-path-slug: multicopy-postnbsp
      parameters:
      - in: query
        name: display_name
        description: a string no longer than 50 characters
        type: string
      - in: query
        name: from
        description: multireddit url path
        type: string
      - in: query
        name: to
        description: destination multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Copy
  /multi/mine:
    get&nbsp;:
      summary: Get Multi Mine
      description: Fetch a list of multis belonging to the current user.
      operationId: get&nbsp;MultiMine
      x-api-path-slug: multimine-getnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Mine
  /multi/rename:
    post&nbsp;:
      summary: Add Multi Rename
      description: Rename a multi.
      operationId: post&nbsp;MultiRename
      x-api-path-slug: multirename-postnbsp
      parameters:
      - in: query
        name: display_name
        description: a string no longer than 50 characters
        type: string
      - in: query
        name: from
        description: multireddit url path
        type: string
      - in: query
        name: to
        description: destination multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Rename
  /multi/user/username:
    get&nbsp;:
      summary: Get Multi User Username
      description: Fetch a list of public multis belonging to username
      operationId: get&nbsp;MultiUserUsername
      x-api-path-slug: multiuserusername-getnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: username
        description: A valid, existing reddit username
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - User
      - Username
  /multi/multipath:
    delete&nbsp;:
      summary: Delete Multi Multipath
      description: Delete a multi.
      operationId: delete&nbsp;MultiMultipath
      x-api-path-slug: multimultipath-deletenbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
    get&nbsp;:
      summary: Get Multi Multipath
      description: Fetch a multi&#39;s data and subreddit list by name.
      operationId: get&nbsp;MultiMultipath
      x-api-path-slug: multimultipath-getnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
    post&nbsp;:
      summary: Add Multi Multipath
      description: Create a multi. Responds with 409 Conflict if it already exists.
      operationId: post&nbsp;MultiMultipath
      x-api-path-slug: multimultipath-postnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: model
        description: 'json data:{  &quot;description_md&quot;: raw markdown text,  &quot;display_name&quot;:
          a string no longer than 50 characters,  &quot;icon_name&quot;: one of (`art
          and design`, `ask`, `books`, `business`, `cars`, `comics`, `cute animals`,
          `diy`, `entertainment`, `food and drink`, `funny`, `games`, `grooming`,
          `health`, `life advice`, `military`, `models pinup`, `music`, `news`, `philosophy`,
          `pictures and gifs`, `science`, `shopping`, `sports`, `style`, `tech`, `travel`,
          `unusual stories`, `video`, ``, `None`),  &quot;key_color&quot;: a 6-digit
          rgb hex color, e'
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
    put&nbsp;:
      summary: Put Multi Multipath
      description: Create or update a multi.
      operationId: put&nbsp;MultiMultipath
      x-api-path-slug: multimultipath-putnbsp
      parameters:
      - in: query
        name: expand_srs
        description: boolean value
        type: string
      - in: query
        name: model
        description: 'json data:{  &quot;description_md&quot;: raw markdown text,  &quot;display_name&quot;:
          a string no longer than 50 characters,  &quot;icon_name&quot;: one of (`art
          and design`, `ask`, `books`, `business`, `cars`, `comics`, `cute animals`,
          `diy`, `entertainment`, `food and drink`, `funny`, `games`, `grooming`,
          `health`, `life advice`, `military`, `models pinup`, `music`, `news`, `philosophy`,
          `pictures and gifs`, `science`, `shopping`, `sports`, `style`, `tech`, `travel`,
          `unusual stories`, `video`, ``, `None`),  &quot;key_color&quot;: a 6-digit
          rgb hex color, e'
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
  /multi/multipath/description:
    get&nbsp;:
      summary: Get Multi Multipath Description
      description: Get a multi&#39;s description.
      operationId: get&nbsp;MultiMultipathDescription
      x-api-path-slug: multimultipathdescription-getnbsp
      parameters:
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Description
    put&nbsp;:
      summary: Put Multi Multipath Description
      description: Change a multi&#39;s markdown description.
      operationId: put&nbsp;MultiMultipathDescription
      x-api-path-slug: multimultipathdescription-putnbsp
      parameters:
      - in: query
        name: model
        description: 'json data:{  &quot;body_md&quot;: raw markdown text,}'
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Description
  /multi/multipath/r/srname:
    delete&nbsp;:
      summary: Delete Multi Multipath Srname
      description: Remove a subreddit from a multi.
      operationId: delete&nbsp;MultiMultipathRSrname
      x-api-path-slug: multimultipathrsrname-deletenbsp
      parameters:
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: srname
        description: subreddit name
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Srname
    get&nbsp;:
      summary: Get Multi Multipath Srname
      description: Get data about a subreddit in a multi.
      operationId: get&nbsp;MultiMultipathRSrname
      x-api-path-slug: multimultipathrsrname-getnbsp
      parameters:
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: srname
        description: subreddit name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Srname
    put&nbsp;:
      summary: Put Multi Multipath Srname
      description: Add a subreddit to a multi.
      operationId: put&nbsp;MultiMultipathRSrname
      x-api-path-slug: multimultipathrsrname-putnbsp
      parameters:
      - in: query
        name: model
        description: 'json data:{  &quot;name&quot;: subreddit name,}'
        type: string
      - in: query
        name: multipath
        description: multireddit url path
        type: string
      - in: query
        name: srname
        description: subreddit name
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Multi
      - Multipath
      - Srname
  '{/r/subreddit}/about/where':
    get&nbsp;:
      summary: Get Subreddit About Where
      description: This endpoint is a listing.
      operationId: get&nbsp;RSubredditAboutWhere
      x-api-path-slug: rsubredditaboutwhere-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      - in: query
        name: user
        description: A valid, existing reddit username
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - About
      - Where
  '{/r/subreddit}/delete_sr_banner':
    post&nbsp;:
      summary: Add Subreddit Delete Sr Banner
      description: Remove the subreddit&#39;s custom mobile banner.
      operationId: post&nbsp;RSubredditDeleteSrBanner
      x-api-path-slug: rsubredditdelete-sr-banner-postnbsp
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - ""
      - Sr
      - Banner
  '{/r/subreddit}/delete_sr_header':
    post&nbsp;:
      summary: Add Subreddit Delete Sr Header
      description: Remove the subreddit&#39;s custom header image.
      operationId: post&nbsp;RSubredditDeleteSrHeader
      x-api-path-slug: rsubredditdelete-sr-header-postnbsp
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - ""
      - Sr
      - Header
  '{/r/subreddit}/delete_sr_icon':
    post&nbsp;:
      summary: Add Subreddit Delete Sr Icon
      description: Remove the subreddit&#39;s custom mobile icon.
      operationId: post&nbsp;RSubredditDeleteSrIcon
      x-api-path-slug: rsubredditdelete-sr-icon-postnbsp
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - ""
      - Sr
      - Icon
  '{/r/subreddit}/delete_sr_img':
    post&nbsp;:
      summary: Add Subreddit Delete Sr Img
      description: Remove an image from the subreddit&#39;s custom image set.
      operationId: post&nbsp;RSubredditDeleteSrImg
      x-api-path-slug: rsubredditdelete-sr-img-postnbsp
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: img_name
        description: a valid subreddit image name
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - ""
      - Sr
      - Img
  /recommend/sr/srnames:
    get&nbsp;:
      summary: Get Recommend Sr Srnames
      description: Return subreddits recommended for the given subreddit(s).
      operationId: get&nbsp;RecommendSrSrnames
      x-api-path-slug: recommendsrsrnames-getnbsp
      parameters:
      - in: query
        name: omit
        description: comma-delimited list of subreddit names
        type: string
      - in: query
        name: over_18
        description: boolean value
        type: string
      - in: query
        name: srnames
        description: comma-delimited list of subreddit names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Recommend
      - Sr
      - Srnames
  /api/search_reddit_names.json:
    get:
      summary: Get Search Reddit Names
      description: List subreddit names that begin with a query string.
      operationId: get&nbsp;SearchRedditNames
      x-api-path-slug: apisearch-reddit-names-json-get
      parameters:
      - in: query
        name: exact
        description: boolean value
        type: string
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_unadvertisable
        description: boolean value
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Search
      - Reddit
      - Names
  /search_reddit_names:
    post&nbsp;:
      summary: Add Search Reddit Names
      description: List subreddit names that begin with a query string.
      operationId: post&nbsp;SearchRedditNames
      x-api-path-slug: search-reddit-names-postnbsp
      parameters:
      - in: query
        name: exact
        description: boolean value
        type: string
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_unadvertisable
        description: boolean value
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Search
      - Reddit
      - Names
  /search_subreddits:
    post&nbsp;:
      summary: Add Search Subreddits
      description: List subreddits that begin with a query string.
      operationId: post&nbsp;SearchSubreddits
      x-api-path-slug: search-subreddits-postnbsp
      parameters:
      - in: query
        name: exact
        description: boolean value
        type: string
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_unadvertisable
        description: boolean value
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Search
      - Subreddits
  /site_admin:
    post&nbsp;:
      summary: Add Site Admin
      description: Create or configure a subreddit.
      operationId: post&nbsp;SiteAdmin
      x-api-path-slug: site-admin-postnbsp
      parameters:
      - in: query
        name: allow_discovery
        description: boolean value
        type: string
      - in: query
        name: allow_images
        description: boolean value
        type: string
      - in: query
        name: allow_post_crossposts
        description: boolean value
        type: string
      - in: query
        name: allow_top
        description: boolean value
        type: string
      - in: query
        name: allow_videos
        description: boolean value
        type: string
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: collapse_deleted_comments
        description: boolean value
        type: string
      - in: query
        name: comment_score_hide_mins
        description: 'an integer between 0 and 1440 (default: 0)'
        type: string
      - in: query
        name: description
        description: raw markdown text
        type: string
      - in: query
        name: exclude_banned_modqueue
        description: boolean value
        type: string
      - in: query
        name: free_form_reports
        description: boolean value
        type: string
      - in: query
        name: g-recaptcha-response
        type: string
      - in: query
        name: header-title
        description: a string no longer than 500 characters
        type: string
      - in: query
        name: hide_ads
        description: boolean value
        type: string
      - in: query
        name: key_color
        description: a 6-digit rgb hex color, e
        type: string
      - in: query
        name: lang
        description: a valid IETF language tag (underscore separated)
        type: string
      - in: query
        name: link_type
        description: one of (any, link, self)
        type: string
      - in: query
        name: name
        description: subreddit name
        type: string
      - in: query
        name: over_18
        description: boolean value
        type: string
      - in: query
        name: public_description
        description: raw markdown text
        type: string
      - in: query
        name: show_media
        description: boolean value
        type: string
      - in: query
        name: show_media_preview
        description: boolean value
        type: string
      - in: query
        name: spam_comments
        description: one of (low, high, all)
        type: string
      - in: query
        name: spam_links
        description: one of (low, high, all)
        type: string
      - in: query
        name: spam_selfposts
        description: one of (low, high, all)
        type: string
      - in: query
        name: spoilers_enabled
        description: boolean value
        type: string
      - in: query
        name: sr
        description: fullname of a thing
        type: string
      - in: query
        name: submit_link_label
        description: a string no longer than 60 characters
        type: string
      - in: query
        name: submit_text
        description: raw markdown text
        type: string
      - in: query
        name: submit_text_label
        description: a string no longer than 60 characters
        type: string
      - in: query
        name: suggested_comment_sort
        description: one of (confidence, top, new, controversial, old, random, qa,
          live)
        type: string
      - in: query
        name: theme_sr
        description: subreddit name
        type: string
      - in: query
        name: theme_sr_update
        description: boolean value
        type: string
      - in: query
        name: title
        description: a string no longer than 100 characters
        type: string
      - in: query
        name: type
        description: one of (gold_restricted, archived, restricted, employees_only,
          gold_only, private, user, public)
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      - in: query
        name: wikimode
        description: one of (disabled, modonly, anyone)
        type: string
      - in: query
        name: wiki_edit_age
        description: 'an integer between 0 and 36600 (default: 0)'
        type: string
      - in: query
        name: wiki_edit_karma
        description: 'an integer between 0 and 1000000000 (default: 0)'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Site
      - Admin
  '{/r/subreddit}/submit_text':
    get:
      summary: Get Subreddit Submit Text
      description: Get the submission text for the subreddit.
      operationId: get&nbsp;RSubredditSubmitText
      x-api-path-slug: rsubredditsubmit-text-get
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Submit
      - Text
  /subreddit_autocomplete:
    get&nbsp;:
      summary: Get Subreddit Autocomplete
      description: |-
        Return a list of subreddits and data for subreddits whose names start
        with &#39;query&#39;.
      operationId: get&nbsp;SubredditAutocomplete
      x-api-path-slug: subreddit-autocomplete-getnbsp
      parameters:
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_profiles
        description: boolean value
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Autocomplete
  /subreddit_autocomplete_v2:
    get&nbsp;:
      summary: Get Subreddit Autocomplete V2
      description: boolean value
      operationId: get&nbsp;SubredditAutocompleteV2
      x-api-path-slug: subreddit-autocomplete-v2-getnbsp
      parameters:
      - in: query
        name: include_over_18
        description: boolean value
        type: string
      - in: query
        name: include_profiles
        description: boolean value
        type: string
      - in: query
        name: limit
        description: 'an integer between 1 and 10 (default: 5)'
        type: string
      - in: query
        name: query
        description: a string up to 50 characters long, consisting of printable characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Autocomplete
      - V2
  '{/r/subreddit}/subreddit_stylesheet':
    post&nbsp;:
      summary: Add Subreddit Subreddit Stylesheet
      description: Update a subreddit&#39;s stylesheet.
      operationId: post&nbsp;RSubredditSubredditStylesheet
      x-api-path-slug: rsubredditsubreddit-stylesheet-postnbsp
      parameters:
      - in: query
        name: api_type
        description: the string json
        type: string
      - in: query
        name: op
        description: one of (save, preview)
        type: string
      - in: query
        name: reason
        description: a string up to 256 characters long, consisting of printable characters
        type: string
      - in: query
        name: stylesheet_contents
        description: the new stylesheet content
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Subreddit
      - Stylesheet
  /subreddits/new.json:
    get:
      summary: Get New Subreddits
      description: Returns new subreddits.
      operationId: getNewSubreddit
      x-api-path-slug: subredditsnew-json-get
      parameters:
      - in: query
        name: query
        description: a string no longer than 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddits
      - New
  /subscribe:
    post&nbsp;:
      summary: Add Subscribe
      description: Subscribe to or unsubscribe from a subreddit.
      operationId: post&nbsp;Subscribe
      x-api-path-slug: subscribe-postnbsp
      parameters:
      - in: query
        name: action
        description: one of (sub, unsub)
        type: string
      - in: query
        name: skip_initial_defaults
        description: boolean value
        type: string
      - in: query
        name: sr / sr_name
        description: A comma-separated list of subreddit fullnames (when using the
          &quot;sr&quot; parameter), or of subreddit names (when using the &quot;sr_name&quot;
          parameter)
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subscribe
  '{/r/subreddit}/upload_sr_img':
    post&nbsp;:
      summary: Add Subreddit Upload Sr Img
      description: |-
        Add or replace a subreddit image, custom header logo, custom mobile
        icon, or custom mobile banner.
      operationId: post&nbsp;RSubredditUploadSrImg
      x-api-path-slug: rsubredditupload-sr-img-postnbsp
      parameters:
      - in: query
        name: file
        description: file upload with maximum size of 500 KiB
        type: string
      - in: query
        name: formid
        description: (optional) can be ignored
        type: string
      - in: query
        name: header
        description: an integer between 0 and 1
        type: string
      - in: query
        name: img_type
        description: 'one of png or jpg (default: png)'
        type: string
      - in: query
        name: name
        description: a valid subreddit image name
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      - in: query
        name: upload_type
        description: one of (img, header, icon, banner)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Upload
      - Sr
      - Img
  /r/subreddit/about:
    get&nbsp;:
      summary: Get Subreddit About
      description: Return information about the subreddit.
      operationId: get&nbsp;RSubredditAbout
      x-api-path-slug: rsubredditabout-getnbsp
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - About
  /r/subreddit/about/edit:
    get&nbsp;:
      summary: Get Subreddit About Edit
      description: Get the current settings of a subreddit.
      operationId: get&nbsp;RSubredditAboutEdit
      x-api-path-slug: rsubredditaboutedit-getnbsp
      parameters:
      - in: query
        name: created
        description: one of (true, false)
        type: string
      - in: query
        name: location
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - About
      - Edit
  /r/subreddit/about/rules:
    get&nbsp;:
      summary: Get Subreddit About Rules
      description: Get the rules for the current subreddit
      operationId: get&nbsp;RSubredditAboutRules
      x-api-path-slug: rsubredditaboutrules-getnbsp
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - About
      - Rules
  /r/subreddit/about/traffic:
    get&nbsp;:
      summary: Get Subreddit About Traffic
      description: Get the traffic for the current subreddit
      operationId: get&nbsp;RSubredditAboutTraffic
      x-api-path-slug: rsubredditabouttraffic-getnbsp
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - About
      - Traffic
  '{/r/subreddit}/sidebar':
    get:
      summary: Get Subreddit Sebar
      description: Get the sidebar for the current subreddit
      operationId: get&nbsp;RSubredditSebar
      x-api-path-slug: rsubredditsidebar-get
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Sebar
  '{/r/subreddit}/sticky':
    get:
      summary: Get Subreddit Sticky
      description: Redirect to one of the posts stickied in the current subreddit
      operationId: get&nbsp;RSubredditSticky
      x-api-path-slug: rsubredditsticky-get
      parameters:
      - in: query
        name: num
        description: 'an integer between 1 and 2 (default: 1)'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddit
      - Sticky
  /subreddits/mine/where:
    get&nbsp;:
      summary: Get Subreddits Mine Where
      description: Get subreddits the user has a relationship with.
      operationId: get&nbsp;SubredditsMineWhere
      x-api-path-slug: subredditsminewhere-getnbsp
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddits
      - Mine
      - Where
  /subreddits/search.json:
    get:
      summary: Get Subreddits Search
      description: Search subreddits by title and description.
      operationId: get&nbsp;SubredditsSearch
      x-api-path-slug: subredditssearch-json-get
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: q
        description: a search query
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sort
        description: one of (relevance, activity)
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddits
      - Search
  /subreddits/popular.json:
    get:
      summary: Get Subreddits Where
      description: Get all subreddits.
      operationId: get&nbsp;SubredditsWhere
      x-api-path-slug: subredditspopular-json-get
      parameters:
      - in: query
        name: after
        description: fullname of a thing
        type: string
      - in: query
        name: before
        description: fullname of a thing
        type: string
      - in: query
        name: count
        description: 'a positive integer (default: 0)'
        type: string
      - in: query
        name: limit
        description: 'the maximum number of items desired (default: 25, maximum: 100)'
        type: string
      - in: query
        name: show
        description: (optional) the string all
        type: string
      - in: query
        name: sr_detail
        description: (optional) expand subreddits
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subreddits
      - Where
x-streamrank:
  polling_total_time_average: "0.82"
  polling_size_download_average: "410383.6"
  streaming_total_time_average: "0.48"
  streaming_size_download_average: "206337.29"
  change_yes: "42"
  change_no: "160"
  time_percentage: "41"
  size_percentage: "50"
  change_percentage: "21"
  last_run: "2018-05-06"
  days_run: "1"
  minute_run: "0"
---