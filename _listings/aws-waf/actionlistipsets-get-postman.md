{
  "info": {
    "name": "AWS WAF API List IP Sets",
    "_postman_id": "c9634d12-d0dc-433e-b196-5810d45edfc2",
    "description": "Service: AWS WAFReturns an array of.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Web ACL",
      "item": [
        {
          "id": "5d95f83c-0de8-4e0a-9928-af56f3556555",
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
              "id": "6e88ee83-0c14-45d4-ba92-f544fca8a85d"
            }
          ]
        },
        {
          "id": "1e6c9c49-6c4f-47a2-9321-eee1418f70cd",
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
              "id": "b5631c51-40d8-46a9-a430-ce060a0166d7"
            }
          ]
        },
        {
          "id": "f3424c11-d926-4502-a5ab-5587166c54db",
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
              "id": "bdca13ef-0265-4d8f-8c4d-d874fdfcde0f"
            }
          ]
        },
        {
          "id": "3ec0f552-43ae-46f6-a4ab-28a8dea78cef",
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
              "id": "e2861b56-d8c6-4346-b0ba-3c5419bbd912"
            }
          ]
        },
        {
          "id": "4da2cd73-7e8a-468c-9e60-597ad066228b",
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
              "id": "10a4aa50-982e-4c7f-90d3-6337f71443bc"
            }
          ]
        },
        {
          "id": "fac43743-6027-4bff-852d-597b4ad39c97",
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
              "id": "83ea7aad-12d0-4ada-b362-97b87c010d1c"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Set",
      "item": [
        {
          "id": "2a7c5cc2-25d5-43d7-b55e-889e2e4e6b4b",
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
              "id": "84b65b23-3b38-432b-902b-48a72bfbcc31"
            }
          ]
        },
        {
          "id": "c790c5cf-7b69-4212-b94f-af6544d64f2f",
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
              "id": "6fff3328-c59a-416b-a9aa-0cfb5109e7b2"
            }
          ]
        },
        {
          "id": "f9a0fe0b-35f1-4329-9a2f-e2bffa626221",
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
              "id": "d1d9fc5b-c52d-48b6-9757-a5667f36242b"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Sets",
      "item": [
        {
          "id": "e63a3a80-1ead-407f-800a-11dcdf31e068",
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
              "id": "a86c69bf-a98f-44a0-83d9-f3e7a67751fe"
            }
          ]
        },
        {
          "id": "4110a151-d08f-4f5c-b7d7-fc1374e216f3",
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
              "id": "ed7d0619-6ad2-4dc4-a583-4e01b31d1603"
            }
          ]
        },
        {
          "id": "2f880c8b-49fb-4b4d-9c78-1775cd30ddc6",
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
              "id": "f3f205e1-a13a-4149-9cf0-113814db9a24"
            }
          ]
        },
        {
          "id": "6f1b4394-e270-4d44-b443-3249c0683e40",
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
              "id": "e7ed648a-d587-49ed-b1df-d415aaf4a99f"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "41598022-fa11-4198-a3f6-c41d35cbdc5e",
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
              "id": "4dadba26-01ad-4129-9854-9e2825db3802"
            }
          ]
        },
        {
          "id": "1f791933-2175-4301-9b59-2fbe538a0141",
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
              "id": "6f0c2310-56bb-4b89-b3be-fccc311a0a02"
            }
          ]
        },
        {
          "id": "74a05e3e-93bd-4a46-a14c-77351e500485",
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
              "id": "0872a233-5f84-49a7-a312-a3017c22b019"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Set",
      "item": [
        {
          "id": "883879c9-53cb-4288-b086-c673c7e7ff2a",
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
              "id": "df634f03-177f-498e-a29b-38e414ddbf8f"
            }
          ]
        },
        {
          "id": "21fdf6ef-ab6f-4712-b82f-c8ac2fc7c6ab",
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
              "id": "5f338889-3f32-488c-905e-683648908230"
            }
          ]
        },
        {
          "id": "b717459c-eba7-4053-ae69-d1c4eae2a870",
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
              "id": "43b4bb82-41fe-436c-8d4b-5a9ca89a140d"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Set",
      "item": [
        {
          "id": "ced2bd24-ffc8-4628-8c5e-357b4fa969ee",
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
              "id": "a2139b83-4c9f-4a27-966e-512b6ed89c07"
            }
          ]
        },
        {
          "id": "dce29838-8f6b-4689-8e2f-fb2c400513de",
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
              "id": "5fa69bbf-6751-4655-88a6-1f9c4732629d"
            }
          ]
        },
        {
          "id": "85e0a035-2e90-4eef-a251-fe9c4c3ce4d5",
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
              "id": "1bc7a816-8266-4b8c-bcb4-c6489b15d387"
            }
          ]
        }
      ]
    },
    {
      "name": "XSS Match Set",
      "item": [
        {
          "id": "393fecf1-4818-4a5f-9885-0f6da8a4b002",
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
              "id": "9518ee38-5ddb-4cc5-9550-40bff2615e6b"
            }
          ]
        },
        {
          "id": "76823e0a-09d0-4586-923a-b4fd6af61208",
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
              "id": "982b3562-9d23-4b58-adfd-1d2c2157b8de"
            }
          ]
        },
        {
          "id": "2ac156dd-6db7-4201-a175-41d60c103e9c",
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
              "id": "8fbeea41-c1e2-4f74-adbd-6954a24c1417"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Token",
      "item": [
        {
          "id": "74d89b5c-d475-4242-ad65-1ceb9fb7ecc0",
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
              "id": "081d0bd3-5441-4e99-ae80-b9be90cb1140"
            }
          ]
        },
        {
          "id": "b116bb06-564f-4508-bcbb-8a47bba43077",
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
              "id": "3d50da92-a4e5-4b0e-815e-66a13a382ab6"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "a546a8a7-fbc8-4ed0-be4f-9347a19bd17a",
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
              "id": "29cf8a9a-17f5-422d-83d7-1658ccfd5128"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Sets",
      "item": [
        {
          "id": "1e49c647-ab21-4917-85c5-d6cfaf2462ee",
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
              "id": "5c02abb4-8cb4-4d90-9a7d-9c23fd31baa5"
            }
          ]
        }
      ]
    }
  ]
}