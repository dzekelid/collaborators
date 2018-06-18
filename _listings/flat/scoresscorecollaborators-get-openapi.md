---
swagger: "2.0"
x-collection-name: Flat
x-complete: 0
info:
  title: Flat List the collaborators
  description: |-
    This API call will list the different collaborators of a score and their rights on the document. The returned list will at least contain the owner of the document.

    Collaborators can be a single user (the object `user` will be populated) or a group (the object `group` will be populated).
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