swagger: "2.0"
x-collection-name: CollabNet
x-complete: 1
info:
  title: Foundation API
  version: 1.0.0
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
  /server/licensekey:
    put:
      summary: Sets/Updates license key
      description: Sets/updates license key.
      operationId: enterLicenseKey
      x-api-path-slug: serverlicensekey-put
      parameters:
      - in: body
        name: body
        description: License key
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sets
      - License
      - Key
  /integrationdata/myself/{namespaceid}:
    put:
      summary: Sets integration data for current user by namespace id
      description: Sets integration data for current user by namespace id.
      operationId: setMyIntegrationData
      x-api-path-slug: integrationdatamyselfnamespaceid-put
      parameters:
      - in: body
        name: body
        description: Integration data
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: namespaceid
        description: Namespace id
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Integration
      - Datacurrent
      - User
      - By
      - Namespace
  /integrationdata/myself/by-name/{namespace}:
    put:
      summary: Sets integration data for current user by namespace name
      description: Sets integration data for current user by namespace name.
      operationId: setMyIntegrationDataByName
      x-api-path-slug: integrationdatamyselfbynamenamespace-put
      parameters:
      - in: body
        name: body
        description: Integration data
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: createNamespace
        description: Create namespace if missing?
      - in: path
        name: namespace
        description: Namespace name
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Integration
      - Datacurrent
      - User
      - By
      - Namespace
      - Name
  /integrationdata/by-objectid/{objectid}/{namespaceid}:
    put:
      summary: Sets integration data for an object by namespace id
      description: Sets integration data for an object by namespace id.
      operationId: setIntegrationData
      x-api-path-slug: integrationdatabyobjectidobjectidnamespaceid-put
      parameters:
      - in: body
        name: body
        description: Integration data
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: namespaceid
        description: Namespace id
      - in: path
        name: objectid
        description: Object id
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Integration
      - Dataan
      - Object
      - By
      - Namespace
  /integrationdata/by-objectid/{objectid}/by-name/{namespace}:
    put:
      summary: Sets integration data for an object by namespace name
      description: Sets integration data for an object by namespace name.
      operationId: setIntegrationDataByName
      x-api-path-slug: integrationdatabyobjectidobjectidbynamenamespace-put
      parameters:
      - in: body
        name: body
        description: Integration data
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: createNamespace
        description: Create namespace if missing?
      - in: path
        name: namespace
        description: Namespace name
      - in: path
        name: objectid
        description: Object id
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Integration
      - Dataan
      - Object
      - By
      - Namespace
      - Name