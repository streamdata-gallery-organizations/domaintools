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
  /ip-monitor/:
    get:
      summary: IP Monitor
      description: Receive notification when there are new and/or deleted domains
        on a given IP Address
      operationId: ipMonitor
      x-api-path-slug: ipmonitor-get
      parameters:
      - in: query
        name: days_back
        description: Use this parameter in exceptional circumstances where you need
          to search domain changes up to six days prior to the current date
        type: string
        format: string
      - in: query
        name: page
        description: If the result set is larger than 1000 records for a given day,
          request additional pages with this parameter
        type: string
        format: string
      - in: query
        name: query
        description: The IP Address you wish to query ( i
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - IP Monitor
  /ip-registrant-monitor/:
    get:
      summary: IP Registrant Monitor
      description: Receive notification when specific people or organizations are
        allocated new IP ranges or have existing ranges de-allocated
      operationId: registrantMonitor
      x-api-path-slug: ipregistrantmonitor-get
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
        name: search_type
        description: Type of changes to return
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
      - IP Registrant Monitor
  /name-server-monitor/:
    get:
      summary: Name Server Monitor
      description: Receive notification when there are new and/or deleted domains
        on a given Domain Name Server
      operationId: nameServerMonitor
      x-api-path-slug: nameservermonitor-get
      parameters:
      - in: query
        name: days_back
        description: Use this parameter in exceptional circumstances where you need
          to search domain changes up to six days prior to the current date
        type: string
        format: string
      - in: query
        name: page
        description: If the result set is larger than 1000 records for a given day,
          request additional pages with this parameter
        type: string
        format: string
      - in: query
        name: query
        description: The hostname of the Name Server you wish to query
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Name Server Monitor
  /{domain}/whois/parsed:
    get:
      summary: Parsed Whois
      description: The Parsed Whois API provides parsed information extracted from
        the raw Whois recor
      operationId: parsedWhois
      x-api-path-slug: domainwhoisparsed-get
      responses:
        200:
          description: OK
      tags:
      - Whois
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
  /{domain]/name-server-domains/:
    get:
      summary: Reverse Name Server
      description: List of domains that share the same primary name server
      operationId: reverseNameServer
      x-api-path-slug: domainnameserverdomains-get
      parameters:
      - in: query
        name: limit
        description: Limits the size of the domain list than can appear in a response
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Reverse Name Server
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