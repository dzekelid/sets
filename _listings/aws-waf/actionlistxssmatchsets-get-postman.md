{
  "info": {
    "name": "AWS WAF API List Xss Match Sets",
    "_postman_id": "64577da2-1b7f-431a-b08a-b1381098db0e",
    "description": "Service: AWS WAFReturns an array of.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Web ACL",
      "item": [
        {
          "id": "f6546823-3eaf-46d3-824b-ce37b939a086",
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
              "id": "2c104940-c5fb-4add-bf6a-da822a135062"
            }
          ]
        },
        {
          "id": "e2507c5e-574d-4568-990c-6a5557aa8423",
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
              "id": "68ff3d8a-ef75-4e3f-9306-cd773b119448"
            }
          ]
        },
        {
          "id": "708112b5-19fb-442c-84d4-9d43abfcb065",
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
              "id": "1df3b8ec-4a29-4724-86fa-5bf6de5eff4b"
            }
          ]
        },
        {
          "id": "340f3084-a29c-4d6a-be42-cef80a689917",
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
              "id": "096334d8-2aa9-414c-b7de-40ffaeafc7a4"
            }
          ]
        },
        {
          "id": "00bfe8ff-de43-41f9-a485-eb34c8d7f1db",
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
              "id": "acec9cc8-2c9f-4245-b95b-cc376c35e8a8"
            }
          ]
        },
        {
          "id": "14326af9-a705-4808-92cd-fb95e9a91ea3",
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
              "id": "8d1ead87-606a-4d62-8b82-dd3124866421"
            }
          ]
        },
        {
          "id": "16a31c32-d16c-4d7a-b908-4963637245d1",
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
              "id": "8a56556e-1453-4cdf-aa15-14cbb7420a17"
            }
          ]
        },
        {
          "id": "c96f8e7e-567f-4485-9093-f6be8cf739eb",
          "name": "listWebACLs",
          "request": {
            "url": "http://example.com/api/?Action=ListWebACLs?Limit=Limit&NextMarker=NextMarker",
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
              "id": "6675ed1d-12d5-4d64-883d-91ad5d914384"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Set",
      "item": [
        {
          "id": "e02fc676-adaa-4d5f-8a8f-c629cb88cad6",
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
              "id": "8fedc157-823f-4130-a1f2-aea00e84dd36"
            }
          ]
        },
        {
          "id": "5ac57f3c-eacf-4271-9ffb-d20449450e4e",
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
              "id": "5fc710da-0e91-4330-9a96-859f87c6888f"
            }
          ]
        },
        {
          "id": "4686a3bd-2e8c-46c9-9d1e-86ba3f10e599",
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
              "id": "e630cce3-35c0-4998-9b65-4db976b60d16"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Sets",
      "item": [
        {
          "id": "bc856f3a-0a5d-4bbb-af18-e4bdb94b7385",
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
              "id": "03cddb51-2654-4a98-8d22-da14ccd0d6f7"
            }
          ]
        },
        {
          "id": "607172a0-e88b-4051-a888-99cc5ae24d9e",
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
              "id": "ec6d95e0-cca7-4557-a6e8-0209a7cf7e9d"
            }
          ]
        },
        {
          "id": "5e0c3f2b-d933-493b-be1d-75f6da3c954c",
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
              "id": "8cb9f151-9a91-4b07-95a7-e2f6d77e9840"
            }
          ]
        },
        {
          "id": "1589758d-c412-4e4d-a911-fa9b950b4a92",
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
              "id": "6b638c47-e071-45e0-9b9e-da0d5a1d04fa"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "492ef04f-4748-48d8-80ae-45d2f13d291e",
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
              "id": "49975319-671a-4d3d-baf6-dbe74161a084"
            }
          ]
        },
        {
          "id": "190fba49-9737-4749-bbbe-68ede0f3c815",
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
              "id": "5c05306b-af8c-4f2b-aa69-5a6e7fbfc600"
            }
          ]
        },
        {
          "id": "c23add58-e674-44c5-9b4d-7a99d6168783",
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
              "id": "05d385e5-858b-4cdb-97b9-9747964d76bc"
            }
          ]
        },
        {
          "id": "34b29d3b-5453-4011-80c3-58040b41326a",
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
              "id": "e8d37b21-e4bd-479d-b985-b97c23f1b740"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Set",
      "item": [
        {
          "id": "529af6ed-ceda-4c4a-b0fa-1b71b5f4d663",
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
              "id": "bb20a98d-1ca9-436e-a187-fd3907669765"
            }
          ]
        },
        {
          "id": "666101d7-9199-4718-9e26-4700ae69c620",
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
              "id": "3938ec1c-a35f-42e2-b705-b6d4baf74c4e"
            }
          ]
        },
        {
          "id": "b37a5c8d-bc41-44f1-90e0-7e35497a5565",
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
              "id": "1f1b5724-5482-403e-9fab-17a0a81005fc"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Set",
      "item": [
        {
          "id": "233b2482-2db0-432c-8582-7e80070f7f04",
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
              "id": "11f4b0ae-2877-48a7-9331-3f2a1c5fd6fe"
            }
          ]
        },
        {
          "id": "ceca5fd8-7904-4043-9219-71a7945b2e1e",
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
              "id": "c1282985-f4dd-4d26-99ec-c616185fca0e"
            }
          ]
        },
        {
          "id": "5e46beb3-e1f5-4474-937e-4c29561cf1e4",
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
              "id": "63a3aff9-5718-44fe-9af2-bfeb3bc6cb8c"
            }
          ]
        }
      ]
    },
    {
      "name": "XSS Match Set",
      "item": [
        {
          "id": "fd8cb65e-7a83-423c-9d7f-f2a171650b0f",
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
              "id": "e15ed3f6-90ca-4cf3-83e1-5a1d6de9af31"
            }
          ]
        },
        {
          "id": "40be21d2-6430-4de9-a5d7-b4b2a0b4f65a",
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
              "id": "f938504d-7a57-463d-a7ad-65315171ce9d"
            }
          ]
        },
        {
          "id": "85f614d4-1070-4354-872e-e4e53cd64c87",
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
              "id": "f21d09bf-47a7-4f2c-957e-978c77db63cb"
            }
          ]
        },
        {
          "id": "4d083bdd-ad26-4b14-a2d6-deaf8669f20c",
          "name": "listXssMatchSets",
          "request": {
            "url": "http://example.com/api/?Action=ListXssMatchSets?Limit=Limit&NextMarker=NextMarker",
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
              "id": "1c99cd9c-9961-4b54-922f-4cb176044ce9"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Token",
      "item": [
        {
          "id": "455ca871-1892-477e-ab7b-4f8bf311c66b",
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
              "id": "3a5b15c7-23dc-40e4-8631-cf3da92f3a62"
            }
          ]
        },
        {
          "id": "efcaa65f-a997-47f4-9d12-a46f43ae7963",
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
              "id": "01b0a59b-6a9d-4d12-a159-4c7f4ed4b17f"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "9b5ac189-79c1-4853-8fff-39601852f263",
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
              "id": "9402d334-d0fd-4586-a057-4e649cc260fb"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Sets",
      "item": [
        {
          "id": "a938dbf4-69d6-4df4-868c-df063a43b7d8",
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
              "id": "74476d03-9c7e-4185-a628-28954955f41d"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Sets",
      "item": [
        {
          "id": "8db2e19c-62ed-4d4d-ba95-b56020440e0d",
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
              "id": "95c515a1-6fb2-429e-a02e-af63b7e60858"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Sets",
      "item": [
        {
          "id": "676ad665-fc0c-4ff3-a1e5-fe10d71e2207",
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
              "id": "99556b7e-6c4b-4227-b52f-6566d1cf4f69"
            }
          ]
        }
      ]
    }
  ]
}