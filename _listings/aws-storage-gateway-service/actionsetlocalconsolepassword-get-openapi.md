---
swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 0
info:
  title: AWS Storage Gateway Service API Set Local Console Password
  version: 1.0.0
  description: Sets the password for your VM local console.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetLocalConsolePassword:
    get:
      summary: Set Local Console Password
      description: Sets the password for your VM local console.
      operationId: setLocalConsolePassword
      x-api-path-slug: actionsetlocalconsolepassword-get
      parameters:
      - in: query
        name: GatewayARN
        description: The Amazon Resource Name (ARN) of the gateway
        type: string
      - in: query
        name: LocalConsolePassword
        description: The password you want to set for your VM local console
        type: string
      responses:
        200:
          description: OK
      tags:
      - Local Console Password
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