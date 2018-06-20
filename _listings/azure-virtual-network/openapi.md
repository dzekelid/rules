---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 1
info:
  title: NetworkManagementClient
  description: the-microsoft-azure-network-management-api-provides-a-restful-set-of-web-services-that-interact-with-microsoft-azure-networks-service-to-manage-your-network-resources--the-api-has-entities-that-capture-the-relationship-between-an-end-user-and-the-microsoft-azure-networks-service-
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules/{securityRuleName}
  : delete:
      summary: Security Rules Delete
      description: Deletes the specified network security rule.
      operationId: SecurityRules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-delete
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: securityRuleName
        description: The name of the security rule
      responses:
        200:
          description: OK
      tags:
      - Security Rules
    get:
      summary: Security Rules Get
      description: Get the specified network security rule.
      operationId: SecurityRules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-get
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: securityRuleName
        description: The name of the security rule
      responses:
        200:
          description: OK
      tags:
      - Security Rules
    put:
      summary: Security Rules Create Or Update
      description: Creates or updates a security rule in the specified network security
        group.
      operationId: SecurityRules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-put
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: securityRuleName
        description: The name of the security rule
      - in: body
        name: securityRuleParameters
        description: Parameters supplied to the create or update network security
          rule operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Security Rules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules
  : get:
      summary: Security Rules List
      description: Gets all security rules in a network security group.
      operationId: SecurityRules_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrules-get
      parameters:
      - in: path
        name: networkSecurityGroupName
        description: The name of the network security group
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Security Rules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  : delete:
      summary: Route Filter Rules Delete
      description: Deletes the specified rule from a route filter.
      operationId: RouteFilterRules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: path
        name: ruleName
        description: The name of the rule
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
    get:
      summary: Route Filter Rules Get
      description: Gets the specified rule from a route filter.
      operationId: RouteFilterRules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: path
        name: ruleName
        description: The name of the rule
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
    put:
      summary: Route Filter Rules Create Or Update
      description: Creates or updates a route in the specified route filter.
      operationId: RouteFilterRules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: body
        name: routeFilterRuleParameters
        description: Parameters supplied to the create or update route filter rule
          operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: ruleName
        description: The name of the route filter rule
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
    patch:
      summary: Route Filter Rules Update
      description: Updates a route in the specified route filter.
      operationId: RouteFilterRules_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-patch
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      - in: body
        name: routeFilterRuleParameters
        description: Parameters supplied to the update route filter rule operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: ruleName
        description: The name of the route filter rule
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules
  : get:
      summary: Route Filter Rules List By Route Filter
      description: Gets all RouteFilterRules in a route filter.
      operationId: RouteFilterRules_ListByRouteFilter
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrules-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: routeFilterName
        description: The name of the route filter
      responses:
        200:
          description: OK
      tags:
      - Route Filter Rules
---