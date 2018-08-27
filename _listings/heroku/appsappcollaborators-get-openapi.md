---
swagger: "2.0"
x-collection-name: Heroku
x-complete: 0
info:
  title: Heroku Get Application Collaborators
  description: List collaborators for an app.
  version: "1"
host: api.heroku.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps/{app}/collaborators:
    parameters:
      summary: Parameters Application Collaborators
      description: Parameters application collaborators.
      operationId: parametersAppsAppCollaborators
      x-api-path-slug: appsappcollaborators-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Collaborators
    get:
      summary: Get Application Collaborators
      description: List collaborators for an app.
      operationId: getAppsAppCollaborators
      x-api-path-slug: appsappcollaborators-get
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      responses:
        200:
          description: OK
      tags:
      - Application
      - Collaborators
  /apps/{app}/collaborators/{email}:
    parameters:
      summary: Parameters Application Collaborators Email
      description: Parameters application collaborators email.
      operationId: parametersAppsAppCollaboratorsEmail
      x-api-path-slug: appsappcollaboratorsemail-parameters
      responses:
        200:
          description: OK
      tags:
      - Parameters
      - Application
      - Collaborators
      - Email
    delete:
      summary: Delete Application Collaborators Email
      description: Delete application collaborators email.
      operationId: deleteAppsAppCollaboratorsEmail
      x-api-path-slug: appsappcollaboratorsemail-delete
      parameters:
      - in: header
        name: Accept
        description: Content type
      - in: query
        name: Accept
        description: Content type
      - in: query
        name: app
        description: The app name
      - in: path
        name: app
      - in: query
        name: email
        description: The email of the user to remove as a collaborator
      - in: path
        name: email
      responses:
        200:
          description: OK
      tags:
      - Application
      - Collaborators
      - Email
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