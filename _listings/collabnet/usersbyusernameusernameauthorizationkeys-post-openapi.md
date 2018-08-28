---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Sets authorization keys by username
  version: 1.0.0
  description: Sets authorization keys by username.
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
  /users/myself/preferences:
    patch:
      summary: Sets preferences for current user
      description: Sets preferences for current user.
      operationId: setPreferencesForMyself
      x-api-path-slug: usersmyselfpreferences-patch
      parameters:
      - in: body
        name: body
        description: Preferences
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Preferencescurrent
      - User
  /users/myself/authorization-keys:
    post:
      summary: Sets authorization keys for current user
      description: Sets authorization keys for current user.
      operationId: setAuthorizationKeysForMyself
      x-api-path-slug: usersmyselfauthorizationkeys-post
      parameters:
      - in: body
        name: body
        description: Authorization keys
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Authorization
      - Keyscurrent
      - User
  /users/by-username/{username}/profile-picture:
    post:
      summary: Uploads and sets profile picture by username
      description: Uploads and sets profile picture by username.
      operationId: setProfilePictureByUsername
      x-api-path-slug: usersbyusernameusernameprofilepicture-post
      parameters:
      - in: body
        name: body
        description: Picture
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: username
        description: Username
      responses:
        200:
          description: OK
      tags:
      - Uploads
      - Sets
      - Profile
      - Picture
      - By
      - Username
  /users/by-username/{username}/preferences:
    patch:
      summary: Sets preferences by user name
      description: Sets preferences by user name.
      operationId: setPreferences
      x-api-path-slug: usersbyusernameusernamepreferences-patch
      parameters:
      - in: body
        name: body
        description: Preferences
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: username
        description: Username
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Preferences
      - By
      - User
      - Name
  /users/by-username/{username}/authorization-keys:
    post:
      summary: Sets authorization keys by username
      description: Sets authorization keys by username.
      operationId: setAuthorizationKeys
      x-api-path-slug: usersbyusernameusernameauthorizationkeys-post
      parameters:
      - in: body
        name: body
        description: Authorization keys
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: username
        description: Username
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Authorization
      - Keys
      - By
      - Username
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