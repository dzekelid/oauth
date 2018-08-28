{
  "info": {
    "name": "Bitly User API OAuth App",
    "_postman_id": "2a5ecce9-c70f-4113-b195-db3422eabf16",
    "description": "Return information about an OAuth app.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "OAuth",
      "item": [
        {
          "id": "7694db14-12a0-48f9-8a08-a0a45ace3320",
          "name": "oauthApp",
          "request": {
            "url": "http://api-ssl.bitly.com/v3/v3/oauth/app?client_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return information about an OAuth app."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6aaaa08-c8b2-498d-a1a6-fdff5cdf0a2a"
            }
          ]
        }
      ]
    }
  ]
}