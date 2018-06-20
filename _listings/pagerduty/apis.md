---
name: PagerDuty
x-slug: pagerduty
description: See how PagerDuty Digital Operations Management Platform integrates machine
  data & human intelligence to improve visibility & agility across organizations.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
x-kinRank: "8"
x-alexaRank: "19574"
tags: Rules
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/pagerduty/apis.md
specificationVersion: "0.14"
apis:
- name: PagerDuty List a user's notification rules
  x-api-slug: pagerduty
  description: List notification rules of your PagerDuty user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/pagerduty/usersidnotification-rules-get-openapi.md
- name: PagerDuty Create a user notification rule
  x-api-slug: pagerduty
  description: Create a new notification rule.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/pagerduty/usersidnotification-rules-post-openapi.md
- name: PagerDuty Get a user's notification rule
  x-api-slug: pagerduty
  description: Get users  notification rules notification rule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules/{notification_rule_id}
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/pagerduty/usersidnotification-rulesnotification-rule-id-get-openapi.md
- name: PagerDuty Delete a user's notification rule
  x-api-slug: pagerduty
  description: Delete users  notification rules notification rule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules/{notification_rule_id}
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/pagerduty/usersidnotification-rulesnotification-rule-id-delete-openapi.md
- name: PagerDuty Update a user's notification rule
  x-api-slug: pagerduty
  description: Put users  notification rules notification rule
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https://///users/{id}/notification_rules/{notification_rule_id}
  tags: User Notification Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/pagerduty/usersidnotification-rulesnotification-rule-id-put-openapi.md
- name: PagerDuty
  x-api-slug: pagerduty
  description: See how PagerDuty Digital Operations Management Platform integrates
    machine data & human intelligence to improve visibility & agility across organizations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/632-pagerduty.jpg
  humanURL: http://www.pagerduty.com
  baseURL: https:///
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/pagerduty/openapi.md
x-common:
- type: x-base
  url: https://acme.pagerduty.com/api/
- type: x-blog
  url: http://blog.pagerduty.com/
- type: x-blog-rss
  url: http://blog.pagerduty.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/pagerduty
- type: x-crunchbase
  url: https://crunchbase.com/organization/pagerduty
- type: x-developer
  url: http://developer.pagerduty.com/
- type: x-email
  url: info@pagerduty.com
- type: x-email
  url: sales@pagerduty.com
- type: x-email
  url: support@pagerduty.com
- type: x-email
  url: legal@pagerduty.com
- type: x-github
  url: https://github.com/PagerDuty
- type: x-openapi-spec--authoritative
  url: https://api-reference.pagerduty.com/output.json
- type: x-pricing
  url: https://www.pagerduty.com/pricing/
- type: x-twitter
  url: https://twitter.com/pagerduty
- type: x-website
  url: http://www.pagerduty.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---