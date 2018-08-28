{
  "info": {
    "name": "AWS Identity and Access Management API Update Service Specific Credential",
    "_postman_id": "8914bc31-70d8-4683-91b7-5f4a4f9285a9",
    "description": "Sets the status of a service-specific credential to Active or\n        Inactive.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "OpenID Connect Providers",
      "item": [
        {
          "id": "77009b8e-3cc0-433f-8f0d-59dd2d1cb9ad",
          "name": "addClientIDToOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=AddClientIDToOpenIDConnectProvider?ClientID=ClientID&OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new client ID (also known as audience) to the list of client IDs already\n      registered for the specified IAM OpenID Connect (OIDC) provider resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab9b7e70-44eb-4a6a-b37f-3fec33e38b9d"
            }
          ]
        },
        {
          "id": "ea039f86-4699-493e-a774-0c0c005940a5",
          "name": "createOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=CreateOpenIDConnectProvider?ClientIDList.member.N=ClientIDList.member.N&ThumbprintList.member.N=ThumbprintList.member.N&Url=Url",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an IAM entity to describe an identity provider (IdP) that supports."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0b1d67e-4a66-4cd8-997c-8a081f44fd58"
            }
          ]
        },
        {
          "id": "461a4d6a-c3f6-4737-b5fe-123c0ebf4736",
          "name": "deleteOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=DeleteOpenIDConnectProvider?OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an OpenID Connect identity provider (IdP) resource object in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4b0c6fb-9788-4ec4-8c77-2fd39736f7bf"
            }
          ]
        },
        {
          "id": "a1985529-bfea-4003-8a1e-a922b6ffe965",
          "name": "getOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIDConnectProvider?OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the specified OpenID Connect (OIDC) provider resource object\n      in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af9b2b3e-445e-4243-a19b-07940d98b499"
            }
          ]
        },
        {
          "id": "e2eb09da-4ec5-4d35-ade6-141d7703d0ce",
          "name": "listOpenIDConnectProviders",
          "request": {
            "url": "http://example.com/api/?Action=ListOpenIDConnectProviders?OpenIDConnectProviderList.member.N=OpenIDConnectProviderList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists information about the IAM OpenID Connect (OIDC) provider resource objects\n      defined in the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d92a1a5-aaa9-46d1-84a8-6872ea44ba4a"
            }
          ]
        },
        {
          "id": "84359cad-ea77-4542-a7af-10234ea19b07",
          "name": "removeClientIDFromOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=RemoveClientIDFromOpenIDConnectProvider?ClientID=ClientID&OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified client ID (also known as audience) from the list of client IDs\n      registered for the specified IAM OpenID Connect (OIDC) provider resource object."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9880471c-ea04-4704-bb7a-4fd2f63f4ce5"
            }
          ]
        },
        {
          "id": "c281d5aa-ee60-4098-821e-3d6c97f2a463",
          "name": "updateOpenIDConnectProviderThumbprint",
          "request": {
            "url": "http://example.com/api/?Action=UpdateOpenIDConnectProviderThumbprint?OpenIDConnectProviderArn=OpenIDConnectProviderArn&ThumbprintList.member.N=ThumbprintList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Replaces the existing list of server certificate thumbprints associated with an OpenID\n      Connect (OIDC) provider resource object with a new list of thumbprints."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3f7fe6c-663d-4695-90a4-70dad901b3ab"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Instance",
      "item": [
        {
          "id": "279277a0-feec-40dd-81ac-3379b6e454b1",
          "name": "addRoleToInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=AddRoleToInstanceProfile?InstanceProfileName=InstanceProfileName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified IAM role to the specified instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f379942-eb90-4638-81cc-4e47e1d4ce7a"
            }
          ]
        }
      ]
    },
    {
      "name": "User Groups",
      "item": [
        {
          "id": "32227a60-6867-47b1-b8ad-cfde94bf2c57",
          "name": "addUserToGroup",
          "request": {
            "url": "http://example.com/api/?Action=AddUserToGroup?GroupName=GroupName&UserName=UserName",
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
              "id": "6146f065-a276-4a90-90bc-c3c6b5a42e63"
            }
          ]
        }
      ]
    },
    {
      "name": "Group Policies",
      "item": [
        {
          "id": "db8f8799-6d05-4eb7-aedc-33b46705cec5",
          "name": "attachGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachGroupPolicy?GroupName=GroupName&PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe462f10-60df-43ef-b9ba-470551df6de2"
            }
          ]
        },
        {
          "id": "91f0cb9f-1f95-4602-add6-e553691dd7ad",
          "name": "deleteGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroupPolicy?GroupName=GroupName&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb1d153d-d4b6-4a08-9abb-23e4d94d6fea"
            }
          ]
        },
        {
          "id": "66d446f7-6e9b-4da7-81cb-6970e89802f9",
          "name": "detachGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachGroupPolicy?GroupName=GroupName&PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d40e512-2991-4bf9-b8f8-67f9d975987b"
            }
          ]
        },
        {
          "id": "177afb45-7bb1-4c86-a104-fffbadb935a4",
          "name": "getGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetGroupPolicy?GroupName=GroupName&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9075795d-6c19-4124-bd0e-713ceb6a64b3"
            }
          ]
        },
        {
          "id": "c5d95092-816b-4d6b-a8d9-28573a7ccdbf",
          "name": "listGroupPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListGroupPolicies?GroupName=GroupName&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies that are embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60a54d35-612b-458f-91ea-960860cca32b"
            }
          ]
        },
        {
          "id": "a2c3d20d-5737-4878-8226-288ef9ac1bfa",
          "name": "putGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutGroupPolicy?GroupName=GroupName&PolicyDocument=PolicyDocument&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates an inline policy document that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c66964a-033f-44ef-94be-6e6fa2655bef"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Policies",
      "item": [
        {
          "id": "e868cfb6-959d-4342-ae26-fdf1a52612d3",
          "name": "attachRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachRolePolicy?PolicyArn=PolicyArn&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified IAM role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1794f962-20a1-43b2-b2f4-ca4fe04fe6a2"
            }
          ]
        },
        {
          "id": "37b0526b-f0ce-467b-8c01-21ee9c148f94",
          "name": "deleteRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRolePolicy?PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "047dc50f-6536-4cb3-af5e-05bf77c274a6"
            }
          ]
        },
        {
          "id": "3c46ffd2-3cba-48c7-97d9-587ae1f0b600",
          "name": "detachRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachRolePolicy?PolicyArn=PolicyArn&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "313bd4f9-91b2-437b-84af-047690a2f962"
            }
          ]
        },
        {
          "id": "76800df3-c727-4469-8fa7-8eb0393d7fca",
          "name": "getRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetRolePolicy?PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded with the specified\n      IAM role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "546d9077-d3f4-48ff-9b4c-6666dbbbd1b5"
            }
          ]
        },
        {
          "id": "733c553e-f324-43ce-9eb6-b84d84040d80",
          "name": "listRolePolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListRolePolicies?Marker=Marker&MaxItems=MaxItems&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies that are embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6581072b-1e1a-4756-9645-2a360a127966"
            }
          ]
        },
        {
          "id": "e50fac3d-9d5e-4625-888f-b588c36ac174",
          "name": "putRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutRolePolicy?PolicyDocument=PolicyDocument&PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or updates an inline policy document that is embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e61e836-71e2-4a94-8b41-91cc6b79da68"
            }
          ]
        }
      ]
    },
    {
      "name": "User Policies",
      "item": [
        {
          "id": "4a528ecd-033c-404a-b62c-a56a4dc94d52",
          "name": "attachUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachUserPolicy?PolicyArn=PolicyArn&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79451930-1f11-43ca-afe5-7b388113b378"
            }
          ]
        },
        {
          "id": "a83fe2ab-dcbc-4bcd-8ca8-8c170602ecb8",
          "name": "deleteUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPolicy?PolicyName=PolicyName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a864becb-0ce5-4a19-88f7-e997b96b72a5"
            }
          ]
        },
        {
          "id": "aa4ca282-96e7-49a7-a6a7-9630128948be",
          "name": "detachUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachUserPolicy?PolicyArn=PolicyArn&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2af0130-c983-4678-9f56-1b8baff88db3"
            }
          ]
        },
        {
          "id": "707ab409-1f32-4086-b2fd-67d434eb7783",
          "name": "getUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetUserPolicy?PolicyName=PolicyName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified inline policy document that is embedded in the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e2e5ea0-d8d8-4132-af10-effadb919ac2"
            }
          ]
        },
        {
          "id": "2e3f25fd-1980-48df-beac-31b46d458d59",
          "name": "listUserPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPolicies?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the names of the inline policies embedded in the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66adb1af-9100-4686-88a0-8d2f01fd999d"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "9d3e2f66-624f-47e2-a79b-5f818492c1fe",
          "name": "changePassword",
          "request": {
            "url": "http://example.com/api/?Action=ChangePassword?NewPassword=NewPassword&OldPassword=OldPassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password of the IAM user who is calling this action."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab6092f3-cead-4034-8bf3-02425f482ba1"
            }
          ]
        }
      ]
    },
    {
      "name": "Access Keys",
      "item": [
        {
          "id": "da7172c9-dffe-4f79-8819-fed23875cc69",
          "name": "createAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=CreateAccessKey?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new AWS secret access key and corresponding AWS access key ID for the\n      specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af6761d2-54be-4dca-8bc8-e5a48d105600"
            }
          ]
        },
        {
          "id": "41ff5de8-f335-4c5f-b08c-ec94ae76072a",
          "name": "deleteAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccessKey?AccessKeyId=AccessKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the access key pair associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e58bc34-eee0-4a8e-b399-9add099e4303"
            }
          ]
        },
        {
          "id": "e569844f-402d-447a-9c48-4c876582c03e",
          "name": "getAccessKeyLastUsed",
          "request": {
            "url": "http://example.com/api/?Action=GetAccessKeyLastUsed?AccessKeyId=AccessKeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about when the specified access key was last used."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f240dc0-5053-4811-90fb-66603061c54a"
            }
          ]
        },
        {
          "id": "c24c720d-b20b-463c-a098-e40e602c82e8",
          "name": "listAccessKeys",
          "request": {
            "url": "http://example.com/api/?Action=ListAccessKeys?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the access key IDs associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e061a7a9-d73f-4fc1-8924-88ee1dca12c2"
            }
          ]
        },
        {
          "id": "0e9aa90a-6cb9-4bd9-bda6-06458a5310e8",
          "name": "updateAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=UpdateAccessKey?AccessKeyId=AccessKeyId&Status=Status&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the status of the specified access key from Active to Inactive, or vice versa."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba21345b-661e-4a18-b16d-9a0f4bbc6865"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Alias",
      "item": [
        {
          "id": "a70273ba-36d1-403f-8c83-df9873cdcec9",
          "name": "createAccountAlias",
          "request": {
            "url": "http://example.com/api/?Action=CreateAccountAlias?AccountAlias=AccountAlias",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an alias for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9bbefe86-c4ac-4084-a0f6-a41d547d84e5"
            }
          ]
        },
        {
          "id": "ae8f2117-7c95-4e1d-b1d9-f1aed295e5b5",
          "name": "deleteAccountAlias",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccountAlias?AccountAlias=AccountAlias",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified AWS account alias."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d05834c-3052-404c-b376-953df95585bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "f3d6a16d-97b9-4961-85ef-8129f2ff643e",
          "name": "createGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateGroup?GroupName=GroupName&Path=Path",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65cdf2c5-5eb1-4719-b09c-6a0108637409"
            }
          ]
        },
        {
          "id": "84d34dac-803d-4228-b8e6-fe198a1936ee",
          "name": "deleteGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroup?GroupName=GroupName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "843c83f5-240d-4a5a-ad06-bccec127b834"
            }
          ]
        },
        {
          "id": "f7edf68d-f449-48fe-978f-ff24a647f9db",
          "name": "getGroup",
          "request": {
            "url": "http://example.com/api/?Action=GetGroup?GroupName=GroupName&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of IAM users that are in the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ba45b40-666e-4cdf-bc1a-f5ac9346a6f8"
            }
          ]
        },
        {
          "id": "ec3368c7-fb2a-4d47-8300-4b231d28a38d",
          "name": "listGroups",
          "request": {
            "url": "http://example.com/api/?Action=ListGroups?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM groups that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab3a8976-1320-4e56-b980-7c75d8a2ab40"
            }
          ]
        },
        {
          "id": "dc291ea1-5ed6-4395-b224-d8419635eda6",
          "name": "updateGroup",
          "request": {
            "url": "http://example.com/api/?Action=UpdateGroup?GroupName=GroupName&NewGroupName=NewGroupName&NewPath=NewPath",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the name and/or the path of the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a948ce58-95c8-43bb-a702-7c7a4ce83b6e"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance Profiles",
      "item": [
        {
          "id": "dda7227b-125c-4b5a-ac22-750937bde8c1",
          "name": "createInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstanceProfile?InstanceProfileName=InstanceProfileName&Path=Path",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39c52121-381a-4a32-a0db-c327cdc0ad38"
            }
          ]
        },
        {
          "id": "90b43558-fb22-46fc-8372-347727063019",
          "name": "deleteInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInstanceProfile?InstanceProfileName=InstanceProfileName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2981c7d2-d858-4a21-99c5-e646ea8b0c02"
            }
          ]
        },
        {
          "id": "b4a5031f-419d-4175-8d83-5bfc5cf21d82",
          "name": "getInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=GetInstanceProfile?InstanceProfileName=InstanceProfileName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified instance profile, including the instance\n      profile's path, GUID, ARN, and role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6cf0b7f-087b-4fa6-8fea-ae17183e8c30"
            }
          ]
        },
        {
          "id": "37347c3a-5753-46bf-adc2-f8d024f7b6a6",
          "name": "listInstanceProfiles",
          "request": {
            "url": "http://example.com/api/?Action=ListInstanceProfiles?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the instance profiles that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6b98588-5162-422d-b5ee-1c77ed7bc6b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Login Profiles",
      "item": [
        {
          "id": "98a7d60b-5477-4ad3-9a97-c965cb27d21b",
          "name": "createLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateLoginProfile?Password=Password&PasswordResetRequired=PasswordResetRequired&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a password for the specified user, giving the user the ability to access AWS\n      services through the AWS Management Console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca3d9684-89ff-47e8-8ca2-46163723e975"
            }
          ]
        },
        {
          "id": "14d20572-5af6-48bf-9b34-73c577df260c",
          "name": "deleteLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLoginProfile?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the password for the specified IAM user, which terminates the user's ability\n      to access AWS services through the AWS Management Console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "775ceef1-cdc6-4e70-941e-5637209a4843"
            }
          ]
        },
        {
          "id": "48831ea9-853c-4b84-a05e-634c019a2c04",
          "name": "getLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=GetLoginProfile?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the user name and password-creation date for the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c3c39d6-e171-486f-80b7-8163dd2b932d"
            }
          ]
        },
        {
          "id": "56ad5938-c322-460d-913a-fe6245aade8c",
          "name": "updateLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=UpdateLoginProfile?Password=Password&PasswordResetRequired=PasswordResetRequired&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password for the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f58a3ccd-c8a4-438b-acf5-25e4fee3ad2e"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "c774e282-94a1-4506-bffd-d41cfc2855aa",
          "name": "createPolicy",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicy?Description=Description&Path=Path&PolicyDocument=PolicyDocument&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new managed policy for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03b5643c-0f6d-4f40-b498-d1054e10002a"
            }
          ]
        },
        {
          "id": "a2538b10-e956-406a-821d-a3a43e296676",
          "name": "createPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicyVersion?PolicyArn=PolicyArn&PolicyDocument=PolicyDocument&SetAsDefault=SetAsDefault",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new version of the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af235c12-b271-4fb9-b1de-23e34bcf68b5"
            }
          ]
        },
        {
          "id": "f11f69bb-a8b4-428d-b341-2f43707f5084",
          "name": "deletePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicy?PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02e11c52-a95a-4538-8944-c4bbe6283a46"
            }
          ]
        },
        {
          "id": "49199249-44dc-46d1-94fe-3a754fe42c5c",
          "name": "deletePolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicyVersion?PolicyArn=PolicyArn&VersionId=VersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified version from the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "748a7892-481f-4380-b962-f010d6422cf4"
            }
          ]
        },
        {
          "id": "d2d8d281-22e8-4bcb-9280-a41dfdefebfa",
          "name": "getPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicy?PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified managed policy, including the policy's\n      default version and the total number of IAM users, groups, and roles to which the policy is\n      attached."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49240474-1a5a-4245-8535-1c72775260d8"
            }
          ]
        },
        {
          "id": "fc797e65-3605-48f3-8f95-7a4e54f7e351",
          "name": "getPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=GetPolicyVersion?PolicyArn=PolicyArn&VersionId=VersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified version of the specified managed policy,\n      including the policy document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "373cad51-d2c2-4a3a-9d00-a16a8ff8a589"
            }
          ]
        }
      ]
    },
    {
      "name": "Roles",
      "item": [
        {
          "id": "3537986b-c7dc-4e92-bcd8-305c2fe5ca19",
          "name": "createRole",
          "request": {
            "url": "http://example.com/api/?Action=CreateRole?AssumeRolePolicyDocument=AssumeRolePolicyDocument&Path=Path&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new role for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27947685-e789-4daa-90cf-786d585f81dd"
            }
          ]
        },
        {
          "id": "09ac1c70-c164-45d6-af51-c7cbdd1f72cf",
          "name": "deleteRole",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRole?RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5f2e927-7ce3-407e-842e-a93aada60832"
            }
          ]
        },
        {
          "id": "e2a212b9-ce02-417f-9b82-480ac6ed9fb7",
          "name": "getRole",
          "request": {
            "url": "http://example.com/api/?Action=GetRole?RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified role, including the role's path, GUID, ARN,\n      and the role's trust policy that grants permission to assume the role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34a308e2-ac7a-4455-abf0-f4ce7ce5e770"
            }
          ]
        },
        {
          "id": "cde8f540-328d-489a-9a89-838a99ed3f29",
          "name": "listRoles",
          "request": {
            "url": "http://example.com/api/?Action=ListRoles?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM roles that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa2f8a6c-9d7d-4440-81a1-120d0c863789"
            }
          ]
        }
      ]
    },
    {
      "name": "SAML Providers",
      "item": [
        {
          "id": "ac4f52f1-f4de-4d02-954d-aa0b6ceda3ff",
          "name": "createSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=CreateSAMLProvider?Name=Name&SAMLMetadataDocument=SAMLMetadataDocument",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an IAM resource that describes an identity provider (IdP) that supports SAML\n      2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d274e26-3f64-41a0-b95f-940c32176350"
            }
          ]
        },
        {
          "id": "11be3b9b-81cd-44f3-8551-fcd1a817dabb",
          "name": "deleteSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSAMLProvider?SAMLProviderArn=SAMLProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a SAML provider resource in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba55d537-535e-4573-81a5-3b34c4c2476b"
            }
          ]
        },
        {
          "id": "6a04d0cd-f35a-4bf6-9f43-67f5ba95f1ec",
          "name": "getSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=GetSAMLProvider?SAMLProviderArn=SAMLProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the SAML provider metadocument that was uploaded when the IAM SAML provider\n      resource object was created or updated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3ab89bf-8d03-4b83-8bdf-142b2b09f655"
            }
          ]
        },
        {
          "id": "0f4beddb-fe0e-4d8c-b81c-8d87229d4b30",
          "name": "listSAMLProviders",
          "request": {
            "url": "http://example.com/api/?Action=ListSAMLProviders?SAMLProviderList.member.N=SAMLProviderList.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the SAML provider resource objects defined in IAM in the account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a9074b3-c374-4ff6-a2e7-09a6de947730"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Specific Credentials",
      "item": [
        {
          "id": "c4586407-1a2d-4a22-9acd-e7a5860983f5",
          "name": "createServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=CreateServiceSpecificCredential?ServiceName=ServiceName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a set of credentials consisting of a user name and password that can be used\n      to access the service specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b58486f5-d4bd-46f5-9cb5-0e054b95c806"
            }
          ]
        },
        {
          "id": "b9d087d2-d1c9-4cd6-bf29-3e947d2ecaed",
          "name": "deleteServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=DeleteServiceSpecificCredential?ServiceSpecificCredentialId=ServiceSpecificCredentialId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified service-specific credential."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df7fc8c9-b1a4-41c7-a270-864126eae98e"
            }
          ]
        },
        {
          "id": "be6883e6-dbaa-4074-8aa4-98f690064ba5",
          "name": "listServiceSpecificCredentials",
          "request": {
            "url": "http://example.com/api/?Action=ListServiceSpecificCredentials?ServiceName=ServiceName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the service-specific credentials associated with the\n      specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63bdc9de-76dd-4839-bf0c-caf0219ad395"
            }
          ]
        },
        {
          "id": "b3211838-6b43-44cc-871c-b1ab9a9a03d8",
          "name": "resetServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=ResetServiceSpecificCredential?ServiceSpecificCredentialId=ServiceSpecificCredentialId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the password for a service-specific credential."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b09d38b-f547-4e69-812d-62eb00e111fd"
            }
          ]
        },
        {
          "id": "781cfa01-c808-4702-bd28-341f6a839bf9",
          "name": "updateServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=UpdateServiceSpecificCredential?ServiceSpecificCredentialId=ServiceSpecificCredentialId&Status=Status&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the status of a service-specific credential to Active or\n        Inactive."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb226afa-be88-4f55-8bc1-da27d5ac1420"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "84c5eac6-789b-46ef-8ad0-43323d62c563",
          "name": "createUser",
          "request": {
            "url": "http://example.com/api/?Action=CreateUser?Path=Path&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new IAM user for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9ace49b-fad7-4e0b-8a53-039cf2d945bc"
            }
          ]
        },
        {
          "id": "3abbd12e-5881-42c1-a56b-026d45f8b5d1",
          "name": "deleteUser",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUser?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0ae17f4-5051-4c16-9a47-a94ec526e88a"
            }
          ]
        },
        {
          "id": "5f758f02-c7c4-40f0-92f2-e974aca9c4a4",
          "name": "getUser",
          "request": {
            "url": "http://example.com/api/?Action=GetUser?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified IAM user, including the user's creation\n      date, path, unique ID, and ARN."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6a0c7d0-f8b4-47e3-a7c9-8bce2b43872a"
            }
          ]
        },
        {
          "id": "d291c563-1d41-4317-97f6-6e9c6d1e5688",
          "name": "listUsers",
          "request": {
            "url": "http://example.com/api/?Action=ListUsers?Marker=Marker&MaxItems=MaxItems&PathPrefix=PathPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the IAM users that have the specified path prefix."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "131685d4-f120-42f6-a17a-c08ccae852f4"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Device",
      "item": [
        {
          "id": "5355b91a-0331-45ec-89e4-2547f7006274",
          "name": "createVirtualMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=CreateVirtualMFADevice?Path=Path&VirtualMFADeviceName=VirtualMFADeviceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new virtual MFA device for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f3bbfa6-dbf0-4ff0-9022-feda05be9090"
            }
          ]
        },
        {
          "id": "c126e6f2-74eb-46fe-9ae8-d7f64e767004",
          "name": "deactivateMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=DeactivateMFADevice?SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivates the specified MFA device and removes it from association with the user name\n      for which it was originally enabled."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c62c60a-0494-4952-bec2-7b720faf3cc4"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Password Policies",
      "item": [
        {
          "id": "7a28c11f-0d57-47e2-8f43-fda2398d7221",
          "name": "deleteAccountPasswordPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccountPasswordPolicy?LimitExceeded=LimitExceeded&NoSuchEntity=NoSuchEntity&ServiceFailure=ServiceFailure",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the password policy for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b287fad6-aada-4d89-aaf8-deaf0d22f892"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Certificates",
      "item": [
        {
          "id": "9d2bc6db-2268-4817-afe5-70d7571476ff",
          "name": "deleteServerCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteServerCertificate?ServerCertificateName=ServerCertificateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified server certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "49f8ba45-7b41-4602-8bc3-2312f1296ae6"
            }
          ]
        },
        {
          "id": "2d64187e-409c-4868-b600-de1e8f27f117",
          "name": "getServerCertificate",
          "request": {
            "url": "http://example.com/api/?Action=GetServerCertificate?ServerCertificateName=ServerCertificateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about the specified server certificate stored in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62786047-b27f-4b8c-a09d-29f73cc7d5ac"
            }
          ]
        },
        {
          "id": "9bc8d044-32ea-4459-8047-99dc980cd91d",
          "name": "updateServerCertificate",
          "request": {
            "url": "http://example.com/api/?Action=UpdateServerCertificate?NewPath=NewPath&NewServerCertificateName=NewServerCertificateName&ServerCertificateName=ServerCertificateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the name and/or the path of the specified server certificate stored in\n      IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e121765-cc92-41c8-981d-43dbe1ca7ea8"
            }
          ]
        }
      ]
    },
    {
      "name": "Signing Certificates",
      "item": [
        {
          "id": "9cf0c962-1fdb-43b4-9fc1-bd1c00f86428",
          "name": "deleteSigningCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSigningCertificate?CertificateId=CertificateId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a signing certificate associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1c5d8f7-edf5-4be3-9823-c824fcee932e"
            }
          ]
        },
        {
          "id": "041858ef-a3f5-4c87-a4ea-97ace5a0e825",
          "name": "listSigningCertificates",
          "request": {
            "url": "http://example.com/api/?Action=ListSigningCertificates?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the signing certificates associated with the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59407d2e-977d-4e72-b170-c15c3f11e8f1"
            }
          ]
        }
      ]
    },
    {
      "name": "SSH Public Key",
      "item": [
        {
          "id": "350a45c2-4f6b-4969-af89-d057a43dca18",
          "name": "deleteSSHPublicKey",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSSHPublicKey?SSHPublicKeyId=SSHPublicKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified SSH public key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8778bfc8-b48d-4b3b-bd79-4b28e3006569"
            }
          ]
        },
        {
          "id": "ee6b59c3-9cdc-45f4-afa7-3b2480208d78",
          "name": "getSSHPublicKey",
          "request": {
            "url": "http://example.com/api/?Action=GetSSHPublicKey?Encoding=Encoding&SSHPublicKeyId=SSHPublicKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the specified SSH public key, including metadata about the key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df670b32-d8af-40ef-9714-77d16875f40a"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Devices",
      "item": [
        {
          "id": "ff486334-94fe-4de4-8001-a9d4a93259e1",
          "name": "deleteVirtualMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVirtualMFADevice?SerialNumber=SerialNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a virtual MFA device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "907edc0c-5d47-4d2d-86dc-6a952e9f6fb4"
            }
          ]
        },
        {
          "id": "dffb26da-018d-4f0c-beb2-a7d2eb599615",
          "name": "listVirtualMFADevices",
          "request": {
            "url": "http://example.com/api/?Action=ListVirtualMFADevices?AssignmentStatus=AssignmentStatus&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the virtual MFA devices defined in the AWS account by assignment status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16a5272a-9af1-44dd-8fbe-8595e3f0f5b8"
            }
          ]
        }
      ]
    },
    {
      "name": "MFA Devices",
      "item": [
        {
          "id": "75405b62-ec8d-4d3e-83d3-73677111fdb5",
          "name": "enableMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=EnableMFADevice?AuthenticationCode1=AuthenticationCode1&AuthenticationCode2=AuthenticationCode2&SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified MFA device and associates it with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ede0127-7877-41c4-a41e-690153d88e7f"
            }
          ]
        },
        {
          "id": "507b5ff8-7c22-47fc-8f4e-db251d4af621",
          "name": "listMFADevices",
          "request": {
            "url": "http://example.com/api/?Action=ListMFADevices?Marker=Marker&MaxItems=MaxItems&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the MFA devices for an IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e96eb25a-db4a-41a7-8d88-47c5e6d1038c"
            }
          ]
        },
        {
          "id": "fc8387e5-43d1-4049-a5d0-b7a2493e0a99",
          "name": "resyncMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=ResyncMFADevice?AuthenticationCode1=AuthenticationCode1&AuthenticationCode2=AuthenticationCode2&SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Synchronizes the specified MFA device with its IAM resource object on the AWS\n      servers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "580450cc-e497-4053-90e0-5822cab927b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Credential Reports",
      "item": [
        {
          "id": "e249cc9d-ce86-440c-bbb9-3c4cf8fb6c6d",
          "name": "generateCredentialReport",
          "request": {
            "url": "http://example.com/api/?Action=GenerateCredentialReport?Description=Description&State=State",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a credential report for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "815e4f25-55c1-47f9-a937-415d4e5339a5"
            }
          ]
        },
        {
          "id": "533e280e-88f6-4707-bf16-082e03e80fdc",
          "name": "getCredentialReport",
          "request": {
            "url": "http://example.com/api/?Action=GetCredentialReport?Content=Content&GeneratedTime=GeneratedTime&ReportFormat=ReportFormat",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a credential report for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70d449bd-85ab-4388-8614-4e3e5f14f912"
            }
          ]
        }
      ]
    },
    {
      "name": "Accounts",
      "item": [
        {
          "id": "80ef5390-2d69-4aeb-9567-050dc1654e5e",
          "name": "getAccountAuthorizationDetails",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountAuthorizationDetails?Filter.member.N=Filter.member.N&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about all IAM users, groups, roles, and policies in your AWS\n      account, including their relationships to one another."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53c7a092-eb88-4342-b0a3-1d49c3ea54d8"
            }
          ]
        },
        {
          "id": "7b14d207-583d-4dce-94af-b594b7c3abea",
          "name": "getAccountPasswordPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountPasswordPolicy?PasswordPolicy=PasswordPolicy",