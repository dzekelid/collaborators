---
swagger: "2.0"
x-collection-name: uebermaps
x-complete: 0
info:
  title: uebermaps Delete collaborator invitation
  description: Delete collaborator invitation.
  termsOfService: https://uebermaps.com/terms/
  contact:
    name: uebermaps API Team
  version: "2.0"
host: uebermaps.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /maps/{id}/collaborators/:
    get:
      summary: List collaborators of a map
      description: List collaborators of a map.
      operationId: maps.id.collaborators.get
      x-api-path-slug: mapsidcollaborators-get
      parameters:
      - in: path
        name: id
        description: Map id
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Collaborators
      - Of
      - Map
  /collaborator_invitations:
    get:
      summary: List your collaborator invitations
      description: List your collaborator invitations.
      operationId: collaborator_invitations.get
      x-api-path-slug: collaborator-invitations-get
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Your
      - Collaborator
      - Invitations
  /collaborator_invitations/{id}:
    delete:
      summary: Delete collaborator invitation
      description: Delete collaborator invitation.
      operationId: collaborator_invitations.id.delete
      x-api-path-slug: collaborator-invitationsid-delete
      parameters:
      - in: path
        name: id
        description: Collaborator invitation id
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Collaborator
      - Invitation
    get:
      summary: Show collaborator invitation
      description: Show collaborator invitation
      operationId: collaborator_invitations.id.get
      x-api-path-slug: collaborator-invitationsid-get
      parameters:
      - in: path
        name: id
        description: Collaborator invitation id
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Show
      - Collaborator
      - Invitation
    patch:
      summary: Accept collaborator invitation.
      description: Accept collaborator invitation.
      operationId: collaborator_invitations.id.patch
      x-api-path-slug: collaborator-invitationsid-patch
      parameters:
      - in: path
        name: id
        description: Collaborator invitation id
      responses:
        200:
          description: OK
      tags:
      - Mapping
      - Accept
      - Collaborator
      - Invitation
  /maps/{id}/collaborators/{user_id}:
    patch:
      summary: Update collaborator
      description: Update collaborator. Wrap collaborator parameters in [collaborator]
      operationId: maps.id.collaborators.user_id.patch
      x-api-path-slug: mapsidcollaboratorsuser-id-patch
      parameters:
      - in: body
        name: collaborator
        description: collaborator attributes
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: map id
      - in: path
        name: user_id
        description: user id
      responses:
        200:
          description: OK
      tags:
      - Mapping
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