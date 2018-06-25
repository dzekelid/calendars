---
name: Microsoft Office 365
x-slug: microsoft-office-365
description: Integrate Office 365 REST APIs powered by Microsoft Graph into your own
  app to connect to files, calendars, mail and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Calendars
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Office 365 Get Calendar Groups Calendars
  x-api-slug: microsoft-office-365
  description: You can request all the user's calendars (or a filtered list...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}/Calendars
  tags: Calendargroups, Calendargroup, , Calendars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-get-openapi.md
- name: Microsoft Office 365 Add Calendar Groups Calendars
  x-api-slug: microsoft-office-365
  description: You can create a calendar by sending a POST request with a J...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}/Calendars
  tags: Calendargroups, Calendargroup, , Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-post-openapi.md
- name: Microsoft Office 365 Parameters Calendar Groups Calendars
  x-api-slug: microsoft-office-365
  description: Parameters calendargroups calendargroup  calendars
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}/Calendars
  tags: Calendargroups, Calendargroup, , Calendars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-parameters-openapi.md
- name: Microsoft Office 365 Get Calendars Calendar
  x-api-slug: microsoft-office-365
  description: You can also retrieve information about a specific calendar ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}
  tags: Calendars, Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-id-get-openapi.md
- name: Microsoft Office 365 Delete Calendars Calendar
  x-api-slug: microsoft-office-365
  description: Deleting a calendar is as simple as sending a DELETE request...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}
  tags: Calendars, Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-id-delete-openapi.md
- name: Microsoft Office 365 Patch Calendars Calendar
  x-api-slug: microsoft-office-365
  description: You can update a calendar by sending a PATCH request with a ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}
  tags: Calendars, Calendar
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Calendars Calendar
  x-api-slug: microsoft-office-365
  description: Parameters calendars calendar
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}
  tags: Calendars, Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-id-parameters-openapi.md
- name: Microsoft Office 365 Get Calendars Calendar Events
  x-api-slug: microsoft-office-365
  description: You can request all the events across all calendars (or a fi...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}/Events
  tags: Calendars, Calendar, , Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-idevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-idevents-get-openapi.md
- name: Microsoft Office 365 Add Calendars Calendar Events
  x-api-slug: microsoft-office-365
  description: Post calendars calendar  events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}/Events
  tags: Calendars, Calendar, , Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-idevents-post-openapi.md
- name: Microsoft Office 365 Parameters Calendars Calendar Events
  x-api-slug: microsoft-office-365
  description: Parameters calendars calendar  events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}/Events
  tags: Calendars, Calendar, , Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-idevents-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/calendarscalendar-idevents-parameters-openapi.md
- name: Microsoft Office 365
  x-api-slug: microsoft-office-365
  description: Integrate Office 365 REST APIs powered by Microsoft Graph into your
    own app to connect to files, calendars, mail and more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me
  tags: Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/calendars/master/_listings/microsoft-office-365/openapi.md
x-common:
- type: x-developer
  url: http://dev.office.com
- type: x-github
  url: https://github.com/OfficeDev
- type: x-twitter
  url: https://twitter.com/OfficeDev
- type: x-website
  url: http://office.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---