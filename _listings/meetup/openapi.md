swagger: "2.0"
x-collection-name: Meetup
x-complete: 1
info:
  title: Meetup
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:urlname/member/approvals:
    post:
      summary: Membership Approval
      description: Approves one or more requests for group membership
      operationId: profiles
      x-api-path-slug: urlnamememberapprovals-post
      parameters:
      - in: query
        name: member
        description: Comma-delimited numeric pending member IDs
        type: string
      - in: query
        name: send_copy
        description: Optional boolean value indicating whether or not the org should
          receive a copy of the message sent to the approved members
        type: string
      - in: query
        name: welcome_message
        description: Optional message to send to the members being approved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Members