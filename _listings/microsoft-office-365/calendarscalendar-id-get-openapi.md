---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Get Calendars Calendar
  description: You can also retrieve information about a specific calendar ...
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /CalendarGroups{calendargroup_id}/Calendars:
    get:
      summary: Get Calendar Groups Calendars
      description: You can request all the user's calendars (or a filtered list...
      operationId: getCalendargroupsCalendargroupCalendars
      x-api-path-slug: calendargroupscalendargroup-idcalendars-get
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
      - ""
      - Calendars
    post:
      summary: Add Calendar Groups Calendars
      description: You can create a calendar by sending a POST request with a J...
      operationId: postCalendargroupsCalendargroupCalendars
      x-api-path-slug: calendargroupscalendargroup-idcalendars-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
      - ""
      - Calendars
    parameters:
      summary: Parameters Calendar Groups Calendars
      description: Parameters calendargroups calendargroup  calendars
      operationId: parametersCalendargroupsCalendargroupCalendars
      x-api-path-slug: calendargroupscalendargroup-idcalendars-parameters
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
      - ""
      - Calendars
  /Calendars{calendar_id}:
    get:
      summary: Get Calendars Calendar
      description: You can also retrieve information about a specific calendar ...
      operationId: getCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-get
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---