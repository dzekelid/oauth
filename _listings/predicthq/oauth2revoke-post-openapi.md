---
swagger: "2.0"
x-collection-name: PredictHQ
x-complete: 0
info:
  title: PredictHQ Revoking an Access Token
  description: |-
    Access Tokens never expire so once you have it, it's yours for the life of your PredictHQ API subscription.

    However, if you think your token may have been compromised, you have the power to revoke it at any time.
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