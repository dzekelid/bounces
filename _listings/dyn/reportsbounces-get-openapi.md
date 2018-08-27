---
swagger: "2.0"
x-collection-name: Dyn
x-complete: 0
info:
  title: Dyn Retrieve Email Bounces
  version: 1.0.0
  description: Retrieving the Email SPAM Complaints
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  reports/bounces:
    get:
      summary: Retrieve Email Bounces
      description: Retrieving the Email SPAM Complaints
      operationId: getReportsBounces
      x-api-path-slug: reportsbounces-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: bounce_code - Indicates the code associated with the bounced Email.
      - in: query
        name: bounce_code_id - The numeric code determined by the bounce processor.
      - in: query
        name: bounce_rule - Indicates the rule that caused this email to bounce.
      - in: query
        name: bounce_type
        description: Type of bounce for filtering
      - in: query
        name: bounce_type_id - Indicates whether the bounce type is a hard or soft
          bounce.nValid Values:n1 - Hard Bouncen2 - Soft Bounce
      - in: query
        name: emailaddress
        description: Email address of recipient for filtering
      - in: query
        name: endtime
        description: Required
      - in: query
        name: noheaders
        description: Determines whether or not headers are included in the response
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: sender_id
        description: Identifying number of the sender
      - in: query
        name: startindex
        description: Number indicating where to begin reporting results
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Email
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