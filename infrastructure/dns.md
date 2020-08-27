# DNS

### \(DNS-100\) Domain Name

Each product will have a single registered domain that will be used for all endpoints in all services and for all projects.

* Naming
  * All lowercase
  * Alphanumeric and hyphens only
  * Register in the `dev` TLD
  * Registered and managed by Lambda School engineering managers
  * Hosted in AWS Route 53 as a Hosted Zone
  * Examples:
    * `bridges-to-prosperity.dev`
    * `ecosoap.dev`

Rationale:

* DNS is the root of many network operations and having a consistent naming convention across our products will help manage the complexity.

Alternatives:

* None

Exceptions:

* None

### \(DNS-200\) Subdomains

Subdomains should be used for various endpoints of a product: e.g. DS API, Web Front-end, etc.

* Naming
  * All lowercase
  * Alphanumeric and hyphens only
  * Hosted as records in the product domain hosted zone
  * Web API
    * Use the format: `<cohort>-<team letter>-api`
      * Examples:
        * `labs25-c-api.bridges-to-prosperity.dev`
        * `labs26-a-api.ecosoap.dev`
  * Data Science API:
    * Use the format: `<cohort>-<team letter>-ds`
      * `labs25-c-ds.bridges-to-prosperity.dev`
      * `labs26-a-ds.ecosoap.dev`

Rationale:

* DNS is the root of many network operations and having a consistent naming convention across our products will help manage the complexity.

Alternatives:

* None

Exceptions:

* None

