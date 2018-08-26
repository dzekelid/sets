---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List all Sets
  description: Lists all available sets.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/item_sets:
    delete:
      summary: Delete item sets
      description: Delete item sets.
      operationId: deleteRestItemSets
      x-api-path-slug: restitem-sets-delete
      responses:
        200:
          description: OK
      tags:
      - Item
      - Sets
    get:
      summary: List item sets
      description: Lists all item sets.
      operationId: getRestItemSets
      x-api-path-slug: restitem-sets-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Item
      - Sets
    post:
      summary: Create item sets
      description: Create item sets.
      operationId: postRestItemSets
      x-api-path-slug: restitem-sets-post
      parameters:
      - in: query
        name: params
        description: includes the item sets that have to be created
      responses:
        200:
          description: OK
      tags:
      - Item
      - Sets
    put:
      summary: Update item sets
      description: Update item sets.
      operationId: putRestItemSets
      x-api-path-slug: restitem-sets-put
      responses:
        200:
          description: OK
      tags:
      - Item
      - Sets
  /rest/plugin_sets:
    get:
      summary: List all Sets
      description: Lists all available sets.
      operationId: getRestPluginSets
      x-api-path-slug: restplugin-sets-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Sets
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