{
  "info": {
    "name": "AWS Simple Email Service API Clone Receipt Rule Set",
    "_postman_id": "b431d172-0360-49c5-9000-9533ed209128",
    "description": "Creates a receipt rule set by cloning an existing one.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Receipt Rule Sets",
      "item": [
        {
          "id": "c57ca48d-58dc-412d-83d2-004856431860",
          "name": "cloneReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=CloneReceiptRuleSet?OriginalRuleSetName=OriginalRuleSetName&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a receipt rule set by cloning an existing one."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61aff98d-8158-479c-9d88-5ad79319dc3e"
            }
          ]
        }
      ]
    }
  ]
}