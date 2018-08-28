---
swagger: "2.0"
x-collection-name: AWS Redshift
x-complete: 0
info:
  title: Amazon Redshift API Reset Cluster Parameter Group
  version: 1.0.0
  description: |-
    Sets one or more parameters of the specified parameter group to their default
                values and sets the source values of the parameters to "engine-default".
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ResetClusterParameterGroup:
    get:
      summary: Reset Cluster Parameter Group
      description: |-
        Sets one or more parameters of the specified parameter group to their default
                    values and sets the source values of the parameters to "engine-default".
      operationId: resetClusterParameterGroup
      x-api-path-slug: actionresetclusterparametergroup-get
      parameters:
      - in: query
        name: ParameterGroupName
        description: The name of the cluster parameter group to be reset
        type: string
      - in: query
        name: Parameters.Parameter.N
        description: An array of names of parameters to be reset
        type: string
      - in: query
        name: ResetAllParameters
        description: If true, all parameters in the specified parameter group will
          be reset            to their default values
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
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