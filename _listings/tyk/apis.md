---
name: Tyk
x-slug: tyk
description: An open source, lightweight, fast and scalable API Gateway. Set rate
  limiting, request throttling, and auto-renewing request quotas to manage how your
  users access your API. Tyk supports access tokens, HMAC request signing, basic authentication
  and OAuth 2.0 to integrate old and new services easily. Tyk can record and store
  detailed analytics which can be segmented by user, error, endpoint and client ID
  across multiple APIs and versions. Integrate your existing or new applications with
  Tyk using a simple REST API, Tyk even support hot-reloads so you can introduce new
  services without downtime.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tyk_io_logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: OAuth
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/apis.md
specificationVersion: "0.14"
apis:
- name: Tyk API Management OAuth Create Client
  x-api-slug: tyk-api-management
  description: Create a new OAuth client
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tyk_io_logo.png
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/clients/create
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthclientscreate-post-openapi.md
- name: Tyk API Management Delete Client
  x-api-slug: tyk-api-management
  description: Delete the OAuth client
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tyk_io_logo.png
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/clients/{apiId}/{clientId}
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthclientsapiidclientid-delete-openapi.md
- name: Tyk API Management OAuth Get Clients
  x-api-slug: tyk-api-management
  description: Get a list of OAuth clients bound to this back end
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tyk_io_logo.png
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/clients/{apiId}
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthclientsapiid-get-openapi.md
- name: Tyk API Management OAuth Authorize Client
  x-api-slug: tyk-api-management
  description: The final request from an authorising party for a redirect URI during
    the Tyk OAuth flow
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tyk_io_logo.png
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/authorize-client/
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthauthorizeclient-post-openapi.md
- name: Tyk API Management Invalidate Key
  x-api-slug: tyk-api-management
  description: Invalidate a refresh token
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tyk_io_logo.png
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}////tyk/oauth/refresh/{keyId}
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthrefreshkeyid-delete-openapi.md
- name: Tyk API Management
  x-api-slug: tyk-api-management
  description: An open source, lightweight, fast and scalable API Gateway. Set rate
    limiting, request throttling, and auto-renewing request quotas to manage how your
    users access your API. Tyk supports access tokens, HMAC request signing, basic
    authentication and OAuth 2.0 to integrate old and new services easily. Tyk can
    record and store detailed analytics which can be segmented by user, error, endpoint
    and client ID across multiple APIs and versions. Integrate your existing or new
    applications with Tyk using a simple REST API, Tyk even support hot-reloads so
    you can introduce new services without downtime.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/tyk_io_logo.png
  humanURL: http://tyk.io/
  baseURL: https://{baseURL}//
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/openapi.md
x-common:
- type: x-blog
  url: https://tyk.io/news-2/
- type: x-blog-rss
  url: https://tyk.io/feed/
- type: x-github
  url: https://github.com/TykTechnologies
- type: x-twitter
  url: https://twitter.com/tyk_io
- type: x-website
  url: http://tyk.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---