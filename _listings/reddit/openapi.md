swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
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