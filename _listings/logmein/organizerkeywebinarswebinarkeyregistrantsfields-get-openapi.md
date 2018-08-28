---
swagger: "2.0"
x-collection-name: LogMeIn
x-complete: 0
info:
  title: GoToWebinar Get registration fields
  description: Get registration fields.
  version: 1.0.0
host: api.getgo.com
basePath: /G2W/rest/organizers
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{organizerKey}/webinars/{webinarKey}/registrants/fields:
    get:
      summary: Get registration fields
      description: Get registration fields.
      operationId: WebinarsRegistrantsFieldsByOrganizerKeyAndWebinarKeyGet
      x-api-path-slug: organizerkeywebinarswebinarkeyregistrantsfields-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: organizerKey
      - in: path
        name: webinarKey
      responses:
        2:
          description: Successful response
        200:
          description: OK
      tags:
      - Registration
      - Fields
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---