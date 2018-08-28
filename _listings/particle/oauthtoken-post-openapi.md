---
swagger: "2.0"
x-collection-name: Particle
x-complete: 0
info:
  title: Particle Add Oauth Token
  description: Creates an access token that gives you access to the Cloud API.
  version: 1.0.0
host: api.particle.io
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth/token:
    post:
      summary: Add Oauth Token
      description: Creates an access token that gives you access to the Cloud API.
      operationId: postOauthToken
      x-api-path-slug: oauthtoken-post
      parameters:
      - in: formData
        name: expires_at
        description: When should the token expire? This should be an ISO8601 formatted
          date string
      - in: formData
        name: expires_in
        description: How many seconds the token will be valid for
      - in: formData
        name: grant_type
        description: OAuth grant type
      - in: formData
        name: password
        description: Your Particle account password
      - in: formData
        name: username
        description: Your Particle account username
      responses:
        200:
          description: OK
      tags:
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