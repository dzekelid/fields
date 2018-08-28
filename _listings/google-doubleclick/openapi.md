swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
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