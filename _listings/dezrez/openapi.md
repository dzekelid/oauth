swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/sync/calendarsyncoauthurl/{personId}:
    get:
      summary: Get the oauth url for the calendar sync service
      description: Get the oauth url for the calendar sync service.
      operationId: Sync_CalendarSyncOauthUrlBypersonId
      x-api-path-slug: apisynccalendarsyncoauthurlpersonid-get
      parameters:
      - in: path
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Oauth
      - Urlthe
      - Calendar
      - Sync
      - Service
  /api/sync/googleanalyticsoauthurl/{brandId}/{personId}:
    get:
      summary: Get the oauth url for the google analytics integration service
      description: Get the oauth url for the google analytics integration service.
      operationId: Sync_GoogleAnalyticsOauthUrlBybrandIdBypersonId
      x-api-path-slug: apisyncgoogleanalyticsoauthurlbrandidpersonid-get
      parameters:
      - in: path
        name: brandId
      - in: path
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Oauth
      - Urlthe
      - Google
      - Analytics
      - Integration
      - Service
  /api/twitter/oauthurl/{brandId}/{personId}:
    get:
      summary: Get the oauth url for the twitter integration service
      description: Get the oauth url for the twitter integration service.
      operationId: Twitter_TwitterOauthUrlBybrandIdBypersonId
      x-api-path-slug: apitwitteroauthurlbrandidpersonid-get
      parameters:
      - in: path
        name: brandId
      - in: path
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Oauth
      - Urlthe
      - Twitter
      - Integration
      - Service
  /api/ExternalProvider:
    get:
      summary: Returns a URL that will start the process of authorisation with the
        external provider - normally using the OAuth1/2 protocol suite.
      description: Returns a url that will start the process of authorisation with
        the external provider - normally using the oauth1/2 protocol suite..
      operationId: ExternalProvider_GetAuthoriseAgencyUrlByexternalProviderId
      x-api-path-slug: apiexternalprovider-get
      parameters:
      - in: query
        name: externalProviderId
        description: The external provider identifier
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - URL
      - That
      - Will
      - Start
      - Process
      - Of
      - Authorisation
      - External
      - Provider
      - '-'
      - Normally
      - Using
      - OAuth1
      - "2"
      - Protocol
      - Suite