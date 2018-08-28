{
  "info": {
    "name": "AWS WAF API List Size Constraint Sets",
    "_postman_id": "0c08af52-ba27-46a1-b666-61ef5350c2e7",
    "description": "Service: AWS WAFReturns an array of.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Web ACL",
      "item": [
        {
          "id": "2a21941f-7bed-461c-8be9-62560d13ca27",
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
              "id": "498276e8-62ab-4b32-b276-7cf685972ef7"
            }
          ]
        },
        {
          "id": "f757a716-3d1e-4463-b748-17bf894122f7",
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
              "id": "4f903eb6-5fac-4dc4-928f-6bb7ca45d5d5"
            }
          ]
        },
        {
          "id": "422e7db2-fcf4-4d90-8fd5-a37fa2855117",
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
              "id": "bca20686-1086-4282-b868-3d9f533505d2"
            }
          ]
        },
        {
          "id": "a6a49d1a-4cf2-47d8-ac0b-fdc6976b56dd",
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
              "id": "00fb8818-27e2-42d7-9579-fbaebfb416dd"
            }
          ]
        },
        {
          "id": "b06d3451-6c66-4f59-9121-5120686e0cfe",
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
              "id": "cd0c9636-532f-4536-9fba-f85d83f81a4f"
            }
          ]
        },
        {
          "id": "63436a6a-82fc-4224-9e42-7995e5a2a4e4",
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
              "id": "9be153d4-a5f3-43f4-93fa-31bb3fcb27db"
            }
          ]
        },
        {
          "id": "4c546c84-0e91-43e8-93f4-1fc36175a80e",
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
              "id": "e4af06db-db90-4d42-b440-9df8211a4a49"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Set",
      "item": [
        {
          "id": "b40214ad-aef0-4a7b-86f7-4fe3ab96f31e",
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
              "id": "0062941c-7f21-435b-a9b2-2bc53ff6e012"
            }
          ]
        },
        {
          "id": "c7346c9d-9c41-4f98-8f72-53049bd05d94",
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
              "id": "c1e50521-c6c5-46a2-96f3-354e52c0cada"
            }
          ]
        },
        {
          "id": "46d49590-92c1-4278-8101-3a46be77a129",
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
              "id": "3d80becb-333a-4f94-8942-4d44eaf1ff37"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Sets",
      "item": [
        {
          "id": "d3360a4e-e097-4469-9ce4-bc2fe920d933",
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
              "id": "77e61336-07a9-42f4-8573-4045edec3613"
            }
          ]
        },
        {
          "id": "c162973c-73b9-45dd-87f9-d1c6c745d8e4",
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
              "id": "c4af6580-fcdc-4079-86f2-c01ea5f6b43d"
            }
          ]
        },
        {
          "id": "46ee9fde-53e6-4737-bd45-d9b090f09e28",
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
              "id": "4610a039-39e0-4576-9be8-457b6eeca442"
            }
          ]
        },
        {
          "id": "dd192755-332a-4cdb-a8b7-1a0125ba44f3",
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
              "id": "1beb681d-881d-420b-a71d-f8ea2e7b68c3"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "4e3591d2-ca7c-4803-b3eb-762ca2db22b2",
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
              "id": "77db1db5-21ae-4ec6-96ee-0bde8c13808c"
            }
          ]
        },
        {
          "id": "7115a4b0-8f27-412e-9434-a618c2609edc",
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
              "id": "aaa550e7-73e9-4f16-b6e0-e82a35e4a339"
            }
          ]
        },
        {
          "id": "49a16eed-33f0-4ace-ad6a-6590e198136c",
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
              "id": "9f490050-2abe-4492-b673-fca72b06fb0f"
            }
          ]
        },
        {
          "id": "79216613-07e1-4d91-8a7f-0c4a93978073",
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
              "id": "575b5d76-56cc-4626-834a-40ecd5055d01"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Set",
      "item": [
        {
          "id": "96423db7-ca32-422c-88fd-22827be16ded",
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
              "id": "53aaff64-8b9a-4f3a-91cb-fb5a8754c27a"
            }
          ]
        },
        {
          "id": "a618f165-d5b3-408d-bf08-5bc92a935cd5",
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
              "id": "9a9f98cd-1d9f-48db-9729-3a3b671bff89"
            }
          ]
        },
        {
          "id": "76dd267a-e784-4032-903c-6d67fa9cd002",
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
              "id": "2921bd8f-1631-4492-b633-4cca60ffdf57"
            }
          ]
        }
      ]
    },
    {
      "name": "SQL Injection Match Set",
      "item": [
        {
          "id": "f149eaf6-33c6-47f6-9df5-a02f6236fec6",
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
              "id": "e6fafe71-fb6d-45cf-b0c3-eaad8f8c57ed"
            }
          ]
        },
        {
          "id": "e3528802-f8a7-471e-949d-06faa82ed93c",
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
              "id": "7c86bcab-9ec8-4748-b585-d75955202c40"
            }
          ]
        },
        {
          "id": "3b62465e-f0a3-4c52-9ada-b4094778a17a",
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
              "id": "30224049-ba21-429c-ad26-be71601e90d1"
            }
          ]
        }
      ]
    },
    {
      "name": "XSS Match Set",
      "item": [
        {
          "id": "813527be-b281-4c0b-b320-ed3f61135a99",
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
              "id": "14f0a6af-e7ca-45b0-a7b8-df7d67c39788"
            }
          ]
        },
        {
          "id": "40578034-976f-4f0b-98d3-b57702a9ed68",
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
              "id": "d4d3d454-4ee6-4db9-b843-2751e9abcd45"
            }
          ]
        },
        {
          "id": "8ca7160c-d985-4cfc-ba50-743fc62d85c2",
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
              "id": "d6245f03-4a3c-4591-b535-0d502fb98aaf"
            }
          ]
        }
      ]
    },
    {
      "name": "Change Token",
      "item": [
        {
          "id": "fe724a43-e66b-4071-8f48-00f637747e89",
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
              "id": "6f746108-f4fe-414f-bdc1-551bc67e330f"
            }
          ]
        },
        {
          "id": "2cf74cf7-002d-4126-ab00-ec7ea2336d8c",
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
              "id": "16c2e3e7-9daa-481f-b16d-05a330e1c68b"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "13bb94d5-9abe-44ab-831b-a7e71f12567d",
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
              "id": "14148c55-dd92-485e-b534-eaf7f76a7a34"
            }
          ]
        }
      ]
    },
    {
      "name": "Byte Match Sets",
      "item": [
        {
          "id": "98f7b804-4ea6-4b6a-833c-b3512d4f8493",
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
              "id": "00dd144a-b744-4ad5-9fa1-e3c7b36654d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Size Constraint Sets",
      "item": [
        {
          "id": "9ce103c9-d311-4e74-a437-c47210bfb490",
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
              "id": "033dec98-c7d4-4033-b36e-7e3495ddb82a"
            }
          ]
        }
      ]
    }
  ]
}