---
swagger: "2.0"
x-collection-name: aWhere
x-complete: 0
info:
  title: aWhere Create a Field
  description: "####Request\nThis API call creates a field location in your account.
    Be sure to change the body payload. \n\n[Create Fields Documentation](http://developer.awhere.com/api/reference/fields/create-field)\n\n\n####Security\nThis
    API call uses the security Access Token that is retrieved with the \"Get a Token\"
    request. If you run that request first, it will save a token to Postman and this
    API will use it automatically. You can also see where the token should normally
    go by clicking the \"Headers\" tab below. The Authorization header holds the token,
    replacing the \"{{aWhereAccessToken}}\" part."
  version: 1.0.0
host: api.awhere.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/fields:
    get:
      summary: Get Fields List
      description: "####Request\nThis API call retrieves the list of fields in your
        account. \n\n[Get Fields Documentation](http://developer.awhere.com/api/reference/fields/get-fields)\n\n\n####Security\nThis
        API call uses the security Access Token that is retrieved with the \"Get a
        Token\" request. If you run that request first, it will save a token to Postman
        and this API will use it automatically. You can also see where the token should
        normally go by clicking the \"Headers\" tab below. The Authorization header
        holds the token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2FieldsGet
      x-api-path-slug: v2fields-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Fields
      - List
    post:
      summary: Create a Field
      description: "####Request\nThis API call creates a field location in your account.
        Be sure to change the body payload. \n\n[Create Fields Documentation](http://developer.awhere.com/api/reference/fields/create-field)\n\n\n####Security\nThis
        API call uses the security Access Token that is retrieved with the \"Get a
        Token\" request. If you run that request first, it will save a token to Postman
        and this API will use it automatically. You can also see where the token should
        normally go by clicking the \"Headers\" tab below. The Authorization header
        holds the token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2FieldsPost
      x-api-path-slug: v2fields-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Field
  /v2/fields/field1:
    get:
      summary: Get a Single Field by ID
      description: |-
        ####Request
        This API call retrieves a single field by ID.

        [Get Fields Documentation](http://developer.awhere.com/api/reference/fields/get-fields)


        ####Security
        This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
      operationId: V2FieldsField1Get
      x-api-path-slug: v2fieldsfield1-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Single
      - Field
      - By
      - ID
    patch:
      summary: Update Field
      description: |-
        ####Request
        This API call shows how to update the farm ID on a field location. You can also change the name.

        [Update Field Documentation](http://developer.awhere.com/api/reference/fields/update-field)


        ####Security
        This API call uses the security Access Token that is retrieved with the "Get a Token" request. If you run that request first, it will save a token to Postman and this API will use it automatically. You can also see where the token should normally go by clicking the "Headers" tab below. The Authorization header holds the token, replacing the "{{aWhereAccessToken}}" part.
      operationId: V2FieldsField1Patch
      x-api-path-slug: v2fieldsfield1-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Field
  /v2/agronomics/fields/field1/plantings:
    get:
      summary: Get Plantings List for a Field
      description: "####Request\nThis API call retrieves the list of plantings for
        a specific field in your account. \n\n[Get Plantings Documentation](http://developer.awhere.com/api/reference/plantings/get-plantings)\n\n\n####Security\nThis
        API call uses the security Access Token that is retrieved with the \"Get a
        Token\" request. If you run that request first, it will save a token to Postman
        and this API will use it automatically. You can also see where the token should
        normally go by clicking the \"Headers\" tab below. The Authorization header
        holds the token, replacing the \"{{aWhereAccessToken}}\" part."
      operationId: V2AgronomicsFieldsField1PlantingsGet
      x-api-path-slug: v2agronomicsfieldsfield1plantings-get
      responses:
        200:
          description: OK
      tags:
      - Agriculture
      - Plantings
      - Lista
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