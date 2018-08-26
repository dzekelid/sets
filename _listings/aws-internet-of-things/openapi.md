---
swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 1
info:
  title: AWS Internet of Things API
  version: 1.0.0
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
      description: Sets the specified version of the specified policy as the policy's
        default (operative) version.
      operationId: setDefaultPolicyVersion
      x-api-path-slug: actionsetdefaultpolicyversion-get
      parameters:
      - in: query
        name: policyName
        description: The policy name
        type: string
      - in: query
        name: policyVersionId
        description: The policy version ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
  /?Action=SetLoggingOptions:
    get:
      summary: Set Logging Options
      description: Sets the logging options.
      operationId: setLoggingOptions
      x-api-path-slug: actionsetloggingoptions-get
      parameters:
      - in: query
        name: loggingOptionsPayload
        description: The logging options payload
        type: string
      responses:
        200:
          description: OK
      tags:
      - Logging
---