swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 1
info:
  title: IDX API 1.4.0 Test Runner
  description: idx-broker-api-calls-in-version-1-4-0required-environment-variable-url-environment-variable-for-request-headers-environment-variable-partner-key-client-account-with-at-least-one-featured-listingtests-are-in-this-order-as-variables-such-as-listing-id-and-approved-mls-are-passed-to-subsequent-api-calls-
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /clients/listallowedfields/{approvedMLS}/{featuredId}:
    get:
      summary: Get List Allowed Fields Approved MLS Featured
      description: Returns the allowed returnable fields for a given listingID.
      operationId: ClientsListallowedfieldsByApprovedMLSAndFeaturedIdGet
      x-api-path-slug: clientslistallowedfieldsapprovedmlsfeaturedid-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: path
        name: featuredId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - List
      - Owed
      - Fields
      - Approved
      - MLS
      - Featured
  /mls/searchfieldvalues/{approvedMLS}:
    get:
      summary: Get Mls Search Field Values Approved MLS
      description: Field values in a given MLS that are currently allowed to be searched
        according to MLS guidelines.
      operationId: MlsSearchfieldvaluesByApprovedMLSGet
      x-api-path-slug: mlssearchfieldvaluesapprovedmls-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: path
        name: approvedMLS
      - in: header
        name: Content-Type
      - in: query
        name: mlsPtID
      - in: query
        name: name
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Mls
      - Search
      - Field
      - Values
      - Approved
      - MLS