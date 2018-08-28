swagger: "2.0"
x-collection-name: AWS Inspector
x-complete: 1
info:
  title: AWS Inspector API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetTagsForResource:
    get:
      summary: Set Tags For Resource
      description: |-
        Sets tags (key and value pairs) to the assessment template that is specified by the
                 ARN of the assessment template.
      operationId: setTagsForResource
      x-api-path-slug: actionsettagsforresource-get
      parameters:
      - in: query
        name: resourceArn
        description: The ARN of the assessment template that you want to set tags
          to
        type: string
      - in: query
        name: tags
        description: A collection of key and value pairs that you want to set to the
          assessment         template
        type: string
      responses:
        200:
          description: OK
      tags:
      - Tags For Resources