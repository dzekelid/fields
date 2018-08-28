---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Get all screen tab fields
  description: Gets all fields for a given tab
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/field:
    get:
      summary: Get fields
      description: |-
        Returns all issue fields in Jira, both system and custom fields.

        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None, however the following rules apply:

        *   Fields that cannot be added to the issue navigator are always returned.
        *   Fields that cannot be placed on an issue screen are always returned.
        *   Fields that depend on global Jira settings are only returned if the setting is enabled. That is, timetracking fields, subtasks, votes, and watches.
        *   For all other fields, this method only returns the fields that the current user has permission to see (that is, the field can be used in at least one project that the user can see).
      operationId: com.atlassian.jira.rest.v2.issue.FieldResource.getFields_get
      x-api-path-slug: api2field-get
      responses:
        200:
          description: OK
      tags:
      - Fields
  /api/2/screens/{screenId}/availableFields:
    get:
      summary: Get available screen fields
      description: Gets available fields for screen. i.e ones that haven't already
        been added.
      operationId: com.atlassian.jira.rest.v2.issue.ScreensResource.getAvailableScreenFields_get
      x-api-path-slug: api2screensscreenidavailablefields-get
      parameters:
      - in: path
        name: screenId
        description: id of screen
      responses:
        200:
          description: OK
      tags:
      - Available
      - Screen
      - Fields
  /api/2/screens/{screenId}/tabs/{tabId}/fields:
    get:
      summary: Get all screen tab fields
      description: Gets all fields for a given tab
      operationId: com.atlassian.jira.rest.v2.issue.ScreensResource.getAllScreenTabFields_get
      x-api-path-slug: api2screensscreenidtabstabidfields-get
      parameters:
      - in: query
        name: projectKey
        description: the key of the project; this parameter is optional
      - in: path
        name: screenId
        description: id of screen
      - in: path
        name: tabId
        description: id of tab
      responses:
        200:
          description: OK
      tags:
      - Screen
      - Tab
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