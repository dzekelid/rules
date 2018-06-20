---
name: Azure Event Hubs
x-slug: azure-event-hubs
description: Azure Event Hubs is a hyper-scale telemetry ingestion service that collects,
  transforms, and stores millions of events. As a distributed streaming platform,
  it gives you low latency and configurable time retention, which enables you to ingress
  massive amounts of telemetry into the cloud and read the data from multiple applications
  using publish-subscribe semantics.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-event-hubs-stream.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Rules
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-event-hubs/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Event Hubs API Namespaces List Authorization Rules
  x-api-slug: azure-event-hubs-api
  description: Gets a list of authorization rules for a Namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-event-hubs-stream.png
  humanURL: https://azure.microsoft.com/en-us/services/event-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventHub/namespaces/{namespaceName}/AuthorizationRules
  tags: Namespaces Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameauthorizationrules-get-openapi.md
- name: Azure Event Hubs API Event Hubs List Authorization Rules
  x-api-slug: azure-event-hubs-api
  description: Gets the authorization rules for an Event Hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-event-hubs-stream.png
  humanURL: https://azure.microsoft.com/en-us/services/event-hubs/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventHub/namespaces/{namespaceName}/eventhubs/{eventHubName}/authorizationRules
  tags: Event Hubs Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameeventhubseventhubnameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-event-hubs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-eventhubnamespacesnamespacenameeventhubseventhubnameauthorizationrules-get-openapi.md
- name: Azure Event Hubs API
  x-api-slug: azure-event-hubs-api
  description: Azure Event Hubs is a hyper-scale telemetry ingestion service that
    collects, transforms, and stores millions of events. As a distributed streaming
    platform, it gives you low latency and configurable time retention, which enables
    you to ingress massive amounts of telemetry into the cloud and read the data from
    multiple applications using publish-subscribe semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-event-hubs-stream.png
  humanURL: https://azure.microsoft.com/en-us/services/event-hubs/
  baseURL: ://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-event-hubs/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/event-hubs/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/event-hubs/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/event-hubs/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/event-hubs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---