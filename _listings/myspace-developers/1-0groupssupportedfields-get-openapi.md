---
swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 0
info:
  title: My Space Get Groups Supported Fields
  description: Retrieves all supported fields.
  version: 1.0.0
host: api.myspace.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1.0/mediaItems/@supportedFields:
    get:
      summary: Get Mediaitems Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.mediaItems._supportedFields.get
      x-api-path-slug: 1-0mediaitemssupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - Supported
      - Fields
  /1.0/people/@supportedFields:
    get:
      summary: Get People Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.people._supportedFields.get
      x-api-path-slug: 1-0peoplesupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - People
      - Supported
      - Fields
  /1.0/groups/@supportedFields:
    get:
      summary: Get Groups Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.groups._supportedFields.get
      x-api-path-slug: 1-0groupssupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: 'The following field names are supported: id and title'
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Supported
      - Fields
  /1.0/albums/@supportedFields:
    get:
      summary: Get Albums Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.albums._supportedFields.get
      x-api-path-slug: 1-0albumssupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - Albums
      - Supported
      - Fields
  /1.0/activities/@supportedFields:
    get:
      summary: Get Activities Supported Fields
      description: Retrieves all supported fields.
      operationId: 1.0.activities._supportedFields.get
      x-api-path-slug: 1-0activitiessupportedfields-get
      parameters:
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      - in: query
        name: updatedSince
        description: Indicates the date before which no activities should be returned
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Supported
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