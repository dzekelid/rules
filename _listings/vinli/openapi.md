swagger: "2.0"
x-collection-name: Vinli
x-complete: 1
info:
  title: Vinli
  description: todo-add-description
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rules/b7ad3604-c795-46af-9d5f-71be30ed4143:
    get:
      summary: Get a Specific Rule
      description: Get a specific rule.
      operationId: RulesB7ad3604C79546af9d5f71be30ed4143Get
      x-api-path-slug: rulesb7ad3604c79546af9d5f71be30ed4143-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Specific
      - Rule
  /rules/68d489c0-d7a2-11e3-9c1a-0800200c9a66:
    delete:
      summary: Delete a Rule
      description: Delete a rule.
      operationId: Rules68d489c0D7a211e39c1a0800200c9a66Delete
      x-api-path-slug: rules68d489c0d7a211e39c1a0800200c9a66-delete
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Rule