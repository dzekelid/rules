---
swagger: "2.0"
x-collection-name: AWS Config
x-complete: 0
info:
  title: AWS Config API Delete Config Rule
  version: 1.0.0
  description: Deletes the specified AWS Config rule and all of its evaluation results.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteConfigRule:
    get:
      summary: Delete Config Rule
      description: Deletes the specified AWS Config rule and all of its evaluation
        results.
      operationId: deleteConfigRule
      x-api-path-slug: actiondeleteconfigrule-get
      parameters:
      - in: query
        name: ConfigRuleName
        description: The name of the AWS Config rule that you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Rules
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