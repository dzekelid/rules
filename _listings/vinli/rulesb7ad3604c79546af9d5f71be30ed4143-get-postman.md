{
  "info": {
    "name": "Vinli Get a Specific Rule",
    "_postman_id": "4fe5859c-b0f7-47a6-89db-2ba7ec2ed390",
    "description": "Get a specific rule.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Eventsa",
      "item": [
        {
          "id": "01ad7bb1-b366-47bc-8fe3-d371de170d73",
          "name": "Devices62976d30B6dc40f18422Ccc367572101EventsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/devices/62976d30-b6dc-40f1-8422-ccc367572101/events",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get all events for a device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cdf5c1b0-2e44-41ac-8b84-1cabb470a30f"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "888c38a9-5dfb-4247-9e2a-8b60082d0812",
          "name": "DevicesCf217c2dDf3c41f7B6108bc3e11b4b79VehiclesGet",
          "request": {
            "url": "http://events.vin.li/api/v1/devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/vehicles",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List a device's vehicles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e9f8e83-4253-4c25-98e5-99e9734f745c"
            }
          ]
        }
      ]
    },
    {
      "name": "Specific",
      "item": [
        {
          "id": "10545951-50c9-4a88-94fd-58325acf187d",
          "name": "RulesB7ad3604C79546af9d5f71be30ed4143Get",
          "request": {
            "url": "http://events.vin.li/api/v1/rules/b7ad3604-c795-46af-9d5f-71be30ed4143",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a specific rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ec992c9-8608-4c2d-9a9e-fdbf797f7322"
            }
          ]
        }
      ]
    }
  ]
}