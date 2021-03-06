swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3scale Service Management API
  description: the-api-for-managing-3scale-services-
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /transactions/oauth_authorize.xml:
    get:
      summary: Authorize (Oauth authentication mode pattern)
      description: Authorize (oauth authentication mode pattern).
      operationId: authorize
      x-api-path-slug: transactionsoauth-authorize-xml-get
      parameters:
      - in: query
        name: app_id
        description: Client Id (identifier of the application if the auth
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      - in: query
        name: redirect_url
        description: Optional redirect URL for OAuth
      - in: query
        name: referrer
        description: Referrer IP Address or Domain
      - in: query
        name: service_id
        description: Service id
      - in: query
        name: usage
        description: Predicted Usage
      - in: query
        name: user_id
        description: User id
      responses:
        200:
          description: OK
      tags:
      - Transactions
      - Oauth
      - Authorize
      - Xml