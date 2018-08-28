---
swagger: "2.0"
x-collection-name: AWS CloudFormation
x-complete: 0
info:
  title: AWS CloudFormation API Set Stack Policy
  version: 1.0.0
  description: Sets a stack policy for a specified stack.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListChangeSets:
    get:
      summary: List Change Sets
      description: Returns the ID and status of each active change set for a stack.
      operationId: listChangeSets
      x-api-path-slug: actionlistchangesets-get
      parameters:
      - in: query
        name: NextToken
        description: A string (provided by the ListChangeSets response output) that
          identifies the next page of change sets that you want to retrieve
        type: string
      - in: query
        name: StackName
        description: The name or the Amazon Resource Name (ARN) of the stack for which
          you want to list change sets
        type: string
      responses:
        200:
          description: OK
      tags:
      - Change Sets
  /?Action=SetStackPolicy:
    get:
      summary: Set Stack Policy
      description: Sets a stack policy for a specified stack.
      operationId: setStackPolicy
      x-api-path-slug: actionsetstackpolicy-get
      parameters:
      - in: query
        name: StackName
        description: The name or unique stack ID that you want to associate a policy
          with
        type: string
      - in: query
        name: StackPolicyBody
        description: Structure containing the stack policy body
        type: string
      - in: query
        name: StackPolicyURL
        description: Location of a file containing the stack policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stack Policies
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