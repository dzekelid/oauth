swagger: "2.0"
x-collection-name: Tyk
x-complete: 1
info:
  title: Tyk Gateway REST API
  description: the-api-for-managing-the-tyk-api-management-gateway-allowing-api-control-over-the-operation-of-a-variety-of-apis-
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
  /tyk/oauth/authorize-client/:
    post:
      summary: OAuth Authorize Client
      description: The final request from an authorising party for a redirect URI
        during the Tyk OAuth flow
      operationId: the-final-request-from-an-authorising-party-for-a-redirect-uri-during-the-tyk-oauth-flow
      x-api-path-slug: tykoauthauthorizeclient-post
      parameters:
      - in: formData
        name: client_id
        description: Should be provided by requesting client as part of authorisation
          request
      - in: formData
        name: key_rules
        description: A string representation of a *Session Object (form-encoded)*
      - in: formData
        name: redirect_uri
        description: Should be provided by requesting client as part of authorisation
          request
      - in: formData
        name: response_type
        description: Should be provided by requesting client as part of authorisation
          request, this should be either `code` or `token` depending on the methods
          you have specified for the API
      - in: header
        name: x-tyk-authorization
        description: tyk gateway shared secret
      responses:
        200:
          description: OK
      tags:
      - OAuth
  /tyk/oauth/refresh/{keyId}:
    delete:
      summary: Invalidate Key
      description: Invalidate a refresh token
      operationId: invalidate-a-refresh-token
      x-api-path-slug: tykoauthrefreshkeyid-delete
      parameters:
      - in: query
        name: apiID
        description: API ID
      - in: path
        name: keyId
        description: Access Token
      - in: header
        name: x-tyk-authorization
        description: tyk gateway shared secret
      responses:
        200:
          description: OK
      tags:
      - OAuth