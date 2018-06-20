---
swagger: "2.0"
x-collection-name: AWS Config
x-complete: 1
info:
  title: AWS Config API
  version: 1.0.0
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
  /?Action=DescribeConfigRules:
    get:
      summary: Describe Config Rules
      description: Returns details about your AWS Config rules.
      operationId: describeConfigRules
      x-api-path-slug: actiondescribeconfigrules-get
      parameters:
      - in: query
        name: ConfigRuleNames
        description: The names of the AWS Config rules for which you want details
        type: string
      - in: query
        name: NextToken
        description: The nextToken string returned on a previous page thatyou use
          to get the next page of results in a paginated response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Rules
  /?Action=DescribeConfigurationRecorders:
    get:
      summary: Describe Configuration Recorders
      description: Returns the details for the specified configuration recorders.
      operationId: describeConfigurationRecorders
      x-api-path-slug: actiondescribeconfigurationrecorders-get
      parameters:
      - in: query
        name: ConfigurationRecorderNames
        description: A list of configuration recorder names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Rules
  /?Action=DescribeConfigurationRecorderStatus:
    get:
      summary: Describe Configuration Recorder Status
      description: Returns the current status of the specified configuration recorder.
      operationId: describeConfigurationRecorderStatus
      x-api-path-slug: actiondescribeconfigurationrecorderstatus-get
      parameters:
      - in: query
        name: ConfigurationRecorderNames
        description: The name(s) of the configuration recorder
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Rules
  /?Action=PutConfigRule:
    get:
      summary: Put Config Rule
      description: "Adds or updates an AWS Config rule for evaluating whether your
        AWS resources comply\n\t\t\twith your desired configurations."
      operationId: putConfigRule
      x-api-path-slug: actionputconfigrule-get
      parameters:
      - in: query
        name: ConfigRule
        description: An AWS Config rule represents an AWS Lambda function that you
          create for a custom rule or a predefined function for an AWS managed rule
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Rules
---