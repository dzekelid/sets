{
  "info": {
    "name": "AWS Auto Scaling API Set Desired Capacity",
    "_postman_id": "051947bc-7cbc-4152-b64d-16da61aaddd7",
    "description": "Sets the size of the specified Auto Scaling group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "9d4bf57e-ae81-4cd6-8322-8e823afe2d91",
          "name": "attachInstances",
          "request": {
            "url": "http://example.com/api/?Action=AttachInstances?AutoScalingGroupName=AutoScalingGroupName&InstanceIds.member.N=InstanceIds.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches one or more EC2 instances to the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c5668c7-d4a5-412b-86f1-2dde72d45f24"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "0860a104-a4ce-48b4-9d56-2e61b261094b",
          "name": "attachLoadBalancers",
          "request": {
            "url": "http://example.com/api/?Action=AttachLoadBalancers?AutoScalingGroupName=AutoScalingGroupName&LoadBalancerNames.member.N=LoadBalancerNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches one or more Classic load balancers to the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34527a9e-007b-43e0-992a-b36bf36408a6"
            }
          ]
        },
        {
          "id": "f2273333-9bbf-403b-b97b-247527cfdbd5",
          "name": "attachLoadBalancerTargetGroups",
          "request": {
            "url": "http://example.com/api/?Action=AttachLoadBalancerTargetGroups?AutoScalingGroupName=AutoScalingGroupName&TargetGroupARNs.member.N=TargetGroupARNs.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches one or more target groups to the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd4e3b6a-faad-44fc-944a-597f971fd566"
            }
          ]
        },
        {
          "id": "7f66b483-a559-4cdd-bffd-a88757e9f713",
          "name": "describeLoadBalancers",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLoadBalancers?AutoScalingGroupName=AutoScalingGroupName&MaxRecords=MaxRecords&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the load balancers for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ffc63ce-229d-4d70-8cc4-b9c25f8f24aa"
            }
          ]
        },
        {
          "id": "5e37e791-8d1d-4272-83df-17dc3644abe4",
          "name": "describeLoadBalancerTargetGroups",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLoadBalancerTargetGroups?AutoScalingGroupName=AutoScalingGroupName&MaxRecords=MaxRecords&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the target groups for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93c3b72e-445e-4df7-81ce-377047ca19dd"
            }
          ]
        },
        {
          "id": "be104f82-671a-4c48-86d0-76e2f0f09e2e",
          "name": "detachLoadBalancers",
          "request": {
            "url": "http://example.com/api/?Action=DetachLoadBalancers?AutoScalingGroupName=AutoScalingGroupName&LoadBalancerNames.member.N=LoadBalancerNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches one or more Classic load balancers from the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86353dc3-fd81-4629-957e-6b5f296be148"
            }
          ]
        },
        {
          "id": "df0e3ff3-2f26-43c0-bdbb-2c547f4c876b",
          "name": "detachLoadBalancerTargetGroups",
          "request": {
            "url": "http://example.com/api/?Action=DetachLoadBalancerTargetGroups?AutoScalingGroupName=AutoScalingGroupName&TargetGroupARNs.member.N=TargetGroupARNs.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches one or more target groups from the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9041015f-7a80-44ba-88b4-a456a956389f"
            }
          ]
        }
      ]
    },
    {
      "name": "Life Cycle",
      "item": [
        {
          "id": "4acaa202-ba08-40bc-8bdd-3fb4a1875cb2",
          "name": "completeLifecycleAction",
          "request": {
            "url": "http://example.com/api/?Action=CompleteLifecycleAction?AutoScalingGroupName=AutoScalingGroupName&InstanceId=InstanceId&LifecycleActionResult=LifecycleActionResult&LifecycleActionToken=LifecycleActionToken&LifecycleHookName=LifecycleHookName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Completes the lifecycle action for the specified token or instance with the specified result."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fce6e91-a36b-4008-88a1-27b1892ef7b3"
            }
          ]
        },
        {
          "id": "ba5200b9-9139-40a6-aa18-c95442147fe9",
          "name": "deleteLifecycleHook",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLifecycleHook?AutoScalingGroupName=AutoScalingGroupName&LifecycleHookName=LifecycleHookName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified lifecycle hook."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1bb3a7e-c3b8-4b57-b3d7-85903237030d"
            }
          ]
        },
        {
          "id": "19cd57d5-4e9e-482f-822a-8dd15d36bb9f",
          "name": "describeLifecycleHooks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLifecycleHooks?AutoScalingGroupName=AutoScalingGroupName&LifecycleHookNames.member.N=LifecycleHookNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the lifecycle hooks for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7361ae0-2331-4759-8e3e-4a03382a66c4"
            }
          ]
        },
        {
          "id": "904112db-75f4-48de-a6e2-025fbc486a9a",
          "name": "describeLifecycleHookTypes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLifecycleHookTypes?LifecycleHookTypes.member.N=LifecycleHookTypes.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the available types of lifecycle hooks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57dd6d97-aefd-4889-a66c-2b94ce2888a0"
            }
          ]
        },
        {
          "id": "36a8e1ec-30cf-4dc7-aa41-48a4b0c0c14c",
          "name": "putLifecycleHook",
          "request": {
            "url": "http://example.com/api/?Action=PutLifecycleHook?AutoScalingGroupName=AutoScalingGroupName&DefaultResult=DefaultResult&HeartbeatTimeout=HeartbeatTimeout&LifecycleHookName=LifecycleHookName&LifecycleTransition=LifecycleTransition&NotificationMetadata=NotificationMetadata&NotificationTargetARN=NotificationTargetARN&RoleARN=RoleARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates or updates a lifecycle hook for the specified Auto Scaling Group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bfa7f4fe-4eb0-4c3d-a35d-d8c7b3a3c722"
            }
          ]
        },
        {
          "id": "85c79d5d-d415-4dec-b027-24bb26c73fd3",
          "name": "recordLifecycleActionHeartbeat",
          "request": {
            "url": "http://example.com/api/?Action=RecordLifecycleActionHeartbeat?AutoScalingGroupName=AutoScalingGroupName&InstanceId=InstanceId&LifecycleActionToken=LifecycleActionToken&LifecycleHookName=LifecycleHookName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Records a heartbeat for the lifecycle action associated with the specified token or instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d476d504-2dc9-4618-bd37-52c396c97af2"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling Groups",
      "item": [
        {
          "id": "4f12bf21-1f90-4e75-b964-9224546c617e",
          "name": "createAutoScalingGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateAutoScalingGroup?AutoScalingGroupName=AutoScalingGroupName&AvailabilityZones.member.N=AvailabilityZones.member.N&DefaultCooldown=DefaultCooldown&DesiredCapacity=DesiredCapacity&HealthCheckGracePeriod=HealthCheckGracePeriod&HealthCheckType=HealthCheckType&InstanceId=InstanceId&LaunchConfigurationName=LaunchConfigurationName&LoadBalancerNames.member.N=LoadBalancerNames.member.N&MaxSize=MaxSize&MinSize=MinSize&NewInstancesProtectedFromScaleIn=NewInstancesProtectedFromScaleIn&PlacementGroup=PlacementGroup&Tags.member.N=Tags.member.N&TargetGroupARNs.member.N=TargetGroupARNs.member.N&TerminationPolicies.member.N=TerminationPolicies.member.N&VPCZoneIdentifier=VPCZoneIdentifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Auto Scaling group with the specified name and attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17742b5b-3df2-4bd5-9a82-9d97154f63fe"
            }
          ]
        },
        {
          "id": "b26b761d-4c89-4cb5-8c56-a1c81a039e77",
          "name": "deleteAutoScalingGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAutoScalingGroup?AutoScalingGroupName=AutoScalingGroupName&ForceDelete=ForceDelete",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "765bf1e6-edd7-4371-a42f-4d1a90af79e8"
            }
          ]
        },
        {
          "id": "48a24b65-9216-4613-9007-1134c2a152a6",
          "name": "describeAutoScalingGroups",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAutoScalingGroups?AutoScalingGroupNames.member.N=AutoScalingGroupNames.member.N&MaxRecords=MaxRecords&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more Auto Scaling groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "597b6215-6c00-4170-baf1-0fb6605ee222"
            }
          ]
        }
      ]
    },
    {
      "name": "Launch",
      "item": [
        {
          "id": "79c2b7e0-2cdd-4d4a-988f-e656be844fe4",
          "name": "createLaunchConfiguration",
          "request": {
            "url": "http://example.com/api/?Action=CreateLaunchConfiguration?AssociatePublicIpAddress=AssociatePublicIpAddress&BlockDeviceMappings.member.N=BlockDeviceMappings.member.N&ClassicLinkVPCId=ClassicLinkVPCId&ClassicLinkVPCSecurityGroups.member.N=ClassicLinkVPCSecurityGroups.member.N&EbsOptimized=EbsOptimized&IamInstanceProfile=IamInstanceProfile&ImageId=ImageId&InstanceId=InstanceId&InstanceMonitoring=InstanceMonitoring&InstanceType=InstanceType&KernelId=KernelId&KeyName=KeyName&LaunchConfigurationName=LaunchConfigurationName&PlacementTenancy=PlacementTenancy&RamdiskId=RamdiskId&SecurityGroups.member.N=SecurityGroups.member.N&SpotPrice=SpotPrice&UserData=UserData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a launch configuration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11ca92b6-cb8b-4bb0-99f1-4c07708ecd30"
            }
          ]
        },
        {
          "id": "26e455ab-0f42-4de9-97fc-5a8ad6f5ddd0",
          "name": "deleteLaunchConfiguration",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLaunchConfiguration?LaunchConfigurationName=LaunchConfigurationName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified launch configuration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f31a34ce-b2c2-4769-a6ee-f1c3581cf433"
            }
          ]
        },
        {
          "id": "652c3d36-e5b0-4d0e-9f34-734169583e9b",
          "name": "describeLaunchConfigurations",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLaunchConfigurations?LaunchConfigurationNames.member.N=LaunchConfigurationNames.member.N&MaxRecords=MaxRecords&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more launch configurations."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73b362a8-2454-47d2-9b76-85188a29f4c7"
            }
          ]
        }
      ]
    },
    {
      "name": "Tags",
      "item": [
        {
          "id": "ad2c5ed6-f3d7-4cc5-a223-f866c21c7520",
          "name": "createOrUpdateTags",
          "request": {
            "url": "http://example.com/api/?Action=CreateOrUpdateTags?Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates or updates tags for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51027ee2-eb79-4831-a4e9-a3cb4799545b"
            }
          ]
        },
        {
          "id": "2afd6704-aaf8-45a6-be1e-01966478dd21",
          "name": "deleteTags",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTags?Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified tags."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c76a89e-b212-4e05-824a-a72c45c11a43"
            }
          ]
        },
        {
          "id": "73849ea9-0805-4fd6-8ea6-b843de65443e",
          "name": "describeTags",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTags?Filters.member.N=Filters.member.N&MaxRecords=MaxRecords&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified tags."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98115ac1-824b-4e33-9f04-e4841b58449d"
            }
          ]
        }
      ]
    },
    {
      "name": "Notifications",
      "item": [
        {
          "id": "d07595ea-35f6-434d-b991-4f2291703443",
          "name": "deleteNotificationConfiguration",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNotificationConfiguration?AutoScalingGroupName=AutoScalingGroupName&TopicARN=TopicARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified notification."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33da5878-2535-4b7d-8592-985f6ab0ada0"
            }
          ]
        },
        {
          "id": "d54eacc4-6e6d-498a-bf07-908d6a2f4a1d",
          "name": "describeNotificationConfigurations",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNotificationConfigurations?AutoScalingGroupNames.member.N=AutoScalingGroupNames.member.N&MaxRecords=MaxRecords&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the notification actions associated with the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2f105fe-9464-4ef4-b216-a78a2ed7cb0d"
            }
          ]
        },
        {
          "id": "d15db2ad-adca-4a55-8571-5bf495458292",
          "name": "putNotificationConfiguration",
          "request": {
            "url": "http://example.com/api/?Action=PutNotificationConfiguration?AutoScalingGroupName=AutoScalingGroupName&NotificationTypes.member.N=NotificationTypes.member.N&TopicARN=TopicARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Configures an Auto Scaling group to send notifications when specified events take place."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c5ee037-7011-4423-a6ed-f7d9ccb8d67c"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "15d25f9a-b2d7-4db2-aea1-2f44ccb23a71",
          "name": "deletePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicy?AutoScalingGroupName=AutoScalingGroupName&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Auto Scaling policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cac34186-04f5-4eef-a419-e4333d838a81"
            }
          ]
        },
        {
          "id": "ba2bc2c0-219f-431f-9d15-6e9d990db29b",
          "name": "describePolicies",
          "request": {
            "url": "http://example.com/api/?Action=DescribePolicies?AutoScalingGroupName=AutoScalingGroupName&MaxRecords=MaxRecords&NextToken=NextToken&PolicyNames.member.N=PolicyNames.member.N&PolicyTypes.member.N=PolicyTypes.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the policies for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73d1f7a8-40e4-4b9b-a917-793b0d6dbc76"
            }
          ]
        },
        {
          "id": "f32b5666-e173-4293-ab0a-80052fe3abde",
          "name": "executePolicy",
          "request": {
            "url": "http://example.com/api/?Action=ExecutePolicy?AutoScalingGroupName=AutoScalingGroupName&BreachThreshold=BreachThreshold&HonorCooldown=HonorCooldown&MetricValue=MetricValue&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Executes the specified policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5334175-988f-4b92-bb61-35704917c508"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Action",
      "item": [
        {
          "id": "af3b986f-3b6c-40c0-8547-b7069046dddb",
          "name": "deleteScheduledAction",
          "request": {
            "url": "http://example.com/api/?Action=DeleteScheduledAction?AutoScalingGroupName=AutoScalingGroupName&ScheduledActionName=ScheduledActionName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified scheduled action."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4f467044-9663-4bf6-bbfd-773b3c48ce28"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Limits",
      "item": [
        {
          "id": "199f0c5a-27af-4565-87f2-99b7858cfb0a",
          "name": "describeAccountLimits",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAccountLimits?MaxNumberOfAutoScalingGroups=MaxNumberOfAutoScalingGroups&MaxNumberOfLaunchConfigurations=MaxNumberOfLaunchConfigurations&NumberOfAutoScalingGroups=NumberOfAutoScalingGroups&NumberOfLaunchConfigurations=NumberOfLaunchConfigurations",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the current Auto Scaling resource limits for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "adcd1ece-c666-496d-a1cf-d23c9675dbc7"
            }
          ]
        }
      ]
    },
    {
      "name": "Adjustment Types",
      "item": [
        {
          "id": "d3b050ef-c876-4fcb-ad70-80b187c62bda",
          "name": "describeAdjustmentTypes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAdjustmentTypes?AdjustmentTypes.member.N=AdjustmentTypes.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the policy adjustment types for use with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e23601fa-227a-4f3d-a5fc-1accec9c7830"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling Instances",
      "item": [
        {
          "id": "a618e71b-b995-40fb-80ad-1fd5b53c9bf6",
          "name": "describeAutoScalingInstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAutoScalingInstances?InstanceIds.member.N=InstanceIds.member.N&MaxRecords=MaxRecords&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more Auto Scaling instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cd92f92-1cfa-4724-a4e2-08435369f99a"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling Notifications",
      "item": [
        {
          "id": "86821914-abbe-4fda-8c60-1bad7889f9b2",
          "name": "describeAutoScalingNotificationTypes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAutoScalingNotificationTypes?AutoScalingNotificationTypes.member.N=AutoScalingNotificationTypes.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the notification types that are supported by Auto Scaling."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e92d2be1-2134-4b6e-b8d9-9fc39b0831a5"
            }
          ]
        }
      ]
    },
    {
      "name": "Metric Collection",
      "item": [
        {
          "id": "f79db535-1813-4972-90e7-84d9d0398238",
          "name": "describeMetricCollectionTypes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMetricCollectionTypes?Granularities.member.N=Granularities.member.N&Metrics.member.N=Metrics.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the available CloudWatch metrics for Auto Scaling."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7473ced0-eae8-459c-ad05-3df2861a169b"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Activities",
      "item": [
        {
          "id": "359bdd75-3faa-47c7-83b0-dea77e0872d9",
          "name": "describeScalingActivities",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScalingActivities?ActivityIds.member.N=ActivityIds.member.N&AutoScalingGroupName=AutoScalingGroupName&MaxRecords=MaxRecords&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more scaling activities for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9079ffed-ad5d-45cb-9a5d-0f0d53d13bbb"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Process",
      "item": [
        {
          "id": "18d31814-7764-4bd4-9b65-4c4b56d67078",
          "name": "describeScalingProcessTypes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScalingProcessTypes?Processes.member.N=Processes.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the scaling process types for use with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd09d028-6e4f-4592-baa1-d5027247febd"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Actions",
      "item": [
        {
          "id": "0569a06f-5431-4d8f-8e64-e29f090409b6",
          "name": "describeScheduledActions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScheduledActions?AutoScalingGroupName=AutoScalingGroupName&EndTime=EndTime&MaxRecords=MaxRecords&NextToken=NextToken&ScheduledActionNames.member.N=ScheduledActionNames.member.N&StartTime=StartTime",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the actions scheduled for your Auto Scaling group that haven't run."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "badaa847-a24a-4870-90d6-f093ebbcb476"
            }
          ]
        }
      ]
    },
    {
      "name": "Termination Policies",
      "item": [
        {
          "id": "1a745467-4b10-4fc8-8062-d3b3cc4b0641",
          "name": "describeTerminationPolicyTypes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTerminationPolicyTypes?TerminationPolicyTypes.member.N=TerminationPolicyTypes.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the termination policies supported by Auto Scaling."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "608f9d44-285a-4eea-93f0-c4a109e4c25d"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instances",
      "item": [
        {
          "id": "093874d6-accc-4c19-94ef-11ccfd561c21",
          "name": "detachInstances",
          "request": {
            "url": "http://example.com/api/?Action=DetachInstances?AutoScalingGroupName=AutoScalingGroupName&InstanceIds.member.N=InstanceIds.member.N&ShouldDecrementDesiredCapacity=ShouldDecrementDesiredCapacity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes one or more instances from the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d58755a-0e3c-40ba-8819-ad8aeb8c6b43"
            }
          ]
        }
      ]
    },
    {
      "name": "Metrics Collection",
      "item": [
        {
          "id": "18033298-572b-470d-9dbe-447b1b851634",
          "name": "disableMetricsCollection",
          "request": {
            "url": "http://example.com/api/?Action=DisableMetricsCollection?AutoScalingGroupName=AutoScalingGroupName&Metrics.member.N=Metrics.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables group metrics for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b388530-aa9b-49c2-9f4d-8e81f73e8931"
            }
          ]
        },
        {
          "id": "462ab922-b2aa-42f7-be85-70f540aa17f7",
          "name": "enableMetricsCollection",
          "request": {
            "url": "http://example.com/api/?Action=EnableMetricsCollection?AutoScalingGroupName=AutoScalingGroupName&Granularity=Granularity&Metrics.member.N=Metrics.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables group metrics for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "017b5ea6-e201-4170-93c4-ea779f0abdce"
            }
          ]
        }
      ]
    },
    {
      "name": "Stand By",
      "item": [
        {
          "id": "6278a389-17eb-4b13-a4c2-dd39a6d0822b",
          "name": "enterStandby",
          "request": {
            "url": "http://example.com/api/?Action=EnterStandby?AutoScalingGroupName=AutoScalingGroupName&InstanceIds.member.N=InstanceIds.member.N&ShouldDecrementDesiredCapacity=ShouldDecrementDesiredCapacity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Moves the specified instances into Standby mode."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0505a08f-9167-42db-8764-e9d576da4c1b"
            }
          ]
        },
        {
          "id": "07730b64-c328-43b9-ab52-4aa185cc404b",
          "name": "exitStandby",
          "request": {
            "url": "http://example.com/api/?Action=ExitStandby?AutoScalingGroupName=AutoScalingGroupName&InstanceIds.member.N=InstanceIds.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Moves the specified instances out of Standby mode."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81b83fbe-0a4d-4617-8661-20f5fb021918"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Policy",
      "item": [
        {
          "id": "cca37795-cb1b-4095-8bab-c4f0c44da600",
          "name": "putScalingPolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutScalingPolicy?AdjustmentType=AdjustmentType&AutoScalingGroupName=AutoScalingGroupName&Cooldown=Cooldown&EstimatedInstanceWarmup=EstimatedInstanceWarmup&MetricAggregationType=MetricAggregationType&MinAdjustmentMagnitude=MinAdjustmentMagnitude&MinAdjustmentStep=MinAdjustmentStep&PolicyName=PolicyName&PolicyType=PolicyType&ScalingAdjustment=ScalingAdjustment&StepAdjustments.member.N=StepAdjustments.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates or updates a policy for an Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f561706-8f8b-4af7-a36a-5f24c45fb688"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Update",
      "item": [
        {
          "id": "8558bc93-79a7-416e-a6d7-dbdfc7858129",
          "name": "putScheduledUpdateGroupAction",
          "request": {
            "url": "http://example.com/api/?Action=PutScheduledUpdateGroupAction?AutoScalingGroupName=AutoScalingGroupName&DesiredCapacity=DesiredCapacity&EndTime=EndTime&MaxSize=MaxSize&MinSize=MinSize&Recurrence=Recurrence&ScheduledActionName=ScheduledActionName&StartTime=StartTime&Time=Time",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates or updates a scheduled scaling action for an Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4a398aa-386b-48af-966e-a5dd7dea5e7b"
            }
          ]
        }
      ]
    },
    {
      "name": "Processes",
      "item": [
        {
          "id": "97ac6981-6619-4f57-b310-351755333ad3",
          "name": "resumeProcesses",
          "request": {
            "url": "http://example.com/api/?Action=ResumeProcesses?AutoScalingGroupName=AutoScalingGroupName&ScalingProcesses.member.N=ScalingProcesses.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resumes the specified suspended Auto Scaling processes, or all suspended process, for the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68c43dc0-a779-44ff-97f5-5aac9ea754f3"
            }
          ]
        }
      ]
    },
    {
      "name": "Desired Capacity",
      "item": [
        {
          "id": "8711ea6c-4e4c-40de-b41f-f1e43f50848a",
          "name": "setDesiredCapacity",
          "request": {
            "url": "http://example.com/api/?Action=SetDesiredCapacity?AutoScalingGroupName=AutoScalingGroupName&DesiredCapacity=DesiredCapacity&HonorCooldown=HonorCooldown",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the size of the specified Auto Scaling group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91bdb003-faa6-4a62-b396-f2e110df2307"
            }
          ]
        }
      ]
    }
  ]
}