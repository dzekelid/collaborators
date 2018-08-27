{
  "info": {
    "name": "App Veyor Get Collaborators",
    "_postman_id": "849f3b99-de3f-4211-88e4-3407578d3ce1",
    "description": "Get collaborators.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Collaborators",
      "item": [
        {
          "id": "69bd47a6-b007-4850-aae7-6876988dc630",
          "name": "getCollaborators",
          "request": {
            "url": "http://ci.appveyor.com/api/collaborators",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get collaborators."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74a8d40b-aeb1-4ed4-a92c-24a3240016b3"
            }
          ]
        }
      ]
    }
  ]
}