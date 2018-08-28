{
  "info": {
    "name": "Azure Virtual Network API Security Rules Get",
    "_postman_id": "a07ce0ef-017a-4811-88fd-155fb38372c1",
    "description": "Get the specified network security rule.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "security rules",
      "item": [
        {
          "id": "b6238efd-a9c4-44bf-a83a-86e70ad82322",
          "name": "SecurityRules_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/networkSecurityGroups/:networkSecurityGroupName/securityRules/:securityRuleName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "networkSecurityGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "securityRuleName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the specified network security rule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7bfff333-2040-4692-8060-53d01cc12564"
            }
          ]
        }
      ]
    }
  ]
}