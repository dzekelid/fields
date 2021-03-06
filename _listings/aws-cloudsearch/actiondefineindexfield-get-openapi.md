---
swagger: "2.0"
x-collection-name: AWS CloudSearch
x-complete: 0
info:
  title: AWS CloudSearch Define Index Field
  version: 1.0.0
  description: Configures an ndexField  for the search domain.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeIndexFields:
    get:
      summary: Describe Index Fields
      description: Gets information about the index fields configured for the search
        domain.
      operationId: DescribeIndexFields
      x-api-path-slug: actiondescribeindexfields-get
      parameters:
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      - in: query
        name: FieldNames.member.N
        description: A list of the index fields you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Index Fields
  /?Action=DefineIndexField:
    get:
      summary: Define Index Field
      description: Configures an ndexField  for the search domain.
      operationId: DefineIndexField
      x-api-path-slug: actiondefineindexfield-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: IndexField
        description: The index field and field options you want to configure
        type: string
      responses:
        200:
          description: OK
      tags:
      - Index Fields
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