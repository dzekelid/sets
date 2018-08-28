swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 1
info:
  title: AWS Cognito Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AdminSetUserSettings:
    get:
      summary: Admin Set User Settings
      description: Sets all the user settings for a specified user name.
      operationId: adminSetUserSettings
      x-api-path-slug: actionadminsetusersettings-get
      parameters:
      - in: query
        name: MFAOptions
        description: Specifies the options for MFA (e
        type: string
      - in: query
        name: Username
        description: The user name of the user for whom you wish to set user settings
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to set the
          users settings, such            as MFA options
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users
  /?Action=SetCognitoEvents:
    get:
      summary: Set Cognito Events
      description: Sets the AWS Lambda function for a given event type for an identity
        pool.
      operationId: setCognitoEvents
      x-api-path-slug: actionsetcognitoevents-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: The Cognito Identity Pool to use when configuring Cognito Events
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
  /?Action=SetIdentityPoolConfiguration:
    get:
      summary: Set Identity Pool Configuration
      description: Sets the necessary configuration for push sync.
      operationId: setIdentityPoolConfiguration
      x-api-path-slug: actionsetidentitypoolconfiguration-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: A name-spaced GUID (for example, us-east-1:23EC4050-6AEA-7089-A2DD-08002EXAMPLE)
          created by Amazon Cognito
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pools
  /?Action=SetIdentityPoolRoles:
    get:
      summary: Set Identity Pool Roles
      description: Sets the roles for an identity pool.
      operationId: setIdentityPoolRoles
      x-api-path-slug: actionsetidentitypoolroles-get
      parameters:
      - in: query
        name: IdentityPoolId
        description: An identity pool ID in the format REGION:GUID
        type: string
      - in: query
        name: RoleMappings
        description: How users for a specific identity provider are to mapped to roles
        type: string
      - in: query
        name: Roles
        description: The map of roles associated with this pool
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity Pool
  /?Action=SetUserSettings:
    get:
      summary: Set User Settings
      description: Sets the user settings like multi-factor authentication (MFA).
      operationId: setUserSettings
      x-api-path-slug: actionsetusersettings-get
      parameters:
      - in: query
        name: AccessToken
        description: The access token for the set user settings request
        type: string
      - in: query
        name: MFAOptions
        description: Specifies the options for MFA (e
        type: string
      responses:
        200:
          description: OK
      tags:
      - Users