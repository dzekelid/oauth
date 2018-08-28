---
swagger: "2.0"
x-collection-name: Particle
x-complete: 1
info:
  title: Particle
  description: the-particle-cloud-api-is-a-rest-api-rest-means-a-lot-of-things-but-first-and-foremost-it-means-that-we-use-the-url-in-the-way-that-its-intended-as-a-uniform-resource-locatorin-this-case-the-unique-resource-in-question-is-your-device-core-photon-electron-every-device-has-a-url-which-can-be-used-to-get-variables-post-a-function-call-or-put-new-firmware-the-variables-and-functions-that-you-have-written-in-your-firmware-are-exposed-as-subresources-under-the-deviceall-requests-to-the-device-come-through-our-api-server-using-tls-security
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
---