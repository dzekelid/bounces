---
name: Postmark
x-slug: postmark
description: Trusted by thousands of developers, Postmark is a fast and reliable transactional
  email service. Send with Postmark to ensure your transactional emails get to the
  inbox on time, every time.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
x-kinRank: "8"
x-alexaRank: "87545"
tags: Bounces
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/apis.md
specificationVersion: "0.14"
apis:
- name: Postmark - Parameters Bounces
  x-api-slug: bounces-parameters
  description: Parameters bounces.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bounces-parameters-openapi.md
- name: Postmark - Get Bounces
  x-api-slug: bounces-get
  description: 'Fetches a portion of bounces according to the specified input criteria.
    Supported filters: type, inactive, email like, tag. Paging: page_size (count),
    page_start (offset). Bounces are sorted by BouncedAt in a descending order.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bounces-get-openapi.md
- name: Postmark - Parameters Bounces Bounce
  x-api-slug: bouncesbounceid-parameters
  description: Parameters bounces bounce.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceid-parameters-openapi.md
- name: Postmark - Get Bounces Bounce
  x-api-slug: bouncesbounceid-get
  description: Gets details about a single bounce. Note that the bounce ID is a numeric
    value that you typically obtain after a getting a list of bounces.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceid-get-openapi.md
- name: Postmark - Parameters Bounces Bounce Dump
  x-api-slug: bouncesbounceiddump-parameters
  description: Parameters bounces bounce dump.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceiddump-parameters-openapi.md
- name: Postmark - Get Bounces Bounce Dump
  x-api-slug: bouncesbounceiddump-get
  description: Returns the raw source of the bounce we accepted. If Postmark does
    not have a dump for that bounce, it will return an empty string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceiddump-get-openapi.md
- name: Postmark - Parameters Bounces Tags
  x-api-slug: bouncestags-parameters
  description: Parameters bounces tags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncestags-parameters-openapi.md
- name: Postmark - Get Bounces Tags
  x-api-slug: bouncestags-get
  description: Returns a list of tags used for the current server.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncestags-get-openapi.md
- name: Postmark - Parameters Bounces Bounce Activate
  x-api-slug: bouncesbounceidactivate-parameters
  description: Parameters bounces bounce activate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceidactivate-parameters-openapi.md
- name: Postmark - Put Bounces Bounce Activate
  x-api-slug: bouncesbounceidactivate-put
  description: Activates a deactivated bounce. Note that you do not need to send anything
    in the request body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceidactivate-put-openapi.md
- name: Postmark - Get Stats Outbound Bounces
  x-api-slug: statsoutboundbounces-get
  description: Get stats outbound bounces.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/statsoutboundbounces-get-openapi.md
- name: Postmark - Parameters Bounces Bounce
  x-api-slug: bouncesbounceid-parameters
  description: Parameters bounces bounce.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceid-parameters-openapi.md
- name: Postmark - Get Bounces Bounce
  x-api-slug: bouncesbounceid-get
  description: Gets details about a single bounce. Note that the bounce ID is a numeric
    value that you typically obtain after a getting a list of bounces.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceid-get-openapi.md
- name: Postmark - Parameters Bounces Bounce Dump
  x-api-slug: bouncesbounceiddump-parameters
  description: Parameters bounces bounce dump.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceiddump-parameters-openapi.md
- name: Postmark - Get Bounces Bounce Dump
  x-api-slug: bouncesbounceiddump-get
  description: Returns the raw source of the bounce we accepted. If Postmark does
    not have a dump for that bounce, it will return an empty string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceiddump-get-openapi.md
- name: Postmark - Parameters Bounces Bounce Activate
  x-api-slug: bouncesbounceidactivate-parameters
  description: Parameters bounces bounce activate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceidactivate-parameters-openapi.md
- name: Postmark - Put Bounces Bounce Activate
  x-api-slug: bouncesbounceidactivate-put
  description: Activates a deactivated bounce. Note that you do not need to send anything
    in the request body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceidactivate-put-openapi.md
- name: Postmark - Parameters Bounces Bounce
  x-api-slug: bouncesbounceid-parameters
  description: Parameters bounces bounce.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceid-parameters-openapi.md
