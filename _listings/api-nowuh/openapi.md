---
swagger: "2.0"
x-collection-name: API.nowuh
x-complete: 1
info:
  title: API.noah
  description: for-more-information-on-the-project-background-visit-api-noahkoch-comhttpsapi-noahkoch-comapi-base-httpsapi-noahkoch-comv1
  version: "1.0"
host: api.noahkoch.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /activities:
    get:
      summary: /activities
      description: ""
      operationId: ActivitiesGet
      x-api-path-slug: activities-get
      responses:
        200:
          description: OK
      tags:
      - Activities
  /activities/steps:
    get:
      summary: /activities/steps
      description: "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]`
        *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
      operationId: ActivitiesStepsGet
      x-api-path-slug: activitiessteps-get
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Steps
  /activities/distance:
    get:
      summary: /activities/distance
      description: "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]`
        *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
      operationId: ActivitiesDistanceGet
      x-api-path-slug: activitiesdistance-get
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Distance
  /activities/sleep_quality:
    get:
      summary: /activities/sleep_quality
      description: "All durations are in seconds. Date refers to the night I went
        to sleep, not the night I woke up.\n\nTo get the total sleep time either use
        the `/activities/sleep_time` endpoint or add      \n```\nwakeupduration +
        lightsleepduration + deepsleepduration\n```\n\n\n**Optional Params**\n\n`sort=[asc|desc]`
        *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`
        \   \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
      operationId: ActivitiesSleepQualityGet
      x-api-path-slug: activitiessleep-quality-get
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Sleep
      - Quality
  /activities/sleep_time:
    get:
      summary: /activities/sleep_time
      description: "Sleep time duration is returned in seconds. Date refers to the
        night I went to sleep, not the night I woke up.\n\n**Optional Params**\n\n`sort=[asc|desc]`
        *Default: desc*    \n`page=[integer]` *Default: 1*    \n`date=[yyyy-mm-dd]`
        \   \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
      operationId: ActivitiesSleepTimeGet
      x-api-path-slug: activitiessleep-time-get
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Sleep
      - Time
  /activities/productivity:
    get:
      summary: /activities/productivity
      description: "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]`
        *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
      operationId: ActivitiesProductivityGet
      x-api-path-slug: activitiesproductivity-get
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Productivity
  /transits:
    get:
      summary: /transits
      description: ""
      operationId: TransitsGet
      x-api-path-slug: transits-get
      responses:
        200:
          description: OK
      tags:
      - Transits
  /measurements:
    get:
      summary: /measurements
      description: ""
      operationId: MeasurementsGet
      x-api-path-slug: measurements-get
      responses:
        200:
          description: OK
      tags:
      - Measurements
  /measurements/weight_in_pounds:
    get:
      summary: /measurements/weight_in_pounds
      description: "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]`
        *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
      operationId: MeasurementsWeightInPoundsGet
      x-api-path-slug: measurementsweight-in-pounds-get
      responses:
        200:
          description: OK
      tags:
      - Measurements
      - Weight
      - In
      - Pounds
  /measurements/weight_in_kilos:
    get:
      summary: /measurements/weight_in_kilos
      description: "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]`
        *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
      operationId: MeasurementsWeightInKilosGet
      x-api-path-slug: measurementsweight-in-kilos-get
      responses:
        200:
          description: OK
      tags:
      - Measurements
      - Weight
      - In
      - Kilos
  /intakes:
    get:
      summary: /intakes
      description: ""
      operationId: IntakesGet
      x-api-path-slug: intakes-get
      responses:
        200:
          description: OK
      tags:
      - Intakes
  /intakes/water:
    get:
      summary: /intakes/water
      description: "**Optional Params**\n\n`sort=[asc|desc]` *Default: desc*    \n`page=[integer]`
        *Default: 1*    \n`date=[yyyy-mm-dd]`    \n`start_date=[yyyy-mm-dd]`   \n`end_date=[yyyy-mm-dd]`"
      operationId: IntakesWaterGet
      x-api-path-slug: intakeswater-get
      responses:
        200:
          description: OK
      tags:
      - Intakes
      - Water
---