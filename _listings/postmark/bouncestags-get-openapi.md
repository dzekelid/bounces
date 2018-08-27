---
swagger: "2.0"
x-collection-name: Postmark
x-complete: 0
info:
  title: Postmark Get Bounces Tags
  description: Returns a list of tags used for the current server.
  version: 1.0.0
host: spamcheck.postmarkapp.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /bounces:
    parameters:
      summary: Parameters Bounces
      description: Parameters bounces.
      operationId: parametersBounces
      x-api-path-slug: bounces-parameters
      responses:
        200:
          description: OK
      tags:
      - Bounces
    get:
      summary: Get Bounces
      description: 'Fetches a portion of bounces according to the specified input
        criteria. Supported filters: type, inactive, email like, tag. Paging: page_size
        (count), page_start (offset). Bounces are sorted by BouncedAt in a descending
        order.'
      operationId: getBounces
      x-api-path-slug: bounces-get
      parameters:
      - in: query
        name: Accept
        description: The accepted type for the response
      - in: query
        name: Content-Type
        description: The content type of the request
      - in: query
        name: count
        description: Number of bounces to return per request
      - in: query
        name: emailFilter
        description: Filter by email address
      - in: query
        name: fromdate
        description: Filter messages starting from the date specified
      - in: query
        name: inactive
        description: Filter by emails that were deactivated by Postmark due to the
          bounce
      - in: query
        name: messageID
        description: Filter by messageID
      - in: query
        name: offset
        description: Number of bounces to skip
      - in: query
        name: tag
        description: Filter by tag
      - in: query
        name: todate
        description: Filter messages up to the date specified
      - in: query
        name: type
        description: Filter by type of bounce
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Bounces
  /bounces/{bounceID}:
    parameters:
      summary: Parameters Bounces Bounce
      description: Parameters bounces bounce.
      operationId: parametersBouncesBounce
      x-api-path-slug: bouncesbounceid-parameters
      responses:
        200:
          description: OK
      tags:
      - Bounces
      - BounceID
    get:
      summary: Get Bounces Bounce
      description: Gets details about a single bounce. Note that the bounce ID is
        a numeric value that you typically obtain after a getting a list of bounces.
      operationId: getBouncesBounce
      x-api-path-slug: bouncesbounceid-get
      parameters:
      - in: query
        name: Accept
        description: The accepted type for the response
      - in: path
        name: bounceid
        description: The ID of the bounce to retrieve
      - in: query
        name: Content-Type
        description: The content type of the request
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Bounces
      - BounceID
  /bounces/{bounceID}/dump:
    parameters:
      summary: Parameters Bounces Bounce Dump
      description: Parameters bounces bounce dump.
      operationId: parametersBouncesBounceDump
      x-api-path-slug: bouncesbounceiddump-parameters
      responses:
        200:
          description: OK
      tags:
      - Bounces
      - BounceID
      - Dump
    get:
      summary: Get Bounces Bounce Dump
      description: Returns the raw source of the bounce we accepted. If Postmark does
        not have a dump for that bounce, it will return an empty string.
      operationId: getBouncesBounceDump
      x-api-path-slug: bouncesbounceiddump-get
      parameters:
      - in: query
        name: Accept
        description: The accepted type for the response
      - in: path
        name: bounceid
        description: The ID for the bounce dump to retrieve
      - in: query
        name: Content-Type
        description: The content type of the request
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Bounces
      - BounceID
      - Dump
  /bounces/tags:
    parameters:
      summary: Parameters Bounces Tags
      description: Parameters bounces tags.
      operationId: parametersBouncesTags
      x-api-path-slug: bouncestags-parameters
      responses:
        200:
          description: OK
      tags:
      - Bounces
      - Tags
    get:
      summary: Get Bounces Tags
      description: Returns a list of tags used for the current server.
      operationId: getBouncesTags
      x-api-path-slug: bouncestags-get
      parameters:
      - in: query
        name: Accept
        description: The accepted type for the response
      - in: query
        name: Content-Type
        description: The content type of the request
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Bounces
      - Tags
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