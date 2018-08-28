---
swagger: "2.0"
x-collection-name: GoToMeeting
x-complete: 0
info:
  title: Go To Webinar Get registration fields
  description: Retrieve required, optional registration, and custom questions for
    a specified webinar.
  termsOfService: https://developer.citrixonline.com/terms-use
  contact:
    name: Developer Support
    url: https://developer.citrixonline.com
    email: developer-support@citrixonline.com
  version: 1.0.0
host: api.citrixonline.com
basePath: /G2W/rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizers/{organizerKey}/webinars/{webinarKey}/registrants/fields:
    get:
      summary: Get registration fields
      description: Retrieve required, optional registration, and custom questions
        for a specified webinar.
      operationId: getRegistrationFields
      x-api-path-slug: organizersorganizerkeywebinarswebinarkeyregistrantsfields-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Organizers
      - OrganizerKey
      - Webinars
      - WebinarKey
      - Registrants
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