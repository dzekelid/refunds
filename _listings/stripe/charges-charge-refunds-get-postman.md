{
  "info": {
    "name": "Stripe Get Charges Charge Refunds",
    "_postman_id": "1c423eb0-2202-4955-a28a-9befcf8dcdca",
    "description": "You can see a list of the refunds belonging to a specific charge. Note that the 10 most recent refunds are always available by default on the charge object. If you need more than those 10, you can use this API method and the limit and starting_after parameters to page through additional refunds.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "charges",
      "item": [
        {
          "id": "3c13a6e4-cf4c-42f6-8b7a-b41133a3dbe6",
          "name": "getChargesChargeRefunds",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "charges/:charge/refunds"
              ],
              "query": [
                {
                  "key": "ending_before",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "starting_after",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "charge",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "You can see a list of the refunds belonging to a specific charge"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3f5b94b-e287-499a-afbc-286e39a1fe75"
            }
          ]
        }
      ]
    }
  ]
}