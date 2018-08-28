---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Fields
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: Jira Cloud REST API - Get fields
  x-api-slug: api2field-get
  description: |-
    Returns all issue fields in Jira, both system and custom fields.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None, however the following rules apply:

    *   Fields that cannot be added to the issue navigator are always returned.
    *   Fields that cannot be placed on an issue screen are always returned.
    *   Fields that depend on global Jira settings are only returned if the setting is enabled. That is, timetracking fields, subtasks, votes, and watches.
    *   For all other fields, this method only returns the fields that the current user has permission to see (that is, the field can be used in at least one project that the user can see).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-get-openapi.md
- name: Jira Cloud REST API - Get available screen fields
  x-api-slug: api2screensscreenidavailablefields-get
  description: Gets available fields for screen. i.e ones that haven't already been
    added.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidavailablefields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidavailablefields-get-openapi.md
- name: Jira Cloud REST API - Get all screen tab fields
  x-api-slug: api2screensscreenidtabstabidfields-get
  description: Gets all fields for a given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-get-openapi.md
- name: Jira Cloud REST API - Get custom field option
  x-api-slug: api2customfieldoptionid-get
  description: "Returns a custom field option. For example, an option in a cascading
    select list.  \n  \n**[Permissions](https://developer.atlassian.com/cloud/jira/platform/rest/#permissions)
    required:** None."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2customfieldoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2customfieldoptionid-get-openapi.md
- name: Jira Cloud REST API - Create custom field
  x-api-slug: api2field-post
  description: |-
    Creates a custom field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-post-openapi.md
- name: Jira Cloud REST API - Get all issue field options
  x-api-slug: api2fieldfieldkeyoption-get
  description: |-
    Returns all options defined for a select list issue field. A select list issue field is a type of [issue field](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field/) that allows a user to select an value from a list of options.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-get-openapi.md
- name: Jira Cloud REST API - Create issue field option
  x-api-slug: api2fieldfieldkeyoption-post
  description: |-
    Creates an option for a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-post-openapi.md
- name: Jira Cloud REST API - Get selectable issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionsedit-get
  description: |-
    Returns options defined for a select list issue field that can be viewed and selected by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-openapi.md
- name: Jira Cloud REST API - Get visible issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionssearch-get
  description: |-
    Returns options defined for a select list issue field that can be viewed by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-openapi.md
- name: Jira Cloud REST API - Get issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-get
  description: |-
    Returns an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-openapi.md
- name: Jira Cloud REST API - Update issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-put
  description: |-
    Updates an option for a select list issue field. If the option does not exist, a new option is created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-openapi.md
- name: Jira Cloud REST API - Delete issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-delete
  description: |-
    Deletes an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-openapi.md
- name: Jira Cloud REST API - Replace issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionidissue-delete
  description: |-
    Deselects a select list issue field option in all issues that it has been selected in. A different option can be selected to replace the deselected option. The update can also be limited to a smaller set of issues by using a JQL query.

    This is an [asynchronous method](#async). The response object will contain a link to the long-running task. For example, _https://your-domain.atlassian.net/rest/api/2/task/10127_.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-openapi.md
- name: Jira Cloud REST API - Get field auto complete for query string
  x-api-slug: api2jqlautocompletedatasuggestions-get
  description: Returns auto complete suggestions for JQL search.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2jqlautocompletedatasuggestions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2jqlautocompletedatasuggestions-get-openapi.md
- name: Jira Cloud REST API - Add field to default screen
  x-api-slug: api2screensaddtodefaultfieldid-post
  description: Adds field or custom field to the default tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensaddtodefaultfieldid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensaddtodefaultfieldid-post-openapi.md
- name: Jira Cloud REST API - Add screen tab field
  x-api-slug: api2screensscreenidtabstabidfields-post
  description: Adds field to the given tab.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-openapi.md
- name: Jira Cloud REST API - Remove screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsid-delete
  description: Removes field from given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-openapi.md
- name: Jira Cloud REST API - Move screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsidmove-post
  description: Moves field on the given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-openapi.md
- name: Jira Cloud REST API - Get create issue meta
  x-api-slug: api2issuecreatemeta-get
  description: |-
    Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

    The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

    Fields will only be returned if `expand=projects.issuetypes.fields` is set.

    The results can be filtered by project and/or issue type, controlled by the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issuecreatemeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issuecreatemeta-get-openapi.md
- name: Jira Cloud REST API - Get edit issue meta
  x-api-slug: api2issueissueidorkeyeditmeta-get
  description: |-
    Returns the metadata for editing an issue.

    The fields returned by editmeta resource are the ones shown on the issue's Edit screen. Fields hidden from the screen will not be returned unless `overrideScreenSecurity` parameter is set to true.

    If an issue cannot be edited in Jira because of its workflow status (for example the issue is closed), then no fields will be returned, unless `overrideEditableFlag` is set to true.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-openapi.md
- name: Jira Cloud REST API - Get transitions
  x-api-slug: api2issueissueidorkeytransitions-get
  description: |-
    Returns a list of transitions available for this issue for the current user.

    Specify `expand=transitions.fields` parameter to retrieve the fields required for a transition together with their types.

    Fields metadata corresponds to the fields available in a transition screen for a particular transition. Fields hidden from the screen will not be returned in the metadata.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeytransitions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeytransitions-get-openapi.md
- name: Jira Cloud REST API - Update worklog
  x-api-slug: api2issueissueidorkeyworklogid-put
  description: |-
    Updates an existing worklog entry.

    Note that:

    *   Fields possible for editing are: comment, visibility, started, timeSpent and timeSpentSeconds.
    *   Either timeSpent or timeSpentSeconds can be set.
    *   Fields which are not set will not be updated.
    *   For a request to be valid, it has to have at least one field change.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeyworklogid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeyworklogid-put-openapi.md
- name: Jira Cloud REST API - Get custom field option
  x-api-slug: api2customfieldoptionid-get
  description: "Returns a custom field option. For example, an option in a cascading
    select list.  \n  \n**[Permissions](https://developer.atlassian.com/cloud/jira/platform/rest/#permissions)
    required:** None."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2customfieldoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2customfieldoptionid-get-openapi.md
- name: Jira Cloud REST API - Create custom field
  x-api-slug: api2field-post
  description: |-
    Creates a custom field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-post-openapi.md
- name: Jira Cloud REST API - Get all issue field options
  x-api-slug: api2fieldfieldkeyoption-get
  description: |-
    Returns all options defined for a select list issue field. A select list issue field is a type of [issue field](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field/) that allows a user to select an value from a list of options.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-get-openapi.md
- name: Jira Cloud REST API - Create issue field option
  x-api-slug: api2fieldfieldkeyoption-post
  description: |-
    Creates an option for a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-post-openapi.md
- name: Jira Cloud REST API - Get selectable issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionsedit-get
  description: |-
    Returns options defined for a select list issue field that can be viewed and selected by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-openapi.md
- name: Jira Cloud REST API - Get visible issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionssearch-get
  description: |-
    Returns options defined for a select list issue field that can be viewed by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-openapi.md
- name: Jira Cloud REST API - Get issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-get
  description: |-
    Returns an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-openapi.md
- name: Jira Cloud REST API - Update issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-put
  description: |-
    Updates an option for a select list issue field. If the option does not exist, a new option is created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-openapi.md
- name: Jira Cloud REST API - Delete issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-delete
  description: |-
    Deletes an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-openapi.md
- name: Jira Cloud REST API - Replace issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionidissue-delete
  description: |-
    Deselects a select list issue field option in all issues that it has been selected in. A different option can be selected to replace the deselected option. The update can also be limited to a smaller set of issues by using a JQL query.

    This is an [asynchronous method](#async). The response object will contain a link to the long-running task. For example, _https://your-domain.atlassian.net/rest/api/2/task/10127_.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-openapi.md
- name: Jira Cloud REST API - Get field auto complete for query string
  x-api-slug: api2jqlautocompletedatasuggestions-get
  description: Returns auto complete suggestions for JQL search.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2jqlautocompletedatasuggestions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2jqlautocompletedatasuggestions-get-openapi.md
- name: Jira Cloud REST API - Add field to default screen
  x-api-slug: api2screensaddtodefaultfieldid-post
  description: Adds field or custom field to the default tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensaddtodefaultfieldid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensaddtodefaultfieldid-post-openapi.md
- name: Jira Cloud REST API - Add screen tab field
  x-api-slug: api2screensscreenidtabstabidfields-post
  description: Adds field to the given tab.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-openapi.md
- name: Jira Cloud REST API - Remove screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsid-delete
  description: Removes field from given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-openapi.md
- name: Jira Cloud REST API - Move screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsidmove-post
  description: Moves field on the given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-openapi.md
- name: Jira Cloud REST API - Get fields
  x-api-slug: api2field-get
  description: |-
    Returns all issue fields in Jira, both system and custom fields.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None, however the following rules apply:

    *   Fields that cannot be added to the issue navigator are always returned.
    *   Fields that cannot be placed on an issue screen are always returned.
    *   Fields that depend on global Jira settings are only returned if the setting is enabled. That is, timetracking fields, subtasks, votes, and watches.
    *   For all other fields, this method only returns the fields that the current user has permission to see (that is, the field can be used in at least one project that the user can see).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-get-openapi.md
- name: Jira Cloud REST API - Get create issue meta
  x-api-slug: api2issuecreatemeta-get
  description: |-
    Returns the metadata for creating issues. This includes the available projects, issue types, fields (with information whether those fields are required) and field types. Projects, in which the user does not have permission to create issues, will not be returned.

    The fields in the createmeta response correspond to the fields on the issue's Create screen for the specific project/issuetype. Fields hidden from the screen will not be returned in the createmeta response.

    Fields will only be returned if `expand=projects.issuetypes.fields` is set.

    The results can be filtered by project and/or issue type, controlled by the query parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issuecreatemeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issuecreatemeta-get-openapi.md
- name: Jira Cloud REST API - Edit issue
  x-api-slug: api2issueissueidorkey-put
  description: "Edits the issue from a JSON representation.\n\nThe fields available
    for update can be determined using the **/rest/api/2/issue/{issueIdOrKey}/editmeta**
    resource.  \nIf a field is hidden from the Edit screen then it will not be returned
    by the editmeta resource. A field validation error will occur if such field is
    submitted in an edit request. However connect add-on with admin scope may override
    a screen security configuration.\n\nIf an issue cannot be edited in Jira because
    of its workflow status (for example the issue is closed), then you will not be
    able to edit it with this resource.\n\nField to be updated should appear either
    in `fields` or `update` request's body parameter, but not in both.  \nTo update
    a single sub-field of a complex field (e.g. timetracking) please use the `update`
    parameter of the edit operation. Using a `\"field_id\": field_value` construction
    in the `fields` parameter is a shortcut of \"set\" operation in the `update` parameter."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkey-put-openapi.md
- name: Jira Cloud REST API - Get edit issue meta
  x-api-slug: api2issueissueidorkeyeditmeta-get
  description: |-
    Returns the metadata for editing an issue.

    The fields returned by editmeta resource are the ones shown on the issue's Edit screen. Fields hidden from the screen will not be returned unless `overrideScreenSecurity` parameter is set to true.

    If an issue cannot be edited in Jira because of its workflow status (for example the issue is closed), then no fields will be returned, unless `overrideEditableFlag` is set to true.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeyeditmeta-get-openapi.md
- name: Jira Cloud REST API - Get transitions
  x-api-slug: api2issueissueidorkeytransitions-get
  description: |-
    Returns a list of transitions available for this issue for the current user.

    Specify `expand=transitions.fields` parameter to retrieve the fields required for a transition together with their types.

    Fields metadata corresponds to the fields available in a transition screen for a particular transition. Fields hidden from the screen will not be returned in the metadata.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeytransitions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeytransitions-get-openapi.md
- name: Jira Cloud REST API - Update worklog
  x-api-slug: api2issueissueidorkeyworklogid-put
  description: |-
    Updates an existing worklog entry.

    Note that:

    *   Fields possible for editing are: comment, visibility, started, timeSpent and timeSpentSeconds.
    *   Either timeSpent or timeSpentSeconds can be set.
    *   Fields which are not set will not be updated.
    *   For a request to be valid, it has to have at least one field change.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeyworklogid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2issueissueidorkeyworklogid-put-openapi.md
- name: Jira Cloud REST API - Get notification schemes paginated
  x-api-slug: api2notificationscheme-get
  description: |-
    Returns a [paginated](https://developer.atlassian.com/cloud/jira/platform/rest/#pagination) list of [notification schemes](https://confluence.atlassian.com/x/8YdKLg) in order by display name.

    ### About notification schemes

    A notification scheme is a list of events and recipients who will receive notifications for those events. The list is contained within the `notificationSchemeEvents` object and contains pairs of `events` and `notifications`:

    *   `event` Identifies the type of event. The events can be [Jira system events](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-eventsEvents) or [custom events](https://confluence.atlassian.com/x/AIlKLg).
    *   `notifications` Identifies the [recipients](https://confluence.atlassian.com/x/8YdKLg#Creatinganotificationscheme-recipientsRecipients) of notifications for each event. Recipients can be any of the following types:

    *   `CurrentAssignee`
    *   `Reporter`
    *   `CurrentUser`
    *   `ProjectLead`
    *   `ComponentLead`
    *   `User` (the `parameter` is the user key)
    *   `Group` (the `parameter` is the group name)
    *   `ProjectRole` (the `parameter` is the project role ID)
    *   `EmailAddress`
    *   `AllWatchers`
    *   `UserCustomField` (the `parameter` is the ID of the custom field)
    *   `GroupCustomField`(the `parameter` is the ID of the custom field)

    _Note that you should allow for events without recipients to appear in responses._

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** None, however the requesting user must have permission to administer at least one project associated with a notification scheme for it to be returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2notificationscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2notificationscheme-get-openapi.md
- name: Jira Cloud REST API - Get all permission schemes
  x-api-slug: api2permissionscheme-get
  description: |-
    Returns all permission schemes.

    ### About permission schemes and grants

    A permission scheme is a collection of permission grants. A permission grant consists of a `holder` and a `permission`.

    #### Holder

    The `holder` object contains information about the user or group being granted the permission. For example, the _Administer projects_ permission is granted to a group named _Teams in space administrators_. In this case, the type is `"type": "group"`, and the parameter is the group name, `"parameter": "Teams in space administrators"`. The `holder` object is defined by the following properties:

    *   `type` Identifies the user or group (see the list of types below).
    *   `parameter` The value of this property depends on the `type`. For example, if the `type` is a group, then you need to specify the group name.

    The following `types` are available. The expected values for the `parameter` are given in parenthesis (some `types` may not have a `parameter`):

    *   `anyone` Grant for anonymous users.
    *   `applicationRole` Grant for users with access to the specified application (application name). See [Manage application access](https://confluence.atlassian.com/cloud/manage-application-access-744721629.html) for more information.
    *   `assignee` Grant for the user currently assigned to an issue.
    *   `group` Grant for the specified group (group name).
    *   `groupCustomField` Grant for a user in the group selected in the specified custom field (custom field ID).
    *   `projectLead` Grant for a project lead.
    *   `projectRole` Grant for the specified project role (project role ID).
    *   `reporter` Grant for the user who reported the issue.
    *   `sd.customer.portal.only` Jira Service Desk only. Grants customers permission to access the customer portal but not Jira. See [Customizing Jira Service Desk permissions](https://confluence.atlassian.com/x/24dKLg) for more information.
    *   `user` Grant for the specified user (user ID).
    *   `userCustomField` Grant for a user selected in the specified custom field (custom field ID).

    #### Permissions

    The [built-in Jira permissions](https://confluence.atlassian.com/x/yodKLg) are listed below. Apps can also define custom permissions. See the [project permission](https://developer.atlassian.com/cloud/jira/platform/modules/project-permission/) and [global permission](https://developer.atlassian.com/cloud/jira/platform/modules/global-permission/) module documentation for more information.

    **Project permissions**

    *   `ADMINISTER_PROJECTS`
    *   `BROWSE_PROJECTS`
    *   `MANAGE_SPRINTS_PERMISSION` (Jira Software only)
    *   `SERVICEDESK_AGENT` (Jira Service Desk only)
    *   `VIEW_DEV_TOOLS` (Jira Software only)
    *   `VIEW_READONLY_WORKFLOW`

    **Issue permissions**

    *   `ASSIGNABLE_USER`
    *   `ASSIGN_ISSUES`
    *   `CLOSE_ISSUES`
    *   `CREATE_ISSUES`
    *   `DELETE_ISSUES`
    *   `EDIT_ISSUES`
    *   `LINK_ISSUES`
    *   `MODIFY_REPORTER`
    *   `MOVE_ISSUES`
    *   `RESOLVE_ISSUES`
    *   `SCHEDULE_ISSUES`
    *   `SET_ISSUE_SECURITY`
    *   `TRANSITION_ISSUES`

    **Voters and watchers permissions**

    *   `MANAGE_WATCHERS`
    *   `VIEW_VOTERS_AND_WATCHERS`

    **Comments permissions**

    *   `ADD_COMMENTS`
    *   `DELETE_ALL_COMMENTS`
    *   `DELETE_OWN_COMMENTS`
    *   `EDIT_ALL_COMMENTS`
    *   `EDIT_OWN_COMMENTS`

    **Attachments permissions**

    *   `CREATE_ATTACHMENTS`
    *   `DELETE_ALL_ATTACHMENTS`
    *   `DELETE_OWN_ATTACHMENTS`

    **Time tracking permissions**

    *   `DELETE_ALL_WORKLOGS`
    *   `DELETE_OWN_WORKLOGS`
    *   `EDIT_ALL_WORKLOGS`
    *   `EDIT_OWN_WORKLOGS`
    *   `WORK_ON_ISSUES`

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to log in to Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2permissionscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2permissionscheme-get-openapi.md
- name: Jira Cloud REST API - Get available screen fields
  x-api-slug: api2screensscreenidavailablefields-get
  description: Gets available fields for screen. i.e ones that haven't already been
    added.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidavailablefields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidavailablefields-get-openapi.md
- name: Jira Cloud REST API - Move screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsidmove-post
  description: Moves field on the given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-openapi.md
- name: Jira Cloud REST API - Move screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsidmove-post
  description: Moves field on the given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-openapi.md
- name: Jira Cloud REST API - Move screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsidmove-post
  description: Moves field on the given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-openapi.md
- name: Jira Cloud REST API - Move screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsidmove-post
  description: Moves field on the given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsidmove-post-openapi.md
- name: Jira Cloud REST API - Remove screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsid-delete
  description: Removes field from given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-openapi.md
- name: Jira Cloud REST API - Remove screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsid-delete
  description: Removes field from given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-openapi.md
- name: Jira Cloud REST API - Remove screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsid-delete
  description: Removes field from given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-openapi.md
- name: Jira Cloud REST API - Remove screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsid-delete
  description: Removes field from given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-openapi.md
- name: Jira Cloud REST API - Remove screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsid-delete
  description: Removes field from given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-openapi.md
- name: Jira Cloud REST API - Remove screen tab field
  x-api-slug: api2screensscreenidtabstabidfieldsid-delete
  description: Removes field from given tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfieldsid-delete-openapi.md
- name: Jira Cloud REST API - Add screen tab field
  x-api-slug: api2screensscreenidtabstabidfields-post
  description: Adds field to the given tab.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-openapi.md
- name: Jira Cloud REST API - Add screen tab field
  x-api-slug: api2screensscreenidtabstabidfields-post
  description: Adds field to the given tab.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-openapi.md
- name: Jira Cloud REST API - Add screen tab field
  x-api-slug: api2screensscreenidtabstabidfields-post
  description: Adds field to the given tab.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-openapi.md
- name: Jira Cloud REST API - Add screen tab field
  x-api-slug: api2screensscreenidtabstabidfields-post
  description: Adds field to the given tab.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-openapi.md
- name: Jira Cloud REST API - Add screen tab field
  x-api-slug: api2screensscreenidtabstabidfields-post
  description: Adds field to the given tab.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-openapi.md
- name: Jira Cloud REST API - Add screen tab field
  x-api-slug: api2screensscreenidtabstabidfields-post
  description: Adds field to the given tab.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensscreenidtabstabidfields-post-openapi.md
- name: Jira Cloud REST API - Add field to default screen
  x-api-slug: api2screensaddtodefaultfieldid-post
  description: Adds field or custom field to the default tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensaddtodefaultfieldid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensaddtodefaultfieldid-post-openapi.md
- name: Jira Cloud REST API - Add field to default screen
  x-api-slug: api2screensaddtodefaultfieldid-post
  description: Adds field or custom field to the default tab
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensaddtodefaultfieldid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2screensaddtodefaultfieldid-post-openapi.md
- name: Jira Cloud REST API - Get field auto complete for query string
  x-api-slug: api2jqlautocompletedatasuggestions-get
  description: Returns auto complete suggestions for JQL search.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2jqlautocompletedatasuggestions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2jqlautocompletedatasuggestions-get-openapi.md
- name: Jira Cloud REST API - Get field auto complete for query string
  x-api-slug: api2jqlautocompletedatasuggestions-get
  description: Returns auto complete suggestions for JQL search.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2jqlautocompletedatasuggestions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2jqlautocompletedatasuggestions-get-openapi.md
- name: Jira Cloud REST API - Replace issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionidissue-delete
  description: |-
    Deselects a select list issue field option in all issues that it has been selected in. A different option can be selected to replace the deselected option. The update can also be limited to a smaller set of issues by using a JQL query.

    This is an [asynchronous method](#async). The response object will contain a link to the long-running task. For example, _https://your-domain.atlassian.net/rest/api/2/task/10127_.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-openapi.md
- name: Jira Cloud REST API - Replace issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionidissue-delete
  description: |-
    Deselects a select list issue field option in all issues that it has been selected in. A different option can be selected to replace the deselected option. The update can also be limited to a smaller set of issues by using a JQL query.

    This is an [asynchronous method](#async). The response object will contain a link to the long-running task. For example, _https://your-domain.atlassian.net/rest/api/2/task/10127_.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionidissue-delete-openapi.md
- name: Jira Cloud REST API - Delete issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-delete
  description: |-
    Deletes an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-openapi.md
- name: Jira Cloud REST API - Delete issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-delete
  description: |-
    Deletes an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-delete-openapi.md
- name: Jira Cloud REST API - Update issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-put
  description: |-
    Updates an option for a select list issue field. If the option does not exist, a new option is created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-openapi.md
- name: Jira Cloud REST API - Update issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-put
  description: |-
    Updates an option for a select list issue field. If the option does not exist, a new option is created.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-put-openapi.md
- name: Jira Cloud REST API - Get issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-get
  description: |-
    Returns an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-openapi.md
- name: Jira Cloud REST API - Get issue field option
  x-api-slug: api2fieldfieldkeyoptionoptionid-get
  description: |-
    Returns an option from a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionoptionid-get-openapi.md
- name: Jira Cloud REST API - Get visible issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionssearch-get
  description: |-
    Returns options defined for a select list issue field that can be viewed by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-openapi.md
- name: Jira Cloud REST API - Get visible issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionssearch-get
  description: |-
    Returns options defined for a select list issue field that can be viewed by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionssearch-get-openapi.md
- name: Jira Cloud REST API - Get selectable issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionsedit-get
  description: |-
    Returns options defined for a select list issue field that can be viewed and selected by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-openapi.md
- name: Jira Cloud REST API - Get selectable issue field options
  x-api-slug: api2fieldfieldkeyoptionsuggestionsedit-get
  description: |-
    Returns options defined for a select list issue field that can be viewed and selected by the currently logged in user.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission to access Jira.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoptionsuggestionsedit-get-openapi.md
- name: Jira Cloud REST API - Create issue field option
  x-api-slug: api2fieldfieldkeyoption-post
  description: |-
    Creates an option for a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-post-openapi.md
- name: Jira Cloud REST API - Create issue field option
  x-api-slug: api2fieldfieldkeyoption-post
  description: |-
    Creates an option for a select list issue field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-post-openapi.md
- name: Jira Cloud REST API - Get all issue field options
  x-api-slug: api2fieldfieldkeyoption-get
  description: |-
    Returns all options defined for a select list issue field. A select list issue field is a type of [issue field](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field/) that allows a user to select an value from a list of options.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-get-openapi.md
- name: Jira Cloud REST API - Get all issue field options
  x-api-slug: api2fieldfieldkeyoption-get
  description: |-
    Returns all options defined for a select list issue field. A select list issue field is a type of [issue field](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field/) that allows a user to select an value from a list of options.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission. Jira permissions are not required for the app providing the field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2fieldfieldkeyoption-get-openapi.md
- name: Jira Cloud REST API - Create custom field
  x-api-slug: api2field-post
  description: |-
    Creates a custom field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-post-openapi.md
- name: Jira Cloud REST API - Create custom field
  x-api-slug: api2field-post
  description: |-
    Creates a custom field.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ global permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2field-post-openapi.md
- name: Jira Cloud REST API - Get custom field option
  x-api-slug: api2customfieldoptionid-get
  description: "Returns a custom field option. For example, an option in a cascading
    select list.  \n  \n**[Permissions](https://developer.atlassian.com/cloud/jira/platform/rest/#permissions)
    required:** None."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2customfieldoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2customfieldoptionid-get-openapi.md
- name: Jira Cloud REST API - Get custom field option
  x-api-slug: api2customfieldoptionid-get
  description: "Returns a custom field option. For example, an option in a cascading
    select list.  \n  \n**[Permissions](https://developer.atlassian.com/cloud/jira/platform/rest/#permissions)
    required:** None."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2customfieldoptionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/atlassian/api2customfieldoptionid-get-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---