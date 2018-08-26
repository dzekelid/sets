{
  "info": {
    "name": "AWS Cognito API Set Cognito Events",
    "_postman_id": "c1d26d4e-08ff-49b7-a078-64e61f6666ec",
    "description": "Sets the AWS Lambda function for a given event type for an identity pool.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attributes",
      "item": [
        {
          "id": "896b6f20-e5f8-48b4-a27e-1e9527dd2477",
          "name": "addCustomAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AddCustomAttributes?CustomAttributes=CustomAttributes&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds additional user attributes to the user pool schema."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f4e5da8-94b4-49ea-b98c-13ff25c1ef2f"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "6529827e-2e48-4031-b3f7-50408143ac36",
          "name": "adminAddUserToGroup",
          "request": {
            "url": "http://example.com/api/?Action=AdminAddUserToGroup?GroupName=GroupName&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified user to the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5811f8d9-b54e-480a-8203-a19f09ca3d98"
            }
          ]
        },
        {
          "id": "66e36847-5e7a-4a40-be3b-0589000091c7",
          "name": "adminCreateUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminCreateUser?DesiredDeliveryMediums=DesiredDeliveryMediums&ForceAliasCreation=ForceAliasCreation&MessageAction=MessageAction&TemporaryPassword=TemporaryPassword&UserAttributes=UserAttributes&Username=Username&UserPoolId=UserPoolId&ValidationData=ValidationData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new user in the specified user pool and sends a welcome message via email\n            or phone (SMS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a213658-54e2-4c0e-a372-882e9aa24640"
            }
          ]
        },
        {
          "id": "b6388391-a904-4efe-9abe-04d88e949af7",
          "name": "adminDeleteUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminDeleteUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02d0808b-1bfd-4150-962a-04fc23dc3bae"
            }
          ]
        },
        {
          "id": "c8f100d4-a15a-4e7b-929f-ef1e5a23d9bf",
          "name": "adminDeleteUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AdminDeleteUserAttributes?UserAttributeNames=UserAttributeNames&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the user attributes in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8e57978-c6cb-4b89-89be-6bcf55611731"
            }
          ]
        },
        {
          "id": "d90e2086-520c-4741-b9ed-483ec719f076",
          "name": "adminDisableUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminDisableUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables the specified user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6385d943-aafe-4306-999f-4fa33a97e429"
            }
          ]
        },
        {
          "id": "b8bf34fd-244a-4569-ad7b-3d77ba2b3380",
          "name": "adminEnableUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminEnableUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e8b1bb9-5ce9-4714-917a-bf819cf62ffe"
            }
          ]
        },
        {
          "id": "c47ccc2c-f951-4655-a1fb-e12bfedc959c",
          "name": "adminGetUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminGetUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the specified user by user name in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9caebee9-e831-4bea-a16f-d99508a8c918"
            }
          ]
        },
        {
          "id": "0a76717e-5c97-4804-8b08-f6e34be0be25",
          "name": "adminListGroupsForUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminListGroupsForUser?Limit=Limit&NextToken=NextToken&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the groups that the user belongs to."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9447881f-674b-475f-a94d-f22d7e49a0d3"
            }
          ]
        },
        {
          "id": "6ea0bd05-f868-4a4d-9fa2-3e8d391b5a62",
          "name": "adminRemoveUserFromGroup",
          "request": {
            "url": "http://example.com/api/?Action=AdminRemoveUserFromGroup?GroupName=GroupName&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified user from the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17b81a19-26aa-42ed-9c9f-3e57a61cf275"
            }
          ]
        },
        {
          "id": "c916c045-cf1e-4ad7-9723-3d4bc0255824",
          "name": "adminResetUserPassword",
          "request": {
            "url": "http://example.com/api/?Action=AdminResetUserPassword?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the specified user's password in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5bf5ceb1-7c20-41de-a4f9-995c45d61b53"
            }
          ]
        },
        {
          "id": "e4d73210-9d71-41f3-b08f-07b0a7dec820",
          "name": "adminSetUserSettings",
          "request": {
            "url": "http://example.com/api/?Action=AdminSetUserSettings?MFAOptions=MFAOptions&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets all the user settings for a specified user name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efa5d435-12ca-44df-99fa-20e7c3abc602"
            }
          ]
        },
        {
          "id": "17297c61-1810-46d2-8cd0-07975f038ea3",
          "name": "adminUpdateDeviceStatus",
          "request": {
            "url": "http://example.com/api/?Action=AdminUpdateDeviceStatus?DeviceKey=DeviceKey&DeviceRememberedStatus=DeviceRememberedStatus&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the device status as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37d9f7c3-b798-44e5-a2a2-17473528f96c"
            }
          ]
        },
        {
          "id": "216e8ef1-58c4-45c4-b74a-c421c74fbcda",
          "name": "adminUpdateUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AdminUpdateUserAttributes?UserAttributes=UserAttributes&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified user's attributes, including developer attributes, as an\n            administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "180a5f75-dc3f-4249-829d-4ed34e4b3bc1"
            }
          ]
        },
        {
          "id": "c5f03c6d-d64f-4d88-a561-a62c69459f95",
          "name": "adminUserGlobalSignOut",
          "request": {
            "url": "http://example.com/api/?Action=AdminUserGlobalSignOut?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Signs out users from all devices, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6271c79-d384-4ee7-9ba0-a22b7676350b"
            }
          ]
        },
        {
          "id": "41b1e0b4-eceb-4cf1-a294-6a6fdf12d103",
          "name": "createUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserImportJob?CloudWatchLogsRoleArn=CloudWatchLogsRoleArn&JobName=JobName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e06bd77d-b98e-44ce-8020-a6f225a64f30"
            }
          ]
        },
        {
          "id": "128c9dc2-dc02-4169-a549-c13c4346ac46",
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
              "id": "a0cf4b6c-2905-4e43-b3fc-dd7a1cbb807d"
            }
          ]
        },
        {
          "id": "cd17a3e1-0c00-42cd-aba6-71022985997d",
          "name": "createUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserPoolClient?ClientName=ClientName&ExplicitAuthFlows=ExplicitAuthFlows&GenerateSecret=GenerateSecret&ReadAttributes=ReadAttributes&RefreshTokenValidity=RefreshTokenValidity&UserPoolId=UserPoolId&WriteAttributes=WriteAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b011aab2-27a3-48e1-af3a-d300cd2afd67"
            }
          ]
        },
        {
          "id": "8ea56ff6-46bc-4df5-a8bb-9c98bee08f26",
          "name": "deleteUser",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUser?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to delete one's self."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a94923b-6973-4370-84d2-54ef68d8b524"
            }
          ]
        },
        {
          "id": "5809c739-d386-4eba-8b16-1ecb49c5cd67",
          "name": "deleteUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserAttributes?AccessToken=AccessToken&UserAttributeNames=UserAttributeNames",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the attributes for a user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8723444e-7330-49c5-88bf-47be17f5a191"
            }
          ]
        },
        {
          "id": "b0b180d8-1255-4195-ba90-1ae6658f3770",
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
              "id": "47c9198d-9207-46ed-9b77-218821fa3efb"
            }
          ]
        },
        {
          "id": "3d4c66b6-5c12-4316-ae45-26219cb9a607",
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
              "id": "0c651505-7430-42e9-9ccd-7e5a74a335ed"
            }
          ]
        },
        {
          "id": "86aa91b2-36b4-4733-ac64-56e892eafecc",
          "name": "describeUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fb3c9b0-4fc8-454c-bac7-5ac095f9870d"
            }
          ]
        },
        {
          "id": "7d119096-ea5a-485f-8827-a02c2fc11f82",
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
              "id": "fbeb62a0-72e6-42be-b8d2-0ae8989fe147"
            }
          ]
        },
        {
          "id": "1a02b99e-1666-4e80-9457-a9d7c5a223e8",
          "name": "describeUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserPoolClient?ClientId=ClientId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Client method for returning the configuration information and metadata of the\n            specified user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c94d409-ec1c-492c-89db-d008ad87ca09"
            }
          ]
        },
        {
          "id": "c592fad2-8080-4edf-b107-d4aebb19971c",
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
              "id": "a33b7ce6-85ea-4d5d-a1c1-a0741b80b46e"
            }
          ]
        },
        {
          "id": "8a964f04-2aad-4ec8-b1eb-944581d338c3",
          "name": "getUser",
          "request": {
            "url": "http://example.com/api/?Action=GetUser?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the user attributes and metadata for a user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c531a488-ee9f-4f17-8a57-7de99d2021f5"
            }
          ]
        },
        {
          "id": "08ed3f14-cc10-4647-95af-7e09968f4fe2",
          "name": "listUserImportJobs",
          "request": {
            "url": "http://example.com/api/?Action=ListUserImportJobs?MaxResults=MaxResults&PaginationToken=PaginationToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the user import jobs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ba85ca0-961a-4e79-857b-814348b327de"
            }
          ]
        },
        {
          "id": "a0e71a23-2687-44cd-8175-df6404fc948b",
          "name": "listUsers",
          "request": {
            "url": "http://example.com/api/?Action=ListUsers?AttributesToGet=AttributesToGet&Filter=Filter&Limit=Limit&PaginationToken=PaginationToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the users in the Amazon Cognito user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e4fe4ca-1b09-450c-a70d-ad3fe8eba6bb"
            }
          ]
        },
        {
          "id": "36a8cd7e-c748-4998-ae67-62787824f3f7",
          "name": "listUsersInGroup",
          "request": {
            "url": "http://example.com/api/?Action=ListUsersInGroup?GroupName=GroupName&Limit=Limit&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the users in the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06700376-bd69-4056-bdc2-aa2dad6b9dbf"
            }
          ]
        },
        {
          "id": "e4edd6f3-1be4-43fc-9fdb-84379e85116d",
          "name": "setUserSettings",
          "request": {
            "url": "http://example.com/api/?Action=SetUserSettings?AccessToken=AccessToken&MFAOptions=MFAOptions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the user settings like multi-factor authentication (MFA)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2da033df-c207-444c-b303-f1d30c2822ac"
            }
          ]
        },
        {
          "id": "1bfc596a-d653-4185-9361-66a255dfb033",
          "name": "startUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=StartUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts the user import."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d52c05f-85ed-4997-8f01-e42d7521f830"
            }
          ]
        },
        {
          "id": "fb128ad1-9dcb-43cc-b3a5-a0c7eb2e426b",
          "name": "stopUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=StopUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ddba577-82a9-4c07-9f56-280079f3fbfc"
            }
          ]
        },
        {
          "id": "e7925541-45ec-49ca-b67e-67d047712f3d",
          "name": "updateUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserAttributes?AccessToken=AccessToken&UserAttributes=UserAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to update a specific attribute (one at a time)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04d92e24-e958-4936-82cb-9bf265ecfcbf"
            }
          ]
        },
        {
          "id": "5ace114c-fe5a-4404-98d9-870bdb5976db",
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
              "id": "0b6ab2d5-0950-431f-9a5f-9d96445827ab"
            }
          ]
        },
        {
          "id": "adc18756-c22f-4ac3-a1e2-4bc4780d9105",
          "name": "updateUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserPoolClient?ClientId=ClientId&ClientName=ClientName&ExplicitAuthFlows=ExplicitAuthFlows&ReadAttributes=ReadAttributes&RefreshTokenValidity=RefreshTokenValidity&UserPoolId=UserPoolId&WriteAttributes=WriteAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the developer to update the specified user pool client and password\n            policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f66c472a-bf08-40c5-9c37-e1c5a15d89f0"
            }
          ]
        },
        {
          "id": "5c9f83c2-3520-4f84-9dfc-6d23393c1976",
          "name": "verifyUserAttribute",
          "request": {
            "url": "http://example.com/api/?Action=VerifyUserAttribute?AccessToken=AccessToken&AttributeName=AttributeName&Code=Code",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Verifies the specified user attributes in the user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b184cac6-a64d-4603-8089-cea8a4be4204"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Up",
      "item": [
        {
          "id": "6705aea7-be26-42d7-a39c-89fa0019e037",
          "name": "adminConfirmSignUp",
          "request": {
            "url": "http://example.com/api/?Action=AdminConfirmSignUp?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms user registration as an admin without using a confirmation code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0aed696a-d7c7-472e-8653-588fa2e97c12"
            }
          ]
        },
        {
          "id": "254d91d7-ba34-4a42-ac33-a863918f56b0",
          "name": "signUp",
          "request": {
            "url": "http://example.com/api/?Action=SignUp?ClientId=ClientId&Password=Password&SecretHash=SecretHash&UserAttributes=UserAttributes&Username=Username&ValidationData=ValidationData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers the user in the specified user pool and creates a user name, password,\n            and user attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95e35de0-0c47-4749-83b7-3db0f934cd33"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "e60343c5-c15b-49c2-8b3c-776fbfb2eb00",
          "name": "adminForgetDevice",
          "request": {
            "url": "http://example.com/api/?Action=AdminForgetDevice?DeviceKey=DeviceKey&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Forgets the device, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1daa3138-1c13-45ae-9409-e72f278d1c92"
            }
          ]
        },
        {
          "id": "f484c788-3c7c-4367-bc7d-5e855de0c0b6",
          "name": "confirmDevice",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmDevice?AccessToken=AccessToken&DeviceKey=DeviceKey&DeviceName=DeviceName&DeviceSecretVerifierConfig=DeviceSecretVerifierConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms tracking of the device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1001b3f0-c0f6-44ac-b2ae-5963f18b0511"
            }
          ]
        },
        {
          "id": "cfdd71b0-cd53-4892-bbac-55282eafcef2",
          "name": "forgetDevice",
          "request": {
            "url": "http://example.com/api/?Action=ForgetDevice?AccessToken=AccessToken&DeviceKey=DeviceKey",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Forgets the specified device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "747f3319-fb53-4e97-8576-bf46aa1693da"
            }
          ]
        },
        {
          "id": "e735066f-c094-4d3d-9fb1-bb18ad093043",
          "name": "listDevices",
          "request": {
            "url": "http://example.com/api/?Action=ListDevices?AccessToken=AccessToken&Limit=Limit&PaginationToken=PaginationToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the devices."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35a5382a-2c16-4a43-ae83-2ea6ef2403de"
            }
          ]
        },
        {
          "id": "6c57844c-5828-4312-b935-8c5e096ea437",
          "name": "updateDeviceStatus",
          "request": {
            "url": "http://example.com/api/?Action=UpdateDeviceStatus?AccessToken=AccessToken&DeviceKey=DeviceKey&DeviceRememberedStatus=DeviceRememberedStatus",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the device status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6986e8a-dee6-408d-b803-a327e3c447f4"
            }
          ]
        },
        {
          "id": "96a3b00d-93b3-4fe9-b40b-64d978049cc2",
          "name": "registerDevice",
          "request": {
            "url": "http://example.com/api/?Action=RegisterDevice?IdentityId=IdentityId&IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers a device to receive push sync notifications."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa897021-6350-484b-9a51-7559b5767d3d"
            }
          ]
        }
      ]
    },
    {
      "name": "http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php",
      "item": [
        {
          "id": "c0eb18be-84c6-4bfb-99ba-cf6910c3ded1",
          "name": "adminGetDevice",
          "request": {
            "url": "http://example.com/api/?Action=AdminGetDevice?DeviceKey=DeviceKey&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the device, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2d22607-3325-437b-885f-f52d6348d502"
            }
          ]
        },
        {
          "id": "828b8769-c127-4699-b2ef-53032270f548",
          "name": "adminListDevices",
          "request": {
            "url": "http://example.com/api/?Action=AdminListDevices?Limit=Limit&PaginationToken=PaginationToken&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists devices, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2c0da11-5d7b-4d6a-af98-6e2e7d090da4"
            }
          ]
        }
      ]
    },
    {
      "name": "Authnetication",
      "item": [
        {
          "id": "c877f6b9-38b5-4b2d-b8a1-512e6e38d840",
          "name": "adminInitiateAuth",
          "request": {
            "url": "http://example.com/api/?Action=AdminInitiateAuth?AuthFlow=AuthFlow&AuthParameters=AuthParameters&ClientId=ClientId&ClientMetadata=ClientMetadata&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the authentication flow, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2566e416-5979-408c-a378-98cb66991aca"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "13d9a795-3163-456b-bd3e-ad72bf45f3a9",
          "name": "adminRespondToAuthChallenge",
          "request": {
            "url": "http://example.com/api/?Action=AdminRespondToAuthChallenge?ChallengeName=ChallengeName&ChallengeResponses=ChallengeResponses&ClientId=ClientId&Session=Session&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Responds to an authentication challenge, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83b6edbb-46e2-45fc-a98c-1cda4984a238"
            }
          ]
        }
      ]
    },
    {
      "name": "Password",
      "item": [
        {
          "id": "82cc1870-6c21-43c9-952b-cd64058d6c92",
          "name": "changePassword",
          "request": {
            "url": "http://example.com/api/?Action=ChangePassword?AccessToken=AccessToken&PreviousPassword=PreviousPassword&ProposedPassword=ProposedPassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password for a specified user in a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4827b200-8938-4100-b01a-18f0c0d7d617"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "ab8809fe-e20a-4f1a-88ce-e52ba8de8b4f",
          "name": "confirmForgotPassword",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmForgotPassword?ClientId=ClientId&ConfirmationCode=ConfirmationCode&Password=Password&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to enter a code provided when they reset their password to update\n            their password."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c102521-9953-4153-a4ac-d80b136db381"
            }
          ]
        },
        {
          "id": "da08bb38-6eaf-45ff-9d50-f84ae9dbe199",
          "name": "forgotPassword",
          "request": {
            "url": "http://example.com/api/?Action=ForgotPassword?ClientId=ClientId&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the password for the specified client ID or username."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "656645c9-215c-42c9-9ff2-388f5779621b"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Ups",
      "item": [
        {
          "id": "36fa28c9-55e9-43f7-9586-1eddeb34c97e",
          "name": "confirmSignUp",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmSignUp?ClientId=ClientId&ConfirmationCode=ConfirmationCode&ForceAliasCreation=ForceAliasCreation&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms registration of a user and handles the existing alias from a previous\n            user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e92e64a2-1431-4ecf-a1e6-59025adf9772"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "12078145-a8fc-4162-a890-ce4ad6ddfb1a",
          "name": "createGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateGroup?Description=Description&GroupName=GroupName&Precedence=Precedence&RoleArn=RoleArn&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new group in the specified user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "458fc6ab-8121-44b4-ac47-9e6cd2e9ccd9"
            }
          ]
        },
        {
          "id": "992c9268-1adf-4dbb-8e9a-e972c08e5f5d",
          "name": "deleteGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroup?GroupName=GroupName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd1bd397-959b-4956-a8a1-51042d0f6dc7"
            }
          ]
        },
        {
          "id": "0ba2f1a4-f7fa-496b-9f1e-2bec149b6025",
          "name": "getGroup",
          "request": {
            "url": "http://example.com/api/?Action=GetGroup?GroupName=GroupName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f11e043-e8e2-4383-bcf7-b7878df18623"
            }
          ]
        },
        {
          "id": "1f4530fe-d601-4b14-a128-b9eb5c4f9b6c",
          "name": "listGroups",
          "request": {
            "url": "http://example.com/api/?Action=ListGroups?Limit=Limit&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the groups associated with a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0fc5c06-208e-41be-98db-eb24ec271b8c"
            }
          ]
        },
        {
          "id": "b4f10366-fc55-4946-98c7-0fc32c065a08",
          "name": "updateGroup",
          "request": {
            "url": "http://example.com/api/?Action=UpdateGroup?Description=Description&GroupName=GroupName&Precedence=Precedence&RoleArn=RoleArn&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified group with the specified attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c379f9f4-a9da-44cd-ba3c-395af69b8874"
            }
          ]
        }
      ]
    },
    {
      "name": "CSV Header",
      "item": [
        {
          "id": "fcf6d91c-9ff9-43ed-b5f7-769c4e7125ee",
          "name": "getCSVHeader",
          "request": {
            "url": "http://example.com/api/?Action=GetCSVHeader?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the header information for the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95ef7847-bd7b-4ed4-960f-5820ebb95b83"
            }
          ]
        }
      ]
    },
    {
      "name": "Verification Codes",
      "item": [
        {
          "id": "3aee43f7-7c61-40a8-98e2-28609be53621",
          "name": "getUserAttributeVerificationCode",
          "request": {
            "url": "http://example.com/api/?Action=GetUserAttributeVerificationCode?AccessToken=AccessToken&AttributeName=AttributeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the user attribute verification code for the specified attribute\n            name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b9f45a6-076c-4987-b921-d6fd60cf798e"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Out",
      "item": [
        {
          "id": "60c0e61f-6ca5-4bf0-a2b6-d438b4a4e667",
          "name": "globalSignOut",
          "request": {
            "url": "http://example.com/api/?Action=GlobalSignOut?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Signs out users from all devices."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2dd5fc6d-8781-4c16-9622-0918d43e8038"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication",
      "item": [
        {
          "id": "7472c49d-6339-462e-be65-e2626ca870df",
          "name": "initiateAuth",
          "request": {
            "url": "http://example.com/api/?Action=InitiateAuth?AuthFlow=AuthFlow&AuthParameters=AuthParameters&ClientId=ClientId&ClientMetadata=ClientMetadata",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the authentication flow."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e640b5dd-cd87-4f13-b373-1565bbfaa213"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pool Clients",
      "item": [
        {
          "id": "dda5315e-d1b2-442a-bdf3-70dddb2f9cf3",
          "name": "listUserPoolClients",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPoolClients?MaxResults=MaxResults&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the clients that have been created for the specified user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ecc84c7-3d62-487a-b77e-0a35ba8de198"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pools",
      "item": [
        {
          "id": "36b211c6-b65a-455e-8017-3123f719df01",
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
              "id": "e08b1b15-1098-4fec-9ea9-822461b5864e"
            }
          ]
        }
      ]
    },
    {
      "name": "Confirmation Code",
      "item": [
        {
          "id": "55fba67a-7c93-4f6f-b74d-3095a16e077a",
          "name": "resendConfirmationCode",
          "request": {
            "url": "http://example.com/api/?Action=ResendConfirmationCode?ClientId=ClientId&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resends the confirmation (for confirmation of registration) to a specific user in\n            the user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e95ae277-621f-4465-95bf-55e4ac4eab03"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenges",
      "item": [
        {
          "id": "bd6afd27-8483-4db6-b5be-df3c96b56f76",
          "name": "respondToAuthChallenge",
          "request": {
            "url": "http://example.com/api/?Action=RespondToAuthChallenge?ChallengeName=ChallengeName&ChallengeResponses=ChallengeResponses&ClientId=ClientId&Session=Session",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Responds to the authentication challenge."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95746704-27d8-4bed-9099-c0c62ed9369b"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pool",
      "item": [
        {
          "id": "c31b03ae-8b57-43a6-b42b-eaad65de4152",
          "name": "createIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=CreateIdentityPool?AllowUnauthenticatedIdentities=AllowUnauthenticatedIdentities&CognitoIdentityProviders=CognitoIdentityProviders&DeveloperProviderName=DeveloperProviderName&IdentityPoolName=IdentityPoolName&OpenIdConnectProviderARNs=OpenIdConnectProviderARNs&SamlProviderARNs=SamlProviderARNs&SupportedLoginProviders=SupportedLoginProviders",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "903199fb-5b8c-4acc-8307-469b34a147b7"
            }
          ]
        },
        {
          "id": "02438f6a-2d01-4194-9752-37332224bc38",
          "name": "deleteIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentityPool?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb593863-4966-48f6-833c-7d9844799aa2"
            }
          ]
        },
        {
          "id": "d8b23fc8-7dc5-46c1-93a2-99b07e4125ca",
          "name": "describeIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentityPool?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets details about a particular identity pool, including the pool name, ID\n         description, creation date, and current number of users."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8f62f2b-7b60-461f-a938-f4d8f7a64448"
            }
          ]
        },
        {
          "id": "0f595e70-2295-43fa-baab-2dbec1417fd2",
          "name": "listIdentityPools",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentityPools?MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the Cognito identity pools registered for your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d789136f-4fde-49fe-9c40-4a49bc1bb2d8"
            }
          ]
        },
        {
          "id": "525153f6-3dc8-4f21-a578-9726409e5fff",
          "name": "setIdentityPoolRoles",
          "request": {
            "url": "http://example.com/api/?Action=SetIdentityPoolRoles?IdentityPoolId=IdentityPoolId&RoleMappings=RoleMappings&Roles=Roles",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the roles for an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae295f7a-65c7-485d-bb0b-a5061981a77c"
            }
          ]
        },
        {
          "id": "f00866f2-c3e5-4a12-88fc-7bdfe5b8c3ce",
          "name": "updateIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=UpdateIdentityPool?AllowUnauthenticatedIdentities=AllowUnauthenticatedIdentities&CognitoIdentityProviders=CognitoIdentityProviders&DeveloperProviderName=DeveloperProviderName&IdentityPoolId=IdentityPoolId&IdentityPoolName=IdentityPoolName&OpenIdConnectProviderARNs=OpenIdConnectProviderARNs&SamlProviderARNs=SamlProviderARNs&SupportedLoginProviders=SupportedLoginProviders",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a809372-03e1-4e74-8a08-a6262faf4fd9"
            }
          ]
        }
      ]
    },
    {
      "name": "Identities",
      "item": [
        {
          "id": "0165bc56-2648-4c37-82d1-bceb58e0d02c",
          "name": "deleteIdentities",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentities?IdentityIdsToDelete=IdentityIdsToDelete",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes identities from an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49241d61-e756-4da6-b934-3da62a0c7a46"
            }
          ]
        },
        {
          "id": "f8c941c4-2ec0-4009-8ab7-c86b5ed2c57c",
          "name": "describeIdentity",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentity?IdentityId=IdentityId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns metadata related to the given identity, including when the identity was\n         created and any associated linked logins."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9c44fd3-a944-4533-8f09-c5895375b7e0"
            }
          ]
        },
        {
          "id": "c469202e-edef-4f85-8e93-d1bc5883c5e2",
          "name": "getCredentialsForIdentity",
          "request": {
            "url": "http://example.com/api/?Action=GetCredentialsForIdentity?CustomRoleArn=CustomRoleArn&IdentityId=IdentityId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns credentials for the provided identity ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cff73cba-1647-4d59-b5a1-06269dfba57f"
            }
          ]
        },
        {
          "id": "d164db17-b4f3-4776-9aa3-c502363c7567",
          "name": "getId",
          "request": {
            "url": "http://example.com/api/?Action=GetId?AccountId=AccountId&IdentityPoolId=IdentityPoolId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates (or retrieves) a Cognito ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91899dc2-02c4-49e5-8c24-cd042b84464b"
            }
          ]
        },
        {
          "id": "fc61e949-1756-49a6-9d34-a4e2797a5e1c",
          "name": "listIdentities",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentities?HideDisabled=HideDisabled&IdentityPoolId=IdentityPoolId&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the identities in a pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "069a2673-b2c4-47fd-94da-9cfe6a714db9"
            }
          ]
        },
        {
          "id": "16ed8bae-ed5f-4114-971e-04f5999b6b63",
          "name": "unlinkIdentity",
          "request": {
            "url": "http://example.com/api/?Action=UnlinkIdentity?IdentityId=IdentityId&Logins=Logins&LoginsToRemove=LoginsToRemove",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlinks a federated identity from an existing account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9935f3b-dc61-4c99-997a-a036f0b2cad5"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pool Roles",
      "item": [
        {
          "id": "637e5e2a-82a0-4439-9677-307e385228d0",
          "name": "getIdentityPoolRoles",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityPoolRoles?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the roles for an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cc13c72-e8c5-4528-bb48-282c969d7eba"
            }
          ]
        }
      ]
    },
    {
      "name": "Open ID Token",
      "item": [
        {
          "id": "5ca3827f-50ca-45ba-a423-ed6031e00c50",
          "name": "getOpenIdToken",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIdToken?IdentityId=IdentityId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets an OpenID token, using a known Cognito ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21356b23-879c-4a0b-b469-091e7ea02930"
            }
          ]
        }
      ]
    },
    {
      "name": "Open ID Token for Developer Identities",
      "item": [
        {
          "id": "d8d47797-69ef-421e-b229-302160b00606",
          "name": "getOpenIdTokenForDeveloperIdentity",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIdTokenForDeveloperIdentity?IdentityId=IdentityId&IdentityPoolId=IdentityPoolId&Logins=Logins&TokenDuration=TokenDuration",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers (or retrieves) a Cognito IdentityId and an OpenID Connect\n         token for a user authenticated by your backend authentication process."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c011e5b-9cc8-4812-860a-38e55ee80043"
            }
          ]
        }
      ]
    },
    {
      "name": "Developer Identities",
      "item": [
        {
          "id": "81d3bd56-76b6-48b7-a46a-db6346b85f58",
          "name": "lookupDeveloperIdentity",
          "request": {
            "url": "http://example.com/api/?Action=LookupDeveloperIdentity?DeveloperUserIdentifier=DeveloperUserIdentifier&IdentityId=IdentityId&IdentityPoolId=IdentityPoolId&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the IdentityID associated with a\n            DeveloperUserIdentifier or the list of\n         DeveloperUserIdentifiers associated with an IdentityId for an\n         existing identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c2a598d-2ac3-45be-a69b-fc2224408361"
            }
          ]
        },
        {
          "id": "829966d9-858f-4c60-97aa-19995e102cfa",
          "name": "mergeDeveloperIdentities",
          "request": {
            "url": "http://example.com/api/?Action=MergeDeveloperIdentities?DestinationUserIdentifier=DestinationUserIdentifier&DeveloperProviderName=DeveloperProviderName&IdentityPoolId=IdentityPoolId&SourceUserIdentifier=SourceUserIdentifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Merges two users having different IdentityIds, existing in the same\n         identity pool, and identified by the same developer provider."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f50c008-d9fe-456e-a326-32d34353f9f5"
            }
          ]
        },
        {
          "id": "d9b96f75-1990-4599-9f14-8246801f81aa",
          "name": "unlinkDeveloperIdentity",
          "request": {
            "url": "http://example.com/api/?Action=UnlinkDeveloperIdentity?DeveloperProviderName=DeveloperProviderName&DeveloperUserIdentifier=DeveloperUserIdentifier&IdentityId=IdentityId&IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlinks a DeveloperUserIdentifier from an existing identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65c2d96f-e76d-4543-a983-2ba3002f9506"
            }
          ]
        }
      ]
    },
    {
      "name": "Publish",
      "item": [
        {
          "id": "4aa622f4-140e-42ee-a695-7600a13ad3ed",
          "name": "bulkPublish",
          "request": {
            "url": "http://example.com/api/?Action=BulkPublish?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates a bulk publish of all existing datasets for an Identity Pool to the configured stream."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f9f6dd6-d39a-41e4-8bc8-ba3b7b89cb3e"
            }
          ]
        },
        {
          "id": "5c8b29d3-6e67-4b6d-90d2-afba722a289c",
          "name": "getBulkPublishDetails",
          "request": {
            "url": "http://example.com/api/?Action=GetBulkPublishDetails?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the status of the last BulkPublish operation for an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87e107ea-3bea-4838-b995-3fd509f8b3ac"
            }
          ]
        }
      ]
    },
    {
      "name": "Dataset",
      "item": [
        {
          "id": "f2984cfb-3d9a-4ab2-a488-b8192787e1aa",
          "name": "deleteDataset",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDataset?DatasetName=DatasetName&IdentityId=IdentityId&IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "D