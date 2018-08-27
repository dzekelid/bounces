---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 0
info:
  title: AWS Simple Email Service API Send Bounce
  version: 1.0.0
  description: Generates and sends a bounce message to the sender of an email you
    received through Amazon SES.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SendBounce:
    get:
      summary: Send Bounce
      description: Generates and sends a bounce message to the sender of an email
        you received through Amazon SES.
      operationId: sendBounce
      x-api-path-slug: actionsendbounce-get
      parameters:
      - in: query
        name: BouncedRecipientInfoList.member.N
        description: A list of recipients of the bounced message, including the information
          required to create the Delivery Status Notifications (DSNs) for the recipients
        type: string
      - in: query
        name: BounceSender
        description: The address to use in the From header of the bounce message
        type: string
      - in: query
        name: BounceSenderArn
        description: This parameter is used only for sending authorization
        type: string
      - in: query
        name: Explanation
        description: Human-readable text for the bounce message to explain the failure
        type: string
      - in: query
        name: MessageDsn
        description: Message-related DSN fields
        type: string
      - in: query
        name: OriginalMessageId
        description: The message ID of the message to be bounced
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bounce
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