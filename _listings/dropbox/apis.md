---
name: Dropbox
x-slug: dropbox
description: Dropbox is a file hosting service operated by Dropbox, Inc., that offers
  cloud storage, file synchronization, and client software. Dropbox allows users to
  create a special folder on each of their computers, which Dropbox then synchronizes
  so that it appears to be the same folder (with the same contents) regardless of
  which computer is used to view it. Files placed in this folder also are accessible
  through a website and mobile phone applications.
image: https://avatars.githubusercontent.com/u/559357?v=3
x-kinRank: "10"
x-alexaRank: ""
tags: OAuth
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/dropbox/apis.md
specificationVersion: "0.14"
apis:
- name: Dropbox Core Convert OAuth 1 token to OAuth 2 token.
  x-api-slug: dropbox-core
  description: |-
    This endpoint should be used by apps transitioning from OAuth 1 to OAuth 2. It will return an OAuth 2 token
    for the authenticated user.
  image: https://avatars.githubusercontent.com/u/559357?v=3
  humanURL: https://www.dropbox.com
  baseURL: https://api.dropbox.com//1//oauth2/token_from_oauth1
  tags: Storage,Documents,Oauth2,Token_from_oauth1
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/dropbox/oauth2token-from-oauth1-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/dropbox/oauth2token-from-oauth1-post-openapi.md
- name: Dropbox Core
  x-api-slug: dropbox-core
  description: Dropbox is a file hosting service operated by Dropbox, Inc., that offers
    cloud storage, file synchronization, and client software. Dropbox allows users
    to create a special folder on each of their computers, which Dropbox then synchronizes
    so that it appears to be the same folder (with the same contents) regardless of
    which computer is used to view it. Files placed in this folder also are accessible
    through a website and mobile phone applications.
  image: https://avatars.githubusercontent.com/u/559357?v=3
  humanURL: https://www.dropbox.com
  baseURL: https://api.dropbox.com//1
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/dropbox/openapi.md
x-common:
- type: x-application-management
  url: https://www.dropbox.com/developers/apps
- type: x-base
  url: https://api.dropbox.com/
- type: x-blog
  url: https://blog.dropbox.com/
- type: x-blog-rss
  url: https://blog.dropbox.com/feed/
- type: x-branding
  url: https://www.dropbox.com/developers/reference/branding
- type: x-branding
  url: https://www.dropbox.com/branding
- type: x-contact-form
  url: https://www.dropbox.com/developers/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/dropbox
- type: x-developer
  url: https://www.dropbox.com/developers
- type: x-faq
  url: https://www.dropbox.com/developers/support
- type: x-forum
  url: https://www.dropboxforum.com/hc/communities/public/topics/200209245-API-Development
- type: x-github
  url: https://github.com/dropbox
- type: x-pricing
  url: https://www.dropbox.com/plans
- type: x-privacy
  url: https://www.dropbox.com/privacy
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/dropbox-api?sort=votes&pagesize=15
- type: x-support
  url: https://www.dropbox.com/help
- type: x-terms-of-service
  url: https://www.dropbox.com/privacy#terms
- type: x-transparency-report
  url: https://www.dropbox.com/transparency
- type: x-twitter
  url: https://twitter.com/dropbox
- type: x-webhooks
  url: https://www.dropbox.com/developers/webhooks/docs
- type: x-website
  url: https://www.dropbox.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---