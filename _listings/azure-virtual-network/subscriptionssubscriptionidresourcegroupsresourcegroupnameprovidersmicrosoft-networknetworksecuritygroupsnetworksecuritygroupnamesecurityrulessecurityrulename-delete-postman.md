{
  "info": {
    "name": "Azure Virtual Network API Security Rules Delete",
    "_postman_id": "b36a089c-ecf0-472e-8169-4a611eaf980d",
    "description": "Deletes the specified network security rule.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "security rules",
      "item": [
        {
          "id": "c4185d28-bc0c-4f24-ace1-497e26d81d56",
          "name": "SecurityRules_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified network security rule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be82c727-e00c-4426-b1de-3a8f7848af92"
            }
          ]
        }
      ]
    }
  ]
}