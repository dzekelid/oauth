---
name: Backupify
x-slug: backupify
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: OAuth
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/backupify/apis.md
specificationVersion: "0.14"
apis:
- name: Backupify - Retrieve an Access Token authenticated using the provided client_id
    and client_secret.
  x-api-slug: oauthtoken-post
  description: All actions and visibility is limited in scope to items that are descendents
    of the authenticated vendor and the backup_definitions owned thereby. At this
    time, all Access Tokens are scoped with full write capabilities.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: API Not Found, API Provider, Backups, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/backupify/oauthtoken-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/backupify/oauthtoken-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.virtual.network.api.gallery.streamdata.io
- type: x-api-stack
  url: http://backupify.stack.network
- type: x-blog
  url: https://www.backupify.com/blog
- type: x-website
  url: http://backupify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---