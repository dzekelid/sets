---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Sets
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: Jira Cloud REST API - Set comment property
  x-api-slug: api2commentcommentidpropertiespropertykey-put
  description: |-
    Sets the value of the specified comment's property.

    You can use this resource to store a custom data against the comment identified by the key or by the id. The user who stores the data is required to have permissions to administer the comment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2commentcommentidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2commentcommentidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Set time tracking settings
  x-api-slug: api2configurationtimetrackingoptions-put
  description: "Sets the time tracking settings.  \n  \n**[Permissions](https://developer.atlassian.com/cloud/jira/platform/rest/#permissions)
    required:** Jira administration (that is, member of the _administrators_ [group](https://confluence.atlassian.com/x/24xjL))."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2configurationtimetrackingoptions-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2configurationtimetrackingoptions-put-openapi.md
- name: Jira Cloud REST API - Set dashboard item property
  x-api-slug: api2dashboarddashboardiditemsitemidpropertiespropertykey-put
  description: "Sets the value of a dashboard item property. Use this resource in
    apps to store custom data against a dashboard item.  \n  \nA dashboard item enables
    an app to add user-specific information to a user dashboard. Dashboard items are
    exposed to users as gadgets that users can add to their dashboards. For more information
    on how users do this, see [Adding and customizing gadgets](https://confluence.atlassian.com/x/7AeiLQ).
    \ \n  \nWhen an app creates a dashboard item it registers a callback to receive
    the dashboard item ID. The callback fires whenever the item is rendered or, where
    the item is configurable, the user edits the item. The app then uses this resource
    to store the item's content or configuration details. For more information on
    working with dashboard items, see [Building a dashboard item for a JIRA Connect
    add-on](https://developer.atlassian.com/server/jira/platform/guide-building-a-dashboard-item-for-a-jira-connect-add-on-33746254/)
    and the [Dashboard Item](https://developer.atlassian.com/cloud/jira/platform/modules/dashboard-item/)
    documentation.  \n  \nThere is no resource to set or get dashboard items.  \n
    \ \n**[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission
    to access Jira. However, to set a dashboard item property the user must be the
    owner of the dashboard. Note, users with the _Administer Jira_ [global permission](href=)
    are considered owners of the System dashboard.  \n  \nThe value of the request
    body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob.
    The maximum length is 32768 bytes."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2dashboarddashboardiditemsitemidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2dashboarddashboardiditemsitemidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Set default share scope
  x-api-slug: api2filterdefaultsharescope-put
  description: Sets the default sharing for new filters and dashboards for a user.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission
    to log in to Jira (i.e., member of the _users_ [group](https://confluence.atlassian.com/x/24xjL)).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2filterdefaultsharescope-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2filterdefaultsharescope-put-openapi.md
- name: Jira Cloud REST API - Set columns
  x-api-slug: api2filteridcolumns-put
  description: Sets the columns for a filter. Only navigable fields can be set as
    columns. Use [Get fields](https://developer.atlassian.com/cloud/jira/platform/rest#api-api-2-field-get)
    to get the list fields in Jira. A navigable field has `navigable` set to `true`.
    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission
    to log in to Jira (i.e., member of the _users_ [group](https://confluence.atlassian.com/x/24xjL))
    and permission to view the filter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2filteridcolumns-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2filteridcolumns-put-openapi.md
- name: Jira Cloud REST API - Set issue property
  x-api-slug: api2issueissueidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the specified issue's property.

    You can use this resource to store a custom data against the issue identified by the key or by the id. The user who stores the data is required to have permissions to edit the issue.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2issueissueidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Update remote issue link
  x-api-slug: api2issueissueidorkeyremotelinklinkid-put
  description: Updates a remote issue link from a JSON representation. Sets all fields
    without values provided to null.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2issueissueidorkeyremotelinklinkid-put-openapi.md
- name: Jira Cloud REST API - Set worklog property
  x-api-slug: api2issueissueidorkeyworklogworklogidpropertiespropertykey-put
  description: |-
    Sets the value of the specified worklog's property.

    You can use this resource to store a custom data against the worklog identified by the key or by the id. The user who stores the data is required to have permissions to administer the worklog.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2issueissueidorkeyworklogworklogidpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2issueissueidorkeyworklogworklogidpropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Set preference
  x-api-slug: api2mypreferences-put
  description: Sets preference of the currently logged in user. Preference key must
    be provided as input parameters (key). Value must be provided as POST body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2mypreferences-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2mypreferences-put-openapi.md
- name: Jira Cloud REST API - Set locale
  x-api-slug: api2mypreferenceslocale-put
  description: Sets the locale of the currently logged in user. Locale JSON must be
    provided as PUT body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2mypreferenceslocale-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2mypreferenceslocale-put-openapi.md
- name: Jira Cloud REST API - Set project property
  x-api-slug: api2projectprojectidorkeypropertiespropertykey-put
  description: |-
    Sets the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). You can use project properties to store custom data against the project.

    The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 bytes.

    **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** _Administer Jira_ [global permission](https://confluence.atlassian.com/x/x4dKLg) or _Administer Projects_ [project permission](https://confluence.atlassian.com/x/yodKLg).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2projectprojectidorkeypropertiespropertykey-put-openapi.md
- name: Jira Cloud REST API - Set base url
  x-api-slug: api2settingsbaseurl-put
  description: Sets the base URL that is configured for this Jira instance.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2settingsbaseurl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2settingsbaseurl-put-openapi.md
- name: Jira Cloud REST API - Set issue navigator default columns
  x-api-slug: api2settingscolumns-put
  description: Sets the default system columns for issue navigator. Admin permission
    will be required.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2settingscolumns-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2settingscolumns-put-openapi.md
- name: Jira Cloud REST API - Set user default columns
  x-api-slug: api2usercolumns-put
  description: |-
    Sets the default [issue table columns](https://confluence.atlassian.com/x/XYdKLg) for the user. If a username is not passed, the calling user's default columns are set. If no column details are sent, then all default columns are removed. The parameters for this resource are expressed as HTML form data. For example, in curl: `curl -X PUT -d username= -d columns=summary -d columns=description ` **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   To set the columns on any user: _Administer Jira_ [global permission](https://confluence.atlassian.com/adminjiracloud/managing-global-permissions-776636359.html).
    *   To set the calling user's columns: None
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2usercolumns-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2usercolumns-put-openapi.md
- name: Jira Cloud REST API - Set user property
  x-api-slug: api2userpropertiespropertykey-put
  description: |-
    Sets the value of a user's property. Use this resource to store custom data against a user. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:**

    *   To set a property on any user: _Administer Jira_ [global permission](https://confluence.atlassian.com/adminjiracloud/managing-global-permissions-776636359.html).
    *   To set a property on the calling user's record: None

    Note: These user properties are unrelated to the [Jira properties](https://confluence.atlassian.com/cloud/add-data-to-users-for-advanced-functions-jira-applications-only-744721649.html) that can be set through the UI.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2userpropertiespropertykey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sets/master/_listings/atlassian/api2userpropertiespropertykey-put-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---