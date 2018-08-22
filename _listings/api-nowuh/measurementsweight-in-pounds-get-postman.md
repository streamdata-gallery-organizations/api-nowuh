{
  "info": {
    "name": "api.noahkoch.com /measurements/weight_in_pounds",
    "_postman_id": "e88d6783-c7ac-4d3e-9451-4df8e4930dfa",
    "description": "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Activities",
      "item": [
        {
          "id": "f22b5373-53d4-44a1-adae-8d7212185335",
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
              "id": "4d595c7e-ff11-4ccf-9618-76447cb87993"
            }
          ]
        },
        {
          "id": "cb8fc10a-3070-4e9e-a57d-2296a9ef82c3",
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
              "id": "c3a3ee54-ad34-4ac8-bf16-521068db0128"
            }
          ]
        },
        {
          "id": "fd8d5138-ef9a-4784-80b8-532218b6256a",
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
              "id": "4cb6d6b2-f811-44aa-a51a-c05daccfcaaf"
            }
          ]
        },
        {
          "id": "f3f0decc-0071-4811-924f-b081ae7ceb97",
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
              "id": "a6d84475-7dd4-4658-91d7-5a14755d7350"
            }
          ]
        },
        {
          "id": "cf323bf5-b8b2-408f-9b60-d6cdc65ac2b4",
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
              "id": "4c1b1295-f5f8-4ff0-a2c0-b94021c5afe8"
            }
          ]
        },
        {
          "id": "2b68209a-b062-40a3-8471-25c15fb3e480",
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
              "id": "27556db3-a8d4-453e-86ee-b7f37907e5e3"
            }
          ]
        }
      ]
    },
    {
      "name": "Transits",
      "item": [
        {
          "id": "bad11f86-681a-4c3f-b2e0-1ec0956dc983",
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
              "id": "b13a3f20-13c2-4ed3-9345-88c2abcafc66"
            }
          ]
        }
      ]
    },
    {
      "name": "Measurements",
      "item": [
        {
          "id": "a14d4249-cb45-4e0b-a916-77bc511ce43e",
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
              "id": "59a8bb30-6172-4fd3-b5f5-1a0931520555"
            }
          ]
        },
        {
          "id": "97da4072-9d37-4e7c-9205-72daf4517d47",
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
              "id": "47c3ab9a-493d-4e4a-bb97-ccd6f697e74e"
            }
          ]
        }
      ]
    }
  ]
}