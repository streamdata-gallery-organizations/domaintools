---
swagger: "2.0"
x-collection-name: DomainTools
x-complete: 0
info:
  title: Domain Suggestions API Domain Suggestions
  description: Generates available domain suggestions that are related to a query
    string
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
  /domain-suggestions/:
    get:
      summary: Domain Suggestions
      description: Generates available domain suggestions that are related to a query
        string
      operationId: domainSuggestions
      x-api-path-slug: domainsuggestions-get
      parameters:
      - in: query
        name: query
        description: Query string  must be at least two characters long
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Domain Suggestions
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