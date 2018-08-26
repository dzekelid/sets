---
swagger: "2.0"
x-collection-name: AWS S3
x-complete: 1
info:
  title: No Title
  version: 1.0.0
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
---