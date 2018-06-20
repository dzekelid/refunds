---
swagger: "2.0"
x-collection-name: Square
x-complete: 1
info:
  title: Square Connect
  description: client-library-for-accessing-the-square-connect-apis
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{location_id}/refunds:
    get:
      summary: Provides the details for all refunds initiated by a merchant or any
        of the merchant's mobile staff during a date range. Date ranges cannot exceed
        one year in length.
      description: Provides the details for all refunds initiated by a merchant or
        any of the merchant's mobile staff during a date range. Date ranges cannot
        exceed one year in length.
      operationId: v1.location_id.refunds.get
      x-api-path-slug: v1location-idrefunds-get
      parameters:
      - in: query
        name: batch_token
        description: A pagination cursor to retrieve the next set of results for youroriginal
          query to the endpoint
      - in: query
        name: begin_time
        description: The beginning of the requested reporting period, in ISO 8601
          format
      - in: query
        name: end_time
        description: The end of the requested reporting period, in ISO 8601 format
      - in: query
        name: limit
        description: The maximum number of payments to return in a single response
      - in: path
        name: location_id
        description: The ID of the location to list refunds for
      - in: query
        name: order
        description: TThe order in which payments are listed in the response
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Details
      - Refunds
      - Initiated
      - By
      - Merchant
      - Any
      - Of
      - Merchants
      - Mobile
      - Staff
      - During
      - Date
      - Range
      - ""
      - Date
      - Ranges
      - Cannot
      - Exceed
      - Year
      - In
      - Length
  /v2/locations/{location_id}/refunds:
    get:
      summary: ListRefunds
      description: |-
        Lists refunds for one of a business's locations.

        Refunds with a `status` of `PENDING` are not currently included in this
        endpoint's response.

        Max results per [page](#paginatingresults): 50
      operationId: v2.locations.location_id.refunds.get
      x-api-path-slug: v2locationslocation-idrefunds-get
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: query
        name: begin_time
        description: The beginning of the requested reporting period, in RFC 3339
          format
      - in: query
        name: cursor
        description: A pagination cursor returned by a previous call to this endpoint
      - in: query
        name: end_time
        description: The end of the requested reporting period, in RFC 3339 format
      - in: path
        name: location_id
        description: The ID of the location to list refunds for
      - in: query
        name: sort_order
        description: The order in which results are listed in the response (`ASC`
          foroldest first, `DESC` for newest first)
      responses:
        200:
          description: OK
      tags:
      - ListRefunds
---