---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Uploads and sets profile picture for
    current user
  version: 1.0.0
  description: Uploads and sets profile picture for current user.
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
  /users/{userid}/authorization-keys:
    post:
      summary: Sets authorization keys by user id
      description: Sets authorization keys by user id.
      operationId: setAuthorizationKeysById
      x-api-path-slug: usersuseridauthorizationkeys-post
      parameters:
      - in: body
        name: body
        description: Authorization keys
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
      - Authorization
      - Keys
      - By
      - User
  /users/myself/profile-picture:
    post:
      summary: Uploads and sets profile picture for current user
      description: Uploads and sets profile picture for current user.
      operationId: setProfilePictureForMyself
      x-api-path-slug: usersmyselfprofilepicture-post
      parameters:
      - in: body
        name: body
        description: Picture
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Uploads
      - Sets
      - Profile
      - Picturecurrent
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