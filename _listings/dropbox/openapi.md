swagger: "2.0"
x-collection-name: Dropbox
x-complete: 1
info:
  title: Dropbox Notify Appendix API v1
  description: the-dropbox-notify--is-a-part-of-dropbox-core-ap-with-a-separate-endpoint-for-notification-call-
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
host: api-notify.dropbox.com
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