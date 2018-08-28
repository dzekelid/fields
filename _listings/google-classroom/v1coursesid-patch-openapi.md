---
swagger: "2.0"
x-collection-name: Google Classroom
x-complete: 0
info:
  title: Google Classroom API Update Fields
  description: |-
    Updates one or more fields in a course.

    This method returns the following error codes:

    * `PERMISSION_DENIED` if the requesting user is not permitted to modify the
    requested course or for access errors.
    * `NOT_FOUND` if no course exists with the requested ID.
    * `INVALID_ARGUMENT` if invalid fields are specified in the update mask or
    if no update mask is supplied.
    * `FAILED_PRECONDITION` for the following request errors:
        * CourseNotModifiable
  contact:
    name: Google
    url: https://google.com
  version: v1
host: classroom.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/courses/{courseId}/courseWork/{courseWorkId}/studentSubmissions/{id}:
    patch:
      summary: Update Fields
      description: |-
        Updates one or more fields of a student submission.

        See google.classroom.v1.StudentSubmission for details
        of which fields may be updated and who may change them.

        This request must be made by the Developer Console project of the
        [OAuth client ID](https://support.google.com/cloud/answer/6158849) used to
        create the corresponding course work item.

        This method returns the following error codes:

        * `PERMISSION_DENIED` if the requesting developer project did not create
        the corresponding course work, if the user is not permitted to make the
        requested modification to the student submission, or for
        access errors.
        * `INVALID_ARGUMENT` if the request is malformed.
        * `NOT_FOUND` if the requested course, course work, or student submission
        does not exist.
      operationId: classroom.courses.courseWork.studentSubmissions.patch
      x-api-path-slug: v1coursescourseidcourseworkcourseworkidstudentsubmissionsid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: courseId
        description: Identifier of the course
      - in: path
        name: courseWorkId
        description: Identifier of the course work
      - in: path
        name: id
        description: Identifier of the student submission
      - in: query
        name: updateMask
        description: Mask that identifies which fields on the student submission to
          update
      responses:
        200:
          description: OK
      tags:
      - Field
  /v1/courses/{courseId}/courseWork/{id}:
    patch:
      summary: Update Fields
      description: |-
        Updates one or more fields of a course work.

        See google.classroom.v1.CourseWork for details
        of which fields may be updated and who may change them.

        This request must be made by the Developer Console project of the
        [OAuth client ID](https://support.google.com/cloud/answer/6158849) used to
        create the corresponding course work item.

        This method returns the following error codes:

        * `PERMISSION_DENIED` if the requesting developer project did not create
        the corresponding course work, if the user is not permitted to make the
        requested modification to the student submission, or for
        access errors.
        * `INVALID_ARGUMENT` if the request is malformed.
        * `FAILED_PRECONDITION` if the requested course work has already been
        deleted.
        * `NOT_FOUND` if the requested course, course work, or student submission
        does not exist.
      operationId: classroom.courses.courseWork.patch
      x-api-path-slug: v1coursescourseidcourseworkid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: courseId
        description: Identifier of the course
      - in: path
        name: id
        description: Identifier of the course work
      - in: query
        name: updateMask
        description: Mask that identifies which fields on the course work to update
      responses:
        200:
          description: OK
      tags:
      - Field
  /v1/courses/{id}:
    patch:
      summary: Update Fields
      description: |-
        Updates one or more fields in a course.

        This method returns the following error codes:

        * `PERMISSION_DENIED` if the requesting user is not permitted to modify the
        requested course or for access errors.
        * `NOT_FOUND` if no course exists with the requested ID.
        * `INVALID_ARGUMENT` if invalid fields are specified in the update mask or
        if no update mask is supplied.
        * `FAILED_PRECONDITION` for the following request errors:
            * CourseNotModifiable
      operationId: classroom.courses.patch
      x-api-path-slug: v1coursesid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Identifier of the course to update
      - in: query
        name: updateMask
        description: Mask that identifies which fields on the course to update
      responses:
        200:
          description: OK
      tags:
      - Field
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