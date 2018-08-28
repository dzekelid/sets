---
name: AWS CloudFormation
x-slug: aws-cloudformation
description: AWS CloudFormation gives developers and systems administrators an easy
  way to create and manage a collection of related AWS resources, provisioning and
  updating them in an orderly and predictable fashion.You can use AWS CloudFormations?sample
  templates?or create your own templates to describe the AWS resources, and any associated
  dependencies or runtime parameters, required to run your application. You do not
  need to figure out the order for provisioning AWS services or the subtleties of
  making those dependencies work. CloudFormation takes care of this for you. After
  the AWS resources are deployed, you can modify and update them in a controlled and
  predictable way, in effect applying version control to your AWS infrastructure the
  same way you do with your software. You can also visualize your templates as diagrams
  and edit them using a drag-and-drop interface with the?AWS CloudFormation Designer.You
  can deploy and update a template and its associated collection of resources (called
  a stack) by using the AWS Management Console, AWS Command Line Interface, or APIs.
  CloudFormation is available at no additional charge, and you pay only for the AWS
  resources needed to run your applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Sets
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-cloudformation/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CloudFormation API - List Change Sets
  x-api-slug: actionlistchangesets-get
  description: Returns the ID and status of each active change set for a stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-cloudformation/actionlistchangesets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-cloudformation/actionlistchangesets-get-openapi.md
- name: AWS CloudFormation API - Set Stack Policy
  x-api-slug: actionsetstackpolicy-get
  description: Sets a stack policy for a specified stack.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSCloudFormation.png
  humanURL: https://aws.amazon.com/cloudformation/
  baseURL: :///
  tags: Amazon Web Services, Management, Cloud, Stack Network, API Service Provider,
    API Service Provider, API Provider, Deployments, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-cloudformation/actionsetstackpolicy-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.certificate.manager.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.cloudformation.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/cloudformation/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/cloudformation/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/cloudformation/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/cloudformation/pricing/
- type: x-sdk
  url: https://aws.amazon.com/cloudformation/aws-cloudformation-templates/
- type: x-website
  url: https://aws.amazon.com/cloudformation/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---