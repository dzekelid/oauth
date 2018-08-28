{
  "info": {
    "name": "Dezrez Get the oauth url for the google analytics integration service",
    "_postman_id": "f18edb3f-ba12-4e45-aa44-4b4ae7ea9d9e",
    "description": "Get the oauth url for the google analytics integration service.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth",
      "item": [
        {
          "id": "f7447702-eec4-4e1a-86e2-11dfebf04b37",
          "name": "Sync_GoogleAnalyticsOauthUrlBybrandIdBypersonId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/sync/googleanalyticsoauthurl/:brandId/:personId"
              ],
              "variable": [
                {
                  "id": "brandId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get the oauth url for the google analytics integration service."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ebb93f1-5f72-4a38-aa08-7887745a3542"
            }
          ]
        }
      ]
    }
  ]
}