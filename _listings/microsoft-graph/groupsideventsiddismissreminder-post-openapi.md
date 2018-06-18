---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Event Dismiss Reminder
  description: 'event: dismissReminder Dissmiss a reminder that has been triggered.'
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