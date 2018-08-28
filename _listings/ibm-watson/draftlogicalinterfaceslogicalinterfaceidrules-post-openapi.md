---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: IBM Watson IoT Platform Create a draft rule
  description: |-
    Creates a new draft rule that is associated with the logical interface
    for the organization in the Watson IoT Platform.
  version: 1.0.0
basePath: /api/v0002
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /logicalinterfaces/{logicalInterfaceId}/rules:
    get:
      summary: Query active rules
      description: |-
        Rules allow you to specify conditions that can be used to trigger
        actions. For example, you might create a rule that sends an email if
        the temperature of a device exceeds a certain value.

        Rules are defined against a specific logical interface schema.  At
        runtime, a rule will be evaluated whenever the state for a Device that
        exposes the logical interface changes.

        The **/logicalinterfaces/{logicalInterfaceId}/rules** endpoint returns
        the list of all of the active rules that have been associated with the
        logical interface. Various query parameters can be used to filter, sort
        and page through the list of rules that are returned.
      operationId: rules-allow-you-to-specify-conditions-that-can-be-used-to-triggeractions-for-example-you-might-creat
      x-api-path-slug: logicalinterfaceslogicalinterfaceidrules-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Logical interfaces
      - LogicalInterfaceId
      - Rules
  /logicalinterfaces/{logicalInterfaceId}/rules/{ruleId}:
    get:
      summary: Get an active rule
      description: |-
        Retrieve the active rule with the specified id that has been associated
        with the specified logical interface.
      operationId: retrieve-the-active-rule-with-the-specified-id-that-has-been-associatedwith-the-specified-logical-in
      x-api-path-slug: logicalinterfaceslogicalinterfaceidrulesruleid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Logical interfaces
      - LogicalInterfaceId
      - Rules
      - RuleId
  /draft/logicalinterfaces/{logicalInterfaceId}/rules:
    get:
      summary: Query draft rules
      description: |-
        Rules allow you to specify conditions that can be used to trigger
        actions. For example, you might create a rule that sends an email if
        the temperature of a device exceeds a certain value.

        Rules are defined against a specific logical interface schema.  At
        runtime, a rule will be evaluated whenever the state for a Device that
        exposes the logical interface changes.

        The **/draft/logicalinterfaces/{logicalInterfaceId}/rules** endpoint
        returns the list of all of the draft rules that have been associated
        with the logical interface. Various query parameters can be used to
        filter, sort and page through the list of rules that are returned.
      operationId: rules-allow-you-to-specify-conditions-that-can-be-used-to-triggeractions-for-example-you-might-creat
      x-api-path-slug: draftlogicalinterfaceslogicalinterfaceidrules-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Logical interfaces
      - LogicalInterfaceId
      - Rules
    post:
      summary: Create a draft rule
      description: |-
        Creates a new draft rule that is associated with the logical interface
        for the organization in the Watson IoT Platform.
      operationId: creates-a-new-draft-rule-that-is-associated-with-the-logical-interfacefor-the-organization-in-the-wa
      x-api-path-slug: draftlogicalinterfaceslogicalinterfaceidrules-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Rule
        description: The JSON representation of the draft rule
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Logical interfaces
      - LogicalInterfaceId
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