---
swagger: "2.0"
x-collection-name: AWS Key Management Service
x-complete: 1
info:
  title: AWS Key Management Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DisableKey:
    get:
      summary: Disable Key
      description: |-
        Sets the state of a customer master key (CMK) to disabled, thereby preventing its use
              for cryptographic operations.
      operationId: disableKey
      x-api-path-slug: actiondisablekey-get
      parameters:
      - in: query
        name: KeyId
        description: A unique identifier for the CMK
        type: string
      responses:
        200:
          description: OK
      tags:
      - Keys
---