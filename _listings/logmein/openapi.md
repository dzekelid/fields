swagger: "2.0"
x-collection-name: LogMeIn
x-complete: 1
info:
  title: GoToWebinar API
  description: todo-add-description
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