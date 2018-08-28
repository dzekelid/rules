---
swagger: "2.0"
x-collection-name: AWS Elastic Load Balancing
x-complete: 0
info:
  title: AWS Elastic Load Balancing API Describe Rules
  version: 1.0.0
  description: Describes the specified rules or the rules for the specified listener.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateRule:
    get:
      summary: Create Rule
      description: Creates a rule for the specified listener.
      operationId: createRule
      x-api-path-slug: actioncreaterule-get
      parameters:
      - in: query
        name: Actions.member.N
        description: An action
        type: string
      - in: query
        name: Conditions.member.N
        description: A condition
        type: string
      - in: query
        name: ListenerArn
        description: The Amazon Resource Name (ARN) of the listener
        type: string
      - in: query
        name: Priority
        description: The priority for the rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
  /?Action=DeleteRule:
    get:
      summary: Delete Rule
      description: Deletes the specified rule.
      operationId: deleteRule
      x-api-path-slug: actiondeleterule-get
      parameters:
      - in: query
        name: RuleArn
        description: The Amazon Resource Name (ARN) of the rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
  /?Action=DescribeRules:
    get:
      summary: Describe Rules
      description: Describes the specified rules or the rules for the specified listener.
      operationId: describeRules
      x-api-path-slug: actiondescriberules-get
      parameters:
      - in: query
        name: ListenerArn
        description: The Amazon Resource Name (ARN) of the listener
        type: string
      - in: query
        name: RuleArns.member.N
        description: The Amazon Resource Names (ARN) of the rules
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
  /?Action=ModifyRule:
    get:
      summary: Modify Rule
      description: Modifies the specified rule.
      operationId: modifyRule
      x-api-path-slug: actionmodifyrule-get
      parameters:
      - in: query
        name: Actions.member.N
        description: The actions
        type: string
      - in: query
        name: Conditions.member.N
        description: The conditions
        type: string
      - in: query
        name: RuleArn
        description: The Amazon Resource Name (ARN) of the rule
        type: string
      responses:
        200:
          description: OK
      tags:
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