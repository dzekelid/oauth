{
  "info": {
    "name": "Apigee Edge Get Organizations Name Oauth1 Verifiers Verifier Code",
    "_postman_id": "21446bee-406a-4444-9fc3-e5c3ad0bf441",
    "description": "Gets the detail of given verifier code.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Organizations",
      "item": [
        {
          "id": "9d6fbae2-dda9-4645-90a1-b515e5c3073d",
          "name": "getOrganizationsOrgNameOauth1VerifiersVerifierCode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.enterprise.apigee.com",
              "path": [
                "v1",
                "organizations/:org_name/oauth1/verifiers/:verifier_code"
              ],
              "variable": [
                {
                  "id": "org_name",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "verifier_code",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the detail of given verifier code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5af2e52d-78bd-482e-b233-a2b2b139b8af"
            }
          ]
        }
      ]
    }
  ]
}