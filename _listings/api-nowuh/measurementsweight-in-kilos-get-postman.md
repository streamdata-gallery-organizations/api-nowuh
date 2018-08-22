{
  "info": {
    "name": "api.noahkoch.com /measurements/weight_in_kilos",
    "_postman_id": "4959f143-f6e2-4c70-b1a5-bec92b8d00fd",
    "description": "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "63c119d5-acdf-4d0c-8c07-47150b73bea9",
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
              "id": "abe81647-def4-4ecf-9c32-2cf8b4956a75"
            }
          ]
        },
        {
          "id": "5ab37271-7e92-41c8-a715-d487520771ae",
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
              "id": "92752050-6879-4f49-9569-69e9d167184b"
            }
          ]
        },
        {
          "id": "130064b3-d7b5-4f3b-a95d-fdfa74c5e70c",
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
              "id": "d7896493-a1b4-4d54-8427-db67d1908210"
            }
          ]
        },
        {
          "id": "e7c84d51-cbe8-48b7-8a04-3f95bd9a451b",
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
              "id": "b35e538b-dae6-4b7b-9732-730467d34aa1"
            }
          ]
        },
        {
          "id": "63dab9a5-fa9c-41e9-82bf-73f8c4d3395d",
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
              "id": "fca19839-288a-412d-a871-06efb970fb54"
            }
          ]
        },
        {
          "id": "b727672c-405a-4422-845a-e6ede293f50a",
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
              "id": "7ad78005-642a-456f-8625-541f7554306f"
            }
          ]
        }
      ]
    },
    {
      "name": "Transits",
      "item": [
        {
          "id": "8c7a3552-fe40-44be-aa1c-6908dc763443",
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
              "id": "45496219-392a-4c2b-ab12-9daca844b117"
            }
          ]
        }
      ]
    },
    {
      "name": "Measurements",
      "item": [
        {
          "id": "b589f3bf-c440-4c9d-9842-a87e87f1e201",
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
              "id": "ccbda4a5-4be4-4e72-9f05-7324356d3783"
            }
          ]
        },
        {
          "id": "fc4ec83e-fb61-4438-81c5-3293a64aba75",
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
              "id": "f1765154-89f5-4248-bfc1-f774c53b2a75"
            }
          ]
        },
        {
          "id": "5148128a-8552-4230-bf73-0a48752736e1",
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
              "id": "2bc6da0b-89cc-49f9-bbc8-f335fb031168"
            }
          ]
        }
      ]
    }
  ]
}