---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: OAuth
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Oauth1accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 1.0 access tokens for a developer's app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/oauth1accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Oauth1accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Oauth2accesstokens
  x-api-slug: apigee-edge
  description: Get count of    OAuth 2.0 access tokens for a developer's app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/oauth2accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Oauth2accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-nameoauth2accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Oauth1accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 1.0 access tokens for a developer's app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/oauth1accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,Oauth1accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Oauth2accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 2.0 access tokens for a developer's app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/oauth2accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,Oauth2accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth2accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Oauth1 Requesttokens Request Token
  x-api-slug: apigee-edge
  description: Gets the Oauth 1.0 a request token for the speficied consumer key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/requesttokens/{request_token}
  tags: Organizations,Oauth1,Requesttokens,Request,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1requesttokensrequest-token-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1requesttokensrequest-token-get-openapi.md
- name: Apigee Edge Post Organizations Name Oauth1 Requesttokens Request Token
  x-api-slug: apigee-edge
  description: Revokes an OAuth 1.0 a request token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/requesttokens/{request_token}
  tags: Organizations,Oauth1,Requesttokens,Request,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1requesttokensrequest-token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1requesttokensrequest-token-post-openapi.md
- name: Apigee Edge Delete Organizations Name Oauth1 Requesttokens Request Token
  x-api-slug: apigee-edge
  description: Deletes the request token specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/requesttokens/{request_token}
  tags: Organizations,Oauth1,Requesttokens,Request,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1requesttokensrequest-token-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1requesttokensrequest-token-delete-openapi.md
- name: Apigee Edge Get Organizations Name Oauth1 Requesttokens
  x-api-slug: apigee-edge
  description: Returns list of all OAuth 1.0a request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/requesttokens
  tags: Organizations,Oauth1,Requesttokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1requesttokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1requesttokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Oauth1 Verifiers Verifier Code
  x-api-slug: apigee-edge
  description: Gets the detail of given verifier code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/verifiers/{verifier_code}
  tags: Organizations,Oauth1,Verifiers,Verifier,Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1verifiersverifier-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1verifiersverifier-code-get-openapi.md
- name: Apigee Edge Delete Organizations Name Oauth1 Verifiers Verifier Code
  x-api-slug: apigee-edge
  description: Deletes the specified verifier code, which is the verifier code given
    by the provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/verifiers/{verifier_code}
  tags: Organizations,Oauth1,Verifiers,Verifier,Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1verifiersverifier-code-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1verifiersverifier-code-delete-openapi.md
- name: Apigee Edge Get Organizations Name Oauth1 Verifiers
  x-api-slug: apigee-edge
  description: Gets a list of all verifiers and details for each verifier in an Organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/verifiers
  tags: Organizations,Oauth1,Verifiers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1verifiers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1verifiers-get-openapi.md
- name: Apigee Edge Get Organizations Name Oauth1 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Fetches the details of given access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/accesstokens/{access_token}
  tags: Organizations,Oauth1,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-get-openapi.md
- name: Apigee Edge Post Organizations Name Oauth1 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Revokes the specified access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/accesstokens/{access_token}
  tags: Organizations,Oauth1,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-post-openapi.md
- name: Apigee Edge Delete Organizations Name Oauth1 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Deletes the specified access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/accesstokens/{access_token}
  tags: Organizations,Oauth1,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1accesstokensaccess-token-delete-openapi.md
- name: Apigee Edge Get Organizations Name Oauth1 Accesstokens
  x-api-slug: apigee-edge
  description: Returns a count of all 1.0a access tokens in an orgnization .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth1/accesstokens
  tags: Organizations,Oauth1,Accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Oauth2 Authorizationcodes Authorization
    Code
  x-api-slug: apigee-edge
  description: Get a specific Authorization Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/authorizationcodes/{authorization_code}
  tags: Organizations,Oauth2,Authorizationcodes,Authorization,Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2authorizationcodesauthorization-code-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2authorizationcodesauthorization-code-get-openapi.md
- name: Apigee Edge Delete Organizations Name Oauth2 Authorizationcodes Authorization
    Code
  x-api-slug: apigee-edge
  description: Deletes the given authorization Code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/authorizationcodes/{authorization_code}
  tags: Organizations,Oauth2,Authorizationcodes,Authorization,Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2authorizationcodesauthorization-code-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2authorizationcodesauthorization-code-delete-openapi.md
- name: Apigee Edge Get Organizations Name Oauth2 Authorizationcodes
  x-api-slug: apigee-edge
  description: Lists all authorization codes in an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/authorizationcodes
  tags: Organizations,Oauth2,Authorizationcodes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2authorizationcodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2authorizationcodes-get-openapi.md
- name: Apigee Edge Get Organizations Name Oauth2 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Gets details of a specific access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/accesstokens/{access_token}
  tags: Organizations,Oauth2,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-get-openapi.md
- name: Apigee Edge Post Organizations Name Oauth2 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Revokes a specific access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/accesstokens/{access_token}
  tags: Organizations,Oauth2,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-post-openapi.md
- name: Apigee Edge Delete Organizations Name Oauth2 Accesstokens Access Token
  x-api-slug: apigee-edge
  description: Deletes a specific access token.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/accesstokens/{access_token}
  tags: Organizations,Oauth2,Accesstokens,Access,Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2accesstokensaccess-token-delete-openapi.md
- name: Apigee Edge Get Organizations Name Oauth2 Accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 2.0 access tokens under an organization .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/oauth2/accesstokens
  tags: Organizations,Oauth2,Accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/organizationsorg-nameoauth2accesstokens-get-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: OAuth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/oauth/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---