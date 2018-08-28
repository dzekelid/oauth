{
  "info": {
    "name": "Dezrez Get the oauth url for the calendar sync service",
    "_postman_id": "eb62a246-b84b-4c36-bc7c-1130e81d6e3e",
    "description": "Get the oauth url for the calendar sync service.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Initially",
      "item": [
        {
          "id": "c54939a3-10c1-4133-a3ef-b8f78a53dd3e",
          "name": "Sync_CalendarBypersonId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/sync/calendarsetup/:personId"
              ],
              "variable": [
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
            "description": "Initially setup the calendar, create rezi calendar, copy upto 16 days prior into calendar, create a subscription channel for the callback."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "183daeaf-45ba-41cb-815f-35dc796461d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Oauth",
      "item": [
        {
          "id": "9ef179bc-b12d-423b-97c6-e6364fa9fb43",
          "name": "Sync_CalendarSyncOauthUrlBypersonId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/sync/calendarsyncoauthurl/:personId"
              ],
              "variable": [
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
            "description": "Get the oauth url for the calendar sync service."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84c58b2e-65f4-4508-9d8a-181403d93df6"
            }
          ]
        }
      ]
    }
  ]
}