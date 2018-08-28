swagger: "2.0"
x-collection-name: AWS Elastic Load Balancing
x-complete: 1
info:
  title: AWS Elastic Load Balancing API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetRulePriorities:
    get:
      summary: Set Rule Priorities
      description: Sets the priorities of the specified rules.
      operationId: setRulePriorities
      x-api-path-slug: actionsetrulepriorities-get
      parameters:
      - in: query
        name: RulePriorities.member.N
        description: The rule priorities
        type: string
      responses:
        200:
          description: OK
      tags:
      - Rule Priorities