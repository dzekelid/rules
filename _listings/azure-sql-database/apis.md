---
name: Azure SQL Database
x-slug: azure-sql-database
description: Make building and maintaining applications easier and more productive.
  With built-in intelligence that learns app patterns and adapts to maximize performance,
  reliability, and data protection, SQL Database is a cloud database built for developers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Rules
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/apis.md
specificationVersion: "0.14"
apis:
- name: Azure SQL Database API Firewall Rules Create Or Update
  x-api-slug: azure-sql-database-api
  description: Creates or updates a firewall rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/firewallRules/{firewallRuleName}
  tags: Firewall Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamefirewallrulesfirewallrulename-put-openapi.md
- name: Azure SQL Database API Firewall Rules Delete
  x-api-slug: azure-sql-database-api
  description: Deletes a firewall rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/firewallRules/{firewallRuleName}
  tags: Firewall Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamefirewallrulesfirewallrulename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamefirewallrulesfirewallrulename-delete-openapi.md
- name: Azure SQL Database API Firewall Rules Get
  x-api-slug: azure-sql-database-api
  description: Gets a firewall rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/firewallRules/{firewallRuleName}
  tags: Firewall Rules
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamefirewallrulesfirewallrulename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamefirewallrulesfirewallrulename-get-openapi.md
- name: Azure SQL Database API Firewall Rules List By Server
  x-api-slug: azure-sql-database-api
  description: Returns a list of firewall rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/firewallRules
  tags: Firewall Rules Server
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamefirewallrules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamefirewallrules-get-openapi.md
- name: Azure SQL Database API
  x-api-slug: azure-sql-database-api
  description: Make building and maintaining applications easier and more productive.
    With built-in intelligence that learns app patterns and adapts to maximize performance,
    reliability, and data protection, SQL Database is a cloud database built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/azure-sql-database/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/sql-database/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/sql-database/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/sql-database/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/sql-database/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---