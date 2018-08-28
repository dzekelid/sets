swagger: "2.0"
x-collection-name: AWS Auto Scaling
x-complete: 1
info:
  title: AWS Auto Scaling API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetDesiredCapacity:
    get:
      summary: Set Desired Capacity
      description: Sets the size of the specified Auto Scaling group.
      operationId: setDesiredCapacity
      x-api-path-slug: actionsetdesiredcapacity-get
      parameters:
      - in: query
        name: AutoScalingGroupName
        description: The name of the Auto Scaling group
        type: string
      - in: query
        name: DesiredCapacity
        description: The number of EC2 instances that should be running in the Auto
          Scaling group
        type: string
      - in: query
        name: HonorCooldown
        description: By default, SetDesiredCapacity overrides any cooldown period
          associated with the Auto Scaling group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Desired Capacity
  /?Action=SetInstanceHealth:
    get:
      summary: Set Instance Health
      description: Sets the health status of the specified instance.
      operationId: setInstanceHealth
      x-api-path-slug: actionsetinstancehealth-get
      parameters:
      - in: query
        name: HealthStatus
        description: The health status of the instance
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: ShouldRespectGracePeriod
        description: If the Auto Scaling group of the specified instance has a HealthCheckGracePeriod             specified
          for the group, by default, this call will respect the grace period
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instance Health