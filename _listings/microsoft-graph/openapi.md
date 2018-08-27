---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: meeventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnameeventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /groups/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: groupsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendareventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendareventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /groups/{id}/calendar/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: groupsidcalendareventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/calendargroup/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendargroupcalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /me/calendargroups/{id}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: mecalendargroupsidcalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/dismissReminder:
    post:
      summary: Event Dismiss Reminder
      description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
      operationId: Event:DismissReminder
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsiddismissreminder-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Event
      - Dismiss
      - Reminder
---