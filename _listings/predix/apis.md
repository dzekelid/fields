---
name: Predix
x-slug: predix
description: Predix (IoT PaaS) helps you develop apps that connect people with industrial
  machines through analytics and data for better business outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
x-kinRank: "7"
x-alexaRank: "264121"
tags: Fields
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/predix/apis.md
specificationVersion: "0.14"
apis:
- name: Analytics Framework - Upload an artifact and attach it to an orchestration
    configuration entry.
  x-api-slug: apiv2configorchestrationsartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an orchestration configuration entry. The multipart MIME structure must
    have the orchestration entry id tagged as 'orchestrationEntryId',  the file contents
    tagged as 'file',  the artifact type tagged as 'type', and  the name of artifact
    tagged as 'name'.  A description (under 1024 characters) tagged as 'description'
    can be optionally specified. Artifact types can be either 'portToFieldMap', 'bpmn'
    or any.   If the artifact type is 'portToFieldMap', specify the orchestration
    step ID tagged as 'stepId'.   Otherwise, 'name' will be used as 'stepId'.  (See
    the documentation for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/predix/apiv2configorchestrationsartifacts-post-openapi.md
- name: Analytics Framework - Update an artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-put
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/predix/apiv2configorchestrationsartifactsid-put-openapi.md
- name: Analytics Framework - Download an orchestration artifact file by orchestration
    id and artifact type.
  x-api-slug: apiv2configorchestrationsidfile-get
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/predix/apiv2configorchestrationsidfile-get-openapi.md
- name: Analytics Runtime - Upload an artifact and attach it to an orchestration configuration
    entry.
  x-api-slug: apiv2configorchestrationsartifacts-post
  description: Upload a single artifact file in a multipart MIME structure and attach
    it to an orchestration configuration entry. The multipart MIME structure must
    have the orchestration entry id tagged as 'orchestrationEntryId',  the file contents
    tagged as 'file',  the artifact type tagged as 'type', and  the name of artifact
    tagged as 'name'.  A description (under 1024 characters) tagged as 'description'
    can be optionally specified. Artifact types can be either 'portToFieldMap', 'bpmn'
    or any.   If the artifact type is 'portToFieldMap', specify the orchestration
    step ID tagged as 'stepId'.   Otherwise, 'name' will be used as 'stepId'.  (See
    the documentation for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/predix/apiv2configorchestrationsartifacts-post-openapi.md
- name: Analytics Runtime - Update an artifact by id.
  x-api-slug: apiv2configorchestrationsartifactsid-put
  description: Update the artifact of the orchestration configuration with the contents
    of the supplied multipart MIME structure. The multipart MIME structure may have
    new file contents tagged as 'file',  new artifact type tagged as 'type',  new
    name of artifact tagged as 'name',  new description (under 1024 characters) tagged
    as 'description', and  new value of the orchestration step id tagged as 'stepId.   Artifact
    types can be either 'portToFieldMap', 'bpmn' or any.  (See the documentation for
    more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/predix/apiv2configorchestrationsartifactsid-put-openapi.md
- name: Analytics Runtime - Download an orchestration artifact file by orchestration
    id and artifact type.
  x-api-slug: apiv2configorchestrationsidfile-get
  description: The file is downloaded as an octet-stream. If the type is bpmn, then
    then bpmn xml is downloaded. If the type is portToFieldMap, then the system expects
    analyticStepId to download the portToFieldMap for the given step
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/fields/master/_listings/predix/apiv2configorchestrationsidfile-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://predicthq.api.gallery.streamdata.io
- type: x-api-stack
  url: http://predix.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/predix
- type: x-documentation
  url: https://docs.predix.io/en-US/platform
- type: x-twitter
  url: https://twitter.com/Predix
- type: x-website
  url: https://www.predix.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---