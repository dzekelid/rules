---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 0
info:
  title: AWS Simple Email Service API Delete Receipt Rule Set
  version: 1.0.0
  description: Deletes the specified receipt rule set and all of the receipt rules
    it contains.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CloneReceiptRuleSet:
    get:
      summary: Clone Receipt Rule Set
      description: Creates a receipt rule set by cloning an existing one.
      operationId: cloneReceiptRuleSet
      x-api-path-slug: actionclonereceiptruleset-get
      parameters:
      - in: query
        name: OriginalRuleSetName
        description: The name of the rule set to clone
        type: string
      - in: query
        name: RuleSetName
        description: The name of the rule set to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Receipt Rule Sets
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
  /?Action=CreateReceiptRuleSet:
    get:
      summary: Create Receipt Rule Set
      description: Creates an empty receipt rule set.
      operationId: createReceiptRuleSet
      x-api-path-slug: actioncreatereceiptruleset-get
      parameters:
      - in: query
        name: RuleSetName
        description: The name of the rule set to create
        type: string
      responses:
        200:
          description: OK
      tags:
      - Receipt Rule Sets
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
  /?Action=DeleteReceiptRuleSet:
    get:
      summary: Delete Receipt Rule Set
      description: Deletes the specified receipt rule set and all of the receipt rules
        it contains.
      operationId: deleteReceiptRuleSet
      x-api-path-slug: actiondeletereceiptruleset-get
      parameters:
      - in: query
        name: RuleSetName
        description: The name of the receipt rule set to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Receipt Rule Sets
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