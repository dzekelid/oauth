---
name: Tyk
x-slug: tyk
description: Tyk - Open Source API Gateway, API Management Platform, Developer Portal
  and Analytics - Tyk
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
x-kinRank: "9"
x-alexaRank: "489034"
tags: OAuth
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/apis.md
specificationVersion: "0.14"
apis:
- name: Tyk Gateway REST API - OAuth Create Client
  x-api-slug: tykoauthclientscreate-post
  description: Create a new OAuth client
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthclientscreate-post-openapi.md
- name: Tyk Gateway REST API - Delete Client
  x-api-slug: tykoauthclientsapiidclientid-delete
  description: Delete the OAuth client
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthclientsapiidclientid-delete-openapi.md
- name: Tyk Gateway REST API - OAuth Get Clients
  x-api-slug: tykoauthclientsapiid-get
  description: Get a list of OAuth clients bound to this back end
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthclientsapiid-get-openapi.md
- name: Tyk Gateway REST API - OAuth Authorize Client
  x-api-slug: tykoauthauthorizeclient-post
  description: The final request from an authorising party for a redirect URI during
    the Tyk OAuth flow
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthauthorizeclient-post-openapi.md
- name: Tyk Gateway REST API - Invalidate Key
  x-api-slug: tykoauthrefreshkeyid-delete
  description: Invalidate a refresh token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11408-tyk.jpg
  humanURL: http://www.tyk.io
  baseURL: https://{baseURL}//
  tags: Management, API Deployment Gateways, Tyk API Management, Stack Network, SaaS,
    Technology, SDIO Partner, Deployments, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/tyk/tykoauthrefreshkeyid-delete-openapi.md
x-common:
- type: x-website
  url: http://www.tyk.io
- type: x-api-gallery
  url: http://twitter.api.gallery.streamdata.io
- type: x-api-stack
  url: http://tyk.stack.network
- type: x-blog
  url: https://tyk.io/news-2/
- type: x-blog-rss
  url: https://tyk.io/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/tyk-technologies-ltd
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