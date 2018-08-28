---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 0
info:
  title: Context.IO Post Accounts Messages Message Flags
  description: Sets message flags for a given email.
  version: 1.0.0
host: api.context.io
basePath: /2.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{id}/messages/{message_id}/flags:
    post:
      summary: Post Accounts Messages Message Flags
      description: Sets message flags for a given email.
      operationId: Create_setAccountMessageFlags_
      x-api-path-slug: accountsidmessagesmessage-idflags-post
      parameters:
      - in: query
        name: answered
        description: Message has been answered
      - in: query
        name: deleted
        description: Message is deleted for later removal
      - in: query
        name: draft
        description: Message has not completed composition (marked as a draft)
      - in: query
        name: flagged
        description: Message is flagged for urgent/special attention
      - in: path
        name: id
        description: Unique id of an account accessible through your API key
      - in: path
        name: message_id
        description: Unique id of a message
      - in: query
        name: seen
        description: Message has been read
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Messages
      - Message
      - Flags
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