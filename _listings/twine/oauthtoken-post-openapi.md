---
swagger: "2.0"
x-collection-name: Twine
x-complete: 0
info:
  title: Twine Create an oauth token
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
  version: 7.18.0
host: api.twinehealth.com
basePath: /pub
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth/token:
    post:
      summary: Create an oauth token
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
      operationId: createToken
      x-api-path-slug: oauthtoken-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: include
        description: List of related resources to include in the response
      responses:
        200:
          description: OK
      tags:
      - Wearables
      - Oauth
      - Token
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