{
  "info": {
    "name": "api.noahkoch.com /measurements",
    "_postman_id": "50325296-8824-479f-96da-2cec3a757d0f",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "e022d1ad-2b3d-4a68-b0be-514008f53081",
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
              "id": "a789cc79-1670-46d6-9d33-297a7b561f60"
            }
          ]
        },
        {
          "id": "92da09cd-477d-453c-8396-932d3fa43edc",
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
              "id": "f814e7f9-2571-416a-9e11-6907d596e37c"
            }
          ]
        },
        {
          "id": "bea71381-b763-4b1c-a49a-72033fe1bcf2",
          "name": "ActivitiesDistanceGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/activities/distance",
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
              "id": "7a3f4e9d-a7f7-4813-9036-5fc670dc4608"
            }
          ]
        },
        {
          "id": "ca5344fb-325f-447b-84ee-5bd6e0a0fc89",
          "name": "ActivitiesSleepQualityGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/activities/sleep_quality",
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
            "description": "All durations are in seconds. Date refers to the night I went to sleep, not the night I woke up.\n\nTo get the total sleep time either use the `/activities/sleep_time` endpoint or add      \n```\nwakeupduration + lightsleepduration + deepsleepduration\n```\n\n\n**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "431595e0-5aa5-4dd8-b942-2b4ad860545d"
            }
          ]
        },
        {
          "id": "91d8e2e1-e743-4e7a-b3ce-71faeb2aab77",
          "name": "ActivitiesSleepTimeGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/activities/sleep_time",
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
            "description": "Sleep time duration is returned in seconds. Date refers to the night I went to sleep, not the night I woke up.\n\n**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7869ede3-5ad0-4e11-9e9b-cd02cd2f2ee6"
            }
          ]
        },
        {
          "id": "3608069f-3a2b-4b28-803d-dcfcc343855b",
          "name": "ActivitiesProductivityGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/activities/productivity",
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
              "id": "ad96a27b-1222-4c7d-a069-8c4763f80773"
            }
          ]
        }
      ]
    },
    {
      "name": "Transits",
      "item": [
        {
          "id": "4209380c-5573-43b7-a92d-449ae58e9dba",
          "name": "TransitsGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/transits",
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
            "description": "/transits"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03ccc69c-8fbc-4ff4-b868-b150eed0490e"
            }
          ]
        }
      ]
    },
    {
      "name": "Measurements",
      "item": [
        {
          "id": "00410dfd-3dde-46ca-a115-6291ece24546",
          "name": "MeasurementsGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/measurements",
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
            "description": "/measurements"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a0f6ff6-c30e-4ed2-ab4f-3023806f4084"
            }
          ]
        }
      ]
    }
  ]
}