---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Get info on an OAuth app
  description: |-
    Get public information about an OAuth 2.0 client application registered with Mattermost. The application's client secret will be blanked out.
    ##### Permissions
    Must be authenticated.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth/apps:
    post:
      summary: Register OAuth app
      description: |-
        Register an OAuth 2.0 client application with Mattermost as the service provider.
        ##### Permissions
        Must have `manage_oauth` permission.
      operationId: register-an-oauth-20-client-application-with-mattermost-as-the-service-provider-permissionsmust-have
      x-api-path-slug: oauthapps-post
      parameters:
      - in: body
        name: body
        description: OAuth application to register
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Register
      - OAuth
      - App
    get:
      summary: Get OAuth apps
      description: |-
        Get a page of OAuth 2.0 client applications registered with Mattermost.
        ##### Permissions
        With `manage_oauth` permission, the apps registered by the logged in user are returned. With `manage_system_wide_oauth` permission, all apps regardless of creator are returned.
      operationId: get-a-page-of-oauth-20-client-applications-registered-with-mattermost-permissionswith-manage-oauth-p
      x-api-path-slug: oauthapps-get
      parameters:
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of apps per page
      responses:
        200:
          description: OK
      tags:
      - OAuth
      - Apps
  /oauth/apps/{app_id}:
    get:
      summary: Get an OAuth app
      description: |-
        Get an OAuth 2.0 client application registered with Mattermost.
        ##### Permissions
        If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
      operationId: get-an-oauth-20-client-application-registered-with-mattermost-permissionsif-app-creator-must-have-ma
      x-api-path-slug: oauthappsapp-id-get
      parameters:
      - in: path
        name: app_id
        description: Application client id
      responses:
        200:
          description: OK
      tags:
      - OAuth
      - App
    put:
      summary: Update an OAuth app
      description: |-
        Update an OAuth 2.0 client application based on OAuth struct.
        ##### Permissions
        If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
      operationId: update-an-oauth-20-client-application-based-on-oauth-struct-permissionsif-app-creator-must-have-mang
      x-api-path-slug: oauthappsapp-id-put
      parameters:
      - in: path
        name: app_id
        description: Application client id
      - in: body
        name: body
        description: OAuth application to update
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - OAuth
      - App
    delete:
      summary: Delete an OAuth app
      description: "Delete and unregister an OAuth 2.0 client application \n#####
        Permissions\nIf app creator, must have `mange_oauth` permission otherwise
        `manage_system_wide_oauth` permission is required."
      operationId: delete-and-unregister-an-oauth-20-client-application--permissionsif-app-creator-must-have-mange-oaut
      x-api-path-slug: oauthappsapp-id-delete
      parameters:
      - in: path
        name: app_id
        description: Application client id
      responses:
        200:
          description: OK
      tags:
      - OAuth
      - App
  /oauth/apps/{app_id}/regen_secret:
    post:
      summary: Regenerate OAuth app secret
      description: |-
        Regenerate the client secret for an OAuth 2.0 client application registered with Mattermost.
        ##### Permissions
        If app creator, must have `mange_oauth` permission otherwise `manage_system_wide_oauth` permission is required.
      operationId: regenerate-the-client-secret-for-an-oauth-20-client-application-registered-with-mattermost-permissio
      x-api-path-slug: oauthappsapp-idregen-secret-post
      parameters:
      - in: path
        name: app_id
        description: Application client id
      responses:
        200:
          description: OK
      tags:
      - Regenerate
      - OAuth
      - App
      - Secret
  /oauth/apps/{app_id}/info:
    get:
      summary: Get info on an OAuth app
      description: |-
        Get public information about an OAuth 2.0 client application registered with Mattermost. The application's client secret will be blanked out.
        ##### Permissions
        Must be authenticated.
      operationId: get-public-information-about-an-oauth-20-client-application-registered-with-mattermost-the-applicati
      x-api-path-slug: oauthappsapp-idinfo-get
      parameters:
      - in: path
        name: app_id
        description: Application client id
      responses:
        200:
          description: OK
      tags:
      - Info
      - "On"
      - OAuth
      - App
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---