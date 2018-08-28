---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Sets the description of the specified group
  version: 1.0.0
  description: Sets the description of the specified group.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/admin/agency/{id}/setfeestructure:
    post:
      summary: Sets the fee structure on an agency
      description: Sets the fee structure on an agency.
      operationId: AgencyAdmin_SetFeeStructureByidByfeeStructure
      x-api-path-slug: apiadminagencyidsetfeestructure-post
      parameters:
      - in: body
        name: feeStructure
        description: The fee structure text
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The agency id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Fee
      - Structure
      - "On"
      - Agency
  /api/todo/claimtask:
    put:
      summary: Sets the claiming negotiator for the task
      description: Sets the claiming negotiator for the task.
      operationId: DefaultToDo_ClaimTaskByclaimTask
      x-api-path-slug: apitodoclaimtask-put
      parameters:
      - in: body
        name: claimTask
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Claiming
      - Negotiatorthe
      - Task
  /api/document/setprivacy:
    put:
      summary: Sets the document privacy for an existing document.  This is used to
        change a document from being publicly accessible to being private, and vice
        versa.
      description: Sets the document privacy for an existing document.  this is used
        to change a document from being publicly accessible to being private, and
        vice versa..
      operationId: Document_SetDocumentPrivacyBysetDocumentPrivacyCommand
      x-api-path-slug: apidocumentsetprivacy-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: setDocumentPrivacyCommand
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Document
      - Privacyan
      - Existing
      - Document
      - ""
      - ""
      - This
      - Is
      - Used
      - To
      - Change
      - Document
      - From
      - Being
      - Publicly
      - Accessible
      - To
      - Being
      - Private
      - ""
      - Vice
      - Versa
  /api/group/{id}/setdescription:
    put:
      summary: Sets the description of the specified group
      description: Sets the description of the specified group.
      operationId: Group_SetDescriptionByidBynewDescriptionCommand
      x-api-path-slug: apigroupidsetdescription-put
      parameters:
      - in: path
        name: id
        description: The id of the group
      - in: body
        name: newDescriptionCommand
        description: The set description data contract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Description
      - Of
      - Specified
      - Group
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