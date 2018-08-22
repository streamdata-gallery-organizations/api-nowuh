{
  "info": {
    "name": "api.noahkoch.com /intakes/water",
    "_postman_id": "782eef84-d741-406b-9d1d-848d583d5a13",
    "description": "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "aece54c5-875b-47ef-bf58-5f4582ba0abb",
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
              "id": "e730b19a-c950-4aef-9cab-6d9c4ff8436b"
            }
          ]
        },
        {
          "id": "38b70ad1-01f3-4998-9559-5e5432354a2d",
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
              "id": "4783e5c0-3c7d-4594-9287-d5b09fa96faf"
            }
          ]
        },
        {
          "id": "74fc5437-e1d6-4634-bbd7-f34b98f6eb78",
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
              "id": "dfbd9ea8-dd6e-45b7-9082-57cddf9027a5"
            }
          ]
        },
        {
          "id": "bd1dfe46-0986-4fe6-be90-fef79b8042d5",
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
              "id": "aa1e1f53-5dbc-40bc-93c7-8ac822bfeb01"
            }
          ]
        },
        {
          "id": "a475bb17-0cc5-4761-b7a9-3a02bcc82436",
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
              "id": "d91981b0-03b4-4f9d-af12-327d02778be7"
            }
          ]
        },
        {
          "id": "d16ea1d0-7c90-4f38-9bb3-de3aa63fd226",
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
              "id": "5ed544dc-5f53-454c-80ea-ac64e8d41a8c"
            }
          ]
        }
      ]
    },
    {
      "name": "Transits",
      "item": [
        {
          "id": "6a19de39-ce94-42f5-9087-0d167f72a34a",
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
              "id": "499017e4-2d81-425b-ba99-66f55a456f34"
            }
          ]
        }
      ]
    },
    {
      "name": "Measurements",
      "item": [
        {
          "id": "92f0eac8-8376-4923-9ced-030108e55ead",
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
              "id": "a1eda76a-15cb-472a-b13b-b5704461b929"
            }
          ]
        },
        {
          "id": "b1f32744-9a69-48df-bdb1-b75c1f5b401e",
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
              "id": "1aa3ff69-50c0-40c5-9b7c-ba5860652ea7"
            }
          ]
        },
        {
          "id": "66a32484-3e8c-4f50-a0c3-13651206f5df",
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
              "id": "286800e5-8711-4309-b0d3-55c685fe2694"
            }
          ]
        }
      ]
    },
    {
      "name": "Intakes",
      "item": [
        {
          "id": "bce97031-2e95-4c57-b9ea-4d81dcce18f5",
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
              "id": "04b636aa-dc2a-47a6-8c6d-5ed7f25e4a80"
            }
          ]
        },
        {
          "id": "04552561-21d7-453a-b29c-93d8eb6c897b",
          "name": "IntakesWaterGet",
          "request": {
            "url": "http://api.noahkoch.com/v1/intakes/water",
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
              "id": "d622853e-9cc4-467f-a451-11875e5731fa"
            }
          ]
        }
      ]
    }
  ]
}