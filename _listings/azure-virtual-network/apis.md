---
name: Azure Virtual Network
x-slug: azure-virtual-network
description: Azure Virtual Network lets you create private networks in the cloud with
  full control over IP addresses, DNS servers, security rules, and traffic flows.
  Securely connect a virtual network to on-premises networks by using a VPN tunnel,
  or connect privately by using the ExpressRoute service.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Rules
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Virtual Network API Security Rules Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified network security rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules/{securityRuleName}
  tags: Security Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-delete-openapi.md
- name: Azure Virtual Network API Security Rules Get
  x-api-slug: azure-virtual-network-api
  description: Get the specified network security rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules/{securityRuleName}
  tags: Security Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-get-openapi.md
- name: Azure Virtual Network API Security Rules Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a security rule in the specified network security
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules/{securityRuleName}
  tags: Security Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrulessecurityrulename-put-openapi.md
- name: Azure Virtual Network API Security Rules List
  x-api-slug: azure-virtual-network-api
  description: Gets all security rules in a network security group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups/{networkSecurityGroupName}/securityRules
  tags: Security Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networknetworksecuritygroupsnetworksecuritygroupnamesecurityrules-get-openapi.md
- name: Azure Virtual Network API Route Filter Rules Delete
  x-api-slug: azure-virtual-network-api
  description: Deletes the specified rule from a route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  tags: Route Filter Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-delete-openapi.md
- name: Azure Virtual Network API Route Filter Rules Get
  x-api-slug: azure-virtual-network-api
  description: Gets the specified rule from a route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  tags: Route Filter Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-get-openapi.md
- name: Azure Virtual Network API Route Filter Rules Create Or Update
  x-api-slug: azure-virtual-network-api
  description: Creates or updates a route in the specified route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  tags: Route Filter Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-put-openapi.md
- name: Azure Virtual Network API Route Filter Rules Update
  x-api-slug: azure-virtual-network-api
  description: Updates a route in the specified route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules/{ruleName}
  tags: Route Filter Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrulesrulename-patch-openapi.md
- name: Azure Virtual Network API Route Filter Rules List By Route Filter
  x-api-slug: azure-virtual-network-api
  description: Gets all RouteFilterRules in a route filter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/routeFilters/{routeFilterName}/routeFilterRules
  tags: Route Filter Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-networkroutefiltersroutefilternameroutefilterrules-get-openapi.md
- name: Azure Virtual Network API
  x-api-slug: azure-virtual-network-api
  description: Azure Virtual Network lets you create private networks in the cloud
    with full control over IP addresses, DNS servers, security rules, and traffic
    flows. Securely connect a virtual network to on-premises networks by using a VPN
    tunnel, or connect privately by using the ExpressRoute service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-network-topology.png
  humanURL: https://azure.microsoft.com/en-us/services/virtual-network/
  baseURL: ://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-virtual-network/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/virtual-network/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/virtual-network/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/virtual-network/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---