---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Sets the team icon
  description: |-
    Sets the team icon for the team.

    __Minimum server version__: 4.9

    ##### Permissions
    Must be authenticated and have the `manage_team` permission.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /teams/{team_id}/image:
    post:
      summary: Sets the team icon
      description: |-
        Sets the team icon for the team.

        __Minimum server version__: 4.9

        ##### Permissions
        Must be authenticated and have the `manage_team` permission.
      operationId: sets-the-team-icon-for-the-team-minimum-server-version--49-permissionsmust-be-authenticated-and-have
      x-api-path-slug: teamsteam-idimage-post
      parameters:
      - in: formData
        name: image
        description: The image to be uploaded
      - in: path
        name: team_id
        description: Team GUID
      responses:
        200:
          description: OK
      tags:
      - Sets
      - Team
      - Icon
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