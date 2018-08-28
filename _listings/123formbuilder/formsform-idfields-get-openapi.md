---
swagger: "2.0"
x-collection-name: 123FormBuilder
x-complete: 0
info:
  title: 123FormBuilder Get form fields
  version: 1.0.0
  description: Get the details of a single form and its fields
host: api.123contactform.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /forms/{form_id}/fields:
    get:
      summary: Get form fields
      description: Get the details of a single form and its fields
      operationId: get-the-details-of-a-single-form-and-its-fields
      x-api-path-slug: formsform-idfields-get
      parameters:
      - in: path
        name: form_id
        description: The ID of the form
      - in: query
        name: JWT
        description: JWT authentication token
      responses:
        200:
          description: OK
      tags:
      - Form
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