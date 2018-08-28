---
swagger: "2.0"
x-collection-name: AWS CodeCommit
x-complete: 0
info:
  title: AWS CodeCommit API Update Default Branch
  version: 1.0.0
  description: Sets or changes the default branch name for the specified repository.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateDefaultBranch:
    get:
      summary: Update Default Branch
      description: Sets or changes the default branch name for the specified repository.
      operationId: updateDefaultBranch
      x-api-path-slug: actionupdatedefaultbranch-get
      parameters:
      - in: query
        name: defaultBranchName
        description: The name of the branch to set as the default
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository to set or change the default branch
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Branches
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