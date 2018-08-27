---
swagger: "2.0"
x-collection-name: Elastic Email
x-complete: 0
info:
  title: Elastic Email SMTP API Bounced
  description: This api will return you the list of email addresses which are currently
    in your block list.
  version: v1
host: api.elasticemail.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  mailer/list/bounced:
    get:
      summary: Bounced
      description: This api will return you the list of email addresses which are
        currently in your block list.
      operationId: getMailerListBounced
      x-api-path-slug: mailerlistbounced-get
      parameters:
      - in: query
        name: api_key
        description: Your API Key
      - in: query
        name: username
        description: Your user name
      responses:
        200:
          description: OK
      tags:
      - Mailer
      - List
      - Bounced
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