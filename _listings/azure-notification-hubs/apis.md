---
name: Azure Notification Hubs
description: Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out
  push engine. With a single cross-platform API call, you can easily send targeted
  and personalized push notifications to any mobile platform from any cloud or on-premises
  backend.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Notifications
- Microsoft
created: "2018-03-24"
modified: "2018-03-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure Notification Hubs API
  description: Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out
    push engine
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-notificationhubs-namespaces-namespacename-notificationhubs-notificationhubname-authorizationrules-get.md
- name: Azure Notification Hubs API Notification Hubs List Authorization Rules
  description: Gets the authorization rules for a NotificationHub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: http:://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-notificationhubs-namespaces-namespacename-notificationhubs-notificationhubname-authorizationrules-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-notificationhubs-namespaces-namespacename-notificationhubs-notificationhubname-authorizationrules-get-postman.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/rest/api/notificationhubs
- type: x-website
  url: https://docs.microsoft.com/en-us/azure/notification-hubs/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/rest/api/notificationhubs
- type: x-website
  url: https://docs.microsoft.com/en-us/azure/notification-hubs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---