---
swagger: "2.0"
x-collection-name: AWS WAF
x-complete: 0
info:
  title: AWS WAF API List IP Sets
  version: 1.0.0
  description: 'Service: AWS WAFReturns an array of.'
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListByteMatchSets:
    get:
      summary: List Byte Match Sets
      description: 'Service: AWS WAFReturns an array of.'
      operationId: listByteMatchSets
      x-api-path-slug: actionlistbytematchsets-get
      parameters:
      - in: query
        name: Limit
        description: Specifies the number of ByteMatchSet objects that you want AWS
          WAF to return for this request
        type: string
      - in: query
        name: NextMarker
        description: If you specify a value for Limit and you have more ByteMatchSets
          than the value of Limit, AWS WAF returns a NextMarker value in the response
          that allows you to list another group of ByteMatchSets
        type: string
      responses:
        200:
          description: OK
      tags:
      - Byte Match Sets
  /?Action=ListIPSets:
    get:
      summary: List IP Sets
      description: 'Service: AWS WAFReturns an array of.'
      operationId: listIPSets
      x-api-path-slug: actionlistipsets-get
      parameters:
      - in: query
        name: Limit
        description: Specifies the number of IPSet objects that you want AWS WAF to
          return for this request
        type: string
      - in: query
        name: NextMarker
        description: If you specify a value for Limit and you have more IPSets than
          the value of Limit, AWS WAF returns a NextMarker value in the response that
          allows you to list another group of IPSets
        type: string
      responses:
        200:
          description: OK
      tags:
      - IP Sets
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