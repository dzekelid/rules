swagger: "2.0"
x-collection-name: Firebase
x-complete: 1
info:
  title: Firebase
  description: you-can-use-any-firebase-database-url-as-a-rest-endpoint--all-you-need-to-do-is-append--json-to-the-end-of-the-url-and-send-a-request-from-your-favorite-https-client-
  version: 1.0.0
host: '{project_id].firebaseio.co}'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}/rulesets:
    get:
      summary: List Rules
      description: |-
        List `Ruleset` metadata only and optionally filter the results by Ruleset
        name.

        The full `Source` contents of a `Ruleset` may be retrieved with
        GetRuleset.
      operationId: firebaserules.projects.rulesets.list
      x-api-path-slug: v1namerulesets-get
      parameters:
      - in: path
        name: name
        description: Resource name for the project
      - in: query
        name: pageSize
        description: Page size to load
      - in: query
        name: pageToken
        description: Next page token for loading the next batch of `Ruleset` instances
      responses:
        200:
          description: OK
      tags:
      - Rules
    post:
      summary: Create Rules
      description: |-
        Create a `Ruleset` from `Source`.

        The `Ruleset` is given a unique generated name which is returned to the
        caller. `Source` containing syntactic or semantics errors will result in an
        error response indicating the first error encountered. For a detailed view
        of `Source` issues, use TestRuleset.
      operationId: firebaserules.projects.rulesets.create
      x-api-path-slug: v1namerulesets-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: Resource name for Project which owns this `Ruleset`
      responses:
        200:
          description: OK
      tags:
      - Rules
  /v1/{name}:test:
    post:
      summary: Test  Rule
      description: |-
        Test `Source` for syntactic and semantic correctness. Issues present in the
        rules, if any, will be returned to the caller with a description, severity,
        and source location.

        The test method will typically be executed with a developer provided
        `Source`, but if regression testing is desired, this method may be
        executed against a `Ruleset` resource name and the `Source` will be
        retrieved from the persisted `Ruleset`.

        The following is an example of `Source` that permits users to upload images
        to a bucket bearing their user id and matching the correct metadata:

        _*Example*_

            // Users are allowed to subscribe and unsubscribe to the blog.
            service firebase.storage {
              match /users/{userId}/images/{imageName} {
                  allow write: if userId == request.userId
                      && (imageName.endsWith('.png') || imageName.endsWith('.jpg'))
                      && resource.mimeType.startsWith('image/')
              }
            }
      operationId: firebaserules.projects.test
      x-api-path-slug: v1nametest-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: Name of the project
      responses:
        200:
          description: OK
      tags:
      - Rules