swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/viewing/{id}/recordslotapproval/{viewingSlotId}:
    put:
      summary: Set approval status of viewing slot on multi viewing appointment
      description: Set approval status of viewing slot on multi viewing appointment.
      operationId: Viewing_RecordViewingSlotApprovalByidByviewingSlotIdBystatus
      x-api-path-slug: apiviewingidrecordslotapprovalviewingslotid-put
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: status
      - in: path
        name: viewingSlotId
      responses:
        200:
          description: OK
      tags:
      - Set
      - Approval
      - Status
      - Of
      - Viewing
      - Slot
      - "On"
      - Multi
      - Viewing
      - Appointment
  /api/people/{id}/updateservicetypes:
    post:
      summary: "Update the service types by PersonId\r\nThis cannot be used internally
        as they do not have the right to move status up to to approved \r\nOnly the
        client does"
      description: "Update the service types by personid\r\nthis cannot be used internally
        as they do not have the right to move status up to to approved \r\nonly the
        client does."
      operationId: People_UpdateServiceTypesByidByServiceTypes
      x-api-path-slug: apipeopleidupdateservicetypes-post
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: body
        name: ServiceTypes
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Types
      - By
      - "PersonId\r\nThis"
      - Cannot
      - Be
      - Used
      - Internally
      - As
      - They
      - Do
      - Not
      - Have
      - Right
      - To
      - Move
      - Status
      - Up
      - To
      - To
      - Approved
      - Only
      - Client
      - Does