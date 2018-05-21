---
swagger: "2.0"
x-collection-name: Tyk
x-complete: 0
info:
  title: Tyk API Management OAuth Get Clients
  description: Get a list of OAuth clients bound to this back end
  termsOfService: https://tyk.io/terms-and-conditions/
  version: "1.9"
host: '{baseURL}'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tyk/oauth/clients/create:
    post:
      summary: OAuth Create Client
      description: Create a new OAuth client
      operationId: create-a-new-oauth-client
      x-api-path-slug: tykoauthclientscreate-post
      parameters:
      - in: body
        name: oauth_client
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: x-tyk-authorization
        description: tyk gateway shared secret
      responses:
        200:
          description: OK
      tags:
      - OAuth
  /tyk/oauth/clients/{apiId}/{clientId}:
    delete:
      summary: Delete Client
      description: Delete the OAuth client
      operationId: delete-the-oauth-client
      x-api-path-slug: tykoauthclientsapiidclientid-delete
      parameters:
      - in: path
        name: apiId
        description: API ID that owns this client (back end)
      - in: path
        name: clientId
        description: OAuth Client ID to delete
      - in: header
        name: x-tyk-authorization
        description: tyk gateway shared secret
      responses:
        200:
          description: OK
      tags:
      - OAuth
  /tyk/oauth/clients/{apiId}:
    get:
      summary: OAuth Get Clients
      description: Get a list of OAuth clients bound to this back end
      operationId: get-a-list-of-oauth-clients-bound-to-this-back-end
      x-api-path-slug: tykoauthclientsapiid-get
      parameters:
      - in: path
        name: apiId
        description: API ID that owns this client (back end)
      - in: header
        name: x-tyk-authorization
        description: tyk gateway shared secret
      responses:
        200:
          description: OK
      tags:
      - OAuth
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