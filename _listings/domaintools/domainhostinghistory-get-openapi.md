---
swagger: "2.0"
x-collection-name: DomainTools
x-complete: 0
info:
  title: Hosting History API Domain History
  description: Provides the registrar, IP and name server history for a domain name
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
  /{domain}:
    get:
      summary: Domain Profile
      description: Basic registrant, server, and registration data for a domain name,
        plus preview data for other products
      operationId: domainProfile
      x-api-path-slug: domain-get
      parameters:
      - in: path
        name: domain
        description: The domain to profile
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Domains
  /domain-search/:
    get:
      summary: Domain Search
      description: Searches active and deleted domain names that match a query string
      operationId: domainSearch
      x-api-path-slug: domainsearch-get
      parameters:
      - in: query
        name: active_only
        description: Return only domains currently registered
        type: string
        format: string
      - in: query
        name: anchor_left
        description: Return only domains that start with the query term
        type: string
        format: string
      - in: query
        name: anchor_right
        description: Return only domains that end with the query term
        type: string
        format: string
      - in: query
        name: deleted_only
        description: Return only domains previously registered but not currently registered
        type: string
        format: string
      - in: query
        name: exclude_query
        description: Terms to exclude from matching ??? each term in the query string
          must be at least three characters long
        type: string
        format: string
      - in: query
        name: has_hyphen
        description: Return results with hyphens in the domain name
        type: string
        format: string
      - in: query
        name: has_number
        description: Return results with numbers in the domain name
        type: string
        format: string
      - in: query
        name: max_length
        description: Limit the maximum domain character coun
        type: string
        format: string
      - in: query
        name: min_length
        description: Limit the minumum domain character count
        type: string
        format: string
      - in: query
        name: page
        description: Sets the page of results to retrieve from the server
        type: string
        format: string
      - in: query
        name: query
        description: Query string ??? each term in the query string must be at least
          three characters long
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Domains
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
        description: Query string ??? must be at least two characters long
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Domain Suggestions
  /{domain}/hosting-history/:
    get:
      summary: Domain History
      description: Provides the registrar, IP and name server history for a domain
        name
      operationId: domainHistory
      x-api-path-slug: domainhostinghistory-get
      parameters:
      - in: path
        name: domain
        description: The domain
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Domain Hosting History
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