{
  "info": {
    "name": "AWS WAF API List SQL Injection Match Sets",
    "_postman_id": "36c992bd-3243-461d-82a2-d111b2c37560",
    "description": "Service: AWS WAFReturns an array of.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Web ACL",
      "item": [
        {
          "id": "c458e658-94bb-40fc-9f46-89f76222ce17",
          "name": "associateWebACL",
          "request": {
            "url": "http://example.com/api/?Action=AssociateWebACL?ResourceArn=ResourceArn&WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalAssociates a web ACL with a resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4382b281-8ad5-41dd-8d81-bae8405f666f"
            }
          ]
        },
        {
          "id": "a75af12f-7d7a-4800-8e17-f3f48a6bb76b",
          "name": "createWebACL",
          "request": {
            "url": "http://example.com/api/?Action=CreateWebACL?ChangeToken=ChangeToken&DefaultAction=DefaultAction&MetricName=MetricName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a WebACL, which contains the Rules that identify the CloudFront web requests that you want to allow, block, or count."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e3f7957-16d4-495b-8520-c736bdba968e"
            }
          ]
        },
        {
          "id": "43310f13-9394-450a-ba74-9fed23b7b8da",
          "name": "deleteWebACL",
          "request": {
            "url": "http://example.com/api/?Action=DeleteWebACL?ChangeToken=ChangeToken&WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ade1aab-266b-4df9-a7fa-4039c33817f1"
            }
          ]
        },
        {
          "id": "f4a66817-df03-45ae-9e4e-f4536f1bffcd",
          "name": "disassociateWebACL",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateWebACL?ResourceArn=ResourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalRemoves a web ACL from the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e91d78b5-fb94-4cbe-a1fd-88cdc7a1b901"
            }
          ]
        },
        {
          "id": "854923f9-3ae3-4929-bc57-34e3e669706f",
          "name": "getWebACL",
          "request": {
            "url": "http://example.com/api/?Action=GetWebACL?WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8880a50e-cb8a-4787-8bd0-d69c3dbac471"
            }
          ]
        },
        {
          "id": "740e515e-0191-4d15-8c71-0e7646221bac",
          "name": "getWebACLForResource",
          "request": {
            "url": "http://example.com/api/?Action=GetWebACLForResource?ResourceArn=ResourceArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalReturns the web ACL for the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9978486-21d8-48c1-b25d-241bbfe55040"
            }
          ]
        },
        {
          "id": "d0a98fde-59a1-411b-8fac-d2607d747cf0",
          "name": "listResourcesForWebACL",
          "request": {
            "url": "http://example.com/api/?Action=ListResourcesForWebACL?WebACLId=WebACLId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAF RegionalReturns an array of resources associated with the specified web ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3970231-3b41-48d4-9dae-d04f09f7d015"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Set",
      "item": [
        {
          "id": "0a33c759-4f73-4d89-8ad2-161d54e56eda",
          "name": "createByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateByteMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a ByteMatchSet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf23f6c2-bb50-42e3-9acf-808f1847df6d"
            }
          ]
        },
        {
          "id": "71a80358-d40d-4da9-a38c-1936bcd63171",
          "name": "deleteByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteByteMatchSet?ByteMatchSetId=ByteMatchSetId&ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "810ecb8b-8f2b-4655-ad39-54141191e8b8"
            }
          ]
        },
        {
          "id": "6a1a523d-9e3d-456f-bbf2-24bed2066193",
          "name": "getByteMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetByteMatchSet?ByteMatchSetId=ByteMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "814236ac-7036-4b05-aad0-fee52130db33"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Sets",
      "item": [
        {
          "id": "ae955033-562f-430d-9a9d-4aea142c2505",
          "name": "createIPSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateIPSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "084a80d3-4199-4608-966f-d009233b8c88"
            }
          ]
        },
        {
          "id": "7adf3c52-abbf-4ea1-a0fb-d1f11b737d49",
          "name": "deleteIPSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIPSet?ChangeToken=ChangeToken&IPSetId=IPSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45977c99-c47b-4202-80c0-be5f2986d9d7"
            }
          ]
        },
        {
          "id": "d1aeb5c6-7b35-407e-9d46-4f26b24ed71f",
          "name": "getIPSet",
          "request": {
            "url": "http://example.com/api/?Action=GetIPSet?IPSetId=IPSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac28507d-84df-4376-9252-5e1a40883d96"
            }
          ]
        },
        {
          "id": "3cb6a171-175e-4427-92cd-f2716c83c84b",
          "name": "listIPSets",
          "request": {
            "url": "http://example.com/api/?Action=ListIPSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54ecbbf7-42a5-4b70-8728-e6fc9bcc7bef"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "4a531d49-340c-4a7c-aa7c-e0eb8216861b",
          "name": "createRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateRule?ChangeToken=ChangeToken&MetricName=MetricName&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a Rule, which contains the IPSet objects, ByteMatchSet objects, and \n\t\t\tother predicates that identify the requests that you want to block."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b86abf3-0ee7-4cf4-a0ad-200198ea8a80"
            }
          ]
        },
        {
          "id": "5c5110fe-dc64-476a-b57e-afc3fc8e2c81",
          "name": "deleteRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRule?ChangeToken=ChangeToken&RuleId=RuleId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8207b01-5437-446e-9d97-d72f539fc768"
            }
          ]
        },
        {
          "id": "62fe692e-1240-4807-b13c-9ec25cddd512",
          "name": "getRule",
          "request": {
            "url": "http://example.com/api/?Action=GetRule?RuleId=RuleId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f11c9fb0-0bf9-4cf5-8e92-239fffbbbc0c"
            }
          ]
        },
        {
          "id": "2f80748e-e9ec-4c5c-9253-e85e965c26d6",
          "name": "listRules",
          "request": {
            "url": "http://example.com/api/?Action=ListRules?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e916002c-2e72-458a-a691-95acb5e0fd61"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Set",
      "item": [
        {
          "id": "52b4ca75-0e62-449a-9065-68b7b37aab8a",
          "name": "createSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateSizeConstraintSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a SizeConstraintSet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cdff261d-15e8-44ee-a770-1105e95adcf3"
            }
          ]
        },
        {
          "id": "0f1f3c44-a77e-43bc-b5a0-9e045d649dc6",
          "name": "deleteSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSizeConstraintSet?ChangeToken=ChangeToken&SizeConstraintSetId=SizeConstraintSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13910c17-1fa4-49b0-81b3-8c367603690b"
            }
          ]
        },
        {
          "id": "e6422794-2876-4052-bf70-c3b7fd027e6d",
          "name": "getSizeConstraintSet",
          "request": {
            "url": "http://example.com/api/?Action=GetSizeConstraintSet?SizeConstraintSetId=SizeConstraintSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3680ca5e-3e6d-490f-b490-746d121c500b"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Set",
      "item": [
        {
          "id": "1abaf91f-58e2-47e2-b5b1-3707cd023d65",
          "name": "createSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateSqlInjectionMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15fce568-cd4f-45e6-8627-f859e384d090"
            }
          ]
        },
        {
          "id": "d77a24d0-bfb2-429e-9474-5a6eae9ad8be",
          "name": "deleteSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSqlInjectionMatchSet?ChangeToken=ChangeToken&SqlInjectionMatchSetId=SqlInjectionMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18f93c01-a901-49f0-8ca4-7ce2727e21e2"
            }
          ]
        },
        {
          "id": "119fbef4-e3f7-4133-8689-495ce43a53ea",
          "name": "getSqlInjectionMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetSqlInjectionMatchSet?SqlInjectionMatchSetId=SqlInjectionMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ad19404-33e8-4d05-9aeb-b0e38c2852e6"
            }
          ]
        }
      ]
    },
    {
      "name": "XSS Match Set",
      "item": [
        {
          "id": "4fa42077-3eb5-4a64-9c16-2199bee6fe41",
          "name": "createXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateXssMatchSet?ChangeToken=ChangeToken&Name=Name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFCreates an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "594ce595-d19a-45b0-936a-bf69c18461a5"
            }
          ]
        },
        {
          "id": "5fd0d365-1281-4d18-a43a-c7498978ea2e",
          "name": "deleteXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteXssMatchSet?ChangeToken=ChangeToken&XssMatchSetId=XssMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFPermanently deletes an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69fcbc58-93f3-4354-95f8-be59d3385066"
            }
          ]
        },
        {
          "id": "01159925-b918-451a-827e-f088deb49bfc",
          "name": "getXssMatchSet",
          "request": {
            "url": "http://example.com/api/?Action=GetXssMatchSet?XssMatchSetId=XssMatchSetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f471677a-5de5-477c-869b-9eb329fb0b02"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Token",
      "item": [
        {
          "id": "20b120d3-0a4f-403b-b99d-ef7edcd7a002",
          "name": "getChangeToken",
          "request": {
            "url": "http://example.com/api/?Action=GetChangeToken?ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFWhen you want to create, update, or delete AWS WAF objects, get a change token and include the change token in the create, update, or delete request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "922633a5-1279-4756-96f5-33ec550244af"
            }
          ]
        },
        {
          "id": "f50fd4fa-8454-4f3c-82e7-c60375c6b613",
          "name": "getChangeTokenStatus",
          "request": {
            "url": "http://example.com/api/?Action=GetChangeTokenStatus?ChangeToken=ChangeToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns the status of a ChangeToken that you got by calling."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "090af6cd-0d1e-4364-b06b-96d506a6c7b7"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "8d444df0-a373-4e46-acd6-af622d8a8903",
          "name": "getSampledRequests",
          "request": {
            "url": "http://example.com/api/?Action=GetSampledRequests?MaxItems=MaxItems&RuleId=RuleId&TimeWindow=TimeWindow&WebAclId=WebAclId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFGets detailed information about a specified number of requests--a sample--that AWS WAF randomly selects from among the first 5,000 requests that your AWS resource received during a time range that you choose."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "976d1d9e-0427-4e0c-920f-ad098748e7dc"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Sets",
      "item": [
        {
          "id": "0dbf0354-0dda-4a87-acc0-0b2af315bb9f",
          "name": "listByteMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListByteMatchSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd5ec0f8-5045-41b9-9374-b86e0349900f"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Sets",
      "item": [
        {
          "id": "685050ba-fa0d-4904-a175-313780a3efa2",
          "name": "listSizeConstraintSets",
          "request": {
            "url": "http://example.com/api/?Action=ListSizeConstraintSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "104331b9-170c-44c4-955d-7915a304baf2"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Sets",
      "item": [
        {
          "id": "9bfc4f21-6733-40ca-b4bd-3425e80c94d6",
          "name": "listSqlInjectionMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListSqlInjectionMatchSets?Limit=Limit&NextMarker=NextMarker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Service: AWS WAFReturns an array of."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b6bcf1d-1d71-4281-a956-0a552217b12f"
            }
          ]
        }
      ]
    }
  ]
}