---
swagger: "2.0"
x-collection-name: AWS S3
x-complete: 0
info:
  title: AWS S3 PUT Bucket website
  version: 1.0.0
  description: Sets the configuration of the website that is specified in thewebsite
    subresource
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?metrics&amp;id=Id:
    put:
      summary: PUT Bucket Metrics
      description: Sets or updates a metrics configuration for the CloudWatch request
        metrics (specified by themetrics configuration ID) from the bucket
      operationId: put-bucket-metrics
      x-api-path-slug: metricsampidid-put
      responses:
        200:
          description: OK
      tags:
      - Bucket
      - Metrics
  /?website:
    put:
      summary: PUT Bucket website
      description: Sets the configuration of the website that is specified in thewebsite
        subresource
      operationId: put-bucket-website
      x-api-path-slug: website-put
      responses:
        200:
          description: OK
      tags:
      - Bucket
      - Website
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