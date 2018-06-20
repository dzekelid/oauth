---
name: PredictHQ
x-slug: predicthq
description: Event visibility yields higher returns & reduces operational costs. PredictHQ
  is the worlds largest source of intelligent event data making businesses smarter.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28211-developer-predicthq-com.jpg
x-kinRank: "7"
x-alexaRank: "428389"
tags: OAuth
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/predicthq/apis.md
specificationVersion: "0.14"
apis:
- name: PredictHQ Revoking an Access Token
  x-api-slug: predicthq
  description: |-
    Access Tokens never expire so once you have it, it's yours for the life of your PredictHQ API subscription.

    However, if you think your token may have been compromised, you have the power to revoke it at any time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28211-developer-predicthq-com.jpg
  humanURL: http://www.predicthq.com/
  baseURL: https://api.predicthq.com////oauth2/revoke/
  tags: Oauth2,Revoke
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/predicthq/oauth2revoke-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/predicthq/oauth2revoke-post-openapi.md
- name: PredictHQ Requesting an Access Token
  x-api-slug: predicthq
  description: |-
    When requesting an Access Token, use the `client_credentials` grant type, then request the scope or scopes you wish to have access to.

    These scopes can be any or all of the following, separated by a space:
      - `account` Grants access to the account endpoint.
      - `events` Grants access to the events endpoint.
      - `places` Grants access to the places endpoint.
      - `signals` Grants access to the signals endpoint.

    Please note that Access Tokens requested via the client_credentials grant type never expire.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28211-developer-predicthq-com.jpg
  humanURL: http://www.predicthq.com/
  baseURL: https://api.predicthq.com////oauth2/token/
  tags: Oauth2,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/predicthq/oauth2token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/predicthq/oauth2token-post-openapi.md
- name: PredictHQ
  x-api-slug: predicthq
  description: Event visibility yields higher returns & reduces operational costs.
    PredictHQ is the worlds largest source of intelligent event data making businesses
    smarter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28211-developer-predicthq-com.jpg
  humanURL: http://www.predicthq.com/
  baseURL: https://api.predicthq.com//
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/predicthq/openapi.md
x-common:
- type: x-website
  url: http://www.predicthq.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/predicthq
- type: x-email
  url: support@predicthq.com
- type: x-email
  url: 8Bsupport@predicthq.com
- type: x-email
  url: notices@predicthq.com
- type: x-github
  url: https://github.com/predicthq
- type: x-twitter
  url: https://twitter.com/PredictHQ
- type: x-website
  url: https://developer.predicthq.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---