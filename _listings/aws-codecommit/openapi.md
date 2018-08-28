swagger: "2.0"
x-collection-name: AWS CodeCommit
x-complete: 1
info:
  title: AWS CodeCommit API
  version: 1.0.0
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
  /?Action=UpdateRepositoryDescription:
    get:
      summary: Update Repository Description
      description: Sets or changes the comment or description for a repository.
      operationId: updateRepositoryDescription
      x-api-path-slug: actionupdaterepositorydescription-get
      parameters:
      - in: query
        name: repositoryDescription
        description: The new comment or description for the specified repository
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository to set or change the comment or description
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repositories