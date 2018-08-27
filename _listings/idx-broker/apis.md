---
name: IDX Broker
x-slug: idx-broker
description: Based in Eugene, OR, IDX, LLC is nationally known as a leading provider
  of real estate search applications. IDX, LLC actively manages more than $2 trillion
  worth of active listing data from more than 600 individual Multiple Listings Services
  (MLS). IDX, LLC provides integrated IDX software, customizable listing search utilities
  and lead management tools for real estate based websites (IDX Broker).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Approvals
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/apis.md
specificationVersion: "0.14"
apis:
- name: IDX API 1.4.0 Test Runner - Get Approved MLS
  x-api-slug: mlsapprovedmls-get
  description: |-
    This method provides all of the IDX IDs and names for all of the paperwork approved MLSs on the client's account.

    Note: This method was previously camelcased as "approvedMLS" but was made lower case to fit the API naming convention. Calls to "approvedMLS" will be forwarded to "approvedmls" and "approvedMLS" is listed as deprecated in the method list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Age Approved MLS
  x-api-slug: mlsageapprovedmls-get
  description: 'TODO: Add Description'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Cities Approved MLS
  x-api-slug: mlscitiesapprovedmls-get
  description: All cities represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlscitiesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlscitiesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Search Field Values Approved MLS
  x-api-slug: mlssearchfieldvaluesapprovedmls-get
  description: Field values in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Zipcodes Approved MLS
  x-api-slug: mlszipcodesapprovedmls-get
  description: All zip codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlszipcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlszipcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get List Allowed Fields Approved MLS Featured
  x-api-slug: clientslistallowedfieldsapprovedmlsfeaturedid-get
  description: Returns the allowed returnable fields for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Listing Approved MLS Featuredid
  x-api-slug: clientslistingapprovedmlsfeaturedid-get
  description: Returns the detailed information for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Addalcodes Approvedmls
  x-api-slug: mlspostalcodesapprovedmls-get
  description: All postal codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Prices Approvedmls
  x-api-slug: mlspricesapprovedmls-get
  description: The sum total of properties listed in a given MLS as well as sums for
    each property type in the MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertycount Approvedmls
  x-api-slug: mlspropertycountapprovedmls-get
  description: Gives a total number of listings available for a given city, county,
    or zipcode
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertycountapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertycountapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertytypes Approvedmls
  x-api-slug: mlspropertytypesapprovedmls-get
  description: Gives the property type information for all types that are available
    on a given MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Searchfields Approvedmls
  x-api-slug: mlssearchfieldsapprovedmls-get
  description: All the fields in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Approved MLS
  x-api-slug: mlsapprovedmls-get
  description: |-
    This method provides all of the IDX IDs and names for all of the paperwork approved MLSs on the client's account.

    Note: This method was previously camelcased as "approvedMLS" but was made lower case to fit the API naming convention. Calls to "approvedMLS" will be forwarded to "approvedmls" and "approvedMLS" is listed as deprecated in the method list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Age Approved MLS
  x-api-slug: mlsageapprovedmls-get
  description: 'TODO: Add Description'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Cities Approved MLS
  x-api-slug: mlscitiesapprovedmls-get
  description: All cities represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlscitiesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlscitiesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Search Field Values Approved MLS
  x-api-slug: mlssearchfieldvaluesapprovedmls-get
  description: Field values in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Zipcodes Approved MLS
  x-api-slug: mlszipcodesapprovedmls-get
  description: All zip codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlszipcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlszipcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get List Allowed Fields Approved MLS Featured
  x-api-slug: clientslistallowedfieldsapprovedmlsfeaturedid-get
  description: Returns the allowed returnable fields for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Listing Approved MLS Featuredid
  x-api-slug: clientslistingapprovedmlsfeaturedid-get
  description: Returns the detailed information for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Addalcodes Approvedmls
  x-api-slug: mlspostalcodesapprovedmls-get
  description: All postal codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Prices Approvedmls
  x-api-slug: mlspricesapprovedmls-get
  description: The sum total of properties listed in a given MLS as well as sums for
    each property type in the MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertycount Approvedmls
  x-api-slug: mlspropertycountapprovedmls-get
  description: Gives a total number of listings available for a given city, county,
    or zipcode
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertycountapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertycountapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertytypes Approvedmls
  x-api-slug: mlspropertytypesapprovedmls-get
  description: Gives the property type information for all types that are available
    on a given MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Searchfields Approvedmls
  x-api-slug: mlssearchfieldsapprovedmls-get
  description: All the fields in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Listing Approved MLS Featuredid
  x-api-slug: clientslistingapprovedmlsfeaturedid-get
  description: Returns the detailed information for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Listing Approved MLS Featuredid
  x-api-slug: clientslistingapprovedmlsfeaturedid-get
  description: Returns the detailed information for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Listing Approved MLS Featuredid
  x-api-slug: clientslistingapprovedmlsfeaturedid-get
  description: Returns the detailed information for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistingapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get List Allowed Fields Approved MLS Featured
  x-api-slug: clientslistallowedfieldsapprovedmlsfeaturedid-get
  description: Returns the allowed returnable fields for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get List Allowed Fields Approved MLS Featured
  x-api-slug: clientslistallowedfieldsapprovedmlsfeaturedid-get
  description: Returns the allowed returnable fields for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get List Allowed Fields Approved MLS Featured
  x-api-slug: clientslistallowedfieldsapprovedmlsfeaturedid-get
  description: Returns the allowed returnable fields for a given listingID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/clientslistallowedfieldsapprovedmlsfeaturedid-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Zipcodes Approved MLS
  x-api-slug: mlszipcodesapprovedmls-get
  description: All zip codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlszipcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlszipcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Zipcodes Approved MLS
  x-api-slug: mlszipcodesapprovedmls-get
  description: All zip codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlszipcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlszipcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Search Field Values Approved MLS
  x-api-slug: mlssearchfieldvaluesapprovedmls-get
  description: Field values in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Search Field Values Approved MLS
  x-api-slug: mlssearchfieldvaluesapprovedmls-get
  description: Field values in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldvaluesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Cities Approved MLS
  x-api-slug: mlscitiesapprovedmls-get
  description: All cities represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlscitiesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlscitiesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Cities Approved MLS
  x-api-slug: mlscitiesapprovedmls-get
  description: All cities represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlscitiesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlscitiesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Age Approved MLS
  x-api-slug: mlsageapprovedmls-get
  description: 'TODO: Add Description'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Age Approved MLS
  x-api-slug: mlsageapprovedmls-get
  description: 'TODO: Add Description'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Age Approved MLS
  x-api-slug: mlsageapprovedmls-get
  description: 'TODO: Add Description'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsageapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Approved MLS
  x-api-slug: mlsapprovedmls-get
  description: |-
    This method provides all of the IDX IDs and names for all of the paperwork approved MLSs on the client's account.

    Note: This method was previously camelcased as "approvedMLS" but was made lower case to fit the API naming convention. Calls to "approvedMLS" will be forwarded to "approvedmls" and "approvedMLS" is listed as deprecated in the method list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Approved MLS
  x-api-slug: mlsapprovedmls-get
  description: |-
    This method provides all of the IDX IDs and names for all of the paperwork approved MLSs on the client's account.

    Note: This method was previously camelcased as "approvedMLS" but was made lower case to fit the API naming convention. Calls to "approvedMLS" will be forwarded to "approvedmls" and "approvedMLS" is listed as deprecated in the method list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Searchfields Approvedmls
  x-api-slug: mlssearchfieldsapprovedmls-get
  description: All the fields in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Searchfields Approvedmls
  x-api-slug: mlssearchfieldsapprovedmls-get
  description: All the fields in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Searchfields Approvedmls
  x-api-slug: mlssearchfieldsapprovedmls-get
  description: All the fields in a given MLS that are currently allowed to be searched
    according to MLS guidelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlssearchfieldsapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertytypes Approvedmls
  x-api-slug: mlspropertytypesapprovedmls-get
  description: Gives the property type information for all types that are available
    on a given MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertytypes Approvedmls
  x-api-slug: mlspropertytypesapprovedmls-get
  description: Gives the property type information for all types that are available
    on a given MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertytypes Approvedmls
  x-api-slug: mlspropertytypesapprovedmls-get
  description: Gives the property type information for all types that are available
    on a given MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertytypesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Propertycount Approvedmls
  x-api-slug: mlspropertycountapprovedmls-get
  description: Gives a total number of listings available for a given city, county,
    or zipcode
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertycountapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspropertycountapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Prices Approvedmls
  x-api-slug: mlspricesapprovedmls-get
  description: The sum total of properties listed in a given MLS as well as sums for
    each property type in the MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Prices Approvedmls
  x-api-slug: mlspricesapprovedmls-get
  description: The sum total of properties listed in a given MLS as well as sums for
    each property type in the MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Prices Approvedmls
  x-api-slug: mlspricesapprovedmls-get
  description: The sum total of properties listed in a given MLS as well as sums for
    each property type in the MLS.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspricesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Addalcodes Approvedmls
  x-api-slug: mlspostalcodesapprovedmls-get
  description: All postal codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-openapi.md
- name: IDX API 1.4.0 Test Runner - Get Mls Addalcodes Approvedmls
  x-api-slug: mlspostalcodesapprovedmls-get
  description: All postal codes represented in the current set of MLS data are available
    from this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/idx-broker.png
  humanURL: http://www.idxbroker.com
  baseURL: https://example.com//
  tags: Real Estate, API Provider, Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/approvals/master/_listings/idx-broker/mlspostalcodesapprovedmls-get-openapi.md
x-common:
- type: x-blog
  url: https://blog.idxbroker.com/
- type: x-blog-rss
  url: https://blog.idxbroker.com/feed/
- type: x-website
  url: http://www.idxbroker.com
- type: x-api-gallery
  url: http://iconfinder.api.gallery.streamdata.io
- type: x-api-stack
  url: http://idx.broker.stack.network
- type: x-developer
  url: https://developers.idxbroker.com/
- type: x-forum
  url: https://developers.idxbroker.com/forums-home/
- type: x-getting-started
  url: https://developers.idxbroker.com/getting-started/
- type: x-partners
  url: https://developers.idxbroker.com/partnership/
- type: x-twitter
  url: https://twitter.com/idxbroker
- type: x-website
  url: http://www.idxbroker.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---