---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Get all refunds for a merchant
  version: 1.0.0
  description: Get all refunds for a merchant.
host: /merchants
basePath: https://api.clover.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/merchants/{mId}/refunds:
    get:
      summary: Get all refunds for a merchant
      description: Get all refunds for a merchant.
      operationId: GetRefunds
      x-api-path-slug: v3merchantsmidrefunds-get
      parameters:
      - in: query
        name: expand
        description: 'Expandable fields: [payment, germanInfo, appTracking, employee,
          overrideMerchantTender, serviceCharge, lineItems]'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Refunds
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---