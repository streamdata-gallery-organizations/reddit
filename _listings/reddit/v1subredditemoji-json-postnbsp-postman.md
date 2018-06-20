{
  "info": {
    "name": "Reddit Add Subreddit Emoji.json",
    "_postman_id": "9ea643ca-9b3e-4a59-9e68-0623bd4abd20",
    "description": "Add an emoji to the DB by posting a message on emoji_upload_q.\nA job processor that listens on a queue, uses the s3_key provided\nin the request to locate the image in S3 Temp Bucket and moves it\nto the PERM bucket. It also adds it to the DB using name as the column\nand sr_fullname as the key and sends the status on the websocket URL\nthat is provided as part of this response.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": []
}