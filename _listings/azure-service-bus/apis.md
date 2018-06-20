---
name: Azure Service Bus
x-slug: azure-service-bus
description: Depend on Azure Service Bus when you need highly-reliable cloud messaging
  service between applications and services, even when one or more is offline. Available
  in every Azure region, this fully-managed service eliminates the burdens of server
  management and licensing. Asynchronous operations give you flexible, brokered messaging
  between client and server, along with structured first-in, first-out (FIFO) messaging,
  and publish/subscribe capabilities&mdash;excellent for tasks like order processing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Rules
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-service-bus/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Service Bus API Namespaces List Authorization Rules
  x-api-slug: azure-service-bus-api
  description: Gets the authorization rules for a namespace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/AuthorizationRules
  tags: Namespaces Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrules-get-openapi.md
- name: Azure Service Bus API Queues List Authorization Rules
  x-api-slug: azure-service-bus-api
  description: Gets all authorization rules for a queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}/authorizationRules
  tags: Queues Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrules-get-openapi.md
- name: Azure Service Bus API Topics List Authorization Rules
  x-api-slug: azure-service-bus-api
  description: Gets authorization rules for a topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/authorizationRules
  tags: Topics Authorization Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-service-bus/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrules-get-openapi.md
- name: Azure Service Bus API
  x-api-slug: azure-service-bus-api
  description: Depend on Azure Service Bus when you need highly-reliable cloud messaging
    service between applications and services, even when one or more is offline. Available
    in every Azure region, this fully-managed service eliminates the burdens of server
    management and licensing. Asynchronous operations give you flexible, brokered
    messaging between client and server, along with structured first-in, first-out
    (FIFO) messaging, and publish/subscribe capabilities&mdash;excellent for tasks
    like order processing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: ://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-service-bus/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-bus/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/service-bus/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/service-bus/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/service-bus/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---