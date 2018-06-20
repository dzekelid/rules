---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 1
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
      summary: Create Receipt Rule
      description: Creates a receipt rule.
      operationId: createReceiptRule
      x-api-path-slug: actioncreatereceiptrule-get
      parameters:
      - in: query
        name: After
        description: The name of an existing rule after which the new rule will be
          placed
        type: string
      - in: query
        name: Rule
        description: A data structure that contains the specified rules name, actions,
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
      - Receipt Rules
  /?Action=DeleteReceiptRule:
    get:
      summary: Delete Receipt Rule
      description: Deletes the specified receipt rule.
      operationId: deleteReceiptRule
      x-api-path-slug: actiondeletereceiptrule-get
      parameters:
      - in: query
        name: RuleName
        description: The name of the receipt rule to delete
        type: string
      - in: query
        name: RuleSetName
        description: The name of the receipt rule set that contains the receipt rule
          to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Receipt Rules
  /?Action=DescribeReceiptRule:
    get:
      summary: Describe Receipt Rule
      description: Returns the details of the specified receipt rule.
      operationId: describeReceiptRule
      x-api-path-slug: actiondescribereceiptrule-get
      parameters:
      - in: query
        name: RuleName
        description: The name of the receipt rule
        type: string
      - in: query
        name: RuleSetName
        description: The name of the receipt rule set to which the receipt rule belongs
        type: string
      responses:
        200:
          description: OK
      tags:
      - Receipt Rules
  /?Action=SetReceiptRulePosition:
    get:
      summary: Set Receipt Rule Position
      description: Sets the position of the specified receipt rule in the receipt
        rule set.
      operationId: setReceiptRulePosition
      x-api-path-slug: actionsetreceiptruleposition-get
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
      - Receipt Rules
---