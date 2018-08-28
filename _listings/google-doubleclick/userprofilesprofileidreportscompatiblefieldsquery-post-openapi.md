---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Return Compatible Fields
  version: 1.0.0
  description: Returns the fields that are compatible to be selected in the respective
    sections of a report criteria, given the fields already selected in the input
    report and user permissions.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/reports/compatiblefields/query:
    post:
      summary: Return Compatible Fields
      description: Returns the fields that are compatible to be selected in the respective
        sections of a report criteria, given the fields already selected in the input
        report and user permissions.
      operationId: dfareporting.reports.compatibleFields.query
      x-api-path-slug: userprofilesprofileidreportscompatiblefieldsquery-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: The DFA user profile ID
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Field
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