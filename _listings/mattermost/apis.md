---
name: Mattermost
x-slug: mattermost
description: Open source, private cloud Slack-alternative, Workplace messaging for
  web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
  configurable, and scalable from teams to the enterprise.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
x-kinRank: "8"
x-alexaRank: "95684"
tags: OAuth
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/apis.md
specificationVersion: "0.14"
apis:
- name: Mattermost API Register OAuth app
  x-api-slug: mattermost-api
  description: |-
    Register an OAuth 2.0 client application with Mattermost as the service provider.
    ##### Permissions
    Must have `manage_oauth` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//oauth/apps
  tags: Register,OAuth,App
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/oauthapps-post-openapi.md
- name: Mattermost API Get OAuth apps
  x-api-slug: mattermost-api
  description: |-
    Get a page of OAuth 2.0 client applications registered with Mattermost.
    ##### Permissions
    With `manage_oauth` permission, the apps registered by the logged in user are returned. With `manage_system_wide_oauth` permission, all apps regardless of creator are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//oauth/apps
  tags: OAuth,Apps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/oauthapps-get-openapi.md
- name: Mattermost API Get an OAuth app
  x-api-slug: mattermost-api
  description: |-
    Get an OAuth 2.0 client application registered with Mattermost.
    ##### Permissions
    If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//oauth/apps/{app_id}
  tags: OAuth,App
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/oauthappsapp-id-get-openapi.md
- name: Mattermost API Update an OAuth app
  x-api-slug: mattermost-api
  description: |-
    Update an OAuth 2.0 client application based on OAuth struct.
    ##### Permissions
    If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//oauth/apps/{app_id}
  tags: OAuth,App
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/oauthappsapp-id-put-openapi.md
- name: Mattermost API Delete an OAuth app
  x-api-slug: mattermost-api
  description: "Delete and unregister an OAuth 2.0 client application \n##### Permissions\nIf
    app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth`
    permission is required."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//oauth/apps/{app_id}
  tags: OAuth,App
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/oauthappsapp-id-delete-openapi.md
- name: Mattermost API Regenerate OAuth app secret
  x-api-slug: mattermost-api
  description: |-
    Regenerate the client secret for an OAuth 2.0 client application registered with Mattermost.
    ##### Permissions
    If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//oauth/apps/{app_id}/regen_secret
  tags: Regenerate,OAuth,App,Secret
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/oauthappsapp-idregen-secret-post-openapi.md
- name: Mattermost API Get info on an OAuth app
  x-api-slug: mattermost-api
  description: |-
    Get public information about an OAuth 2.0 client application registered with Mattermost. The application's client secret will be blanked out.
    ##### Permissions
    Must be authenticated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//oauth/apps/{app_id}/info
  tags: Info,On,OAuth,App
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/oauthappsapp-idinfo-get-openapi.md
- name: Mattermost API Get authorized OAuth apps
  x-api-slug: mattermost-api
  description: |-
    Get a page of OAuth 2.0 client applications authorized to access a user's account.
    ##### Permissions
    Must be authenticated as the user or have `edit_other_users` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4//users/{user_id}/oauth/apps/authorized
  tags: Authorized,OAuth,Apps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/usersuser-idoauthappsauthorized-get-openapi.md
- name: Mattermost API
  x-api-slug: mattermost-api
  description: Open source, private cloud Slack-alternative, Workplace messaging for
    web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
    configurable, and scalable from teams to the enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/mattermost/openapi.md
x-common:
- type: x-blog
  url: https://about.mattermost.com/blog/
- type: x-blog-rss
  url: https://about.mattermost.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/mattermost
- type: x-developer
  url: https://api.mattermost.com/
- type: x-github
  url: https://github.com/mattermost
- type: x-pricing
  url: https://about.mattermost.com/pricing/
- type: x-security
  url: https://docs.mattermost.com/overview/security.html
- type: x-twitter
  url: https://twitter.com/mattermosthq
- type: x-website
  url: https://mattermost.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---