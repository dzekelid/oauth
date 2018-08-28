{
  "info": {
    "name": "Particle Add Oauth Token",
    "_postman_id": "29cc0d66-c32d-493b-ab54-23ea643113a4",
    "description": "Creates an access token that gives you access to the Cloud API.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth",
      "item": [
        {
          "id": "b6d91c64-a55d-49c5-90c6-e9fb8a97e8fa",
          "name": "postOauthToken",
          "request": {
            "url": "http://api.particle.io/v1/oauth/token",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "expires_at",
                  "value": "{}",
                  "disabled": false,
                  "description": "When should the token expire? This should be an ISO8601 formatted date string"
                },
                {
                  "key": "expires_in",
                  "value": "{}",
                  "disabled": false,
                  "description": "How many seconds the token will be valid for"
                },
                {
                  "key": "grant_type",
                  "value": "{}",
                  "disabled": false,
                  "description": "OAuth grant type"
                },
                {
                  "key": "password",
                  "value": "{}",
                  "disabled": false,
                  "description": "Your Particle account password"
                },
                {
                  "key": "username",
                  "value": "{}",
                  "disabled": false,
                  "description": "Your Particle account username"
                }
              ]
            },
            "description": "Creates an access token that gives you access to the Cloud API."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8eed3eee-0354-4061-b6ef-caa7d4b84360"
            }
          ]
        }
      ]
    }
  ]
}