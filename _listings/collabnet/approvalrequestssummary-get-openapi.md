---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Gets a summary of pending approval
    requests on TF server
  version: 1.0.0
  description: Gets a summary of pending approval requests on tf server.
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /approval-requests/summary:
    get:
      summary: Gets a summary of pending approval requests on TF server
      description: Gets a summary of pending approval requests on tf server.
      operationId: getApprovalRequestSummary
      x-api-path-slug: approvalrequestssummary-get
      parameters:
      - in: query
        name: projectId
        description: Project identifier
      responses:
        200:
          description: OK
      tags:
      - Summary
      - Of
      - Pending
      - Approval
      - Requests
      - "On"
      - TF
      - Server
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