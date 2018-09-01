---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Get Me Prefs
  description: Return the preference settings of the logged in user
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