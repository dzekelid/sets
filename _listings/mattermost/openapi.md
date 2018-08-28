swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost
  version: 1.0.0
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