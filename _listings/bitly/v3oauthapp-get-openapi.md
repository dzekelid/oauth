---
swagger: "2.0"
x-collection-name: Bitly
x-complete: 0
info:
  title: Bitly User API OAuth App
  description: Return information about an OAuth app.
  termsOfService: http://dev.bitly.com/best_practices.html
  version: v3
host: api-ssl.bitly.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/oauth/app:
    get:
      summary: OAuth App
      description: Return information about an OAuth app.
      operationId: oauthApp
      x-api-path-slug: v3oauthapp-get
      parameters:
      - in: query
        name: client_id
        description: the client ID of the app
      responses:
        200:
          description: OK
      tags:
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