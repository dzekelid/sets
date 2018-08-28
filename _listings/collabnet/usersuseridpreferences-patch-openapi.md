---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Sets preferences by user id
  version: 1.0.0
  description: Sets preferences by user id.
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{userid}/profile-picture:
    post:
      summary: Uploads and sets profile picture by user id
      description: Uploads and sets profile picture by user id.
      operationId: setProfilePictureById
      x-api-path-slug: usersuseridprofilepicture-post
      parameters:
      - in: body
        name: body
        description: Picture
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userid
        description: User ID
      responses:
        200:
          description: OK
      tags:
      - Uploads
      - Sets
      - Profile
      - Picture
      - By
      - User
  /users/{userid}/preferences:
    patch:
      summary: Sets preferences by user id
      description: Sets preferences by user id.
      operationId: setPreferencesById
      x-api-path-slug: usersuseridpreferences-patch
      parameters:
      - in: body
        name: body
        description: Preferences
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userid
        description: User ID
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Preferences
      - By
      - User
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