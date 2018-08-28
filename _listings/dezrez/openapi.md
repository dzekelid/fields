swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
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
  /api/customfieldgroup/{typeName}:
    get:
      summary: Get a list of custom field groups for a type and optional group name
        specified.
      description: Get a list of custom field groups for a type and optional group
        name specified..
      operationId: CustomFieldGroup_GetBytypeNameBygroupName
      x-api-path-slug: apicustomfieldgrouptypename-get
      parameters:
      - in: query
        name: groupName
        description: An optional parameter to filter by group name
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: typeName
        description: The name of the type to get the custom field groups for
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Custom
      - Field
      - Groupsa
      - Type
      - Optional
      - Group
      - Name
      - Specified
  /api/CustomField:
    put:
      summary: ""
      description: .
      operationId: CustomField_SaveCustomFieldValueBysaveCustomFieldValueCommandSaveDataContract
      x-api-path-slug: apicustomfield-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: saveCustomFieldValueCommandSaveDataContract
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - ""