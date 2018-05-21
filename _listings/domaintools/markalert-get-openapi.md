---
swagger: "2.0"
x-collection-name: DomainTools
x-complete: 0
info:
  title: Brand Monitor API Brand Monitor
  description: Monitor new domains registrations for specific keywords
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
  /mark-alert/:
    get:
      summary: Brand Monitor
      description: Monitor new domains registrations for specific keywords
      operationId: brandMonitor
      x-api-path-slug: markalert-get
      parameters:
      - in: query
        name: days_back
        description: Use this parameter in exceptional circumstances where you need
          to search domains registered up to six days prior to the current date
        type: string
        format: string
      - in: query
        name: domain_status
        description: Sets the scope of domain names to search
        type: string
        format: string
      - in: query
        name: exclude
        description: Domain names with these words will be excluded from the result
          set
        type: string
        format: string
      - in: query
        name: query
        description: One or more terms separated by the pipe character ( | )
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Brand Monitor
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