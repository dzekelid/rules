---
name: AWS WAF
description: AWS WAF is a web application firewall that helps protect your webnbsp;applications
  from common web exploits that could affect applicationnbsp;availability, compromise
  security, or consume excessive resources. AWSnbsp;WAF gives you control over which
  traffic to allow or block to your webnbsp;applications by defining customizable
  web security rules. You can use AWSnbsp;WAF to create custom rules that block common
  attack patterns, such as SQLnbsp;injection or cross-site scripting, and rules that
  are designed for your specific application. New rules can be deployed within minutes,
  letting you respondnbsp;quickly to changing traffic patterns. Also, AWS WAF includes
  a full-featurednbsp;API that you can use to automate the creation, deployment, and
  maintenancenbsp;of web security rules.nWith AWS WAF you pay only for what you use.
  AWS WAF pricing is based on how many rules you deploy and how many web requests
  your web application receives. There are no upfront commitments.nYou can deploy
  AWS WAF on either Amazon CloudFront as part of your CDN solution or the Application
  Load Balancer (ALB) that fronts your web servers or origin servers running on EC2.nbsp;
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Security
- Firewall
- Amazon Web Services
created: "2018-03-13"
modified: "2018-03-13"
url: https://raw.githubusercontent.com/streamdata-gallery/rules/master/_listings/aws-waf/apis.yaml
specificationVersion: "0.14"
apis:
- name: AWS WAF API
  description: AWS WAF is a web application firewall that helps protect your webnbsp;applications
    from common web exploits that could affect applicationnbsp;availability, compromise
    security, or consume excessive resources
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSWAF.png
  humanURL: ""
  baseURL: :///
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery/rules/master/_listings/aws-waf/action-listrules-get.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/waf/latest/APIReference/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/waf/faq/
- type: x-getting-started
  url: https://aws.amazon.com/waf/getting-started/
- type: x-partners
  url: https://aws.amazon.com/waf/partners/
- type: x-pricing
  url: https://aws.amazon.com/waf/pricing/
- type: x-tutorials
  url: https://aws.amazon.com/waf/preconfiguredrules/
- type: x-webinars
  url: https://aws.amazon.com/waf/webinars/
- type: x-website
  url: https://aws.amazon.com/waf/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---