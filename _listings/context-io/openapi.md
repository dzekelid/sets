---
swagger: "2.0"
x-collection-name: Context.IO
x-complete: 1
info:
  title: Context.IO
  description: context-io-is-the-missing-email-api-that-makes-it-easy-and-fast-to-integrate-your-users-email-data-in-your-application-
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
---