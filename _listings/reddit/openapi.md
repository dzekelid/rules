---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
  description: the-reddit-api-allows-you-to-access-the-user-submitted-and-rated-stories-on-reddit-com--it-also-provides-advanced-functionality-including-user-account-information-and-subreddit-moderation-
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
---