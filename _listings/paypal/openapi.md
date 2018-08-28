swagger: "2.0"
x-collection-name: PayPal
x-complete: 1
info:
  title: PayPal (Sandbox)
  description: bring-payments-to-apps-mobile-and-social-with-adaptive-payments-bsandbox-api-b
  version: 1.0.0
host: svcs.sandbox.paypal.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /AdaptivePayments/Refund:
    post:
      summary: Refund
      description: Use the Refund API operation to refund all or part of a payment.
        You can specify the amount of the refund and identify the accounts to receive
        the refund by the payment key or tracking ID, and optionally, by transaction
        ID or the receivers of the original payment.
      operationId: AdaptivePayments.Refund.post
      x-api-path-slug: adaptivepaymentsrefund-post
      responses:
        200:
          description: OK
      tags:
      - Payments
      - Refunds