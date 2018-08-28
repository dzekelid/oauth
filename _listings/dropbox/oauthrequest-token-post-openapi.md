---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 0
info:
  title: Dropbox Datastore API OAuth Request Token
  description: /oauth/request_token
  version: "1"
host: api.dropbox.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth/access_token:
    post:
      summary: OAuth Access Token
      description: /oauth/access_token
      operationId: oauthaccess-token
      x-api-path-slug: oauthaccess-token-post
      responses:
        200:
          description: OK
      tags:
      - Oauth
      - Access
      - Token
  /oauth/request_token:
    post:
      summary: OAuth Request Token
      description: /oauth/request_token
      operationId: oauthrequest-token
      x-api-path-slug: oauthrequest-token-post
      responses:
        200:
          description: OK
      tags:
      - Oauth
      - Request
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