{
  "info": {
    "name": "api.noahkoch.com /activities",
    "_postman_id": "8ffe12e4-fbd1-4af4-b43f-5c6fc4a048b4",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "d83f931c-e517-4671-97f3-497cb31f6a32",
          "name": "ActivitiesGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/activities",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "/activities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "484269e0-8cb7-4176-b3e1-e06806439d7d"
            }
          ]
        }
      ]
    }
  ]
}