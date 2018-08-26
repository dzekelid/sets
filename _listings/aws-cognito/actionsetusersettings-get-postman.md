{
  "info": {
    "name": "AWS Cognito API Set User Settings",
    "_postman_id": "3a1af436-5d9f-4dda-84d6-426c90120e76",
    "description": "Sets the user settings like multi-factor authentication (MFA).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attributes",
      "item": [
        {
          "id": "215dfd03-7e24-4537-bc50-de81b6e0a3a6",
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
              "id": "5ddc35f0-83d7-4345-9bca-c1d07fe8cf06"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "52691fb4-55c5-45be-944b-e455cf46ac35",
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
              "id": "acbc591d-87dc-4e51-afed-791656393eab"
            }
          ]
        },
        {
          "id": "8aa93ed7-1eed-4bb5-926d-53a19b87cc96",
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
              "id": "bb95c9b3-b9b9-49ad-8c41-e2e0ddf971d5"
            }
          ]
        },
        {
          "id": "a4b663cb-50d3-4287-acb7-5a41125e022b",
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
              "id": "ce926c6c-bcad-4d2d-82fa-a5a1830beb2a"
            }
          ]
        },
        {
          "id": "990443c4-d804-4fbf-b998-f676dc6c5bd6",
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
              "id": "fcc1fd8e-75e5-4f5a-96cd-fa348acb7ba4"
            }
          ]
        },
        {
          "id": "953cf554-7893-4ef3-8a99-06fffc06311a",
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
              "id": "21f918b7-1d85-43bc-8fc1-f3b7f524082f"
            }
          ]
        },
        {
          "id": "baad45d6-af41-4367-b484-5eb57bcdb075",
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
              "id": "d0fc5627-00a8-4794-907f-bed0957a73ad"
            }
          ]
        },
        {
          "id": "2ff7d2f9-9d32-437f-8638-228da2c64029",
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
              "id": "d50e9f5b-7aa8-4589-8695-66cbc3753ee4"
            }
          ]
        },
        {
          "id": "35c59602-9ddb-4ee0-9816-37c4faf11fb7",
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
              "id": "b018ebd4-bd19-4daf-a7a2-e04784cf14c3"
            }
          ]
        },
        {
          "id": "6b5f5c33-6465-47a9-9906-39a7be9dea4e",
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
              "id": "035d1591-3815-48fd-bc33-efea7e7758b9"
            }
          ]
        },
        {
          "id": "20b8cfcb-4790-4f0d-b057-4f80482ffd31",
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
              "id": "a8354c21-dded-4ecd-a76e-b52cfa4f24cd"
            }
          ]
        },
        {
          "id": "bf4d11b5-ee96-4159-b686-9ff14c1b4ecb",
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
              "id": "b240ae81-98f3-4a95-ba93-d5c019c7dbe4"
            }
          ]
        },
        {
          "id": "f229e939-683c-49b4-b62b-70c517242322",
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
              "id": "a33f4aaf-91b5-4d7a-be2d-66edbdde30d2"
            }
          ]
        },
        {
          "id": "728cc6d6-715a-489c-819d-658da50f12aa",
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
              "id": "1c6a6618-670a-4d8e-a560-873c0b249ee1"
            }
          ]
        },
        {
          "id": "5528c37b-35f2-49b1-a876-90ee4ee6df4f",
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
              "id": "39e9b6ac-d95c-4c60-a9a6-fe950cc7aa9a"
            }
          ]
        },
        {
          "id": "42235373-afa8-424a-a957-e821b7ac0d5f",
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
              "id": "3a609f61-2976-4895-b380-20e6c5a8f1b3"
            }
          ]
        },
        {
          "id": "93d90e7b-0ef3-47ca-891f-8f25180285dc",
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
              "id": "43653640-9947-42c0-9736-149a891c9a8e"
            }
          ]
        },
        {
          "id": "61326abf-c58c-4e7e-ae29-0a16b04cda16",
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
              "id": "9569951a-4300-4de8-9e4b-2b8d8d692f20"
            }
          ]
        },
        {
          "id": "938877f3-4ebb-417e-879b-e28344950e85",
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
              "id": "f9636b82-1c06-455e-bbcb-34456d759229"
            }
          ]
        },
        {
          "id": "a1678267-c6b1-4cc1-b1a3-69550e8219d9",
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
              "id": "e775ac9e-28d1-4487-83b9-c3379922cde2"
            }
          ]
        },
        {
          "id": "34c8c1ca-2850-4dbe-b0d5-12bf73305127",
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
              "id": "82e0560f-4199-4a1a-af77-71ba65c959e4"
            }
          ]
        },
        {
          "id": "1a9af5a1-7e98-4b57-a392-cb118648ef6d",
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
              "id": "ba478abf-8073-4430-a5a3-b3a498b28961"
            }
          ]
        },
        {
          "id": "7603a3fe-dab3-4235-a28e-31ab6c9b6084",
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
              "id": "5c091d75-5836-4816-942d-2c49d296be39"
            }
          ]
        },
        {
          "id": "e1e6ff8c-37dd-4e90-a267-b390f2da3d64",
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
              "id": "6e1a4fbe-9d35-4a03-af68-813a2edec476"
            }
          ]
        },
        {
          "id": "f87d4198-f487-463f-a542-dc70380f0a3e",
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
              "id": "85d40c5d-046a-4ce3-bee0-77195ba61b92"
            }
          ]
        },
        {
          "id": "d962fa3c-aa48-4e43-92be-5dc7ad87df15",
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
              "id": "e37a326c-2169-4e07-bd61-8ebd05f3cd9d"
            }
          ]
        },
        {
          "id": "5a4f32f6-9f4f-48b3-90ad-ff8c1afc4013",
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
              "id": "f02dd4fd-a2bb-4950-852c-667855da9de9"
            }
          ]
        },
        {
          "id": "7bd19a9a-ed3f-4ca7-807a-10ea512132c6",
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
              "id": "1ca11f08-c6a4-43d0-afcf-e94e58097e49"
            }
          ]
        },
        {
          "id": "74e4f2e4-bb94-4348-b20d-8655915f4d51",
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
              "id": "5ca41216-e45f-4d47-992f-dec2138c1226"
            }
          ]
        },
        {
          "id": "a2eed613-2980-4e31-9f49-a96eda5ecbd9",
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
              "id": "fdf76163-f78d-4ad0-8cd0-77ddd84b6201"
            }
          ]
        },
        {
          "id": "6a32b564-cc59-4c2d-8e02-955331eb6bf0",
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
              "id": "ed3c385a-21db-4fd0-8826-9fa10fc919d5"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Up",
      "item": [
        {
          "id": "591c3230-0493-4872-8df5-edd50f686f2d",
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
              "id": "3af14335-c551-4946-bd39-3ce4facea9d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "30a7a540-297c-494e-8861-59f5a8d19153",
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
              "id": "d5d8f22f-1f21-46f9-bcd6-1d8a11aa0497"
            }
          ]
        },
        {
          "id": "415ac33e-5ef7-4703-8fec-fe6c11754e99",
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
              "id": "a3882381-eb15-450b-9eb5-4fe0753eb406"
            }
          ]
        },
        {
          "id": "7eca5fd5-4161-4c99-babf-8a050c6e6b1b",
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
              "id": "78a1328a-7bd5-43a9-b62b-93e35f483a02"
            }
          ]
        },
        {
          "id": "5a1fc34a-546d-42bf-9264-6a85cbf0c467",
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
              "id": "73d38753-2778-4dde-aefc-6535f73dbd29"
            }
          ]
        }
      ]
    },
    {
      "name": "http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php",
      "item": [
        {
          "id": "eefe0bfe-0a23-4b87-85e3-5dc0e1d15e0e",
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
              "id": "c7be331f-bee4-4301-854f-59d6a5666255"
            }
          ]
        },
        {
          "id": "bb492f70-fd15-41bd-955f-b82d23a115dc",
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
              "id": "119a3652-2ca9-4fb5-a403-7c8eca13142e"
            }
          ]
        }
      ]
    },
    {
      "name": "Authnetication",
      "item": [
        {
          "id": "928447d9-873b-41e9-b6b2-9d1f1bdfc7fd",
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
              "id": "c0d19be4-5d2b-4039-bca5-271964f779dc"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "4fc66a6f-6a12-4634-bcdf-970fd25e528e",
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
              "id": "ae431d64-ae74-4d54-bdaa-6319e2ee7ce7"
            }
          ]
        }
      ]
    },
    {
      "name": "Password",
      "item": [
        {
          "id": "507ffe1c-1120-4d6b-9a22-a9c5fcbd17b0",
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
              "id": "1463324e-02e7-4771-9d85-cf70135f95d8"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "3d701a89-194f-4bed-83de-e6578a690fb2",
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
              "id": "cff21f64-de6b-434b-bf7a-a70b747d23c1"
            }
          ]
        },
        {
          "id": "99fa7f0a-5740-4316-b89c-340c311eb75a",
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
              "id": "b9a3fead-6c28-467a-bb66-a395bb2028bc"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Ups",
      "item": [
        {
          "id": "5b584405-3f87-4d1c-91c7-e163df5626eb",
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
              "id": "869b08f5-6429-40ee-83fa-fe9b6b090e01"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "df6c6c23-fd3d-4497-86b2-99d0f39aa5f1",
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
              "id": "ca2ef532-62c5-4e31-8d9d-4654c147d10c"
            }
          ]
        },
        {
          "id": "768a3123-2ca0-418a-bf15-4385cbcfd0cb",
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
              "id": "29abb5c3-5b19-4bb8-9aa8-8ecd8c49050c"
            }
          ]
        },
        {
          "id": "cda64265-6415-42b6-a411-ae4a54980f80",
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
              "id": "1062332c-bc95-44a9-9343-481705b90e5f"
            }
          ]
        },
        {
          "id": "64947bb5-2ba0-44b7-ba07-5ea0d53c4b3c",
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
              "id": "3b4d221a-581f-4067-b415-34bdf7c8fa7f"
            }
          ]
        }
      ]
    },
    {
      "name": "CSV Header",
      "item": [
        {
          "id": "a7afaa11-9a02-4382-b478-c64ac0736886",
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
              "id": "0fc03d2b-ff44-4c8f-bc97-34ca7ff53406"
            }
          ]
        }
      ]
    },
    {
      "name": "Verification Codes",
      "item": [
        {
          "id": "b80dd3c5-cc2a-4c86-a7bd-2014b7c48fa1",
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
              "id": "7c6176bd-0ba7-4c12-ab6a-57fc032b2109"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Out",
      "item": [
        {
          "id": "bf32cc3b-a050-4a0f-bf97-171ae055a42f",
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
              "id": "32f9e429-3dfb-45f6-8c73-48d2bfccd57b"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication",
      "item": [
        {
          "id": "e71f4309-ce5f-48e6-94ec-04808c5b4cbe",
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
              "id": "718cdb44-1618-4e41-9967-9dd939876b69"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pool Clients",
      "item": [
        {
          "id": "1cd16720-8a05-40e7-9c50-ddb83167b366",
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
              "id": "42ca984c-a4dc-4998-9729-3444d3d385f4"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pools",
      "item": [
        {
          "id": "7e8e9988-4f63-482f-bd7b-7d28d7ebb662",
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
              "id": "56343e47-93a7-4b3a-81be-eca6d39339d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Confirmation Code",
      "item": [
        {
          "id": "248f4231-2a96-479f-90e0-26d7452239fb",
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
              "id": "a8e9d46c-ee8d-4a31-8cdb-e5ade84d6db2"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenges",
      "item": [
        {
          "id": "f3602d2d-9c0a-41d5-b81c-e0505a2537d6",
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
              "id": "fecb4a83-cf95-43ba-b2d5-974356bd11b9"
            }
          ]
        }
      ]
    }
  ]
}