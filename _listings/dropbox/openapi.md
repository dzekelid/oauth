---
swagger: "2.0"
x-collection-name: Dropbox
x-complete: 1
info:
  title: Dropbox Core API v1
  description: the-dropbox-core-api-is-the-underlying-interface-for-all-of-our-official-dropbox-mobile-appshttpswwwdropboxcommobileand-our-sdkshttpswwwdropboxcomdeveloperscoresdk-its-the-most-direct-way-to-access-the-api-thisreference-document-is-designed-for-those-interested-in-developing-for-platforms-not-supported-by-the-sdks-or-forthose-interested-in-exploring-api-features-in-detail
  termsOfService: https://www.dropbox.com/developers/reference/tos
  contact:
    name: Dropbox
    url: https://www.dropbox.com/developers
  version: 1.0.0
host: api.dropbox.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /oauth2/token_from_oauth1:
    post:
      summary: Convert OAuth 1 token to OAuth 2 token.
      description: |-
        This endpoint should be used by apps transitioning from OAuth 1 to OAuth 2. It will return an OAuth 2 token
        for the authenticated user.
      operationId: this-endpoint-should-be-used-by-apps-transitioning-from-oauth-1-to-oauth-2-it-will-return-an-oauth-2
      x-api-path-slug: oauth2token-from-oauth1-post
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Documents
      - Oauth2
      - Token_from_oauth1
---