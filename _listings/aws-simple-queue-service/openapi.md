---
swagger: "2.0"
x-collection-name: AWS Simple Queue Service
x-complete: 1
info:
  title: AWS Simple Queue Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetQueueAttributes:
    get:
      summary: Set Queue Attributes
      description: Sets the value of one or more queue attributes.
      operationId: setQueueAttributes
      x-api-path-slug: actionsetqueueattributes-get
      parameters:
      - in: query
        name: |-
          Attribute
                      , Attribute.N.Name (key), Attribute.N.Value (value)
        description: A map of attributes to set
        type: string
      - in: query
        name: QueueUrl
        description: The URL of the Amazon SQS queue whose attributes are set
        type: string
      responses:
        200:
          description: OK
      tags:
      - Queues
---