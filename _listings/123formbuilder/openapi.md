swagger: "2.0"
x-collection-name: 123FormBuilder
x-complete: 1
info:
  title: ""
  version: 1.0.0
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