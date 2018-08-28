---
name: Twine
x-slug: twine
description: 'Twine Health is a cloud-based collaborative care platform for chronic
  disease management. It consists of a patient engagement portal, a peer support network,
  a care management solution, and an outcome analytics tool. The platform enables
  users to co-create personalized care plans that serve as common ground for collaboration
  with their care team: their own providers such as physicians and nurse practitioners;
  their family and friends; and coaches such as nurses, pharmacists, health coaches,
  and more.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/twinehealth.png
x-kinRank: "7"
x-alexaRank: "0"
tags: OAuth
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/twine/apis.md
specificationVersion: "0.14"
apis:
- name: Twine - Create an oauth token
  x-api-slug: oauthtoken-post
  description: |-
    Create an OAuth 2.0 Bearer token. A valid bearer token is required for all other API requests.

    Be sure to set the header `Content-Type: "application/vnd.api+json"`. Otherwise, you will get an error
    403 Forbidden. Using `Content-Type: "application/json"` is permitted (to support older oauth clients) but when
    using `application/json` the body should have a body in the following format instead of nesting under
    `data.attributes`:
    ```
    {
      "grant_type": "client_credentials",
      "client_id": "95c78ab2-167f-40b8-8bec-8398d4b87454",
      "client_secret": "35d18dc9-a3dd-4948-b787-063a490b9354"
    }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/twinehealth.png
  humanURL: http://twinehealth.com
  baseURL: https://api.twinehealth.com//pub
  tags: Wearables, Healthcare, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/twine/oauthtoken-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://twilio.api.gallery.streamdata.io
- type: x-api-stack
  url: http://twine.stack.network
- type: x-authentication
  url: http://developer.twinehealth.com/#section/Authentication
- type: x-developer
  url: http://developer.twinehealth.com/
- type: x-website
  url: http://twinehealth.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---