{
  "info": {
    "name": "AWS CloudFormation API List Change Sets",
    "_postman_id": "4e20f769-351a-425a-ab4a-34c700dfcc74",
    "description": "Returns the ID and status of each active change set for a stack.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Stacks",
      "item": [
        {
          "id": "6de31f76-ecb7-4362-8484-c6ce7114d5b1",
          "name": "cancelUpdateStack",
          "request": {
            "url": "http://example.com/api/?Action=CancelUpdateStack?StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels an update on the specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54e25261-f9ae-4eab-84aa-d43e172444c8"
            }
          ]
        },
        {
          "id": "3f3b60ad-d2e7-4659-b9ef-93677c08dcd6",
          "name": "createStack",
          "request": {
            "url": "http://example.com/api/?Action=CreateStack?Capabilities.member.N=Capabilities.member.N&DisableRollback=DisableRollback&NotificationARNs.member.N=NotificationARNs.member.N&OnFailure=OnFailure&Parameters.member.N=Parameters.member.N&ResourceTypes.member.N=ResourceTypes.member.N&RoleARN=RoleARN&StackName=StackName&StackPolicyBody=StackPolicyBody&StackPolicyURL=StackPolicyURL&Tags.member.N=Tags.member.N&TemplateBody=TemplateBody&TemplateURL=TemplateURL&TimeoutInMinutes=TimeoutInMinutes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a stack as specified in the template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9730553-9e4e-422e-9a0c-36930ef3e983"
            }
          ]
        },
        {
          "id": "988d894a-c7cf-4a0d-bf35-a8667e20033d",
          "name": "deleteStack",
          "request": {
            "url": "http://example.com/api/?Action=DeleteStack?RetainResources.member.N=RetainResources.member.N&RoleARN=RoleARN&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffdd0a21-c527-4b8d-a836-a8092e83f933"
            }
          ]
        },
        {
          "id": "c45932c3-0d0a-4435-a72b-91b80fca5f70",
          "name": "describeStacks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStacks?NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the description for the specified stack; if no stack name was specified, then it returns the description for all the stacks created."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ed008940-ab5f-4862-9bb1-b0d073a16cfc"
            }
          ]
        }
      ]
    },
    {
      "name": "Rollback",
      "item": [
        {
          "id": "2b5c5366-d824-4028-a992-cabedbb740af",
          "name": "continueUpdateRollback",
          "request": {
            "url": "http://example.com/api/?Action=ContinueUpdateRollback?ResourcesToSkip.member.N=ResourcesToSkip.member.N&RoleARN=RoleARN&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "For a specified stack that is in the UPDATE_ROLLBACK_FAILED state, continues rolling it back\n         to the UPDATE_ROLLBACK_COMPLETE state."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5db6477d-df0f-4218-83bd-65aac4e7cc30"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Sets",
      "item": [
        {
          "id": "bfb317fb-5f5c-4e7e-9975-5f69ea5f62d1",
          "name": "createChangeSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateChangeSet?Capabilities.member.N=Capabilities.member.N&ChangeSetName=ChangeSetName&ChangeSetType=ChangeSetType&ClientToken=ClientToken&Description=Description&NotificationARNs.member.N=NotificationARNs.member.N&Parameters.member.N=Parameters.member.N&ResourceTypes.member.N=ResourceTypes.member.N&RoleARN=RoleARN&StackName=StackName&Tags.member.N=Tags.member.N&TemplateBody=TemplateBody&TemplateURL=TemplateURL&UsePreviousTemplate=UsePreviousTemplate",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a list of changes for a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94c8aaab-9098-4de7-8153-8cff949d9c32"
            }
          ]
        },
        {
          "id": "7c91fee4-6b27-4b6f-b07e-15950ee06b03",
          "name": "deleteChangeSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteChangeSet?ChangeSetName=ChangeSetName&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified change set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89c5a4e9-4c1b-4e9c-a822-eeaffd969016"
            }
          ]
        },
        {
          "id": "ede90cae-4ed5-408c-ad40-714d5125aae4",
          "name": "describeChangeSet",
          "request": {
            "url": "http://example.com/api/?Action=DescribeChangeSet?ChangeSetName=ChangeSetName&NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the inputs for the change set and a list of changes that AWS CloudFormation will make if you execute the change set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "270e00b1-4050-4b00-bf25-047d6ea9fbfc"
            }
          ]
        },
        {
          "id": "037b937d-9a4e-4185-9793-da184c14fceb",
          "name": "executeChangeSet",
          "request": {
            "url": "http://example.com/api/?Action=ExecuteChangeSet?ChangeSetName=ChangeSetName&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a stack using the input information that was provided when the specified change set was created."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4904ef95-d5b8-4130-94d2-9183cba206d3"
            }
          ]
        },
        {
          "id": "10288e91-2494-4d28-b938-66266273208c",
          "name": "listChangeSets",
          "request": {
            "url": "http://example.com/api/?Action=ListChangeSets?NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the ID and status of each active change set for a stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f830e87-b7d3-4144-8df1-8b7c74f041a0"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Limits",
      "item": [
        {
          "id": "ca1e90f5-1c00-41f6-9f81-48cc6ec0018f",
          "name": "describeAccountLimits",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAccountLimits?NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves your account's AWS CloudFormation limits, such as the maximum number of stacks that you can create in your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46e0e92c-a605-438e-abbe-8a0d06593104"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack Events",
      "item": [
        {
          "id": "1838a13b-ef4b-4ec6-8fdd-69bcc6ff4d65",
          "name": "describeStackEvents",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackEvents?NextToken=NextToken&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all stack related events for a specified stack in reverse chronological order."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1b31f5a-b114-4430-9be4-8dc00d593b67"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack Resources",
      "item": [
        {
          "id": "7d1d677a-e784-49aa-bf89-afcbefe293fc",
          "name": "describeStackResource",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackResource?LogicalResourceId=LogicalResourceId&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the specified resource in the specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2fe738b9-0bfd-40fe-a333-8f75d68103fc"
            }
          ]
        },
        {
          "id": "9e751bd5-58c9-4f38-bff5-d201406fee37",
          "name": "describeStackResources",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStackResources?LogicalResourceId=LogicalResourceId&PhysicalResourceId=PhysicalResourceId&StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns AWS resource descriptions for running and deleted stacks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "335e0646-f703-45d5-95b9-31ec3c597fe3"
            }
          ]
        }
      ]
    },
    {
      "name": "Template Cost",
      "item": [
        {
          "id": "3c7d3126-bf4e-419c-9105-5ed0a34cf1d2",
          "name": "estimateTemplateCost",
          "request": {
            "url": "http://example.com/api/?Action=EstimateTemplateCost?Parameters.member.N=Parameters.member.N&TemplateBody=TemplateBody&TemplateURL=TemplateURL",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the estimated monthly cost of a template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1eb4a7a3-3181-483e-93fa-3290dedab1e6"
            }
          ]
        }
      ]
    },
    {
      "name": "Stack Policies",
      "item": [
        {
          "id": "fbae209f-2df7-4553-bedf-9eb15e471292",
          "name": "getStackPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetStackPolicy?StackName=StackName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the stack policy for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "723d6b49-7048-49fc-be18-23b0707604c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Templates",
      "item": [
        {
          "id": "167f7119-71e1-4c76-9dd6-57cc08b842f8",
          "name": "getTemplate",
          "request": {
            "url": "http://example.com/api/?Action=GetTemplate?ChangeSetName=ChangeSetName&StackName=StackName&TemplateStage=TemplateStage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the template body for a specified stack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40eac720-1575-46c6-afb2-44f43091a0ca"
            }
          ]
        },
        {
          "id": "057686f9-de54-402b-8ee0-58654b210ab7",
          "name": "getTemplateSummary",
          "request": {
            "url": "http://example.com/api/?Action=GetTemplateSummary?StackName=StackName&TemplateBody=TemplateBody&TemplateURL=TemplateURL",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about a new or existing template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef9b3faa-4e07-401b-9570-c90f0b63e565"
            }
          ]
        }
      ]
    }
  ]
}