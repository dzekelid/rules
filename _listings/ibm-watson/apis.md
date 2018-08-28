---
name: IBM Watson
x-slug: ibm-watson
description: Meet IBM Watson, a cognitive system that enables a new partnership between
  people and computers that enhances and scales human expertise. Watson has been learning
  the language of professions and is trained by experts to work across many different
  industries.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Rules
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ibm-watson/apis.md
specificationVersion: "0.14"
apis:
- name: IBM Watson IoT Platform HTTP REST API - Query active rules
  x-api-slug: logicalinterfaceslogicalinterfaceidrules-get
  description: |-
    Rules allow you to specify conditions that can be used to trigger
    actions. For example, you might create a rule that sends an email if
    the temperature of a device exceeds a certain value.

    Rules are defined against a specific logical interface schema.  At
    runtime, a rule will be evaluated whenever the state for a Device that
    exposes the logical interface changes.

    The **/logicalinterfaces/{logicalInterfaceId}/rules** endpoint returns
    the list of all of the active rules that have been associated with the
    logical interface. Various query parameters can be used to filter, sort
    and page through the list of rules that are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceidrules-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active rule
  x-api-slug: logicalinterfaceslogicalinterfaceidrulesruleid-get
  description: |-
    Retrieve the active rule with the specified id that has been associated
    with the specified logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceidrulesruleid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query draft rules
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrules-get
  description: |-
    Rules allow you to specify conditions that can be used to trigger
    actions. For example, you might create a rule that sends an email if
    the temperature of a device exceeds a certain value.

    Rules are defined against a specific logical interface schema.  At
    runtime, a rule will be evaluated whenever the state for a Device that
    exposes the logical interface changes.

    The **/draft/logicalinterfaces/{logicalInterfaceId}/rules** endpoint
    returns the list of all of the draft rules that have been associated
    with the logical interface. Various query parameters can be used to
    filter, sort and page through the list of rules that are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrules-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrules-post
  description: |-
    Creates a new draft rule that is associated with the logical interface
    for the organization in the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrules-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-get
  description: |-
    Retrieve the draft rule with the specified id that has been associated
    with the specified logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-put
  description: "Updates the draft rule with the specified id. The following properties\ncan
    be updated: \n\n  - name\n  - description\n  - condition\n\nNote that if the description
    field is omitted from the body of the\nupdate, then any existing description will
    be removed from the rule.\n  \nAny changes made to the values of the following
    properties will be\nignored:\n\n  - created\n  - createdBy\n  - updated\n  - updatedBy\n
    \ - refs\n  \nThe values of these properties are set on the server as a result
    of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-delete
  description: |-
    Deletes the draft rule with the specified id from the organization in
    the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-delete-openapi.md
x-common:
- type: x-api-gallery
  url: http://ibm.financial.crimes.insight.for.insurance.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ibm.watson.stack.network
- type: x-application-gallery
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/gallery.html
- type: x-blog
  url: https://developer.ibm.com/watson/blog/
- type: x-blog-rss
  url: https://developer.ibm.com/watson/feed/
- type: x-developer
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/
- type: x-developer
  url: https://developer.ibm.com/watson/
- type: x-documentation
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/apis/
- type: x-forum
  url: https://developer.ibm.com/answers/smartspace/watson/
- type: x-getting-started
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/getstarted.html
- type: x-github
  url: https://github.com/IBM-Watson
- type: x-partners
  url: http://www.ibm.com/smarterplanet/us/en/ibmwatson/ecosystem.html
- type: x-privacy
  url: http://www.ibm.com/privacy/us/en/?lnk=flg-priv-usen
- type: x-terms-of-service
  url: http://www.ibm.com/legal/us/en/?lnk=flg-tous-usen
- type: x-twitter
  url: https://twitter.com/IBMWatson
- type: x-videos
  url: http://www.ibm.com/smarterplanet/us/en/ibmwatson/
- type: x-website
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
- type: x-white-papers
  url: https://developer.ibm.com/watson/docs/whitepapers/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---