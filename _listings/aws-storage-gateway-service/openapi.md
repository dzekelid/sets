---
swagger: "2.0"
x-collection-name: AWS Storage Gateway Service
x-complete: 1
info:
  title: AWS Storage Gateway Service API
  version: 1.0.0
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
---