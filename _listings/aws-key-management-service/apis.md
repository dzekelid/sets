---
name: AWS Key Management Service
x-slug: aws-key-management-service
description: AWS Key Management Service (KMS) is a managed service that makes it easy
  for you to create and control the encryption keys used to encrypt your data, and
  uses Hardware Security Modules (HSMs) to protect the security of your keys. AWS
  Key Management Service is integrated with several other AWS services to help you
  protect the data you store with these services. AWS Key Management Service is also
  integrated with AWS CloudTrail to provide you with logs of all key usage to help
  meet your regulatory and compliance needs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
x-kinRank: "10"
x-alexaRank: "0"
tags: Sets
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-key-management-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Key Management Service API - Disable Key
  x-api-slug: actiondisablekey-get
  description: |-
    Sets the state of a customer master key (CMK) to disabled, thereby preventing its use
          for cryptographic operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: :///
  tags: Amazon Web Services, Encryption, Security, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/aws-key-management-service/actiondisablekey-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.internet.of.things.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.key.management.service.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/kms/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/kms/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/kms/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/kms/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/kms/pricing/
- type: x-website
  url: https://aws.amazon.com/kms/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---