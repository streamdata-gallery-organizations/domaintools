---
name: DomainTools
x-slug: domaintools
description: DomainTools helps security analysts turn threat data into threat intelligence.
  We take indicators from your network, including domains and IPs, and connect them
  with nearly every active domain on the Internet. Those connections inform risk assessments,...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
x-kinRank: "7"
x-alexaRank: "6104"
tags: DomainTools
created: "2018-05-25"
modified: "2018-05-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/apis.md
specificationVersion: "0.14"
apis:
- name: Brand Monitor API Brand Monitor
  x-api-slug: brand-monitor-api
  description: Monitor new domains registrations for specific keywords
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//mark-alert/
  tags: Brand Monitor
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/markalert-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/markalert-get-openapi.md
- name: Brand Monitor API
  x-api-slug: brand-monitor-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Domain Profile API Domain Profile
  x-api-slug: domain-profile-api
  description: Basic registrant, server, and registration data for a domain name,
    plus preview data for other products
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com/v1//{domain}
  tags: Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domain-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domain-get-openapi.md
- name: Domain Profile API
  x-api-slug: domain-profile-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com/v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Domain Search API Domain Search
  x-api-slug: domain-search-api
  description: Searches active and deleted domain names that match a query string
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v2//domain-search/
  tags: Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainsearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainsearch-get-openapi.md
- name: Domain Search API
  x-api-slug: domain-search-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v2
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Domain Suggestions API Domain Suggestions
  x-api-slug: domain-suggestions-api
  description: Generates available domain suggestions that are related to a query
    string
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//domain-suggestions/
  tags: Domain Suggestions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainsuggestions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainsuggestions-get-openapi.md
- name: Domain Suggestions API
  x-api-slug: domain-suggestions-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Hosting History API Domain History
  x-api-slug: hosting-history-api
  description: Provides the registrar, IP and name server history for a domain name
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//{domain}/hosting-history/
  tags: Domain Hosting History
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainhostinghistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainhostinghistory-get-openapi.md
- name: Hosting History API
  x-api-slug: hosting-history-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: IP Monitor API IP Monitor
  x-api-slug: ip-monitor-api
  description: Receive notification when there are new and/or deleted domains on a
    given IP Address
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//ip-monitor/
  tags: IP Monitor
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/ipmonitor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/ipmonitor-get-openapi.md
- name: IP Monitor API
  x-api-slug: ip-monitor-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: IP Registrant Monitor API IP Registrant Monitor
  x-api-slug: ip-registrant-monitor-api
  description: Receive notification when specific people or organizations are allocated
    new IP ranges or have existing ranges de-allocated
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//ip-registrant-monitor/
  tags: IP Registrant Monitor
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/ipregistrantmonitor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/ipregistrantmonitor-get-openapi.md
- name: IP Registrant Monitor API
  x-api-slug: ip-registrant-monitor-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Name Server Monitor API Name Server Monitor
  x-api-slug: name-server-monitor-api
  description: Receive notification when there are new and/or deleted domains on a
    given Domain Name Server
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//name-server-monitor/
  tags: Name Server Monitor
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/nameservermonitor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/nameservermonitor-get-openapi.md
- name: Name Server Monitor API
  x-api-slug: name-server-monitor-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Parsed Whois API Parsed Whois
  x-api-slug: parsed-whois-api
  description: The Parsed Whois API provides parsed information extracted from the
    raw Whois recor
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//{domain}/whois/parsed
  tags: Whois
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainwhoisparsed-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainwhoisparsed-get-openapi.md
- name: Parsed Whois API
  x-api-slug: parsed-whois-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Registrant Monitor API IP Registrant Monitor
  x-api-slug: registrant-monitor-api
  description: Receive notification when specific people or organizations are allocated
    new IP ranges or have existing ranges de-allocated
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//ip-registrant-monitor/
  tags: IP Registrant Monitor
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/ipregistrantmonitor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/ipregistrantmonitor-get-openapi.md
- name: Registrant Monitor API
  x-api-slug: registrant-monitor-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Reverse IP API Reverse IP Whois
  x-api-slug: reverse-ip-api
  description: Provides a list of IP network ranges with Whois records that match
    a specific query
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//reverse-ip-whois/
  tags: Reverse IP Whois
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/reverseipwhois-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/reverseipwhois-get-openapi.md
- name: Reverse IP API
  x-api-slug: reverse-ip-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Reverse IP Whois API Reverse IP Whois
  x-api-slug: reverse-ip-whois-api
  description: Provides a list of IP network ranges with Whois records that match
    a specific query
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//reverse-ip-whois/
  tags: Reverse IP Whois
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/reverseipwhois-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/reverseipwhois-get-openapi.md
- name: Reverse IP Whois API
  x-api-slug: reverse-ip-whois-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Reverse Name Server API Reverse Name Server
  x-api-slug: reverse-name-server-api
  description: List of domains that share the same primary name server
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//{domain]/name-server-domains/
  tags: Reverse Name Server
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainnameserverdomains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainnameserverdomains-get-openapi.md
- name: Reverse Name Server API
  x-api-slug: reverse-name-server-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Reverse Whois API Reverse Whois
  x-api-slug: reverse-whois-api
  description: Provides a list of domain names with Whois records that match a specific
    query
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//reverse-whois/
  tags: Reverse Whois
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/reversewhois-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/reversewhois-get-openapi.md
- name: Reverse Whois API
  x-api-slug: reverse-whois-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Whois History API Whois History
  x-api-slug: whois-history-api
  description: Historical Whois records
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1//{domain}/whois/history/
  tags: Whois
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainwhoishistory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainwhoishistory-get-openapi.md
- name: Whois History API
  x-api-slug: whois-history-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
- name: Whois Lookup API Whois Lookup
  x-api-slug: whois-lookup-api
  description: The Whois Lookup API provides the ownership record for a domain name
    or IP address with basic registration details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1/domaintools.com///{domain}/whois
  tags: Whois
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainwhois-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/domainwhois-get-openapi.md
- name: Whois Lookup API
  x-api-slug: whois-lookup-api
  description: DomainTools helps security analysts turn threat data into threat intelligence.
    We take indicators from your network, including domains and IPs, and connect them
    with nearly every active domain on the Internet. Those connections inform risk
    assessments,...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/393-domaintools.jpg
  humanURL: http://www.domaintools.com
  baseURL: http://api.domaintools.com//v1/domaintools.com/
  tags: DomainTools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/domaintools/master/_listings/domaintools/openapi.md
x-common:
- type: x-base
  url: http://api.domaintools.com/
- type: x-blog-rss
  url: http://blog.domaintools.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/domain-tools
- type: x-crunchbase
  url: https://crunchbase.com/organization/domain-tools
- type: x-developer
  url: http://www.domaintools.com/api/docs/
- type: x-email
  url: sales@domaintools.com
- type: x-github
  url: https://github.com/DomainTools
- type: x-pricing
  url: https://www.domaintools.com/products/domain-research/pricing/
- type: x-twitter
  url: https://twitter.com/DomainTools
- type: x-website
  url: http://www.domaintools.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---