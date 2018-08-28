---
swagger: "2.0"
x-collection-name: PredictHQ
x-complete: 1
info:
  title: PredictHQ API
  description: todo-add-description
  version: 1.0.0
host: api.predicthq.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth2/revoke/:
    post:
      summary: Revoking an Access Token
      description: |-
        Access Tokens never expire so once you have it, it's yours for the life of your PredictHQ API subscription.

        However, if you think your token may have been compromised, you have the power to revoke it at any time.
      operationId: Oauth2RevokePost
      x-api-path-slug: oauth2revoke-post
      parameters:
      - in: formData
        name: token
      - in: formData
        name: token_type_hint
      responses:
        200:
          description: OK
      tags:
      - Oauth2
      - Revoke
  /oauth2/token/:
    post:
      summary: Requesting an Access Token
      description: |-
        When requesting an Access Token, use the `client_credentials` grant type, then request the scope or scopes you wish to have access to.

        These scopes can be any or all of the following, separated by a space:
          - `account` Grants access to the account endpoint.
          - `events` Grants access to the events endpoint.
          - `places` Grants access to the places endpoint.
          - `signals` Grants access to the signals endpoint.

        Please note that Access Tokens requested via the client_credentials grant type never expire.
      operationId: Oauth2TokenPost
      x-api-path-slug: oauth2token-post
      parameters:
      - in: formData
        name: grant_type
      - in: formData
        name: scope
      responses:
        200:
          description: OK
      tags:
      - Oauth2
      - Token
---