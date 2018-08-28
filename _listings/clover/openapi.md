swagger: "2.0"
x-collection-name: Clover
x-complete: 1
info:
  title: ""
  version: 1.0.0
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
  /v3/merchants/{mId}/credit_refunds/{crId}:
    get:
      summary: Get a credit refund
      description: Get a credit refund.
      operationId: GetCreditRefund
      x-api-path-slug: v3merchantsmidcredit-refundscrid-get
      parameters:
      - in: path
        name: crId
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
      - CrId