{
  "info": {
    "name": "AWS Simple Email Service API List Configuration Sets",
    "_postman_id": "a8fa826d-f046-4800-87e4-3bb680dbc701",
    "description": "Lists the configuration sets associated with your AWS account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Receipt Rule Sets",
      "item": [
        {
          "id": "b2dd1e7d-4696-435b-b028-0d2d3edf5dbe",
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
              "id": "be279573-7cf9-4154-ada3-31af32ef61e2"
            }
          ]
        },
        {
          "id": "b3efcc43-b968-4f82-88d8-a2c5a2cdc3da",
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
              "id": "148b4327-2620-4a04-9a52-c468ec50375f"
            }
          ]
        },
        {
          "id": "b6c0ae19-1f8e-429e-8cca-6a49747ce912",
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
              "id": "3ddba418-80ad-4cf5-bdbe-b1b0341bb79a"
            }
          ]
        },
        {
          "id": "cd1d2c35-32f5-4eeb-8ec7-26815f543432",
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
              "id": "4f75570d-57da-4b5e-a6f6-38ea8091d0c9"
            }
          ]
        },
        {
          "id": "50898c85-19f9-4158-8362-01ff7e765c5b",
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
              "id": "fb236524-366f-4bcd-9981-edb307e46c22"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Sets",
      "item": [
        {
          "id": "a7170f29-eb19-4114-b958-3c3c39fb902a",
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
              "id": "bcaaea79-9bd2-45d1-8b96-34afa384ef9a"
            }
          ]
        },
        {
          "id": "455f60c6-1407-45ed-80e6-bcd4c76bff21",
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
              "id": "838ff61c-b146-4c1f-9cd2-3e7226082e7d"
            }
          ]
        },
        {
          "id": "75d4bd35-f7bc-4dff-8985-557bffb0cc29",
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
              "id": "79767743-bc97-4655-81b6-ebfb853a1af1"
            }
          ]
        },
        {
          "id": "3aecf1c7-4dec-458a-9727-ae69f004c304",
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
              "id": "69810b28-3aca-476f-9323-27c3fcf33202"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Set Event Destination",
      "item": [
        {
          "id": "ff24a4bc-b381-40fc-8c19-acc83c1bf7ff",
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
              "id": "2dffc977-fbe5-4a59-a76e-75c91a81fc80"
            }
          ]
        },
        {
          "id": "b7a72b00-b322-47e2-8013-2c28d7dc283d",
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
              "id": "82958cf5-d3ed-4ada-9c05-470cea1b950e"
            }
          ]
        }
      ]
    },
    {
      "name": "Receipt Filters",
      "item": [
        {
          "id": "9bfe8615-c2f8-42d0-bc5d-cc97785ea8cb",
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
              "id": "9a321fdb-1c4c-4ca3-ab3e-14bdb1aac5c1"
            }
          ]
        },
        {
          "id": "c60b1440-2e1b-4106-9952-bef7cb110f52",
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
              "id": "4a4bf3b0-3161-4f30-a34a-7b38f56a3cba"
            }
          ]
        }
      ]
    },
    {
      "name": "Receipt Rules",
      "item": [
        {
          "id": "ce8d9f00-e9a3-4a6f-b337-ffe571ec6b78",
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
              "id": "6de9ab9d-e7f2-49e1-a4d4-b588ea72c645"
            }
          ]
        },
        {
          "id": "ba67fc89-0f31-49aa-a3af-f3710b10dd51",
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
              "id": "b8dcbb02-7389-497f-971f-293e38ee92ae"
            }
          ]
        },
        {
          "id": "94e86f70-0859-419f-a264-a216045ab31c",
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
              "id": "cead9e4d-fd73-49a7-91a5-dc65c87be1d6"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "a4a12b99-9c43-4069-b511-33c301620cef",
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
              "id": "6087f2e8-457a-4c43-be13-5e2e3ac3a8a8"
            }
          ]
        },
        {
          "id": "e7832b54-5101-4cbb-9bf1-e81a5fd40694",
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
              "id": "a262ffcf-9c47-41f7-a0fb-8ff61573c40e"
            }
          ]
        },
        {
          "id": "a62e4c19-5b1b-4ec1-b712-f1c7afe00077",
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
              "id": "9279bee4-c58c-46fe-a735-b22bd1ab9b69"
            }
          ]
        },
        {
          "id": "ab60c81e-ee78-4f3e-aeaa-b9e20ab9cbed",
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
              "id": "86027c43-e91c-4932-9add-6e4c7b24e390"
            }
          ]
        },
        {
          "id": "2a7b8e3e-0316-42a1-b8b5-9424cc4c225f",
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
              "id": "96575ecc-9c41-430c-88af-b185c71cea07"
            }
          ]
        },
        {
          "id": "ea64d298-b3ed-4e41-a130-34d27c0dffc3",
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
              "id": "f4075852-2c7a-4909-99f6-94ac34f7f855"
            }
          ]
        },
        {
          "id": "1c1f9f4f-046b-4855-96e7-a36d9b0c1632",
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
              "id": "1bfa414e-90e6-4e44-8377-a61a0fd6ca85"
            }
          ]
        }
      ]
    },
    {
      "name": "Verified Email Addresses",
      "item": [
        {
          "id": "a3045123-d679-4c2a-8eaa-4d5dac674c23",
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
              "id": "7b4a3838-adf3-4361-b1a5-d36e033eaef3"
            }
          ]
        }
      ]
    },
    {
      "name": "Send Quota",
      "item": [
        {
          "id": "5f7ecb13-9c0d-4ba5-96ae-437cbdd481b5",
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
              "id": "be550326-c699-4780-b4c1-4b60397eed4c"
            }
          ]
        }
      ]
    },
    {
      "name": "Send Statistics",
      "item": [
        {
          "id": "d2faea6f-af31-4328-ac58-e48db184b928",
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
              "id": "a78550fe-8949-4f17-b433-b805c53c0d68"
            }
          ]
        }
      ]
    }
  ]
}