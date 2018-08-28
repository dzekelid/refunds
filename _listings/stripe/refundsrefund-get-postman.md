{
  "info": {
    "name": "Stripe Get Refunds Refund",
    "_postman_id": "a01eebbc-0eb2-458e-a68a-0b53f170f784",
    "description": "Retrieves the details of an existing refund.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "refunds",
      "item": [
        {
          "id": "6659a68c-cffe-4e76-a6d4-c354049f2294",
          "name": "getRefundsRefund",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "refunds/:refund"
              ],
              "query": [
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "refund",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the details of an existing refund"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d72bde1-7cc4-4308-a072-7c86a88356f7"
            }
          ]
        }
      ]
    }
  ]
}