---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Add Subreddit Emoji.json
  description: |-
    Add an emoji to the DB by posting a message on emoji_upload_q.
    A job processor that listens on a queue, uses the s3_key provided
    in the request to locate the image in S3 Temp Bucket and moves it
    to the PERM bucket. It also adds it to the DB using name as the column
    and sr_fullname as the key and sends the status on the websocket URL
    that is provided as part of this response.
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
      x-api-path-slug: v1subredditemojijson-postnbsp
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