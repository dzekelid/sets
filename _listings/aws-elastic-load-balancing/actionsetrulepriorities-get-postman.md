{
  "info": {
    "name": "AWS Elastic Load Balancing API Set Rule Priorities",
    "_postman_id": "89ea894c-c19e-4c1e-a731-a664885fc104",
    "description": "Sets the priorities of the specified rules.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tags",
      "item": [
        {
          "id": "f03d972a-daed-42f7-a1bf-3f8524a8c76c",
          "name": "addTags",
          "request": {
            "url": "http://example.com/api/?Action=AddTags?ResourceArns.member.N=ResourceArns.member.N&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified tags to the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5af43f3-a00c-4bae-aa10-ce0336a6924f"
            }
          ]
        },
        {
          "id": "2637ad9b-ae4e-49c9-890c-77acaf207bfa",
          "name": "describeTags",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTags?ResourceArns.member.N=ResourceArns.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the tags for the specified resources."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84ec5ec4-cc76-4507-bb20-5f80a02fa5a3"
            }
          ]
        },
        {
          "id": "c79a69fd-a622-4d6e-b29d-eb5d57bf1bee",
          "name": "removeTags",
          "request": {
            "url": "http://example.com/api/?Action=RemoveTags?ResourceArns.member.N=ResourceArns.member.N&TagKeys.member.N=TagKeys.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified tags from the specified resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d5a93bb-22a3-4712-bae6-58466a1b1238"
            }
          ]
        }
      ]
    },
    {
      "name": "Listeners",
      "item": [
        {
          "id": "4232f83d-2253-416d-9dfd-de1d169a16a0",
          "name": "createListener",
          "request": {
            "url": "http://example.com/api/?Action=CreateListener?Certificates.member.N=Certificates.member.N&DefaultActions.member.N=DefaultActions.member.N&LoadBalancerArn=LoadBalancerArn&Port=Port&Protocol=Protocol&SslPolicy=SslPolicy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a listener for the specified Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50672d03-5e9a-4d68-ae73-07bf43379d51"
            }
          ]
        },
        {
          "id": "517aedc4-c5fe-4cd2-98ad-21615385e9bf",
          "name": "deleteListener",
          "request": {
            "url": "http://example.com/api/?Action=DeleteListener?ListenerArn=ListenerArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90c316ee-f104-43a2-bda7-fffe434dd2c0"
            }
          ]
        },
        {
          "id": "7ba4d447-1235-4260-b781-792811c4d7e5",
          "name": "describeListeners",
          "request": {
            "url": "http://example.com/api/?Action=DescribeListeners?ListenerArns.member.N=ListenerArns.member.N&LoadBalancerArn=LoadBalancerArn&Marker=Marker&PageSize=PageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified listeners or the listeners for the specified Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "168c8e60-b6a8-41f7-a7cc-fe9cd20a5b2b"
            }
          ]
        },
        {
          "id": "d4a2b615-15b7-47f4-bb8a-fe856a955ee4",
          "name": "modifyListener",
          "request": {
            "url": "http://example.com/api/?Action=ModifyListener?Certificates.member.N=Certificates.member.N&DefaultActions.member.N=DefaultActions.member.N&ListenerArn=ListenerArn&Port=Port&Protocol=Protocol&SslPolicy=SslPolicy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified properties of the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25c85eb2-562a-450d-bfe8-00d31647db9f"
            }
          ]
        }
      ]
    },
    {
      "name": "Load Balancers",
      "item": [
        {
          "id": "3fbd19e7-5df2-45b8-ae6b-aaf4a95b0e88",
          "name": "createLoadBalancer",
          "request": {
            "url": "http://example.com/api/?Action=CreateLoadBalancer?Name=Name&Scheme=Scheme&SecurityGroups.member.N=SecurityGroups.member.N&Subnets.member.N=Subnets.member.N&Tags.member.N=Tags.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2272879-9be3-41b9-b1bc-9fb28629e834"
            }
          ]
        },
        {
          "id": "2ed3bb2c-2d93-4857-84df-807f1875c057",
          "name": "deleteLoadBalancer",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLoadBalancer?LoadBalancerArn=LoadBalancerArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Application Load Balancer and its attached listeners."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8cae4d9-d768-402c-9931-fd7434bfd530"
            }
          ]
        },
        {
          "id": "17eaa2e0-e602-409e-91fe-e4f8641f67f9",
          "name": "describeLoadBalancerAttributes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLoadBalancerAttributes?LoadBalancerArn=LoadBalancerArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the attributes for the specified Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2405532-1aa9-4958-ae3c-7a07e59770fa"
            }
          ]
        },
        {
          "id": "d353453c-1af1-4da9-bae9-37dabce684df",
          "name": "describeLoadBalancers",
          "request": {
            "url": "http://example.com/api/?Action=DescribeLoadBalancers?LoadBalancerArns.member.N=LoadBalancerArns.member.N&Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified Application Load Balancers or all of your Application Load Balancers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a1f3176-9800-402a-a89d-31b33662a641"
            }
          ]
        },
        {
          "id": "9ada63d0-d39f-47ad-a9e0-3a8268f1cab0",
          "name": "modifyLoadBalancerAttributes",
          "request": {
            "url": "http://example.com/api/?Action=ModifyLoadBalancerAttributes?Attributes.member.N=Attributes.member.N&LoadBalancerArn=LoadBalancerArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attributes of the specified Application Load Balancer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e5a3054-c69b-40ca-93be-3f4df6971938"
            }
          ]
        }
      ]
    },
    {
      "name": "Rules",
      "item": [
        {
          "id": "69992a4a-853d-4f2f-9bed-e79df15d70d2",
          "name": "createRule",
          "request": {
            "url": "http://example.com/api/?Action=CreateRule?Actions.member.N=Actions.member.N&Conditions.member.N=Conditions.member.N&ListenerArn=ListenerArn&Priority=Priority",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a rule for the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1381fec9-9f00-4eea-bdf0-6be27fdde19b"
            }
          ]
        },
        {
          "id": "b945582d-13a8-4940-a4f2-0bcc558777e3",
          "name": "deleteRule",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRule?RuleArn=RuleArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae720ed1-6284-4bf7-9008-e304115d0920"
            }
          ]
        },
        {
          "id": "513c9469-72b6-4d1d-8495-ecdc619f9a3b",
          "name": "describeRules",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRules?ListenerArn=ListenerArn&RuleArns.member.N=RuleArns.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified rules or the rules for the specified listener."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61c4e283-9cf7-4af6-91c2-a039b323068c"
            }
          ]
        },
        {
          "id": "d4fd40f1-3011-4086-a8ff-9d5eaf105385",
          "name": "modifyRule",
          "request": {
            "url": "http://example.com/api/?Action=ModifyRule?Actions.member.N=Actions.member.N&Conditions.member.N=Conditions.member.N&RuleArn=RuleArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified rule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6068676b-541e-48c8-9e2f-46fe756347a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Target Groups",
      "item": [
        {
          "id": "1c261b27-ccee-408f-b855-a4faa2a1cde3",
          "name": "createTargetGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateTargetGroup?HealthCheckIntervalSeconds=HealthCheckIntervalSeconds&HealthCheckPath=HealthCheckPath&HealthCheckPort=HealthCheckPort&HealthCheckProtocol=HealthCheckProtocol&HealthCheckTimeoutSeconds=HealthCheckTimeoutSeconds&HealthyThresholdCount=HealthyThresholdCount&Matcher=Matcher&Name=Name&Port=Port&Protocol=Protocol&UnhealthyThresholdCount=UnhealthyThresholdCount&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf8b0f3f-ba4d-4d69-a1e8-656f57945bd2"
            }
          ]
        },
        {
          "id": "d72db42f-c36f-4962-854e-6f16faf91322",
          "name": "deleteTargetGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTargetGroup?TargetGroupArn=TargetGroupArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96559265-5e6a-4b94-8ccc-47c4c96c3af1"
            }
          ]
        },
        {
          "id": "899b027f-d2a3-4c57-a783-25d3b3780bcf",
          "name": "describeTargetGroupAttributes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTargetGroupAttributes?TargetGroupArn=TargetGroupArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the attributes for the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e76981b6-2bf6-430d-93ae-2dcddcc2bab5"
            }
          ]
        },
        {
          "id": "e67fef83-a193-4c10-a67e-1a5791053456",
          "name": "describeTargetGroups",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTargetGroups?LoadBalancerArn=LoadBalancerArn&Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize&TargetGroupArns.member.N=TargetGroupArns.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified target groups or all of your target groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28b71109-12aa-4f2b-8436-995190eef169"
            }
          ]
        },
        {
          "id": "d193a128-a0d1-40f1-8799-b35bcbe8264a",
          "name": "modifyTargetGroup",
          "request": {
            "url": "http://example.com/api/?Action=ModifyTargetGroup?HealthCheckIntervalSeconds=HealthCheckIntervalSeconds&HealthCheckPath=HealthCheckPath&HealthCheckPort=HealthCheckPort&HealthCheckProtocol=HealthCheckProtocol&HealthCheckTimeoutSeconds=HealthCheckTimeoutSeconds&HealthyThresholdCount=HealthyThresholdCount&Matcher=Matcher&TargetGroupArn=TargetGroupArn&UnhealthyThresholdCount=UnhealthyThresholdCount",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the health checks used when evaluating the health state of the targets in the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d170125b-3649-4efb-9a43-afd71d550b69"
            }
          ]
        },
        {
          "id": "4fc05b0d-f1c8-449f-ba04-1f56d9d16197",
          "name": "modifyTargetGroupAttributes",
          "request": {
            "url": "http://example.com/api/?Action=ModifyTargetGroupAttributes?Attributes.member.N=Attributes.member.N&TargetGroupArn=TargetGroupArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attributes of the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e80b298-4dab-46cc-96b9-d7e807ffef70"
            }
          ]
        }
      ]
    },
    {
      "name": "Targets",
      "item": [
        {
          "id": "ad5216b4-b8a9-46df-8b72-48f9ea092868",
          "name": "deregisterTargets",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterTargets?TargetGroupArn=TargetGroupArn&Targets.member.N=Targets.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters the specified targets from the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "56c63f72-400f-4e86-8622-949d76eddbdc"
            }
          ]
        },
        {
          "id": "c95fc9c4-914d-4b51-b56f-5cc702198e4e",
          "name": "registerTargets",
          "request": {
            "url": "http://example.com/api/?Action=RegisterTargets?TargetGroupArn=TargetGroupArn&Targets.member.N=Targets.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers the specified targets with the specified target group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8fadff4-6017-4dd2-b04a-aa8f369b506b"
            }
          ]
        }
      ]
    },
    {
      "name": "SSL Policies",
      "item": [
        {
          "id": "31888f27-dae0-435b-ad74-033fb4f42f42",
          "name": "describeSSLPolicies",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSSLPolicies?Marker=Marker&Names.member.N=Names.member.N&PageSize=PageSize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified policies or all policies used for SSL negotiation."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8136bde-05b8-4c55-85fd-3591e7c575a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Target Health",
      "item": [
        {
          "id": "2b3764f9-acc2-4581-aa0b-264e3d09bdf4",
          "name": "describeTargetHealth",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTargetHealth?TargetGroupArn=TargetGroupArn&Targets.member.N=Targets.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the health of the specified targets or all of your targets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "883b85d5-6293-4602-8ed4-1f5d1fee5b6c"
            }
          ]
        }
      ]
    },
    {
      "name": "Rule Priorities",
      "item": [
        {
          "id": "6c274c47-94f5-406d-932a-ccb56969a733",
          "name": "setRulePriorities",
          "request": {
            "url": "http://example.com/api/?Action=SetRulePriorities?RulePriorities.member.N=RulePriorities.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the priorities of the specified rules."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfd71446-6af3-4d7c-b191-48c9988d9e11"
            }
          ]
        }
      ]
    }
  ]
}