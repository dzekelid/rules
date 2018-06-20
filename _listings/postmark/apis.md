---
name: Postmark
x-slug: postmark
description: Trusted by thousands of developers, Postmark is a fast and reliable transactional
  email service. Send with Postmark to ensure your transactional emails get to the
  inbox on time, every time.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
x-kinRank: "8"
x-alexaRank: "92150"
tags: Rules
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/postmark/apis.md
specificationVersion: "0.14"
apis:
- name: Postmark Get Triggers Inboundrules
  x-api-slug: postmark
  description: Get triggers inboundrules.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////triggers/inboundrules
  tags: Triggers,Inboundrules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/postmark/triggersinboundrules-get-openapi.md
- name: Postmark Post Triggers Inboundrules
  x-api-slug: postmark
  description: Post triggers inboundrules.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////triggers/inboundrules
  tags: Triggers,Inboundrules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/postmark/triggersinboundrules-post-openapi.md
- name: Postmark Delete Triggers Inboundrules Trigger
  x-api-slug: postmark
  description: Delete triggers inboundrules trigger.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////triggers/inboundrules/{triggerid}
  tags: Triggers,Inboundrules,Triggerid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/postmark/triggersinboundrulestriggerid-delete-openapi.md
- name: Postmark
  x-api-slug: postmark
  description: Postmark helps deliver and track transactional emails for web applications.
    In a nutshell, the service replaces SMTP (or Sendmail) with a far more reliable,
    scalable and care-free environment. In addition, you can track statistics for
    number of emails sent, bounces and spam complaints.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/postmark/openapi.md
x-common:
- type: x--net-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#dot-net
- type: x-base
  url: https://api.postmarkapp.com
- type: x-blog
  url: http://blog.postmarkapp.com/
- type: x-blog-rss
  url: http://blog.postmarkapp.com/rss
- type: x-contact-form
  url: http://support.postmarkapp.com/customer/portal/emails/new
- type: x-crunchbase
  url: https://crunchbase.com/organization/postmark
- type: x-crunchbase
  url: http://www.crunchbase.com/company/postmark
- type: x-developer
  url: http://developer.postmarkapp.com/
- type: x-email
  url: support@postmarkapp.com
- type: x-email
  url: 451d9b70cf9364d23ff6f9d51d870251569e+ahoy@inbound.postmarkapp.com
- type: x-faq
  url: http://support.postmarkapp.com/
- type: x-pricing
  url: http://developer.postmarkapp.com/developer-api-messages.html
- type: x-privacy
  url: https://postmarkapp.com/privacy-policy
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#rails
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#ruby
- type: x-selfservice-registration
  url: https://postmarkapp.com/sign_up
- type: x-status
  url: http://status.postmarkapp.com/
- type: x-terms-of-service
  url: https://postmarkapp.com/terms-of-service
- type: x-twitter
  url: https://twitter.com/postmarkapp
- type: x-website
  url: http://postmarkapp.com
- type: x-website
  url: http://postmarkapp.com/
- type: x-wordpress-pdk
  url: http://developer.postmarkapp.com/developer-official-libs.html#wordpress
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---