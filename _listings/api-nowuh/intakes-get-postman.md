{
  "info": {
    "name": "api.noahkoch.com /intakes",
    "_postman_id": "e5f0fa0d-5868-4de1-94d7-802a92ef2419",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "90090c57-542b-42b1-8649-e2896c1ec596",
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
              "id": "28b653d4-18a1-47c7-b0bd-c751242fb504"
            }
          ]
        },
        {
          "id": "7c517a67-3f65-46a8-89fd-4559d9a75e2d",
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
              "id": "4307c684-8ec2-4030-bfc3-d94f5dc9f20d"
            }
          ]
        },
        {
          "id": "1b8061bc-fa47-4118-b11b-2906c34fc230",
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
              "id": "986b86cb-1b8c-4a7d-9594-b5e98bf4a448"
            }
          ]
        },
        {
          "id": "46747d12-b130-48bb-bc40-9624eb0e294b",
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
              "id": "a94f8104-e498-43f0-8b82-189362e85c63"
            }
          ]
        },
        {
          "id": "c99534af-cc22-4b4e-b396-79618ac8e191",
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
              "id": "7b0c0759-7bf6-4990-94f4-11ac03a59d18"
            }
          ]
        },
        {
          "id": "96c447e6-64a6-4a53-afa0-08827781ddbf",
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
              "id": "4a03a249-3497-4205-8be6-ecab130cc5ea"
            }
          ]
        }
      ]
    },
    {
      "name": "Transits",
      "item": [
        {
          "id": "02b199c8-ad06-4bf8-8afe-74a83d3353ed",
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
              "id": "39075abd-b873-48e8-82bd-e431f139a33a"
            }
          ]
        }
      ]
    },
    {
      "name": "Measurements",
      "item": [
        {
          "id": "9bb47557-7e9e-447f-b46a-3b3870682124",
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
              "id": "b282aab7-baa7-4b12-bfcc-6889db194561"
            }
          ]
        },
        {
          "id": "b652203e-c82d-45e2-8a35-2506d1942e60",
          "name": "MeasurementsWeightInPoundsGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/measurements/weight_in_pounds",
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
              "id": "adf591ca-00b1-4bf3-ab67-3258e20b1c9f"
            }
          ]
        },
        {
          "id": "41965ff7-cc49-4762-9d05-b68b14294008",
          "name": "MeasurementsWeightInKilosGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/measurements/weight_in_kilos",
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
              "id": "fc0949d4-2ed6-4fc0-b25f-e0e6bd1c52a1"
            }
          ]
        }
      ]
    },
    {
      "name": "Intakes",
      "item": [
        {
          "id": "764e2a04-c35e-4ecc-9bf6-75f2587b2921",
          "name": "IntakesGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/intakes",
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
            "description": "/intakes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1af216d6-6081-4337-8370-af5339ae9e03"
            }
          ]
        }
      ]
    }
  ]
}