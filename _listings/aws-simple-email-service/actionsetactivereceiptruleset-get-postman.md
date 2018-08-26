{
  "info": {
    "name": "AWS Simple Email Service API Set Active Receipt Rule Set",
    "_postman_id": "38610ec9-ad9a-456b-9ea0-090cc0dc052a",
    "description": "Sets the specified receipt rule set as the active receipt rule set.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Receipt Rule Sets",
      "item": [
        {
          "id": "099ed4ee-cd5a-4af2-bee0-044191eac3f5",
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
              "id": "8888c930-e8f1-4cc1-b3a0-dd66465427ec"
            }
          ]
        },
        {
          "id": "be864244-f2df-43e2-81d3-66d1863398b8",
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
              "id": "bdbdc0b9-66d6-4e6b-8712-0be67e5e8ad3"
            }
          ]
        },
        {
          "id": "c9a9e569-be9a-4599-879d-56d930b387bb",
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
              "id": "5761e37a-c915-4cbf-b8e0-530d48d186ff"
            }
          ]
        },
        {
          "id": "0ccd33f7-c508-4a0d-a8de-be0911be429c",
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
              "id": "36d1d137-7e1e-498f-84a3-46b0184a5b2f"
            }
          ]
        },
        {
          "id": "54baf46e-895a-496e-8607-7566a9b3ed24",
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
              "id": "0dec4e9e-a7f2-4069-9528-03f69b8d5af9"
            }
          ]
        },
        {
          "id": "349f022f-6451-422a-a327-a14e40aab471",
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
              "id": "79aa0bea-1cc0-4733-acef-9d60555ec1c1"
            }
          ]
        },
        {
          "id": "5a836bd5-0be1-4dbc-9d7e-832e6fb97afd",
          "name": "reorderReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=ReorderReceiptRuleSet?RuleNames.member.N=RuleNames.member.N&RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Reorders the receipt rules within a receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16fcc4a3-c3df-4f76-a520-044810852907"
            }
          ]
        },
        {
          "id": "e756b262-69de-4771-9b5a-266ae47709bf",
          "name": "setActiveReceiptRuleSet",
          "request": {
            "url": "http://example.com/api/?Action=SetActiveReceiptRuleSet?RuleSetName=RuleSetName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the specified receipt rule set as the active receipt rule set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb854730-fb59-4635-afce-9f9638d21ec0"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Sets",
      "item": [
        {
          "id": "ed774cd1-8fd0-45bb-8965-a2d12552849a",
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
              "id": "02eebf0e-fe34-4adb-8351-5154106ab5d8"
            }
          ]
        },
        {
          "id": "e48b2c84-3fce-4340-b1a8-1ce573531eaa",
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
              "id": "a09ddb1b-3440-483a-a402-e81bade8e77f"
            }
          ]
        },
        {
          "id": "6fe7c00f-5c0b-4516-8ecf-fc0ab12fb546",
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
              "id": "9907d43c-23fe-4f43-885b-cd23a8e29760"
            }
          ]
        },
        {
          "id": "bb55478c-d42a-4769-b43c-afc64b45442c",
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
              "id": "4f2c1b91-c143-4b2b-b3ab-f479f24d9792"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Set Event Destination",
      "item": [
        {
          "id": "48adf7dd-4a5a-426a-93fd-d354bca7999b",
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
              "id": "2c161bc0-cc49-43d0-b663-1057df7e2171"
            }
          ]
        },
        {
          "id": "a42421bf-1314-462b-b1b1-d2aeefba0050",
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
              "id": "87843221-eb12-4f76-891b-a5bbf9356f30"
            }
          ]
        }
      ]
    },
    {
      "name": "Receipt Filters",
      "item": [
        {
          "id": "bd799abe-6aa1-44c8-a2e8-ba367c1454ff",
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
              "id": "26a67fd6-89da-4988-a2be-56966a723844"
            }
          ]
        },
        {
          "id": "c55fd911-6d6a-4194-a25d-979a640fe458",
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
              "id": "f615f98e-e573-4cd0-9d73-600facc4ce48"
            }
          ]
        },
        {
          "id": "f66b5868-0b6f-4610-97d3-ebda519359d8",
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
              "id": "f389b581-3a9b-4d3d-9aed-0424a25fa3b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Receipt Rules",
      "item": [
        {
          "id": "1049c542-2763-4882-bfb6-bee38350f7e6",
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
              "id": "13aee0b0-a6cf-4c97-8d0d-621757e00b42"
            }
          ]
        },
        {
          "id": "8d6de7b9-71fc-44fa-8639-5e352a35310c",
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
              "id": "4de9456a-c06f-4b95-8107-6ce3113445dd"
            }
          ]
        },
        {
          "id": "0f232fd8-0968-4f3e-a471-53de2dff43f0",
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
              "id": "fea9269b-4cde-4290-8a47-022307638898"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "fafd420d-c883-408b-a8ad-4d45692cff0d",
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
              "id": "156cbd6e-4e0a-4cb4-9e2d-045c03e42a0b"
            }
          ]
        },
        {
          "id": "6e3bbfbf-5f24-4f7f-bdd5-b4bcdeea8045",
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
              "id": "6c78069c-4679-472e-8b16-b8e52dfb34dc"
            }
          ]
        },
        {
          "id": "0e8ab4f2-7248-40f8-b404-c7670f941869",
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
              "id": "a13d457b-46cb-4a1b-9c7a-37123258b904"
            }
          ]
        },
        {
          "id": "65a2b11b-5516-46ea-8e44-5c05a02ad7ac",
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
              "id": "cdafe72c-8094-4b7e-b4df-e72878ac123c"
            }
          ]
        },
        {
          "id": "6b53870f-732f-450a-9bc5-57e3159a7e85",
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
              "id": "dda23cc7-266a-4d3f-95d1-692bf0d29449"
            }
          ]
        },
        {
          "id": "fd3339ed-e3d1-41ff-88ce-a7f3bf954c0b",
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
              "id": "437ddc19-1fa5-4e07-9985-29b3779bffca"
            }
          ]
        },
        {
          "id": "ff28bc29-95ab-442a-bafb-c59f8b6de209",
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
              "id": "e02e808a-ba26-48c7-93e7-dfbb8b07a852"
            }
          ]
        },
        {
          "id": "f90d38d9-8c2f-4223-ba35-c9a4881bfcf0",
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
              "id": "424b0f3d-cd7a-4ced-bfc2-2a6a695ef41e"
            }
          ]
        },
        {
          "id": "978f8fc1-b19d-4fe7-97f8-e013c51d145b",
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
              "id": "6fe3b6cf-97d9-464d-ab05-72ae18e203b5"
            }
          ]
        },
        {
          "id": "e49766ba-9c21-4cca-a0d0-7f6c60766508",
          "name": "putIdentityPolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutIdentityPolicy?Identity=Identity&Policy=Policy&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates a sending authorization policy for the specified identity (an email address or a domain)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f8b7741-ba6d-41e9-b74c-33dd5483f6f6"
            }
          ]
        }
      ]
    },
    {
      "name": "Verified Email Addresses",
      "item": [
        {
          "id": "8f528ac9-211d-4ac4-a743-ea0b6d1c3659",
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
              "id": "2722591f-f3aa-4552-a9a2-b894cf6a923a"
            }
          ]
        },
        {
          "id": "a77effa6-b7ae-4d18-a98d-519545d1f4ac",
          "name": "listVerifiedEmailAddresses",
          "request": {
            "url": "http://example.com/api/?Action=ListVerifiedEmailAddresses?VerifiedEmailAddresses.member.N=VerifiedEmailAddresses.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list containing all of the email addresses that have been verified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70793425-cb04-494c-9b89-5eb1bbd72cc6"
            }
          ]
        }
      ]
    },
    {
      "name": "Send Quota",
      "item": [
        {
          "id": "39ab661e-cd03-4f8a-9e60-42448b812b71",
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
              "id": "0f46594e-ea3a-44f5-8eab-42e0a92874bc"
            }
          ]
        }
      ]
    },
    {
      "name": "Send Statistics",
      "item": [
        {
          "id": "0405e26f-d2d2-47ec-a429-2dbbc708680a",
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
              "id": "afc99bef-39ce-4fb7-8d5e-9476b0f6cbba"
            }
          ]
        }
      ]
    },
    {
      "name": "Bounce",
      "item": [
        {
          "id": "d45c66cc-416b-4e6c-8056-ed18af1241a7",
          "name": "sendBounce",
          "request": {
            "url": "http://example.com/api/?Action=SendBounce?BouncedRecipientInfoList.member.N=BouncedRecipientInfoList.member.N&BounceSender=BounceSender&BounceSenderArn=BounceSenderArn&Explanation=Explanation&MessageDsn=MessageDsn&OriginalMessageId=OriginalMessageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates and sends a bounce message to the sender of an email you received through Amazon SES."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d2f0f9cd-af30-4057-b7a5-69183b75e0c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Email",
      "item": [
        {
          "id": "6e83d55d-8d71-4de2-b40c-3a491bf91697",
          "name": "sendEmail",
          "request": {
            "url": "http://example.com/api/?Action=SendEmail?ConfigurationSetName=ConfigurationSetName&Destination=Destination&Message=Message&ReplyToAddresses.member.N=ReplyToAddresses.member.N&ReturnPath=ReturnPath&ReturnPathArn=ReturnPathArn&Source=Source&SourceArn=SourceArn&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Composes an email message based on input data, and then immediately queues the message for sending."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7976c28f-509e-4c63-902d-1b21899fc4f5"
            }
          ]
        },
        {
          "id": "37cbc3b1-83d1-4e5d-a35b-0ce00fdd830f",
          "name": "sendRawEmail",
          "request": {
            "url": "http://example.com/api/?Action=SendRawEmail?ConfigurationSetName=ConfigurationSetName&Destinations.member.N=Destinations.member.N&FromArn=FromArn&RawMessage=RawMessage&ReturnPathArn=ReturnPathArn&Source=Source&SourceArn=SourceArn&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sends an email message, with header and content specified by the client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b984e2d-7fa1-418c-b085-d8f1015617ec"
            }
          ]
        }
      ]
    }
  ]
}