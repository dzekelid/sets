---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 0
info:
  title: AWS Simple Email Service API Set Active Receipt Rule Set
  version: 1.0.0
  description: Sets the specified receipt rule set as the active receipt rule set.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListConfigurationSets:
    get:
      summary: List Configuration Sets
      description: Lists the configuration sets associated with your AWS account.
      operationId: listConfigurationSets
      x-api-path-slug: actionlistconfigurationsets-get
      parameters:
      - in: query
        name: MaxItems
        description: The number of configuration sets to return
        type: string
      - in: query
        name: NextToken
        description: A token returned from a previous call to ListConfigurationSets
          to indicate the position of the configuration set in the configuration set
          list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Sets
  /?Action=ListReceiptRuleSets:
    get:
      summary: List Receipt Rule Sets
      description: Lists the receipt rule sets that exist under your AWS account.
      operationId: listReceiptRuleSets
      x-api-path-slug: actionlistreceiptrulesets-get
      parameters:
      - in: query
        name: NextToken
        description: A token returned from a previous call to ListReceiptRuleSets
          to indicate the position in the receipt rule set list
        type: string
      responses:
        200:
          description: OK
      tags:
      - Receipt Rule Sets
  /?Action=SetActiveReceiptRuleSet:
    get:
      summary: Set Active Receipt Rule Set
      description: Sets the specified receipt rule set as the active receipt rule
        set.
      operationId: setActiveReceiptRuleSet
      x-api-path-slug: actionsetactivereceiptruleset-get
      parameters:
      - in: query
        name: RuleSetName
        description: The name of the receipt rule set to make active
        type: string
      responses:
        200:
          description: OK
      tags:
      - Receipt Rule Sets
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