{
  "info": {
    "name": "AWS Auto Scaling API Set Instance Health",
    "_postman_id": "54258ad5-d3e9-430d-a21f-01da86a5bf80",
    "description": "Sets the health status of the specified instance.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "0f73ffae-7c77-4ce2-bb9d-0727aeec7958",
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
              "id": "49534ab0-a2e1-42e1-ab50-064d416a3574"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "ca5475e2-5da9-4071-86db-12f7d74420e0",
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
              "id": "fbf5e83d-6fd0-41b1-b5d3-d646f85f2e8b"
            }
          ]
        },
        {
          "id": "90be451a-3aaa-4fb6-8161-ac11164362fa",
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
              "id": "ee4a0b09-4817-40fd-8559-60e41cb70147"
            }
          ]
        },
        {
          "id": "80b6ae27-8e2a-476f-8215-69c635c6dfaf",
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
              "id": "7cfb164a-60c0-4f53-ab54-0fe29650effd"
            }
          ]
        },
        {
          "id": "450fae7e-14b0-4089-a0d5-1b96e0058722",
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
              "id": "083b2c4a-893a-4fa3-8585-ea96c7129e5a"
            }
          ]
        },
        {
          "id": "0c029783-5815-4478-bb27-a422a618fc3c",
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
              "id": "2cb0baf2-5811-46f0-8e0e-3b0d58fdcb6c"
            }
          ]
        },
        {
          "id": "74d3f7fa-05e9-4867-a9b6-d36554fe325d",
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
              "id": "fad2d38c-7569-425a-953a-6d445aec6616"
            }
          ]
        }
      ]
    },
    {
      "name": "Life Cycle",
      "item": [
        {
          "id": "8f98d79e-f75e-4940-bf15-4bfa16b67725",
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
              "id": "f527f289-bc68-4d0b-9123-0d9fbeed83bd"
            }
          ]
        },
        {
          "id": "4fb4b23b-1540-44d8-8aed-ab333037bc84",
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
              "id": "242298eb-6b45-4f01-92c8-f638ba112f6f"
            }
          ]
        },
        {
          "id": "9cdc3b97-5e26-4e6b-aebe-c5e679e49f19",
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
              "id": "4c6b8655-c328-4050-a6d6-e6beb830a731"
            }
          ]
        },
        {
          "id": "cbc224c1-c49f-475b-b351-da97b7183526",
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
              "id": "f3ea9aa2-f664-406f-8d68-f6e165e9a405"
            }
          ]
        },
        {
          "id": "7a90cd33-aada-4b1a-a946-b8ae3a234663",
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
              "id": "6467102a-4be2-4a67-919a-65ea9804e816"
            }
          ]
        },
        {
          "id": "7b92daea-0521-45bf-adfd-cb8b8e800ea9",
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
              "id": "0198e407-9705-4442-8442-5a4b639b3cc2"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling Groups",
      "item": [
        {
          "id": "37f2554c-e87a-4fdb-a5bb-d2edf8e49051",
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
              "id": "f3e7898f-edc1-4bdf-9aab-43a9ab12a75e"
            }
          ]
        },
        {
          "id": "d77b9c40-603d-4453-b788-936708ba9b7a",
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
              "id": "493a277b-23eb-4712-9dff-def00aef3a9c"
            }
          ]
        },
        {
          "id": "05043f3b-a73b-49ff-8404-abb5ce1cb206",
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
              "id": "74b8aa66-6cc9-497a-9e2e-8bd3341b32f4"
            }
          ]
        }
      ]
    },
    {
      "name": "Launch",
      "item": [
        {
          "id": "ca2fcc33-243a-4aa5-aefc-4318b61aa685",
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
              "id": "eac90f11-14cc-410d-af39-8cdf3145d21c"
            }
          ]
        },
        {
          "id": "b1693cb4-0b40-4068-999f-25704f506ee0",
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
              "id": "c693cfdc-969e-4f76-b784-a81cdb4bc80f"
            }
          ]
        },
        {
          "id": "ff40c8e5-5f91-4fa5-bf8f-c6e6c263b63d",
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
              "id": "fe855be6-3213-4740-982f-e653531bb202"
            }
          ]
        }
      ]
    },
    {
      "name": "Tags",
      "item": [
        {
          "id": "b74cea25-1253-4f9e-842b-0a8bf4facf72",
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
              "id": "e67e1971-6a67-41ca-9642-91f3c53cef6b"
            }
          ]
        },
        {
          "id": "87e84f19-97e3-493b-b74b-639af7342a53",
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
              "id": "d7f60999-2231-438e-be6e-f4b508063d24"
            }
          ]
        },
        {
          "id": "7be11c44-027d-47a3-b39e-c77a107aff9d",
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
              "id": "40967d57-2dff-4ab0-93d8-1ad60e8f583c"
            }
          ]
        }
      ]
    },
    {
      "name": "Notifications",
      "item": [
        {
          "id": "40f213b0-52c0-41e7-8d40-dcc1fb0fbc10",
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
              "id": "5d9c03de-7dfc-44f0-9cb8-b01e329691b0"
            }
          ]
        },
        {
          "id": "44d59e90-d41d-4a11-96bb-b7397afbb697",
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
              "id": "4260c35c-3b8f-4f8e-98be-7c77c77be0d5"
            }
          ]
        },
        {
          "id": "ac14bf19-364b-4ffa-a31b-2df854c2ad0f",
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
              "id": "99ccba08-80dc-462b-adf9-7f52a1554f1e"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "3ff015fe-670c-4713-8638-10938e3ca13e",
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
              "id": "b9067658-4ff3-4311-bf16-0e5d5d1755c0"
            }
          ]
        },
        {
          "id": "81a842fd-fc91-4963-851b-cabe33d8fefb",
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
              "id": "d3d941d8-9d88-4291-8dbe-dda473d6319f"
            }
          ]
        },
        {
          "id": "099fd245-6b5e-4c06-9d06-7304b619f38c",
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
              "id": "0db04b8b-8bfc-45cf-b728-be52e8192baf"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Action",
      "item": [
        {
          "id": "6459b2eb-8f50-4131-907c-26a1d7133e8f",
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
              "id": "f8e17b82-5187-4f8f-8e8d-135558817ea2"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Limits",
      "item": [
        {
          "id": "488eb57d-ad31-4e02-b9c7-6e7ccecf3b76",
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
              "id": "b4d7b3d5-08c5-43ee-bb7f-43ff12350794"
            }
          ]
        }
      ]
    },
    {
      "name": "Adjustment Types",
      "item": [
        {
          "id": "cd4c8dde-46ab-439f-ab35-3281a5b2de93",
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
              "id": "486d7aba-6044-489d-843f-499b3267684e"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling Instances",
      "item": [
        {
          "id": "98d4d4f6-8e11-441f-97ce-d5b503fc18c0",
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
              "id": "2443eb4c-c5a3-4c7c-b49e-7d95e64ee192"
            }
          ]
        }
      ]
    },
    {
      "name": "Auto Scaling Notifications",
      "item": [
        {
          "id": "f3bcb9ef-c817-405d-8643-4e2d3ade81b6",
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
              "id": "3c328b71-02a6-4b68-8ce5-a2b511fa24c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Metric Collection",
      "item": [
        {
          "id": "7381a3e2-5595-495f-9478-b3467ae1c0b1",
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
              "id": "6d64491b-ea3e-465d-b9b3-f5da18b71593"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Activities",
      "item": [
        {
          "id": "62f078ee-3285-4c93-8707-1256436850e2",
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
              "id": "dac4e874-b57b-43c9-86f9-2c90713833a2"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Process",
      "item": [
        {
          "id": "9f6b1039-2fe5-4683-bf9f-cceceee4bac5",
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
              "id": "7b2fbdc1-43ab-42e6-b087-4540934fca4a"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Actions",
      "item": [
        {
          "id": "904103b9-5ac4-4694-ba1d-9b49f23e00ab",
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
              "id": "3373cc18-6888-41c3-a0d6-5cd4b0e2b3b5"
            }
          ]
        }
      ]
    },
    {
      "name": "Termination Policies",
      "item": [
        {
          "id": "ef8d150d-3935-45ad-b071-e2521dcda3f4",
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
              "id": "a0fd7078-6c6f-4377-bc58-7ccf4eb4d127"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instances",
      "item": [
        {
          "id": "228576c8-eeeb-440f-8754-17c1e134eee7",
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
              "id": "2daf36af-15e1-4571-827f-846a87135a97"
            }
          ]
        }
      ]
    },
    {
      "name": "Metrics Collection",
      "item": [
        {
          "id": "29caf7b7-3177-4243-af36-5eaf3d7de4fc",
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
              "id": "4992704a-a03e-41f5-bf38-5dbbb4e4b09f"
            }
          ]
        },
        {
          "id": "af88899c-e97e-4094-8c3d-9466f5f737ad",
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
              "id": "a1e72213-4928-423d-be51-481d8defc7a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Stand By",
      "item": [
        {
          "id": "4a95f668-95c0-4a6c-a40c-597232bf868c",
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
              "id": "b2f3a9eb-3f6f-43dc-a58f-7ea41469bb5c"
            }
          ]
        },
        {
          "id": "73df4522-7dfa-4798-b777-f5b2f849d2f8",
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
              "id": "d16d9b14-290e-4872-9c12-a27772e5674e"
            }
          ]
        }
      ]
    },
    {
      "name": "Scaling Policy",
      "item": [
        {
          "id": "2c98b4cc-73b5-49bf-bbee-79d9c84344b3",
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
              "id": "acc7199f-975e-4659-8f0b-25253736a2df"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Update",
      "item": [
        {
          "id": "8f934eef-cf7f-4b34-9119-e359ed7be1cf",
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
              "id": "420e3086-2279-4da1-9bab-8f6c04171b75"
            }
          ]
        }
      ]
    },
    {
      "name": "Processes",
      "item": [
        {
          "id": "6c5f7a4a-3c98-45a0-9cca-98020191e206",
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
              "id": "55c88faa-81c4-456a-85aa-9e7f08fb7108"
            }
          ]
        }
      ]
    },
    {
      "name": "Desired Capacity",
      "item": [
        {
          "id": "534401e5-4d19-4534-b23b-83d7f7cdf2d3",
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
              "id": "b9a86654-5eb2-459c-ae46-85f0dc907e71"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance Health",
      "item": [
        {
          "id": "5be9f667-9ecc-443f-a8a8-717b4f006429",
          "name": "setInstanceHealth",
          "request": {
            "url": "http://example.com/api/?Action=SetInstanceHealth?HealthStatus=HealthStatus&InstanceId=InstanceId&ShouldRespectGracePeriod=ShouldRespectGracePeriod",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the health status of the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a239c981-2bfb-4bc6-bbca-1b82ec2dac51"
            }
          ]
        }
      ]
    }
  ]
}