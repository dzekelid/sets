{
  "info": {
    "name": "AWS Cognito API Set Identity Pool Configuration",
    "_postman_id": "1ce12ba4-f6ee-46b6-93bf-7d3b017eebea",
    "description": "Sets the necessary configuration for push sync.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "94207da1-2114-4fe9-8592-3a63961a9c9f",
          "name": "createUserPool",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserPool?AdminCreateUserConfig=AdminCreateUserConfig&AliasAttributes=AliasAttributes&AutoVerifiedAttributes=AutoVerifiedAttributes&DeviceConfiguration=DeviceConfiguration&EmailConfiguration=EmailConfiguration&EmailVerificationMessage=EmailVerificationMessage&EmailVerificationSubject=EmailVerificationSubject&LambdaConfig=LambdaConfig&MfaConfiguration=MfaConfiguration&Policies=Policies&PoolName=PoolName&Schema=Schema&SmsAuthenticationMessage=SmsAuthenticationMessage&SmsConfiguration=SmsConfiguration&SmsVerificationMessage=SmsVerificationMessage&UserPoolTags=UserPoolTags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new Amazon Cognito user pool and sets the password policy for the\n            pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e85c613-23c2-4ae0-8f52-9dab0ee168c1"
            }
          ]
        },
        {
          "id": "24be1f0c-8709-4dab-8fb0-5fb2204f0959",
          "name": "deleteUserPool",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPool?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Amazon Cognito user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4df6520c-9efe-4930-825b-0ba2daa08258"
            }
          ]
        },
        {
          "id": "5b24fb29-0c46-41d4-aedf-49fe2d682a9c",
          "name": "deleteUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPoolClient?ClientId=ClientId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the developer to delete the user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30997b60-abba-47a3-8f1a-80b8bb5e6049"
            }
          ]
        },
        {
          "id": "ae59ef24-e601-40ab-931d-b40dc1b4b3fe",
          "name": "describeUserPool",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserPool?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the configuration information and metadata of the specified user\n            pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "979a900d-2bdb-4a8e-88d8-09cfccd7a5f1"
            }
          ]
        },
        {
          "id": "8c6324fb-b924-40e5-a282-d72a22e3fdb9",
          "name": "getDevice",
          "request": {
            "url": "http://example.com/api/?Action=GetDevice?AccessToken=AccessToken&DeviceKey=DeviceKey",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f37cdab6-6888-479a-bd2e-fb1c5fb29710"
            }
          ]
        },
        {
          "id": "fe65eefc-40c4-4557-a623-a8ba8b3b86f1",
          "name": "updateUserPool",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserPool?AdminCreateUserConfig=AdminCreateUserConfig&AutoVerifiedAttributes=AutoVerifiedAttributes&DeviceConfiguration=DeviceConfiguration&EmailConfiguration=EmailConfiguration&EmailVerificationMessage=EmailVerificationMessage&EmailVerificationSubject=EmailVerificationSubject&LambdaConfig=LambdaConfig&MfaConfiguration=MfaConfiguration&Policies=Policies&SmsAuthenticationMessage=SmsAuthenticationMessage&SmsConfiguration=SmsConfiguration&SmsVerificationMessage=SmsVerificationMessage&UserPoolId=UserPoolId&UserPoolTags=UserPoolTags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified user pool with the specified attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6e1c31eb-af0c-4e52-84b6-9f805e1855d5"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pools",
      "item": [
        {
          "id": "6f37c6ff-e414-4bb6-a1be-2cabf0fb3a33",
          "name": "listUserPools",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPools?MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the user pools associated with an AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "759d4de8-0a80-4b10-b3ae-96d36f84d9a0"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pools",
      "item": [
        {
          "id": "57649a94-6940-4c86-8543-350a96a41238",
          "name": "getIdentityPoolConfiguration",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityPoolConfiguration?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the configuration settings of an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39af0e3b-c038-4706-acc9-275b8cc8ab4c"
            }
          ]
        },
        {
          "id": "af091d95-0df2-438a-bc89-79475c66b52d",
          "name": "listIdentityPoolUsage",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentityPoolUsage?MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of identity pools registered with Cognito."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3819318-d82f-4958-a040-fc705c528ead"
            }
          ]
        },
        {
          "id": "9cc86433-1d30-4e64-bdd8-5afadea22626",
          "name": "setIdentityPoolConfiguration",
          "request": {
            "url": "http://example.com/api/?Action=SetIdentityPoolConfiguration?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the necessary configuration for push sync."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b3efe34-a0a1-421b-a522-4d6052bf6eeb"
            }
          ]
        }
      ]
    }
  ]
}