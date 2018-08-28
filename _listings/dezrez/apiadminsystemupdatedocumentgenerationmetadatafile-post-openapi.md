---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Updates the metadata for document generation merge fields
  version: 1.0.0
  description: Updates the metadata for document generation merge fields.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/searchmergefields:
    get:
      summary: Search Merge Fields
      description: Search merge fields.
      operationId: DocumentGeneration_SearchMergeFieldsBypartialName
      x-api-path-slug: apidocumentgenerationsearchmergefields-get
      parameters:
      - in: query
        name: partialName
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Search
      - Merge
      - Fields
  /api/admin/system/updateDocumentGenerationMetadataFile:
    post:
      summary: Updates the metadata for document generation merge fields
      description: Updates the metadata for document generation merge fields.
      operationId: System_UpdateDocumentGenerationMetadataFile
      x-api-path-slug: apiadminsystemupdatedocumentgenerationmetadatafile-post
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Metadatadocument
      - Generation
      - Merge
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