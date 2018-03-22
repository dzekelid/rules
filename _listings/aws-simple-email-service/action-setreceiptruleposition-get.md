---
swagger: "2.0"
info:
  title: AWS Simple Email Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetReceiptRulePosition:
    get:
      summary: ' Set Receipt Rule Position '
      description: Sets the position of the specified receipt rule in the receipt
        rule set
      operationId: setReceiptRulePosition
      parameters:
      - in: query
        name: After
        description: The name of the receipt rule after which to place the specified
          receipt rule
        type: string
      - in: query
        name: RuleName
        description: The name of the receipt rule to reposition
        type: string
      - in: query
        name: RuleSetName
        description: The name of the receipt rule set that contains the receipt rule
          to reposition
        type: string
      responses:
        200:
          description: OK
      tags:
      - receipt rules
definitions: []
x-collection-name: AWS Simple Email Service
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