---
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
---