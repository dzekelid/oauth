swagger: "2.0"
x-collection-name: Bitly
x-complete: 1
info:
  title: Bitly User Metrics API
  description: the-bitly-user-metrics-api
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