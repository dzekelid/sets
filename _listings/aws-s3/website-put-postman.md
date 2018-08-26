{
  "info": {
    "name": "AWS S3 PUT Bucket website",
    "_postman_id": "e3486e12-733b-4d7a-8d58-eb02c3773f6f",
    "description": "Sets the configuration of the website that is specified in thewebsite subresource",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Bucket",
      "item": [
        {
          "id": "830828a5-dcf0-4af4-a2a1-71e015c0118c",
          "name": "put-bucket",
          "request": {
            "url": "{{default}}/",
            "method": "PUT",
            "header": [
              {
                "key": "x-amz-acl",
                "value": "{}",
                "description": "The canned ACL to apply to the bucket you are creating",
                "disabled": false
              },
              {
                "key": "x-amz-grant-full-control",
                "value": "{}",
                "description": "Allows grantee the READ, WRITE, READ_ACP, and WRITE_ACP permissions on thettttttttttttbucket",
                "disabled": false
              },
              {
                "key": "x-amz-grant-read",
                "value": "{}",
                "description": "Allows grantee to list the objects in the bucket",
                "disabled": false
              },
              {
                "key": "x-amz-grant-read-acp",
                "value": "{}",
                "description": "Allows grantee to read the bucket ACL",
                "disabled": false
              },
              {
                "key": "x-amz-grant-write",
                "value": "{}",
                "description": "Allows grantee to create, overwrite, and delete any object in the bucket",
                "disabled": false
              },
              {
                "key": "x-amz-grant-write-acp",
                "value": "{}",
                "description": "Allows grantee to write the ACL for the applicable bucket",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the PUT operation creates a new bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45d45389-c58e-4eae-b3b8-9c43ddf87942"
            }
          ]
        },
        {
          "id": "3e5de196-75eb-49f6-8a2a-75c0d45ff111",
          "name": "delete-bucket",
          "request": {
            "url": "{{default}}/",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the DELETE operation deletes the bucket named inthe URI"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2fe87584-de0d-417a-95db-24dfd1ae7c6c"
            }
          ]
        },
        {
          "id": "5d644de6-3c53-40d7-82f8-2644998b4eea",
          "name": "get-bucket-accelerate",
          "request": {
            "url": "{{default}}/?accelerate",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation uses the acceleratesubresource to return the Transfer Acceleration state of a bucket, which is eitherEnabled or Suspended"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6affd9cf-8174-4e43-8fcd-ed0297fbb9ed"
            }
          ]
        },
        {
          "id": "5169d84d-37b6-47bc-84a3-8ee841505f8d",
          "name": "put-bucket-accelerate",
          "request": {
            "url": "{{default}}/?accelerate",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the PUT operation uses the acceleratesubresource to set the Transfer Acceleration state of an existing bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9f294af-4515-45aa-b787-d7b349075a88"
            }
          ]
        },
        {
          "id": "19708b97-c771-456a-b2a0-f688b80ed2ab",
          "name": "get-bucket-acl",
          "request": {
            "url": "{{default}}/?acl",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation uses the aclsubresource to return the access control list (ACL) of a bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f7bfc9f-950a-4305-b375-8181c24015e3"
            }
          ]
        },
        {
          "id": "c740da08-efe6-4eca-963a-e098f3c4700a",
          "name": "put-bucket-acl",
          "request": {
            "url": "{{default}}/?acl",
            "method": "PUT",
            "header": [
              {
                "key": "x-amz-acl",
                "value": "{}",
                "description": "Sets the ACL of the bucket using the specified canned ACL",
                "disabled": false
              },
              {
                "key": "x-amz-grant-full-control",
                "value": "{}",
                "description": "Allows the specified grantee(s) the READ, WRITE, READ_ACP, and WRITE_ACPtttttttttpermissions on the bucket",
                "disabled": false
              },
              {
                "key": "x-amz-grant-read",
                "value": "{}",
                "description": "Allows the specified grantee(s) to list the objects in the bucket",
                "disabled": false
              },
              {
                "key": "x-amz-grant-read-acp",
                "value": "{}",
                "description": "Allows the specified grantee(s) to read the bucket ACL",
                "disabled": false
              },
              {
                "key": "x-amz-grant-write",
                "value": "{}",
                "description": "Allows the specified grantee(s) to create, overwrite, and delete any object in thetttttttttbucket",
                "disabled": false
              },
              {
                "key": "x-amz-grant-write-acp",
                "value": "{}",
                "description": "Allows the specified grantee(s) to write the ACL for the applicabletttttttttbucket",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the PUT operation uses the aclsubresource to set the permissions on an existing bucket using access control lists(ACL)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "439824b8-08c8-4b1c-8d4f-0a4d89951d83"
            }
          ]
        },
        {
          "id": "d7e0f19b-b1fe-4f97-8c81-02b918dab758",
          "name": "get-bucket-analytics-configuration",
          "request": {
            "url": "{{default}}/?analytics&amp;id=analytics-configuration-ID",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation returns an analytics configuration (identified bythe analytics configuration ID) from the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d614c693-d27e-4acc-806e-6bc98380d8c6"
            }
          ]
        },
        {
          "id": "977fea11-e934-4054-8baf-7a112ede7252",
          "name": "delete-bucket-analyticsconfiguration",
          "request": {
            "url": "{{default}}/?analytics&amp;id=analytics-configuration-ID?id=%7B%7D",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the DELETE operation deletes an analytics configuration(identified by the analytics configuration ID) from the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "140b443d-de24-4752-bfb0-176d6444bfbc"
            }
          ]
        },
        {
          "id": "524f01b0-5068-46a5-96a7-db032c5eb741",
          "name": "put-bucket-analytics-configuration",
          "request": {
            "url": "{{default}}/?analytics&amp;id=configuration-ID",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the PUT operation adds an analytics configuration(identified by the analytics ID) to the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5972275-5ae5-4f94-9851-93fc69570ad6"
            }
          ]
        },
        {
          "id": "61d28a66-71d6-44b6-8d64-cf9b68242fa8",
          "name": "get-bucket-cors",
          "request": {
            "url": "{{default}}/?cors",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the cors configuration information set for thebucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "152f5550-62a9-43fa-8703-7f057151af56"
            }
          ]
        },
        {
          "id": "ca9994f5-a220-4439-b4e0-e89cd068f718",
          "name": "delete-bucket-cors",
          "request": {
            "url": "{{default}}/?cors",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the cors configuration information set for the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71a6e308-39c7-41f1-8823-09322f576b49"
            }
          ]
        },
        {
          "id": "67bd4978-8351-4607-bece-8dc40c4cd128",
          "name": "put-bucket-inventory-configuration",
          "request": {
            "url": "{{default}}/?inventory&amp;id=configuration-ID",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the PUT operation adds an inventory configuration(identified by the inventory ID) to the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e2ab766-0e60-444a-a76a-3b64f38170c6"
            }
          ]
        },
        {
          "id": "285d6280-3fa0-4462-b3f0-e80cb548ce43",
          "name": "get-bucket-inventory-configuration",
          "request": {
            "url": "{{default}}/?inventory&amp;id=inventory-configuration-ID",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation returns an inventory configuration (identified bythe inventory configuration ID) from the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce9047d9-10ae-4b52-92fb-5556b280f351"
            }
          ]
        },
        {
          "id": "b4e6e5ad-53a3-4c7f-b3f7-7066f72f4814",
          "name": "delete-bucket-inventoryconfiguration",
          "request": {
            "url": "{{default}}/?inventory&amp;id=inventory-configuration-ID?id=%7B%7D",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the DELETE operation deletes an inventory configuration(identified by the inventory configuration ID) from the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8dfc8da-4583-46f4-846a-30974414e3e8"
            }
          ]
        },
        {
          "id": "d39f09bd-f24b-4037-aacb-3d3b1bdb4d72",
          "name": "get-bucket-lifecycle",
          "request": {
            "url": "{{default}}/?lifecycle",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "NoteBucket lifecycle configuration now supports specifying lifecycle rule usingobject key name prefix, one or more object tags, or combination of both"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "944d0dc6-6b57-4625-99da-5b56dd226791"
            }
          ]
        },
        {
          "id": "ff7457f6-34ca-4d02-9a54-20321b29a048",
          "name": "put-bucket-lifecycle",
          "request": {
            "url": "{{default}}/?lifecycle",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new lifecycle configuration for the bucket or replaces an existing lifecycle configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1669c79e-2087-456d-81e3-edcc2d428844"
            }
          ]
        },
        {
          "id": "cf84a80b-b1c3-4f97-9f5a-b804ed5609f5",
          "name": "delete-bucket-lifecycle",
          "request": {
            "url": "{{default}}/?lifecycle",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the lifecycle configuration from the specified bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e2567a3-100c-454a-8699-f556a6f72726"
            }
          ]
        },
        {
          "id": "570967f7-a41f-414b-bbf6-1230dfa9b08c",
          "name": "get-bucket-list-objects-version-2",
          "request": {
            "url": "{{default}}/?list-type=2?continuation-token=%7B%7D&delimiter=%7B%7D&encoding-type=%7B%7D&fetch-owner=%7B%7D&list-type=%7B%7D&max-keys=%7B%7D&prefix=%7B%7D&start-after=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation returns some or all (up to 1,000) ofthe objects in a bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "081e78e2-497c-4224-bde3-cd39a9cc6575"
            }
          ]
        },
        {
          "id": "4368378e-31cb-431e-a69b-3ad10477d2f1",
          "name": "get-bucket-location",
          "request": {
            "url": "{{default}}/?location",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation uses thelocation subresource to return a bucket's region"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9de239b-1e8a-4522-a1b2-cdbe6c087cf5"
            }
          ]
        },
        {
          "id": "a17dcfd6-8c78-445d-8350-09575174217c",
          "name": "get-bucket-logging",
          "request": {
            "url": "{{default}}/?logging",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation uses thelogging subresource to return the logging status of a bucketand the permissions users have to view and modify that status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c694fa99-262a-4e1b-8bfb-7f02243bf57e"
            }
          ]
        },
        {
          "id": "a2519554-0f1c-4240-a356-42107a87298d",
          "name": "put-bucket-metrics",
          "request": {
            "url": "{{default}}/?metrics&amp;id=Id",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Sets or updates a metrics configuration for the CloudWatch request metrics (specified by themetrics configuration ID) from the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4545551-9fbf-43f7-8e45-7f30a5a31910"
            }
          ]
        },
        {
          "id": "4890b8b4-c25a-442c-bffe-477a083ea23b",
          "name": "delete-bucket-metrics",
          "request": {
            "url": "{{default}}/?metrics&amp;id=Id",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a metrics configuration for the CloudWatch request metrics (specified by the metricsconfiguration ID) from the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09f4bcbe-aadd-4091-9880-18ad2200eae5"
            }
          ]
        },
        {
          "id": "9fe19fd2-fdfd-451d-9421-e0405019d120",
          "name": "get-bucket-metrics",
          "request": {
            "url": "{{default}}/?metrics&amp;id=id",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a metrics configuration for the CloudWatch request metrics (specified by the metricsconfiguration ID) from the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb084799-d828-4054-ba51-0a8fef2e8ae0"
            }
          ]
        },
        {
          "id": "5d078898-c188-4918-9db4-320e35a8133e",
          "name": "get-bucket-notification",
          "request": {
            "url": "{{default}}/?notification",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation uses thenotification subresource to return the notificationconfiguration of a bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71ce216d-e486-4f79-97a4-c710f063517c"
            }
          ]
        },
        {
          "id": "ffcf5dc6-c708-4d61-824c-ba84a2a70bce",
          "name": "put-bucket-notification",
          "request": {
            "url": "{{default}}/?notification",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The Amazon S3 notification feature enables you to receive notifications when certain eventshappen in your bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb1d393f-d32f-45d4-84c8-14bf4ddff970"
            }
          ]
        },
        {
          "id": "836d3c5e-6217-41f7-9b5c-55c7c669aae4",
          "name": "get-bucket-policy",
          "request": {
            "url": "{{default}}/?policy",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation uses the policysubresource to return the policy of a specified bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4fbf8862-252b-4310-a526-43d41809b905"
            }
          ]
        },
        {
          "id": "c01b9c34-70a2-4df0-a79c-b911a3e76a63",
          "name": "put-bucket-policy",
          "request": {
            "url": "{{default}}/?policy",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the PUT operation uses the policysubresource to add to or replace a policy on a bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6da054e5-56c0-4936-b24e-7d693499939e"
            }
          ]
        },
        {
          "id": "118b03b5-f397-4c90-8543-65b512c77ee8",
          "name": "delete-bucket-policy",
          "request": {
            "url": "{{default}}/?policy",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the DELETE operation uses the policy subresource to delete the policy on a specified bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a48426d3-f09d-4c01-a5f6-8298e982f781"
            }
          ]
        },
        {
          "id": "17c7d340-b1d8-4eaf-b53b-ca3e7dc9d87e",
          "name": "get-bucket-replication",
          "request": {
            "url": "{{default}}/?replication?AWS Documentation &raquo; Amazon Simple Storage Service (S3) &raquo; API Reference &raquo; Operations on Buckets &raquo; GET Bucket replication=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns the replication configuration information set on the      bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f5b63c5-1f9e-45b4-9a5b-ac1064ce4680"
            }
          ]
        },
        {
          "id": "fa865891-a3d6-441a-b820-37202249128e",
          "name": "put-bucket-replication",
          "request": {
            "url": "{{default}}/?replication?AWS Documentation &raquo; Amazon Simple Storage Service (S3) &raquo; API Reference &raquo; Operations on Buckets &raquo; PUT Bucket replication=%7B%7D",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "In a versioning-enabled bucket, this operation creates a new replication configuration (or      replaces an existing one, if present)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d91080c-8b75-4302-a6c5-95cb6ae09561"
            }
          ]
        },
        {
          "id": "1b753171-0dfc-4e71-b1ce-b6cfba651bf3",
          "name": "delete-bucket-replication",
          "request": {
            "url": "{{default}}/?replication",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the replication subresource associated with the specified bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8bbbaab-e841-4338-a945-38a8bd030f84"
            }
          ]
        },
        {
          "id": "2870b1f9-822d-40b4-bdb9-81ff46e4c493",
          "name": "get-bucket-tagging",
          "request": {
            "url": "{{default}}/?tagging",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation uses the taggingsubresource to return the tag set associated with the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0fd6d3f0-1d0c-42a7-80fb-facdd2464c1a"
            }
          ]
        },
        {
          "id": "37239ebd-d4e9-46d5-b28d-363f245e8fc4",
          "name": "put-bucket-tagging",
          "request": {
            "url": "{{default}}/?tagging",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the PUT operation uses the taggingsubresource to add a set of tags to an existing bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8f916e9-17d6-4d85-8fa9-a6162dbc091c"
            }
          ]
        },
        {
          "id": "cd04c951-47d2-4940-b340-2c47c614d073",
          "name": "delete-bucket-tagging",
          "request": {
            "url": "{{default}}/?tagging",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the DELETE operation uses the taggingsubresource to remove a tag set from the specified bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df11edbd-d1d7-4709-ae7e-1c86402b8c97"
            }
          ]
        },
        {
          "id": "70e9a33f-73a5-4155-b5f5-60f20f161260",
          "name": "get-bucket-versioning",
          "request": {
            "url": "{{default}}/?versioning",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation uses theversioning subresource to return the versioning state of abucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d2af6ae-891d-4f01-9ff4-b80e3a4188a3"
            }
          ]
        },
        {
          "id": "ba0ee8c3-ac25-4f4a-841b-51642606d6c3",
          "name": "put-bucket-versioning",
          "request": {
            "url": "{{default}}/?versioning",
            "method": "PUT",
            "header": [
              {
                "key": "x-amz-mfa",
                "value": "{}",
                "description": "The value is the concatenation of the authenticationtttttttttdevices serial number, a space, and the value displayed on yourtttttttttauthentication device",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the PUT operation uses theversioning subresource to set the versioning state of anexisting bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c31834dc-35a2-4c25-a0b2-cbf0ab356479"
            }
          ]
        },
        {
          "id": "a98400fa-c688-4efb-8a6a-feadb857dc35",
          "name": "get-bucket-object-versions",
          "request": {
            "url": "{{default}}/?versions?delimiter=%7B%7D&encoding-type=%7B%7D&key-marker=%7B%7D&max-keys=%7B%7D&prefix=%7B%7D&version-id-marker=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "You can use the versions subresource to list metadata about all ofthe versions of objects in a bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab693937-e5d2-40d2-910b-f57f1199805d"
            }
          ]
        },
        {
          "id": "6619eab9-9979-406d-ac50-46b1c04566fb",
          "name": "get-bucket-website",
          "request": {
            "url": "{{default}}/?website",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation returns the website configurationassociated with a bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a32fe15f-3852-4520-a420-25850ea69348"
            }
          ]
        },
        {
          "id": "eb0658f6-e077-47a9-8ed3-973cbd7612e7",
          "name": "put-bucket-website",
          "request": {
            "url": "{{default}}/?website",
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Sets the configuration of the website that is specified in thewebsite subresource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9a95ff4-8cf0-46af-b570-a77810b8ee11"
            }
          ]
        },
        {
          "id": "8eb76315-8143-415f-bdb0-438003732bf4",
          "name": "delete-bucket-website",
          "request": {
            "url": "{{default}}/?website",
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This operation removes the website configuration for a bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95b20184-f571-4f68-8f9d-f062d21b6ecc"
            }
          ]
        }
      ]
    },
    {
      "name": "Object",
      "item": [
        {
          "id": "099e8a58-cd45-4bd1-8e2a-84405cbc4831",
          "name": "post-object",
          "request": {
            "url": "{{default}}/",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The POST operation adds an object to a specified bucket using HTML forms"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b93bb48e-afb9-4d91-8a2d-336e467f7de8"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "a95d12e5-e4ba-4d2f-a7ed-54caa875fe68",
          "name": "list-bucket-analytics-configurations",
          "request": {
            "url": "{{default}}/?analytics?ContinuationToken=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation returns a list of analyticsconfigurations for the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0cf1029-4c0d-44f1-a803-19d0d608fbac"
            }
          ]
        },
        {
          "id": "9e042d14-54d1-4b76-b4f3-110b7ff7b1f2",
          "name": "list-bucket-inventory-configurations",
          "request": {
            "url": "{{default}}/?inventory?ContinuationToken=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This implementation of the GET operation returns a list of inventoryconfigurations for the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfc3e47f-9077-48c3-b45d-f84f999684ac"
            }
          ]
        },
        {
          "id": "08560555-ca78-492f-806a-f59d5a59d907",
          "name": "list-bucket-metrics",
          "request": {
            "url": "{{default}}/?metrics?BucketName=%7B%7D&ContinuationToken=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Lists the metrics configurations for the CloudWatch request metrics of the bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2367d58d-10f8-48c7-ba6e-e4d739a7b63b"
            }
          ]
        },
        {
          "id": "0da55206-339c-4e7a-9594-42a2d03466ef",
          "name": "list-multipart-uploads",
          "request": {
            "url": "{{default}}/?uploads?delimiter=%7B%7D&encoding-type=%7B%7D&key-marker=%7B%7D&max-uploads=%7B%7D&prefix=%7B%7D&upload-id-&#8203;marker=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This operation lists in-progress multipart uploads"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7eed21b4-53c7-45a8-9b44-53a260e7e397"
            }
          ]
        }
      ]
    },
    {
      "name": "Multiple",
      "item": [
        {
          "id": "3f2e1a46-11f3-4348-9a93-ea2ae1797a82",
          "name": "delete-multiple-objects",
          "request": {
            "url": "{{default}}/?delete",
            "method": "POST",
            "header": [
              {
                "key": "Content-Length",
                "value": "{}",
                "description": "Length of the body according to RFC 2616",
                "disabled": false
              },
              {
                "key": "Content-MD5",
                "value": "{}",
                "description": "The base64-encoded 128-bit MD5 digest of the data",
                "disabled": false
              },
              {
                "key": "x-amz-mfa",
                "value": "{}",
                "description": "The value is the concatenation of the authentication devices serial number, a space,tttttttttand the value that is displayed on your authenticationtttttttttdevice",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "The Multi-Object Delete operation enables you to delete multiple objects from a bucketusing a single HTTP request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92a9b101-92b8-4980-b840-5d4887dfc15c"
            }
          ]
        }
      ]
    }
  ],
  "variable": [
    {
      "key": "default",
      "value": "http://www.example.com/"
    }
  ]
}