- name: Postmark - Get Bounces Bounce
  x-api-slug: bouncesbounceid-get
  description: Gets details about a single bounce. Note that the bounce ID is a numeric
    value that you typically obtain after a getting a list of bounces.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceid-get-openapi.md
- name: Postmark - Parameters Bounces Bounce Dump
  x-api-slug: bouncesbounceiddump-parameters
  description: Parameters bounces bounce dump.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceiddump-parameters-openapi.md
- name: Postmark - Get Bounces Bounce Dump
  x-api-slug: bouncesbounceiddump-get
  description: Returns the raw source of the bounce we accepted. If Postmark does
    not have a dump for that bounce, it will return an empty string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceiddump-get-openapi.md
- name: Postmark - Parameters Bounces Bounce Activate
  x-api-slug: bouncesbounceidactivate-parameters
  description: Parameters bounces bounce activate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceidactivate-parameters-openapi.md
- name: Postmark - Put Bounces Bounce Activate
  x-api-slug: bouncesbounceidactivate-put
  description: Activates a deactivated bounce. Note that you do not need to send anything
    in the request body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceidactivate-put-openapi.md
- name: Postmark - Put Bounces Bounce Activate
  x-api-slug: bouncesbounceidactivate-put
  description: Activates a deactivated bounce. Note that you do not need to send anything
    in the request body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceidactivate-put-openapi.md
- name: Postmark - Parameters Bounces Bounce Activate
  x-api-slug: bouncesbounceidactivate-parameters
  description: Parameters bounces bounce activate.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceidactivate-parameters-openapi.md
- name: Postmark - Get Bounces Bounce Dump
  x-api-slug: bouncesbounceiddump-get
  description: Returns the raw source of the bounce we accepted. If Postmark does
    not have a dump for that bounce, it will return an empty string.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceiddump-get-openapi.md
- name: Postmark - Parameters Bounces Bounce Dump
  x-api-slug: bouncesbounceiddump-parameters
  description: Parameters bounces bounce dump.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceiddump-parameters-openapi.md
- name: Postmark - Get Bounces Bounce
  x-api-slug: bouncesbounceid-get
  description: Gets details about a single bounce. Note that the bounce ID is a numeric
    value that you typically obtain after a getting a list of bounces.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceid-get-openapi.md
- name: Postmark - Parameters Bounces Bounce
  x-api-slug: bouncesbounceid-parameters
  description: Parameters bounces bounce.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Target, Imports, Stack Network, Technology, SaaS, Emails, Messages, Relative
    Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/bounces/master/_listings/postmark/bouncesbounceid-parameters-openapi.md
x-common:
- type: x--net-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#dot-net
- type: x-api-gallery
  url: http://polygon.api.gallery.streamdata.io
- type: x-api-stack
  url: http://postmark.stack.network
- type: x-base
  url: https://api.postmarkapp.com
- type: x-blog
  url: http://blog.postmarkapp.com/
- type: x-blog-rss
  url: http://blog.postmarkapp.com/rss
- type: x-contact-form
  url: http://support.postmarkapp.com/customer/portal/emails/new
- type: x-crunchbase
  url: https://crunchbase.com/organization/postmark
- type: x-crunchbase
  url: http://www.crunchbase.com/company/postmark
- type: x-developer
  url: http://developer.postmarkapp.com/
- type: x-email
  url: support@postmarkapp.com
- type: x-email
  url: 451d9b70cf9364d23ff6f9d51d870251569e+ahoy@inbound.postmarkapp.com
- type: x-faq
  url: http://support.postmarkapp.com/
- type: x-pricing
  url: http://developer.postmarkapp.com/developer-api-messages.html
- type: x-privacy
  url: https://postmarkapp.com/privacy-policy
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#rails
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#ruby
- type: x-selfservice-registration
  url: https://postmarkapp.com/sign_up
- type: x-status
  url: http://status.postmarkapp.com/
- type: x-terms-of-service
  url: https://postmarkapp.com/terms-of-service
- type: x-twitter
  url: https://twitter.com/postmarkapp
- type: x-website
  url: http://postmarkapp.com
- type: x-website
  url: http://postmarkapp.com/
- type: x-website
  url: https://postmarkapp.com
- type: x-wordpress-pdk
  url: http://developer.postmarkapp.com/developer-official-libs.html#wordpress
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---