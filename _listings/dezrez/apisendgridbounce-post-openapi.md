---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez creates an event when a envelope is bounced by sendgrid
  version: 1.0.0
  description: Creates an event when a envelope is bounced by sendgrid.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/digitalsignature/signable/bounced/{fingerprint}:
    post:
      summary: creates an event when a envelope is bounced by signable
      description: Creates an event when a envelope is bounced by signable.
      operationId: DigitalSignature_BouncedByfingerprintBymetaData
      x-api-path-slug: apidigitalsignaturesignablebouncedfingerprint-post
      parameters:
      - in: path
        name: fingerprint
      - in: body
        name: metaData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Event
      - When
      - Envelope
      - Is
      - Bounced
      - By
      - Signable
  /api/sendgrid/bounce:
    post:
      summary: creates an event when a envelope is bounced by sendgrid
      description: Creates an event when a envelope is bounced by sendgrid.
      operationId: SendGrid_BouncedBybounceData
      x-api-path-slug: apisendgridbounce-post
      parameters:
      - in: body
        name: bounceData
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Event
      - When
      - Envelope
      - Is
      - Bounced
      - By
      - Sendgrid
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