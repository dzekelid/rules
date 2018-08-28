---
name: AWS Config
x-slug: aws-config
description: AWS Config is a fully managed service that provides you with an AWS resource
  inventory, configuration history, and configuration change notifications to enable
  security and governance. Config Rules enables you to create rules that automatically
  check the configuration of AWS resources recorded by AWS Config.With AWS Config,
  you can discover existing and deleted AWS resources, determine your overall compliance
  against rules, and dive into configuration details of a resource at any point in
  time. These capabilities enable compliance auditing, security analysis, resource
  change tracking, and troubleshooting.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Rules
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Config API - Describe Config Rules
  x-api-slug: actiondescribeconfigrules-get
  description: Returns details about your AWS Config rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actiondescribeconfigrules-get-openapi.md
- name: AWS Config API - Start Config Rules Evaluation
  x-api-slug: actionstartconfigrulesevaluation-get
  description: Runs an on-demand evaluation for the specified Config rules against
    the last known configuration state of the resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actionstartconfigrulesevaluation-get-openapi.md
- name: AWS Config API - Delete Config Rule
  x-api-slug: actiondeleteconfigrule-get
  description: Deletes the specified AWS Config rule and all of its evaluation results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actiondeleteconfigrule-get-openapi.md
- name: AWS Config API - Describe Compliance By Config Rule
  x-api-slug: actiondescribecompliancebyconfigrule-get
  description: Indicates whether the specified AWS Config rules are compliant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actiondescribecompliancebyconfigrule-get-openapi.md
- name: AWS Config API - Describe Config Rule Evaluation Status
  x-api-slug: actiondescribeconfigruleevaluationstatus-get
  description: Returns status information for each of your AWS managed Config rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actiondescribeconfigruleevaluationstatus-get-openapi.md
- name: AWS Config API - Describe Config Rules
  x-api-slug: actiondescribeconfigrules-get
  description: Returns details about your AWS Config rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actiondescribeconfigrules-get-openapi.md
- name: AWS Config API - Get Compliance Details By Config Rule
  x-api-slug: actiongetcompliancedetailsbyconfigrule-get
  description: Returns the evaluation results for the specified AWS Config rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actiongetcompliancedetailsbyconfigrule-get-openapi.md
- name: AWS Config API - Get Compliance Summary By Config Rule
  x-api-slug: actiongetcompliancesummarybyconfigrule-get
  description: "Returns the number of AWS Config rules that are compliant and noncompliant,
    up to a\n\t\t\tmaximum of 25 for each."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actiongetcompliancesummarybyconfigrule-get-openapi.md
- name: AWS Config API - Put Config Rule
  x-api-slug: actionputconfigrule-get
  description: "Adds or updates an AWS Config rule for evaluating whether your AWS
    resources comply\n\t\t\twith your desired configurations."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actionputconfigrule-get-openapi.md
- name: AWS Config API - Start Config Rules Evaluation
  x-api-slug: actionstartconfigrulesevaluation-get
  description: Runs an on-demand evaluation for the specified Config rules against
    the last known configuration state of the resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/aws-config/actionstartconfigrulesevaluation-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.cognito.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.config.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/configservice/index.html
- type: x-console
  url: https://console.aws.amazon.com/config
- type: x-documentation
  url: http://docs.aws.amazon.com/config/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/config/faq/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=184
- type: x-getting-started
  url: https://aws.amazon.com/config/getting-started/
- type: x-partners
  url: https://aws.amazon.com/config/partners/
- type: x-pricing
  url: https://aws.amazon.com/config/pricing/
- type: x-support
  url: https://console.aws.amazon.com/support/
- type: x-website
  url: https://aws.amazon.com/config/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---