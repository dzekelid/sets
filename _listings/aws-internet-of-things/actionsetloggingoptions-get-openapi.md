---
swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 0
info:
  title: AWS Internet of Things API Set Logging Options
  version: 1.0.0
  description: Sets the logging options.
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