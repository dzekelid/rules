---
swagger: "2.0"
x-collection-name: AWS WAF
x-complete: 1
info:
  title: AWS WAF API
  version: 1.0.0
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
      description: "Service: AWS WAFCreates a Rule, which contains the IPSet objects,
        ByteMatchSet objects, and \n\t\t\tother predicates that identify the requests
        that you want to block."
      operationId: createRule
      x-api-path-slug: actioncreaterule-get
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: MetricName
        description: A friendly name or description for the metrics for this Rule
        type: string
      - in: query
        name: Name
        description: A friendly name or description of the Rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
  /?Action=DeleteRule:
    get:
      summary: Delete Rule
      description: 'Service: AWS WAFPermanently deletes a.'
      operationId: deleteRule
      x-api-path-slug: actiondeleterule-get
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: RuleId
        description: The RuleId of the Rule that you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
  /?Action=GetRule:
    get:
      summary: Get Rule
      description: 'Service: AWS WAFReturns the.'
      operationId: getRule
      x-api-path-slug: actiongetrule-get
      parameters:
      - in: query
        name: RuleId
        description: The RuleId of the Rule that you want to get
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
  /?Action=ListRules:
    get:
      summary: List Rules
      description: 'Service: AWS WAFReturns an array of.'
      operationId: listRules
      x-api-path-slug: actionlistrules-get
      parameters:
      - in: query
        name: Limit
        description: Specifies the number of Rules that you want AWS WAF to return
          for this request
        type: string
      - in: query
        name: NextMarker
        description: If you specify a value for Limit and you have more Rules than
          the value of Limit, AWS WAF returns a NextMarker value in the response that
          allows you to list another group of Rules
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
  /?Action=UpdateRule:
    get:
      summary: Update Rule
      description: 'Service: AWS WAFInserts or deletes.'
      operationId: updateRule
      x-api-path-slug: actionupdaterule-get
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: RuleId
        description: The RuleId of the Rule that you want to update
        type: string
      - in: query
        name: Updates
        description: An array of RuleUpdate objects that you want to insert into or
          delete from a Rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rules
---