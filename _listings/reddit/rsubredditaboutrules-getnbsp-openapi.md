---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Get Subreddit About Rules
  description: Get the rules for the current subreddit
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