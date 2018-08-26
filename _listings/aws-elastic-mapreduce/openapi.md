---
swagger: "2.0"
x-collection-name: AWS Elastic MapReduce
x-complete: 1
info:
  title: AWS Elastic MapReduce API
  version: 1.0.0
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
---