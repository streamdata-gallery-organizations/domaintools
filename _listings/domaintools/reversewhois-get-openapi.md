---
swagger: "2.0"
x-collection-name: DomainTools
x-complete: 0
info:
  title: Reverse Whois API Reverse Whois
  description: Provides a list of domain names with Whois records that match a specific
    query
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
  /reverse-whois/:
    get:
      summary: Reverse Whois
      description: Provides a list of domain names with Whois records that match a
        specific query
      operationId: reverseWhois
      x-api-path-slug: reversewhois-get
      parameters:
      - in: query
        name: exclude
        description: Domain names with Whois records that match these terms will be
          excluded from the result set
        type: string
        format: string
      - in: query
        name: mode
        description: 'quote : only lists the size and retail price of the query if
          you have per-domain pricing access purchase : includes the complete list
          of domain names that match the query'
        type: string
        format: string
      - in: query
        name: scope
        description: Sets the scope of the report to include only current Whois records,
          or to include both current and historic records
        type: string
        format: string
      - in: query
        name: terms
        description: List of one or more terms to search for in the Whois record,
          separated with the pipe character ( | )
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Reverse Whois
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