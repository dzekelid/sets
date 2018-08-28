---
name: AWS Route 53
x-slug: aws-route-53
description: Amazon Route 53 is a highly available and scalable cloud Domain Name
  System (DNS) web service. It is designed to give developers and businesses an extremely
  reliable and cost effective way to route end users to Internet applications by translating
  names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers
  use to connect to each other. Amazon Route 53 is fully compliant with IPv6 as well.Amazon
  Route 53 effectively connects user requests to infrastructure running in AWS &ndash;
  such as Amazon EC2 instances, Elastic Load Balancing load balancers, or Amazon S3
  buckets &ndash; and can also be used to route users to infrastructure outside of
  AWS. You can use Amazon Route 53 to configure DNS health checks to route traffic
  to healthy endpoints or to independently monitor the health of your application
  and its endpoints. Amazon Route 53 Traffic Flow makes it easy for you to manage
  traffic globally through a variety of routing types, including Latency Based Routing,
  Geo DNS, and Weighted Round Robin&mdash;all of which can be combined with DNS Failover
  in order to enable a variety of low-latency, fault-tolerant architectures. Using
  Amazon Route 53 Traffic Flow&rsquo;s simple visual editor, you can easily manage
  how your end-users are routed to your application&rsquo;s endpoints&mdash;whether
  in a single AWS region or distributed around the globe. Amazon Route 53 also offers
  Domain Name Registration &ndash; you can purchase and manage domain names such as
  example.com and Amazon Route 53 will automatically configure DNS settings for your
  domains.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Sets
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-route-53/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Route 53 API - List Reusable Delegation Sets
  x-api-slug: 20130401delegationsetmarkermarkerampmaxitemsmaxitems-get
  description: To retrieve a list of your reusable delegation sets, send a GET request
    tothe /2013-04-01/delegationset resource. The response to this request includes
    aDelegationSets element with zero, one, or multiple DelegationSetchild elements.
    By default, the list of delegation sets is displayed on a single page. You cancontrol
    the length of the page that is displayed by using the MaxItems parameter.You can
    use the Marker parameter to control the delegation set that the listbegins with.
    Note Amazon Route 53 returns a maximum of 100 items. If you set MaxItems to a
    value greater than100, Amazon Route 53 returns only the first 100.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-route-53/20130401delegationsetmarkermarkerampmaxitemsmaxitems-get-openapi.md
- name: AWS Route 53 API - Create Health Check
  x-api-slug: 20130401healthcheck-post
  description: Creates a new health check.To create a new health check, send a POST
    request to the/2013-04-01/healthcheck resource. The request body must include
    a documentwith a CreateHealthCheckRequest element. The response returns theCreateHealthCheckResponse
    element, containing the health check ID specifiedwhen adding health check to a
    resource record set. For information about adding health checksto resource record
    sets, see ResourceRecordSet:HealthCheckId in ChangeResourceRecordSets. If you
    are registering EC2 instances with an Elastic Load Balancing (ELB) loadbalancer,
    do not create Amazon Route 53 health checks for the EC2 instances. When you register
    anEC2 instance with a load balancer, you configure settings for an ELB health
    check, whichperforms a similar function to an Amazon Route 53 health check.You
    can associate health checks with failover resource record sets in a private hostedzone.
    Note the following:Amazon Route 53 health checkers are outside the VPC. To check
    the health of an endpointwithin a VPC by IP address, you must assign a public
    IP address to the instance in theVPC.You can configure a health checker to check
    the health of an external resource thatthe instance relies on, such as a database
    server.You can create a CloudWatch metric, associate an alarm with the metric,
    and then create ahealth check that is based on the state of the alarm. For example,
    you might create a CloudWatchmetric that checks the status of the Amazon EC2 StatusCheckFailed
    metric, add analarm to the metric, and then create a health check that is based
    on the state of thealarm. For information about creating CloudWatch metrics and
    alarms by using the CloudWatch console,see the Amazon CloudWatch User Guide.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-route-53/20130401healthcheck-post-openapi.md
- name: AWS Route 53 API - Delete Hosted Zone
  x-api-slug: 20130401hostedzoneid-delete
  description: Deletes a hosted zone. Send a DELETE request to the /Amazon Route 53API
    version/hostedzone/hosted zone ID             resource.ImportantDelete a hosted
    zone only if there are no resource record sets other than the defaultSOA record
    and NS resource record sets. If the hosted zone contains other resource recordsets,
    delete them before deleting the hosted zone. If you try to delete a hosted zone
    thatcontains other resource record sets, Amazon Route 53 denies your request with
    aHostedZoneNotEmpty error. For information about deleting records from yourhosted
    zone, see ChangeResourceRecordSets.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-route-53/20130401hostedzoneid-delete-openapi.md
