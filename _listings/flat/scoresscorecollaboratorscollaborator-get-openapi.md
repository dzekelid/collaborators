---
swagger: "2.0"
x-collection-name: Flat
x-complete: 0
info:
  title: Flat Get a collaborator
  description: Get the information about a collaborator (User or Group).
  termsOfService: https://flat.io/legal
  contact:
    name: Flat
    url: https://flat.io/support
    email: developers@flat.io
  version: 2.1.0
host: api.flat.io
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /scores/{score}/collaborators:
    get:
      summary: List the collaborators
      description: |-
        This API call will list the different collaborators of a score and their rights on the document. The returned list will at least contain the owner of the document.

        Collaborators can be a single user (the object `user` will be populated) or a group (the object `group` will be populated).
      operationId: getScoreCollaborators
      x-api-path-slug: scoresscorecollaborators-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - List
      - Collaborators
    post:
      summary: Add a new collaborator
      description: |-
        Share a score with a single user or a group. This API call allows to add, invite and update the collaborators of a document.
        - To add an existing Flat user to the document, specify its unique identifier in the `user` property.
        - To invite an external user to the document, specify its email in the `userEmail` property.
        - To add a Flat group to the document, specify its unique identifier in the `group` property.
        - To update an existing collaborator, process the same request with different rights.
      operationId: addScoreCollaborator
      x-api-path-slug: scoresscorecollaborators-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - New
      - Collaborator
  /scores/{score}/collaborators/{collaborator}:
    delete:
      summary: Delete a collaborator
      description: Remove the specified collaborator from the score
      operationId: removeScoreCollaborator
      x-api-path-slug: scoresscorecollaboratorscollaborator-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Collaborator
    get:
      summary: Get a collaborator
      description: Get the information about a collaborator (User or Group).
      operationId: getScoreCollaborator
      x-api-path-slug: scoresscorecollaboratorscollaborator-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Collaborator
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