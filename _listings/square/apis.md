---
name: Square
x-slug: square
description: Square helps millions of sellers run their business- from secure credit
  card processing to point of sale solutions. Get paid faster with Square and sign
  up today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
x-kinRank: "9"
x-alexaRank: "2436"
tags: Refunds
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/square/apis.md
specificationVersion: "0.14"
apis:
- name: Square Connect API Provides the details for all refunds initiated by a merchant
    or any of the merchant's mobile staff during a date range. Date ranges cannot
    exceed one year in length.
  x-api-slug: square-connect-api
  description: Provides the details for all refunds initiated by a merchant or any
    of the merchant's mobile staff during a date range. Date ranges cannot exceed
    one year in length.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/refunds
  tags: Provides,Details,Refunds,Initiated,By,Merchant,Any,Of,Merchants,Mobile,Staff,During,Date,Range,,Date,Ranges,Cannot,Exceed,Year,In,Length
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/square/v1location-idrefunds-get-openapi.md
- name: Square Connect API ListRefunds
  x-api-slug: square-connect-api
  description: |-
    Lists refunds for one of a business's locations.

    Refunds with a `status` of `PENDING` are not currently included in this
    endpoint's response.

    Max results per [page](#paginatingresults): 50
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/locations/{location_id}/refunds
  tags: ListRefunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/square/v2locationslocation-idrefunds-get-openapi.md
- name: Square Connect API
  x-api-slug: square-connect-api
  description: Square helps millions of sellers run their business- from secure credit
    card processing to point of sale solutions. Get paid faster with Square and sign
    up today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com//
  tags: Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/square/openapi.md
x-common:
- type: x-base
  url: https://connect.squareup.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/square
- type: x-crunchbase
  url: https://crunchbase.com/organization/square
- type: x-developer
  url: https://connect.squareup.com/
- type: x-email
  url: press@squareup.com
- type: x-email
  url: security@squareup.com
- type: x-email
  url: lawenforcement@squareup.com
- type: x-email
  url: redemption@squareup.com
- type: x-email
  url: privacy@squareup.com
- type: x-email
  url: community@squareup.com
- type: x-email
  url: noreply@messaging.squareup.com
- type: x-email
  url: ir@squareup.com
- type: x-email
  url: takedowns@squareup.com
- type: x-github
  url: https://github.com/square
- type: x-twitter
  url: https://twitter.com/Square
- type: x-website
  url: http://squareup.com
- type: x-website
  url: https://squareup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---