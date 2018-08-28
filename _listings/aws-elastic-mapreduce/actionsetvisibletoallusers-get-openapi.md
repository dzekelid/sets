---
swagger: "2.0"
x-collection-name: AWS Elastic MapReduce
x-complete: 0
info:
  title: AWS Elastic MapReduce API Set Visible To All Users
  version: 1.0.0
  description: Sets whether all AWS Identity and Access Management (IAM) users under
    your account can access the specified job flows.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetVisibleToAllUsers:
    get:
      summary: Set Visible To All Users
      description: Sets whether all AWS Identity and Access Management (IAM) users
        under your account can access the specified job flows.
      operationId: setVisibleToAllUsers
      x-api-path-slug: actionsetvisibletoallusers-get
      parameters:
      - in: query
        name: JobFlowIds
        description: Identifiers of the job flows to receive the new visibility setting
        type: string
      - in: query
        name: VisibleToAllUsers
        description: Whether the specified job flows are visible to all IAM users
          of the AWS account associated with the job flow
        type: string
      responses:
        200:
          description: OK
      tags:
      - Visible To All Users
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