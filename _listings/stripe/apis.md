---
name: Stripe
x-slug: stripe
description: Online payment processing for internet businesses. Stripe is a suite
  of payment APIs that powers commerce for online businesses of all sizes, including
  fraud prevention, and subscription management. Use Stripe???s payment platform to
  accept and process p...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
x-kinRank: "10"
x-alexaRank: "1793"
tags: Refunds
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/apis.md
specificationVersion: "0.14"
apis:
- name: Stripe Get Application Fees Fee Refunds
  x-api-slug: stripe
  description: By default, you can see the 10 most recent refunds stored directly
    on the application fee object, but you can also retrieve details about a specific
    refund stored on the application fee.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{fee}/refunds/{id}
  tags: Application, Fees, Fee, Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/application-feesfeerefundsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/application-feesfeerefundsid-get-openapi.md
- name: Stripe Add Application Fees Fee Refunds
  x-api-slug: stripe
  description: Updates the specified application fee refund by setting the values
    of the parameters passed. Any parameters not provided will be left unchanged.This
    request only accepts metadata as an argument.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{fee}/refunds/{id}
  tags: Application, Fees, Fee, Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/application-feesfeerefundsid-post-openapi.md
- name: Stripe Get Application Fees  Refunds
  x-api-slug: stripe
  description: You can see a list of the refunds belonging to a specific application
    fee. Note that the 10 most recent refunds are always available by default on the
    application fee object. If you need more than those 10, you can use this API method
    and the limit and starting_after parameters to page through additional refunds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{id}/refunds
  tags: Application, Fees, , Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/application-feesidrefunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/application-feesidrefunds-get-openapi.md
- name: Stripe Add Application Fees  Refunds
  x-api-slug: stripe
  description: Post Application, Fees, , Refunds
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///application_fees/{id}/refunds
  tags: Application, Fees, , Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/application-feesidrefunds-post-openapi.md
- name: Stripe Get Charges Charge Refunds
  x-api-slug: stripe
  description: You can see a list of the refunds belonging to a specific charge. Note
    that the 10 most recent refunds are always available by default on the charge
    object. If you need more than those 10, you can use this API method and the limit
    and starting_after parameters to page through additional refunds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds
  tags: Charges, Charge, Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/chargeschargerefunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/chargeschargerefunds-get-openapi.md
- name: Stripe Add Charges Charge Refunds
  x-api-slug: stripe
  description: Post Charges, Charge, Refunds
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds
  tags: Charges, Charge, Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/chargeschargerefunds-post-openapi.md
- name: Stripe Get Charges Charge Refunds Refund
  x-api-slug: stripe
  description: Get Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds/{refund}
  tags: Charges, Charge, Refunds, Refund
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/chargeschargerefundsrefund-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/chargeschargerefundsrefund-get-openapi.md
- name: Stripe Add Charges Charge Refunds Refund
  x-api-slug: stripe
  description: Post Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds/{refund}
  tags: Charges, Charge, Refunds, Refund
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/chargeschargerefundsrefund-post-openapi.md
- name: Stripe Get Refunds
  x-api-slug: stripe
  description: "Returns a list of all refunds you\u2019ve previously created. The
    refunds are returned in sorted order, with the most recent refunds appearing first.
    For convenience, the 10 most recent refunds are always available by default on
    the charge object."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///refunds
  tags: Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/refunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/refunds-get-openapi.md
- name: Stripe Add Refunds
  x-api-slug: stripe
  description: Post Refunds
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///refunds
  tags: Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/refunds-post-openapi.md
- name: Stripe Get Refunds Refund
  x-api-slug: stripe
  description: Retrieves the details of an existing refund.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///refunds/{refund}
  tags: Refunds, Refund
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/refundsrefund-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/refundsrefund-get-openapi.md
- name: Stripe Add Refunds Refund
  x-api-slug: stripe
  description: Updates the specified refund by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged.This request only accepts
    metadata as an argument.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///refunds/{refund}
  tags: Refunds, Refund
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/refundsrefund-post-openapi.md
- name: Stripe
  x-api-slug: stripe
  description: Web and mobile payments, built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/refunds/master/_listings/stripe/openapi.md
x-common:
- type: x-base
  url: https://api.stripe.com/
- type: x-blog
  url: https://stripe.com/blog
- type: x-blog-rss
  url: https://stripe.com/blog/feed.rss
- type: x-change-log
  url: https://stripe.com/docs/upgrades
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stripe
- type: x-crunchbase
  url: https://crunchbase.com/organization/stripe
- type: x-email
  url: info@stripe.com
- type: x-email
  url: privacy@stripe.com
- type: x-email
  url: atlas@stripe.com
- type: x-email
  url: notices@stripe.com
- type: x-email
  url: jane.diaz@stripe.com
- type: x-email
  url: nonprofit@stripe.com
- type: x-email
  url: support@stripe.com
- type: x-github
  url: https://github.com/stripe
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
- type: x-website
  url: http://stripe.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---