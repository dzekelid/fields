---
swagger: "2.0"
x-collection-name: moltin
x-complete: 0
info:
  title: Moltin API Create a field
  description: Create a field.
  version: 1.0.0
host: api.moltin.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/flows/{flowSlug}/fields:
    get:
      summary: Get all fields on a flow
      description: Get all fields on a flow.
      operationId: V2FlowsFieldsByFlowSlugGet
      x-api-path-slug: v2flowsflowslugfields-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: flowSlug
      responses:
        200:
          description: Successful response
      tags:
      - Fields
      - "On"
      - Flow
  /v2/fields:
    get:
      summary: Get a field list
      description: Get a field list.
      operationId: V2FieldsGet
      x-api-path-slug: v2fields-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Field
      - List
    post:
      summary: Create a field
      description: Create a field.
      operationId: V2FieldsPost
      x-api-path-slug: v2fields-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Field
  /v2/fields/{fieldID}:
    get:
      summary: Get a field
      description: Get a field.
      operationId: V2FieldsByFieldIDGet
      x-api-path-slug: v2fieldsfieldid-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: fieldID
      responses:
        200:
          description: Successful response
      tags:
      - Field
    put:
      summary: Update a field
      description: Update a field.
      operationId: V2FieldsByFieldIDPut
      x-api-path-slug: v2fieldsfieldid-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: fieldID
      responses:
        200:
          description: Successful response
      tags:
      - Field
    delete:
      summary: Delete a field
      description: Delete a field.
      operationId: V2FieldsByFieldIDDelete
      x-api-path-slug: v2fieldsfieldid-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: fieldID
      responses:
        200:
          description: Successful response
      tags:
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