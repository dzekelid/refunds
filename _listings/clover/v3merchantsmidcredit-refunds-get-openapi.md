---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Get a list of credit refunds
  version: 1.0.0
  description: Get a list of credit refunds.
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
  /v3/merchants/{mId}/refunds/{refundId}:
    get:
      summary: Get a single refund
      description: Get a single refund.
      operationId: GetRefund
      x-api-path-slug: v3merchantsmidrefundsrefundid-get
      parameters:
      - in: query
        name: expand
        description: 'Expandable fields: [payment, germanInfo, appTracking, employee,
          overrideMerchantTender, serviceCharge, lineItems]'
      - in: path
        name: mId
        description: Merchant Id
      - in: path
        name: refundId
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Refunds
      - RefundId
  /v3/merchants/{mId}/credit_refunds:
    get:
      summary: Get a list of credit refunds
      description: Get a list of credit refunds.
      operationId: GetCreditRefunds
      x-api-path-slug: v3merchantsmidcredit-refunds-get
      parameters:
      - in: query
        name: expand
        description: 'Expandable fields: [credit, germanInfo, appTracking]'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Credit
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