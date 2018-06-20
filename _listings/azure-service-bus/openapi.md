---
swagger: "2.0"
x-collection-name: Azure Service Bus
x-complete: 1
info:
  title: ServiceBusManagementClient
  description: azure-service-bus-client
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/AuthorizationRules
  : get:
      summary: Namespaces List Authorization Rules
      description: Gets the authorization rules for a namespace.
      operationId: Namespaces_ListAuthorizationRules
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenameauthorizationrules-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Namespaces Authorization Rules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/queues/{queueName}/authorizationRules
  : get:
      summary: Queues List Authorization Rules
      description: Gets all authorization rules for a queue.
      operationId: Queues_ListAuthorizationRules
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenamequeuesqueuenameauthorizationrules-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Queues Authorization Rules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ServiceBus/namespaces/{namespaceName}/topics/{topicName}/authorizationRules
  : get:
      summary: Topics List Authorization Rules
      description: Gets authorization rules for a topic.
      operationId: Topics_ListAuthorizationRules
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-servicebusnamespacesnamespacenametopicstopicnameauthorizationrules-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Topics Authorization Rules
---