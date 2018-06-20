---
name: Azure Notification Hubs
x-slug: azure-notification-hubs
description: Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out
  push engine. With a single cross-platform API call, you can easily send targeted
  and personalized push notifications to any mobile platform from any cloud or on-premises
  backend.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Rules
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Notification Hubs API Namespaces List Authorization Rules
  x-api-slug: azure-notification-hubs-api
  description: Gets the authorization rules for a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/AuthorizationRules
  tags: Namespaces Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenameauthorizationrules-get-openapi.md
- name: Azure Notification Hubs API Notification Hubs List Authorization Rules
  x-api-slug: azure-notification-hubs-api
  description: Gets the authorization rules for a NotificationHub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.NotificationHubs/namespaces/{namespaceName}/notificationHubs/{notificationHubName}/AuthorizationRules
  tags: Notification Hubs Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-notificationhubsnamespacesnamespacenamenotificationhubsnotificationhubnameauthorizationrules-get-openapi.md
- name: Azure Notification Hubs API
  x-api-slug: azure-notification-hubs-api
  description: Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out
    push engine. With a single cross-platform API call, you can easily send targeted
    and personalized push notifications to any mobile platform from any cloud or on-premises
    backend.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-notification-hubs.png
  humanURL: https://docs.microsoft.com/en-us/azure/notification-hubs/
  baseURL: ://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-notification-hubs/openapi.md
x-common:
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