---
swagger: "2.0"
x-collection-name: DomainTools
x-complete: 0
info:
  title: Reverse IP Whois API Reverse IP Whois
  description: Provides a list of IP network ranges with Whois records that match
    a specific query
  version: 1.0.0
host: api.domaintools.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reverse-ip-whois/:
    get:
      summary: Reverse IP Whois
      description: Provides a list of IP network ranges with Whois records that match
        a specific query
      operationId: reverseIPWhois
      x-api-path-slug: reverseipwhois-get
      parameters:
      - in: query
        name: country
        description: Limits results to IP addresses allocated to an entity with a
          particular country
        type: string
        format: string
      - in: query
        name: include_total_count
        description: Returns the total number of results for a query
        type: string
        format: string
      - in: query
        name: ip
        description: Returns the most recent cached IP Whois record for the allocated
          range the IP is in
        type: string
        format: string
      - in: query
        name: page
        description: Providing the page number allows access to additional pages of
          data
        type: string
        format: string
      - in: query
        name: query
        description: A space separated list of free text query terms
        type: string
        format: string
      - in: query
        name: server
        description: Limits results to ranges from a particular Whois server
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Reverse IP Whois
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