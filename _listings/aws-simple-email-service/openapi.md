---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 1
info:
  title: AWS Simple Email Service API
  version: 1.0.0
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
  /?Action=SetReceiptRulePosition:
    get:
      summary: Set Receipt Rule Position
      description: Sets the position of the specified receipt rule in the receipt
        rule set.
      operationId: setReceiptRulePosition
      x-api-path-slug: actionsetreceiptruleposition-get
      parameters:
      - in: query
        name: After
        description: The name of the receipt rule after which to place the specified
          receipt rule
        type: string
      - in: query
        name: RuleName
        description: The name of the receipt rule to reposition
        type: string
      - in: query
        name: RuleSetName
        description: The name of the receipt rule set that contains the receipt rule
          to reposition
        type: string
      responses:
        200:
          description: OK
      tags:
      - Receipt Rules
---