---
swagger: "2.0"
x-collection-name: AWS Identity and Access Management
x-complete: 0
info:
  title: AWS Identity and Access Management API Update Service Specific Credential
  version: 1.0.0
  description: |-
    Sets the status of a service-specific credential to Active or
            Inactive.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetDefaultPolicyVersion:
    get:
      summary: Set Default Policy Version
      description: |-
        Sets the specified version of the specified policy as the policy's default (operative)
              version.
      operationId: setDefaultPolicyVersion
      x-api-path-slug: actionsetdefaultpolicyversion-get
      parameters:
      - in: query
        name: PolicyArn
        description: The Amazon Resource Name (ARN) of the IAM policy whose default
          version you want to      set
        type: string
      - in: query
        name: VersionId
        description: The version of the policy to set as the default (operative) version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Default Policy Versions
  /?Action=UpdateServiceSpecificCredential:
    get:
      summary: Update Service Specific Credential
      description: |-
        Sets the status of a service-specific credential to Active or
                Inactive.
      operationId: updateServiceSpecificCredential
      x-api-path-slug: actionupdateservicespecificcredential-get
      parameters:
      - in: query
        name: ServiceSpecificCredentialId
        description: The unique identifier of the service-specific credential
        type: string
      - in: query
        name: Status
        description: The status to be assigned to the service-specific credential
        type: string
      - in: query
        name: UserName
        description: The name of the IAM user associated with the service-specific
          credential
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service Specific Credentials
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