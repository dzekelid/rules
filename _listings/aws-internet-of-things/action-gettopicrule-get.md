---
swagger: "2.0"
info:
  title: AWS Internet of Things API Get Topic Rule
  version: 1.0.0
  description: Gets information about the specified rule.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetTopicRule:
    get:
      summary: ' Get Topic Rule '
      description: Gets information about the specified rule
      operationId: getTopicRule
      parameters:
      - in: query
        name: ruleName
        description: The name of the rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - topic rules
definitions: []
x-collection-name: AWS Internet of Things
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