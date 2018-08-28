swagger: "2.0"
x-collection-name: GoToMeeting
x-complete: 1
info:
  title: SCIM
  description: the-scim-api-lets-you-manage-users-in-your-organization--you-can-then-automate-the-provisioning-of-product-licenses-for-these-users-and-they-can-use-your-companys-single-signon-solution-through-an-identity-provider-
  termsOfService: https://developer.citrixonline.com/terms-use
  contact:
    name: Developer Support
    url: https://developer.citrixonline.com
    email: developer-support@citrixonline.com
  version: N/A
host: api.citrixonline.com
basePath: /identity/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizers/{organizerKey}/webinars/{webinarKey}/registrants/fields:
    get:
      summary: Get registration fields
      description: Retrieve required, optional registration, and custom questions
        for a specified webinar.
      operationId: getRegistrationFields
      x-api-path-slug: organizersorganizerkeywebinarswebinarkeyregistrantsfields-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Organizers
      - OrganizerKey
      - Webinars
      - WebinarKey
      - Registrants
      - Fields