{
  "info": {
    "name": "Stripe Get Charges Charge Refunds Refund",
    "_postman_id": "0885cd93-354c-401a-af3f-2972611a9f3e",
    "description": "Get Charges, Charge, Refunds, Refund",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "charges",
      "item": [
        {
          "id": "a2f55b48-be0e-4818-b177-c670969a96ff",
          "name": "getChargesChargeRefundsRefund",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "charges/:charge/refunds/:refund"
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
                  "id": "charge",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Get Charges, Charge, Refunds, Refund"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c51dfad7-0282-4d9c-9e93-7e46e7e07064"
            }
          ]
        }
      ]
    }
  ]
}