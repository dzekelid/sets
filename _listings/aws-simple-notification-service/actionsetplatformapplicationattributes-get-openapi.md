---
swagger: "2.0"
x-collection-name: AWS Simple Notification Service
x-complete: 0
info:
  title: AWS Simple Notification Service API Set Platform Application Attributes
  version: 1.0.0
  description: |-
    Sets the attributes of the platform application object for the supported push notification
          services, such as APNS and GCM.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetEndpointAttributes:
    get:
      summary: Set Endpoint Attributes
      description: |-
        Sets the attributes for an endpoint for a device on one of the supported push notification
              services, such as GCM and APNS.
      operationId: setEndpointAttributes
      x-api-path-slug: actionsetendpointattributes-get
      parameters:
      - in: query
        name: |-
          Attributes
                      , Attributes.entry.N.key (key), Attributesentry.N.value (value)
        description: A map of the endpoint attributes
        type: string
      - in: query
        name: EndpointArn
        description: EndpointArn used for SetEndpointAttributes action
        type: string
      responses:
        200:
          description: OK
      tags:
      - Endpoints
  /?Action=SetPlatformApplicationAttributes:
    get:
      summary: Set Platform Application Attributes
      description: |-
        Sets the attributes of the platform application object for the supported push notification
              services, such as APNS and GCM.
      operationId: setPlatformApplicationAttributes
      x-api-path-slug: actionsetplatformapplicationattributes-get
      parameters:
      - in: query
        name: |-
          Attributes
                      , Attributes.entry.N.key (key), Attributesentry.N.value (value)
        description: A map of the platform application attributes
        type: string
      - in: query
        name: PlatformApplicationArn
        description: PlatformApplicationArn for SetPlatformApplicationAttributes action
        type: string
      responses:
        200:
          description: OK
      tags:
      - Platform Applications
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