- name: AWS Route 53 API - List Resource Record Sets
  x-api-slug: 20130401hostedzoneidrrsetampidentifierstartrecordidentifierampmaxitemsmaxitemsnamestartrecordnameamptypestartrecordtype-get
  description: 'Lists the resource record sets in a specified hosted zone.            ListResourceRecordSets
    returns up to 100 resource record sets at a time in ASCII order, beginning at
    a position specified by the name and type elements. The action sorts results first
    by DNS name with the labels reversed, for example:            com.example.www.         Note
    the trailing dot, which can change the sort order in some circumstances.When multiple
    records have the same DNS name, the action sorts results by the record type.You
    can use the name and type elements to adjust the beginning position of the list
    of resource record sets returned:If you do not specify Name or TypeThe results
    begin with the first resource record set that the hosted zone contains.If you
    specify Name but not TypeThe results begin with the first resource record set
    in the list whose name is greater than or equal to Name.If you specify Type but
    not NameAmazon Route 53 returns the InvalidInput error.If you specify both Name
    and TypeThe results begin with the first resource record set in the list whose
    name is greater than or equal to Name, and whose type is greater than or equal
    to Type.This action returns the most current version of the records. This includes
    records that are PENDING, and that are not yet available on all Amazon Route 53
    DNS servers.To ensure that you get an accurate listing of the resource record
    sets for a hosted zone at a point in time, do not submit a ChangeResourceRecordSets
    request while you''re paging through the results of a ListResourceRecordSets request.
    If you do, some pages may display results without the latest changes while other
    pages display results with the latest changes.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-route-53/20130401hostedzoneidrrsetampidentifierstartrecordidentifierampmaxitemsmaxitemsnamestartrecordnameamptypestartrecordtype-get-openapi.md
- name: AWS Route 53 API - Change Resource Record Sets
  x-api-slug: 20130401hostedzoneidrrset-post
  description: 'Create, change, update, or delete authoritative DNS information on
    all Amazon Route 53 servers.Send a POST request to:             /2013-04-01/hostedzone/Amazon
    Route 53 hosted ZoneID/rrset resource. The request body must include a document
    with aChangeResourceRecordSetsRequest element. The request body contains a list
    ofchange items, known as a change batch. Change batches are considered transactional
    changes.When using the Amazon Route 53 API to change resource record sets, Amazon
    Route 53 either makes all or none of thechanges in a change batch request. This
    ensures that Amazon Route 53 never partially implements theintended changes to
    the resource record sets in a hosted zone. For example, a change batch request
    that deletes the CNAME record forwww.example.com and creates an alias resource
    record set for www.example.com. Amazon Route 53 deletesthe first resource record
    set and creates the second resource record set in a singleoperation. If either
    the DELETE or the CREATE action fails, thenboth changes (plus any other changes
    in the batch) fail, and the original CNAMErecord continues to exist.ImportantDue
    to the nature of transactional changes, you can''t delete the same resourcerecord
    set more than once in a single change batch. If you attempt to delete the same
    changebatch more than once, Amazon Route 53 returns an InvalidChangeBatch error.NoteTo
    create resource record sets for complex routing configurations, use either thetraffic
    flow visual editor in the Amazon Route 53 console or the API actions for traffic
    policies andtraffic policy instances. Save the configuration as a traffic policy,
    then associate thetraffic policy with one or more domain names (such as example.com)
    or subdomain names (suchas www.example.com), in the same hosted zone or in multiple
    hosted zones. You can roll backthe updates if the new configuration isn''t performing
    as expected. For more information, seeUsing Traffic Flow to Route DNSTraffic in
    the Amazon Route 53 Developer Guide.Use ChangeResourceRecordsSetsRequest to perform
    the following actions:                  CREATE: Creates a resource record set
    that has the specified values.                  DELETE: Deletes an existing resource
    record set that has the specified values.                  UPSERT: If a resource
    record set does not already exist, AWS createsit. If a resource set does exist,
    Amazon Route 53 updates it with the values in the request. The values that you
    need to include in the request depend on the type of resource record set that
    you''re creating, deleting, or updating:            Basic resource record sets
    (excluding alias, failover, geolocation, latency, and weighted resource record
    sets)                           Name                                 Type                                 TTL                           Failover,
    geolocation, latency, or weighted resource record sets (excluding alias resource
    record sets)                           Name                                 Type                                 TTL                                 SetIdentifier                           Alias
    resource record sets (including failover alias, geolocation alias, latency alias,
    and weighted alias resource record sets)                           Name                                 Type                                 AliasTarget
    (includes DNSName, EvaluateTargetHealth, and HostedZoneId)                  SetIdentifier
    (for failover, geolocation, latency, and weighted resource record sets)When you
    submit a ChangeResourceRecordSets request, Amazon Route 53 propagates your changes
    to all of the Amazon Route 53 authoritative DNS servers. While your changes are
    propagating, GetChange returns a status of PENDING. When propagation is complete,
    GetChange returns a status of INSYNC. Changes generally propagate to all Amazon
    Route 53 name servers in a few minutes. In rare circumstances, propagation can
    take up to 30 minutes. For more information, see GetChange       For information
    about the limits on a ChangeResourceRecordSets request, see Limits in the Amazon
    Route 53 Developer Guide.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Networking_AmazonRoute53.png
  humanURL: https://aws.amazon.com/route53/
  baseURL: :///
  tags: Amazon Web Services, DNS, API Service Provider, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-route-53/20130401hostedzoneidrrset-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.rekognition.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.route.53.stack.network
- type: x-documentation
  url: http://docs.aws.amazon.com/Route53/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/route53/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=87
- type: x-pricing
  url: https://aws.amazon.com/route53/pricing/
- type: x-registrar-policies
  url: https://aws.amazon.com/route53/amazon-registrar-policies/
- type: x-service-health
  url: http://status.aws.amazon.com/
- type: x-service-level-agreement
  url: https://aws.amazon.com/route53/sla
- type: x-sla
  url: https://aws.amazon.com/route53/sla/
- type: x-website
  url: https://aws.amazon.com/route53/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---