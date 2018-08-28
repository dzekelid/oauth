{
  "info": {
    "name": "Digital River Shopper API Post Oauth20 Token",
    "_postman_id": "22aae90f-f210-4004-b32c-4be75437259d",
    "description": "Post oauth20 token.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "de4741bc-37f6-4cb2-bf0b-99a3f987c6e5",
          "name": "getOauth20Authorize",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/authorize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get oauth20 authorize."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea70d16a-6a1f-4eda-870f-efd0f014ab0f"
            }
          ]
        },
        {
          "id": "4f6ea4b6-b93d-417f-a96c-a60118a193d4",
          "name": "postOauth20Token",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/token",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post oauth20 token."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0280c817-3ab0-482f-b199-fae08c53a765"
            }
          ]
        }
      ]
    }
  ]
}