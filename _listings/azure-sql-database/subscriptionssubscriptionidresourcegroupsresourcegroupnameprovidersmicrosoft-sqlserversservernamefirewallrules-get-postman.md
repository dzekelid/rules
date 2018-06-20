{
  "info": {
    "name": "Azure SQL Database API Firewall Rules List By Server",
    "_postman_id": "20b12291-bd40-4615-8914-c3456b8a3753",
    "description": "Returns a list of firewall rules.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "firewall rules server",
      "item": [
        {
          "id": "f420a1f7-514f-4c54-8c04-3916f11660c0",
          "name": "FirewallRules_ListByServer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Sql/servers/:serverName/firewallRules"
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
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "serverName",
                  "value": "serverName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of firewall rules"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0aa8fee-a37a-4e0b-afe1-0f5dbecc1ff1"
            }
          ]
        }
      ]
    }
  ]
}