---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Sets whether inventory is agreed with tenants
  version: 1.0.0
  description: Sets whether inventory is agreed with tenants.
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
  /api/group/{id}/setgroupmemberstatus:
    put:
      summary: Sets members Active/Inactive system status
      description: Sets members active/inactive system status.
      operationId: Group_SetGroupMemberStatusByidBygroupMemberStatusDataContract
      x-api-path-slug: apigroupidsetgroupmemberstatus-put
      parameters:
      - in: body
        name: groupMemberStatusDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Members
      - Active
      - Inactive
      - System
      - Status
  /api/group/setgroupmembersorder:
    put:
      summary: Sets order for members of a group
      description: Sets order for members of a group.
      operationId: Group_SetGroupMembersOrderBygroupMembersOrderDataContract
      x-api-path-slug: apigroupsetgroupmembersorder-put
      parameters:
      - in: body
        name: groupMembersOrderDataContract
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
      - Ordermembers
      - Of
      - Group
  /api/group/{id}/setflags:
    put:
      summary: Sets the interest flags on groups interest role.
      description: Sets the interest flags on groups interest role..
      operationId: Group_SetInterestFlagsByidByflagsDataContract
      x-api-path-slug: apigroupidsetflags-put
      parameters:
      - in: body
        name: flagsDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Interest
      - Flags
      - "On"
      - Groups
      - Interest
      - Role
  /api/role/lettings/{id}/setdeposit:
    post:
      summary: Sets the deposit on a letting role
      description: Sets the deposit on a letting role.
      operationId: LettingRole_SetDepositByidBydatacontract
      x-api-path-slug: apirolelettingsidsetdeposit-post
      parameters:
      - in: body
        name: datacontract
        description: The deposit to set on the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Deposit
      - "On"
      - Letting
      - Role
  /api/role/lettings/{id}/setlettinginfo:
    post:
      summary: Sets the core information on a letting role
      description: Sets the core information on a letting role.
      operationId: LettingRole_SetInfoByidBydatacontract
      x-api-path-slug: apirolelettingsidsetlettinginfo-post
      parameters:
      - in: body
        name: datacontract
        description: The letting information of the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Core
      - Information
      - "On"
      - Letting
      - Role
  /api/role/lettings/{id}/setfeestructure:
    post:
      summary: Sets the fee structure on a letting role
      description: Sets the fee structure on a letting role.
      operationId: LettingRole_SetFeeStructureByidByfeeStructure
      x-api-path-slug: apirolelettingsidsetfeestructure-post
      parameters:
      - in: body
        name: feeStructure
        description: The fee structure text
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
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
      - Letting
      - Role
  /api/progression/lettings/{id}/setdeposit:
    post:
      summary: Sets the deposit on a letting role
      description: Sets the deposit on a letting role.
      operationId: LettingsProgression_SetDepositByidBydatacontract
      x-api-path-slug: apiprogressionlettingsidsetdeposit-post
      parameters:
      - in: body
        name: datacontract
        description: The deposit to set on the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Deposit
      - "On"
      - Letting
      - Role
  /api/progression/lettings/{id}/setfurnishinglevel:
    post:
      summary: Sets the deposit on a letting role
      description: Sets the deposit on a letting role.
      operationId: LettingsProgression_SetFurnishingLevelByidBydatacontract
      x-api-path-slug: apiprogressionlettingsidsetfurnishinglevel-post
      parameters:
      - in: body
        name: datacontract
        description: The deposit to set on the role
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The role id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Deposit
      - "On"
      - Letting
      - Role
  /api/progression/lettings/{roleId}/inventory/setrequired:
    post:
      summary: Sets whether inventory is needed on tenant role
      description: Sets whether inventory is needed on tenant role.
      operationId: LettingsProgression_SetInventoryRequiredByroleIdByrequired
      x-api-path-slug: apiprogressionlettingsroleidinventorysetrequired-post
      parameters:
      - in: query
        name: required
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: Tenant Role Id
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Whether
      - Inventory
      - Is
      - Needed
      - "On"
      - Tenant
      - Role
  /api/progression/lettings/{roleId}/inventory/setagreed:
    post:
      summary: Sets whether inventory is agreed with tenants
      description: Sets whether inventory is agreed with tenants.
      operationId: LettingsProgression_SetInventoryAgreedByroleIdByagreed
      x-api-path-slug: apiprogressionlettingsroleidinventorysetagreed-post
      parameters:
      - in: query
        name: agreed
        description: Is inventory agreed
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: Tenant role id
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Whether
      - Inventory
      - Is
      - Agreed
      - Tenants
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