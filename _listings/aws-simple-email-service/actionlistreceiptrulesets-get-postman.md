{
  "info": {
    "name": "AWS Simple Email Service API List Receipt Rule Sets",
    "_postman_id": "f8a33078-8b47-48c7-a750-e7a2d46149d6",
    "description": "Lists the receipt rule sets that exist under your AWS account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Receipt Rule Sets",
      "item": [
        {
          "id": "1533329e-8d23-44bc-9b9b-8dd39b90faa2",
          "name": "cloneReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=CloneReceiptRuleSet?OriginalRuleSetName=OriginalRuleSetName&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a receipt rule set by cloning an existing one."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "673cde9f-eaa1-4aea-aa15-469cbe5a240f"
            }
          ]
        },
        {
          "id": "35562559-70ff-4e28-9fcf-b504058d2b18",
          "name": "createReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateReceiptRuleSet?RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an empty receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6bc653db-1034-4663-b948-ae3855fe71e7"
            }
          ]
        },
        {
          "id": "baf0fe9d-672d-4d98-ab5d-9f4ef4aee0f2",
          "name": "deleteReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteReceiptRuleSet?RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified receipt rule set and all of the receipt rules it contains."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65087b98-3843-440c-9385-1d9c0c217d51"
            }
          ]
        },
        {
          "id": "a38cbe63-d2f3-4b49-90bd-caaa4ce45daa",
          "name": "describeActiveReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=DescribeActiveReceiptRuleSet?Metadata=Metadata&Rules.member.N=Rules.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the metadata and receipt rules for the receipt rule set that is currently active."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e561f0d-ac58-4ae5-a51e-9ca8c93043b6"
            }
          ]
        },
        {
          "id": "5fbeb566-e476-4168-92e2-7a42d6d08d1c",
          "name": "describeReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReceiptRuleSet?RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the details of the specified receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d368fa55-10b0-413f-b1e5-f4f5723dc454"
            }
          ]
        },
        {
          "id": "1ba97a22-27d9-4938-9f98-38803a6b4d5c",
          "name": "listReceiptRuleSets",
          "request": {
            "url": "http://example.com/api/?Action=ListReceiptRuleSets?NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the receipt rule sets that exist under your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a8e6b44-448e-4e35-b085-a1ec713a43cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Sets",
      "item": [
        {
          "id": "17bb2d22-37d1-4380-8ea6-ae877447350e",
          "name": "createConfigurationSet",
          "request": {
            "url": "http://example.com/api/?Action=CreateConfigurationSet?ConfigurationSet=ConfigurationSet",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a configuration set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8cf4d40-5039-4adb-8ef3-11b33acc15de"
            }
          ]
        },
        {
          "id": "56b1ce6b-ae15-4d2a-8d24-eff31570d713",
          "name": "deleteConfigurationSet",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConfigurationSet?ConfigurationSetName=ConfigurationSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a configuration set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62c52714-341d-48ac-9e3e-c11199570a99"
            }
          ]
        },
        {
          "id": "15cfae27-4249-4f0c-b819-d4074e50d819",
          "name": "describeConfigurationSet",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConfigurationSet?ConfigurationSetAttributeNames.member.N=ConfigurationSetAttributeNames.member.N&ConfigurationSetName=ConfigurationSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the details of the specified configuration set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94dec691-acc9-4ffe-8bb4-5c7749a896f7"
            }
          ]
        },
        {
          "id": "bae6d337-8fdc-425f-b495-55c94420e8c7",
          "name": "listConfigurationSets",
          "request": {
            "url": "http://example.com/api/?Action=ListConfigurationSets?MaxItems=MaxItems&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the configuration sets associated with your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51836c13-fa3b-418b-b9dc-699da41b21ac"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Set Event Destination",
      "item": [
        {
          "id": "260216a0-904e-4971-b57a-502fe822aadf",
          "name": "createConfigurationSetEventDestination",
          "request": {
            "url": "http://example.com/api/?Action=CreateConfigurationSetEventDestination?ConfigurationSetName=ConfigurationSetName&EventDestination=EventDestination",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a configuration set event destination."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71974788-cdd6-4fd3-8e00-0f7a7b3838ff"
            }
          ]
        },
        {
          "id": "811b5485-ed9c-4da0-9345-ad8f9fdf1dca",
          "name": "deleteConfigurationSetEventDestination",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConfigurationSetEventDestination?ConfigurationSetName=ConfigurationSetName&EventDestinationName=EventDestinationName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a configuration set event destination."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0699ffe1-bc25-4536-995d-681bd5ac3f75"
            }
          ]
        }
      ]
    },
    {
      "name": "Receipt Filters",
      "item": [
        {
          "id": "8750aee2-0586-40d1-bfa8-0cea60c94f30",
          "name": "createReceiptFilter",
          "request": {
            "url": "http://example.com/api/?Action=CreateReceiptFilter?Filter=Filter",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new IP address filter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b3bd89c-62d2-4214-8f59-8ab2aac93c28"
            }
          ]
        },
        {
          "id": "3d86f6a5-3b53-49f2-8784-ee39e2560cca",
          "name": "deleteReceiptFilter",
          "request": {
            "url": "http://example.com/api/?Action=DeleteReceiptFilter?FilterName=FilterName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IP address filter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f677f6cd-bf1f-488c-a436-367badaac3f8"
            }
          ]
        },
        {
          "id": "c2ef55da-f1c7-469f-a8cf-f5ba2c8c31f1",
          "name": "listReceiptFilters",
          "request": {
            "url": "http://example.com/api/?Action=ListReceiptFilters?Filters.member.N=Filters.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IP address filters associated with your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "034750fa-1332-4b2a-bc7c-a45c09b467e8"
            }
          ]
        }
      ]
    },
    {
      "name": "Receipt Rules",
      "item": [
        {
          "id": "3d435a8a-487e-42a8-afc1-ba6f5bb990a6",
          "name": "createReceiptRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateReceiptRule?After=After&Rule=Rule&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a receipt rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "614f98b8-d79b-4741-b845-182708c3dd48"
            }
          ]
        },
        {
          "id": "79668f25-8938-479f-9e10-4775f4ccf116",
          "name": "deleteReceiptRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteReceiptRule?RuleName=RuleName&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified receipt rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fd13a14-8f71-4a27-b494-b6be1b66a95c"
            }
          ]
        },
        {
          "id": "e94c2eb7-9683-467c-82ff-8ca02a04b018",
          "name": "describeReceiptRule",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReceiptRule?RuleName=RuleName&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the details of the specified receipt rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a905f5c-b4b9-4eec-8809-7edde5dc6531"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "407adf7d-36a5-4252-821e-4b9ddb2e6a7c",
          "name": "deleteIdentity",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentity?Identity=Identity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified identity (an email address or a domain) from the list of verified identities."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51d2d555-e17d-4110-a261-01ed8b13047b"
            }
          ]
        },
        {
          "id": "c33c19ed-10d8-44e8-93df-ea6740eda209",
          "name": "deleteIdentityPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentityPolicy?Identity=Identity&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified sending authorization policy for the given identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c18e541-32bb-4cde-a016-b4682fc956b6"
            }
          ]
        },
        {
          "id": "c0c9790c-2d72-4509-a29d-869a76e4b324",
          "name": "getIdentityDkimAttributes",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityDkimAttributes?Identities.member.N=Identities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the current status of Easy DKIM signing for an entity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c91eed27-446d-414f-97de-6c6c865a2702"
            }
          ]
        },
        {
          "id": "6fa84e31-a97c-4905-86aa-cdd9016cca2c",
          "name": "getIdentityMailFromDomainAttributes",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityMailFromDomainAttributes?Identities.member.N=Identities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the custom MAIL FROM attributes for a list of identities (email addresses and/or domains)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd0b539a-0292-4e2c-8d46-077c7154b36d"
            }
          ]
        },
        {
          "id": "5f73ee32-508d-4c49-a5c3-af58ddec93ba",
          "name": "getIdentityNotificationAttributes",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityNotificationAttributes?Identities.member.N=Identities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a list of verified identities (email addresses and/or domains), returns a structure describing identity notification attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a242924-9087-48ec-be3c-7f6d12e5e9e3"
            }
          ]
        },
        {
          "id": "09295c82-3b4b-4d21-b35b-b552cb37a9e1",
          "name": "getIdentityPolicies",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityPolicies?Identity=Identity&PolicyNames.member.N=PolicyNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the requested sending authorization policies for the given identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "794d4b99-48f7-481e-af28-800dfcdbc4a3"
            }
          ]
        },
        {
          "id": "3fd4db92-9405-46e3-bb1b-4be40ef160be",
          "name": "getIdentityVerificationAttributes",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityVerificationAttributes?Identities.member.N=Identities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Given a list of identities (email addresses and/or domains), returns the verification status and (for domain identities) the verification token for each identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9d38a3f-9115-4704-963c-3974787c711e"
            }
          ]
        },
        {
          "id": "425fbb18-db2f-4db8-8fb4-d1512c26f462",
          "name": "listIdentities",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentities?IdentityType=IdentityType&MaxItems=MaxItems&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list containing all of the identities (email addresses and domains) for your AWS account, regardless of verification status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9706c25-f3bf-4888-b6a6-871c322e6bcc"
            }
          ]
        },
        {
          "id": "99f41b76-fe3f-4447-8abd-2bc1ac7bc0eb",
          "name": "listIdentityPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentityPolicies?Identity=Identity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of sending authorization policies that are attached to the given identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae24d4d7-ebf3-4d2a-ad09-62a52148f74d"
            }
          ]
        }
      ]
    },
    {
      "name": "Verified Email Addresses",
      "item": [
        {
          "id": "51227f8f-4161-4ca3-b263-5cd46d57795a",
          "name": "deleteVerifiedEmailAddress",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVerifiedEmailAddress?EmailAddress=EmailAddress",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified email address from the list of verified addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc2e2e86-6188-4acb-9e9f-ee9bf8d57259"
            }
          ]
        }
      ]
    },
    {
      "name": "Send Quota",
      "item": [
        {
          "id": "8d071779-d7c9-43ea-9751-eca19793bee6",
          "name": "getSendQuota",
          "request": {
            "url": "http://example.com/api/?Action=GetSendQuota?Max24HourSend=Max24HourSend&MaxSendRate=MaxSendRate&SentLast24Hours=SentLast24Hours",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the user's current sending limits."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef7a50ee-85c6-4df2-aa97-10db2c2e0668"
            }
          ]
        }
      ]
    },
    {
      "name": "Send Statistics",
      "item": [
        {
          "id": "897e6da1-b308-458a-8695-7d57fc2b7e2f",
          "name": "getSendStatistics",
          "request": {
            "url": "http://example.com/api/?Action=GetSendStatistics?SendDataPoints.member.N=SendDataPoints.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the user's sending statistics."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8778c825-1131-473d-87f4-54d8853c2531"
            }
          ]
        }
      ]
    }
  ]
}