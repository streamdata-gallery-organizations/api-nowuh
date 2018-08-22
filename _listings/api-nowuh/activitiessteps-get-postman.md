{
  "info": {
    "name": "api.noahkoch.com /activities/steps",
    "_postman_id": "404a949a-18d6-44e7-a76b-5d16087e141a",
    "description": "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "16be3cea-ded0-400b-a270-3c5337dae575",
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
              "id": "fcb52c53-baa1-42c5-bcb9-8c6e2f0a07e5"
            }
          ]
        },
        {
          "id": "7d977c82-52f7-46c0-8a30-43977093f4bf",
          "name": "ActivitiesStepsGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/activities/steps",
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
            "description": "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de1d3fb6-7589-4084-8bc8-a58adc0f5504"
            }
          ]
        }
      ]
    }
  ]
}