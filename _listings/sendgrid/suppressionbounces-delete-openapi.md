---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Delete Suppression Bounces
  description: "**This endpoint allows you to delete all of your bounces. You can
    also use this endpoint to remove a specific email address from your bounce list.**\n\nA
    bounced email is when the message is undeliverable and then returned to the server
    that sent it.\n\nFor more information see: \n\n* [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
    for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
    [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)\n\nNote:
    the `delete_all` and `emails` parameters should be used independently of each
    other as they have different purposes."
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /suppression/bounces:
    delete:
      summary: Delete Suppression Bounces
      description: "**This endpoint allows you to delete all of your bounces. You
        can also use this endpoint to remove a specific email address from your bounce
        list.**\n\nA bounced email is when the message is undeliverable and then returned
        to the server that sent it.\n\nFor more information see: \n\n* [User Guide
        > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html)
        for more information\n* [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)\n*
        [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)\n\nNote:
        the `delete_all` and `emails` parameters should be used independently of each
        other as they have different purposes."
      operationId: suppression.bounces.delete
      x-api-path-slug: suppressionbounces-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Suppression
      - Bounces
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