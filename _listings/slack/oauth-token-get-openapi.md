---
swagger: "2.0"
x-collection-name: Slack
x-complete: 0
info:
  title: Slack Oauth Token
  description: Exchanges a temporary OAuth verifier code for a workspace token.
  version: 1.0.3
host: slack.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth.token:
    get:
      summary: Oauth Token
      description: Exchanges a temporary OAuth verifier code for a workspace token.
      operationId: oauth_token
      x-api-path-slug: oauth-token-get
      parameters:
      - in: query
        name: client_id
        description: Issued when you created your application
      - in: query
        name: client_secret
        description: Issued when you created your application
      - in: query
        name: code
        description: The `code` param returned via the OAuth callback
      - in: query
        name: redirect_uri
        description: This must match the originally submitted URI (if one was sent)
      - in: query
        name: single_channel
        description: Request the user to add your app only to a single channel
      responses:
        200:
          description: OK
      tags:
      - Messaging
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