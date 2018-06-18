---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Calendars
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph List Calendars
  x-api-slug: microsoft-graph
  description: List calendars Retrieve a list of calendars belonging to a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroup/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/mecalendargroupcalendars-get-openapi.md
- name: Microsoft Graph List Calendars
  x-api-slug: microsoft-graph
  description: List calendars Retrieve a list of calendars belonging to a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroup/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendars-get-openapi.md
- name: Microsoft Graph List Calendars
  x-api-slug: microsoft-graph
  description: List calendars Retrieve a list of calendars belonging to a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendarGroups/{id}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/mecalendargroupsidcalendars-get-openapi.md
- name: Microsoft Graph List Calendars
  x-api-slug: microsoft-graph
  description: List calendars Retrieve a list of calendars belonging to a calendar
    group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{id}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendars-get-openapi.md
- name: Microsoft Graph List Calendars
  x-api-slug: microsoft-graph
  description: List calendars Get all the user's calendars (/calendars navigation
    property), get the calendars from the default calendar group or from a specific
    calendar group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/usersid--userprincipalnamecalendars-get-openapi.md
- name: Microsoft Graph List Calendars
  x-api-slug: microsoft-graph
  description: List calendars Get all the user's calendars (/calendars navigation
    property), get the calendars from the default calendar group or from a specific
    calendar group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{calendar_group_id}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/mecalendargroupscalendar-group-idcalendars-get-openapi.md
- name: Microsoft Graph List Calendars
  x-api-slug: microsoft-graph
  description: List calendars Get all the user's calendars (/calendars navigation
    property), get the calendars from the default calendar group or from a specific
    calendar group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendarGroups/{calendar_group_id}/calendars
  tags: List, Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupscalendar-group-idcalendars-get-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---