---
swagger: "2.0"
x-collection-name: CloudFlare
x-complete: 0
info:
  title: CloudFlare Update rule state and/or configuration
  version: 1.0.0
  description: Update rule state and/or configuration
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
    post:
      summary: Make a new IP, IP range, or country access rule for all zones owned
        by the organization
      description: Make a new IP, IP range, or country access rule for all zones owned
        by the organization
      operationId: cloudflare-organizationlevel-firewall-access-rule-api
      x-api-path-slug: organizationsorganization-idfirewallaccess-rulesrules-post
      parameters:
      - in: query
        name: configuration
        description: Rule configurationtttttttttttttttttttttOne of the following:tttttttttttttttttttttttttttttShow
          definition &raquo;ttttttttttttttttttttttttttttttttttttttName /typetttttttttttDescription
          /exampletttttttttttConstraintstttttttttttttttttttttttttttttttttttttttttttttttttttttttttargettttttttttttttstring
      - in: query
        name: mode
        description: The action to apply to a matched requestttttttttttttttchallenge
      - in: query
        name: value
        description: The IP address to target in requeststtttttttttttttttttttttttttttttttttt1
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
  /organizations/:organization_id/firewall/access_rules/rules/:identifier:
    delete:
      summary: Remove an access rule so it is no longer evaluated during requests
      description: Remove an access rule so it is no longer evaluated during requests
      operationId: cloudflare-organizationlevel-firewall-access-rule-api
      x-api-path-slug: organizationsorganization-idfirewallaccess-rulesrulesidentifier-delete
      responses:
        200:
          description: OK
      tags:
      - Organization Firewall Access Rules
    patch:
      summary: Update rule state and/or configuration
      description: Update rule state and/or configuration
      operationId: cloudflare-organizationlevel-firewall-access-rule-api
      x-api-path-slug: organizationsorganization-idfirewallaccess-rulesrulesidentifier-patch
      parameters:
      - in: query
        name: configuration
        description: Rule configurationtttttttttttttttttttttOne of the following:tttttttttttttttttttttttttttttShow
          definition &raquo;ttttttttttttttttttttttttttttttttttttttName /typetttttttttttDescription
          /exampletttttttttttConstraintstttttttttttttttttttttttttttttttttttttttttttttttttttttttttargettttttttttttttstring
      - in: query
        name: mode
        description: The action to apply to a matched requestttttttttttttttchallenge
      - in: query
        name: value
        description: The IP address to target in requeststtttttttttttttttttttttttttttttttttt1
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