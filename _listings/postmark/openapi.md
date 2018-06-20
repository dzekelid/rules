---
swagger: "2.0"
x-collection-name: Postmark
x-complete: 1
info:
  title: Postmark
  description: send-emails-retrieve-bounces-and-start-accepting-inbound-emails-all-via-an-easytouse-http-api-
  version: 1.0.0
host: spamcheck.postmarkapp.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /triggers/inboundrules:
    get:
      summary: Get Triggers Inboundrules
      description: Get triggers inboundrules.
      operationId: getTriggersInboundrules
      x-api-path-slug: triggersinboundrules-get
      parameters:
      - in: query
        name: count
        description: Number of records to return per request
      - in: query
        name: offset
        description: Number of records to skip
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Triggers
      - Inboundrules
    post:
      summary: Post Triggers Inboundrules
      description: Post triggers inboundrules.
      operationId: postTriggersInboundrules
      x-api-path-slug: triggersinboundrules-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Triggers
      - Inboundrules
  /triggers/inboundrules/{triggerid}:
    delete:
      summary: Delete Triggers Inboundrules Trigger
      description: Delete triggers inboundrules trigger.
      operationId: deleteTriggersInboundrulesTrigger
      x-api-path-slug: triggersinboundrulestriggerid-delete
      parameters:
      - in: path
        name: triggerid
        description: The ID of the Inbound Rule that should be deleted
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Triggers
      - Inboundrules
      - Triggerid
---