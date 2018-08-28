swagger: "2.0"
x-collection-name: Bureau of Justice Statistics
x-complete: 1
info:
  title: National Crime Victimization Survey (NCVS) API
  description: the-ncvs-national-crime-victimization-survey-restful-api-is-a-web-service-that-provides-criminal-victimization-data-obtained-annually-from-a-nationally-representative-sample-of-about-79800-households-and-143210-persons-interviewed-each-year--
  version: v2
host: www.bjs.gov
basePath: /bjs/ncvs/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  v2/household/fields/:
    get:
      summary: Get Household Fields
      description: Returns a description of the fields/columns used returned in the
        household data sets.
      operationId: getV2HouseholdFields
      x-api-path-slug: v2householdfields-get
      responses:
        200:
          description: OK
      tags:
      - Household
      - Fields
  v2/personal/fields/:
    get:
      summary: Get Personal Fields
      description: Returns a description of the fields/columns used returned in the
        personal data sets.
      operationId: getV2PersonalFields
      x-api-path-slug: v2personalfields-get
      responses:
        200:
          description: OK
      tags:
      - Personal
      - Fields