{
  "info": {
    "name": "Azure Virtual Network API Security Rules List",
    "_postman_id": "472737d7-ce69-4ad3-aa59-07c296d18684",
    "description": "Gets all security rules in a network security group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "security rules",
      "item": [
        {
          "id": "71a9a40c-442e-4037-b700-dd78b178292b",
          "name": "SecurityRules_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Network/networkSecurityGroups/:networkSecurityGroupName/securityRules"
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
            "description": "Gets all security rules in a network security group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b03b9264-98b4-405b-92b6-05e20012c7b6"
            }
          ]
        }
      ]
    }
  ]
}