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
  /?Action=CreateReceiptRule:
    get:
      summary: ' Create Receipt Rule '
      description: Creates a receipt rule
      operationId: createReceiptRule
      parameters:
      - in: query
        name: After
        description: The name of an existing rule after which the new rule will be
          placed
        type: string
      - in: query
        name: Rule
        description: A data structure that contains the specified rule's name, actions,
          recipients, domains, enabled status, scan status, and TLS policy
        type: string
      - in: query
        name: RuleSetName
        description: The name of the rule set to which to add the rule
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