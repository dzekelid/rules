---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Rules
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-get
  description: "Returns the extension answering rules.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n403\nCMN-408\nIn order to call this
    API endpoint, user needs to have [ReadUserAnsweringRules] permission for requested
    resource.\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringrule-post
  description: "Creates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-101\nParameter [forwarding.rules[].forwardingNumbers[].id]
    are duplicated\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-107\nMore
    than one caller with the same [callerId]\n\n\n400\nAWR-108\nOnly custom rule can
    be created\n\n\n400\nAWR-111\nAt least one condition should be specified\n\n\n400\nAWR-113\nMore
    than one called number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-123\nPreset [131840] can not
    be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId specified for
    greeting type [Voicemail] is not found\n\n\n400\nAWR-125\nCustom greeting presetId
    specified for greeting type [Introductory]. Custom greeting uploading method should
    be used\n\n\n400\nAWR-126\nThe amount of schedule ranges exceeds 1000\n\n\n400\nAWR-136\nRing
    group with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater
    than 0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-149\nOnly user, voicemail or shared
    line group extension can be a voicemail recipient\n\n\n400\nAWR-150\nOnly user,
    voicemail, shared line group extension or current department can be a voicemail
    recipient\n\n\n400\nAWR-152\nVoicemail cannot be turned off for call queue extension\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [name] value is invalid\n\n\n400\nFPN-105\nNumber
    +16196093249 duplicates with company/extension direct number\n\n\n400\nFPN-108\nInternational
    calling is currently disabled\n\n\n403\nCMN-401\nIn order to call this API endpoint,
    application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn order
    to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get
  description: "Returns an answering rule by ID.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nLight\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [showInactiveNumbers] value is invalid\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [answering-rule] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Custom Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
  description: "Updates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt
    least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
    number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After
    Hours schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
    [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
    specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing group
    with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater than
    0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction] value
    is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
    direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditExtensions] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete
  description: "Deletes a custom answering rule by a particular ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nAWR-110\nBusiness
    Hours/After Hours rule cannot be deleted\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [answering-rule]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete
  description: "Deletes a custom answering rule by a particular ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nAWR-110\nBusiness
    Hours/After Hours rule cannot be deleted\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [answering-rule]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Delete Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete
  description: "Deletes a custom answering rule by a particular ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n403\nAWR-110\nBusiness
    Hours/After Hours rule cannot be deleted\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [EditExtensions] permission\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [EditUserAnsweringRules] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [answering-rule]
    is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-delete-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Custom Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
  description: "Updates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt
    least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
    number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After
    Hours schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
    [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
    specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing group
    with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater than
    0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction] value
    is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
    direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditExtensions] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Custom Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put
  description: "Updates a custom answering rule for a particular caller ID.\nApp Permission\nEditExtensions\nUser
    Permission\nEditUserAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-100\nRule
    indexes should be sequential\n\n\n400\nAWR-106\nGreeting [Voicemail] is duplicated\n\n\n400\nAWR-111\nAt
    least one condition should be specified\n\n\n400\nAWR-113\nMore than one called
    number with the same [calledNumbers.phoneNumber]\n\n\n400\nAWR-120\nBusiness Hours/After
    Hours schedule condition is allowed only with other answering rule conditions\n\n\n400\nAWR-123\nPreset
    [131840] can not be used for greeting type [Voicemail]\n\n\n400\nAWR-124\npresetId
    specified for greeting type [Voicemail] is not found\n\n\n400\nAWR-136\nRing group
    with index 1 is not found\n\n\n400\nAWR-137\nRule index should be greater than
    0\n\n\n400\nAWR-138\nContact center number cannot be used as called number\n\n\n400\nAWR-139\nHold
    audio interruption period not specified\n\n\n400\nAWR-140\nHold audio interruption
    period should be empty for interruption mode specified\n\n\n400\nAWR-144\nCall
    Queue agent with index 1 is not found\n\n\n400\nAWR-147\nPreset [65792] can not
    be used for extension type [Department]\n\n\n400\nAWR-148\nCall Queue agents should
    be the same as call queue members\n\n\n400\nAWR-179\n[name] is too long: up to
    127 symbols supported\n\n\n400\nCMN-101\nParameter [callHandlingAction] value
    is invalid\n\n\n400\nFPN-105\nNumber +18332051179 duplicates with company/extension
    direct number\n\n\n400\nFPN-108\nInternational calling is currently disabled\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [EditExtensions] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get
  description: "Returns an answering rule by ID.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nLight\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [showInactiveNumbers] value is invalid\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [answering-rule] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get
  description: "Returns an answering rule by ID.\nApp Permission\nReadAccounts\nUser
    Permission\nReadUserAnsweringRules\nUsage Plan Group\nLight\nError Codes\n\n \n
    \ \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [showInactiveNumbers] value is invalid\n\n\n403\nCMN-401\nIn order to call this
    API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [answering-rule] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/rules/master/_listings/ringcentral/restapiv1-0accountaccountidextensionextensionidansweringruleruleid-get-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---