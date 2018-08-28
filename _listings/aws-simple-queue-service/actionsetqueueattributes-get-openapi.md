---
swagger: "2.0"
x-collection-name: AWS Simple Queue Service
x-complete: 0
info:
  title: AWS Simple Queue Service API Set Queue Attributes
  version: 1.0.0
  description: Sets the value of one or more queue attributes.
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