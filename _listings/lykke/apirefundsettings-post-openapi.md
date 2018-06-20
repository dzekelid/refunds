---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Refundsettings
  version: 1.0.0
  description: Add api refundsettings.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/RefundSettings:
    get:
      summary: Get API Refundsettings
      description: Get api refundsettings.
      operationId: ApiRefundSettingsGet
      x-api-path-slug: apirefundsettings-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Refundsettings
    post:
      summary: Add API Refundsettings
      description: Add api refundsettings.
      operationId: ApiRefundSettingsPost
      x-api-path-slug: apirefundsettings-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: refundAddressModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Refundsettings
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