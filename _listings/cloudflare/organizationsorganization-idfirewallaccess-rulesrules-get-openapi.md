---
swagger: "2.0"
x-collection-name: CloudFlare
x-complete: 0
info:
  title: CloudFlare Search, sort, and filter IP/country access rules
  version: 1.0.0
  description: Search, sort, and filter IP/country access rules
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/:organization_id/firewall/access_rules/rules:
    get:
      summary: Search, sort, and filter IP/country access rules
      description: Search, sort, and filter IP/country access rules
      operationId: cloudflare-organizationlevel-firewall-access-rule-api
      x-api-path-slug: organizationsorganization-idfirewallaccess-rulesrules-get
      parameters:
      - in: query
        name: configuration_target
        description: The rule configuration targetttttttttttttttip
      - in: query
        name: configuration_value
        description: Search by IP, range, or country codetttttttttttttt1
      - in: query
        name: direction
        description: Direction to order rulesttttttttttttttdesc
      - in: query
        name: match
        description: Whether to match all search requirements or at least one (any)ttttttttttttttall
      - in: query
        name: mode
        description: The action to apply to a matched requestttttttttttttttchallenge
      - in: query
        name: order
        description: Field to order rules byttttttttttttttmode
      - in: query
        name: page
        description: Page number of paginated resultstttttttttttttt1
      - in: query
        name: per_page
        description: Number of rules per pagetttttttttttttt50
      - in: header
        name: X-AUTH-EMAIL
        description: Email address associated with your account
      - in: header
        name: X-AUTH-KEY
        description: API key generated on the My Account page
      responses:
        200:
          description: OK
      tags:
      - Organization Firewall Access Rules
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