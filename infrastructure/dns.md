# DNS

### \(DNS-100\) Product Domain

Each product will have a single registered domain that will be used for all endpoints in all services and for all projects.

* Naming
  * Lowercase alphanumeric characters only
  * Register in the `dev` TLD
  * Registered and managed by Lambda School engineering managers
  * Hosted in AWS Route 53 as a Hosted Zone
  * Examples:
    * `bridgestoprosperity.dev`
    * `ecosoap.dev`

Rationale:

* DNS is the root of many network operations and having a consistent naming convention across our products will help manage the complexity.

Alternatives:

* None

Exceptions:

* None

### \(DNS-200\) Product Subdomains

Subdomains should be used for various endpoints of a product: e.g. DS API, Web Front-end, etc.

* Naming
  * All lowercase
  * Alphanumeric and hyphens only
  * Hosted as records in the product domain hosted zone
  * Web Frontend
    * Use the format: `<team letter>.<product domain>`
      * `c.bridgestoprosperity.dev`
      * `a.ecosoap.dev`
  * Web API
    * Use the format: `<team letter>-api.<product domain>`
      * Examples:
        * `c-api.bridgestoprosperity.dev`
        * `a-api.ecosoap.dev`
  * Data Science API:
    * Use the format: `<team letter>-ds.<product domain>`
      * `c-ds.bridgestoprosperity.dev`
      * `a-ds.ecosoap.dev`

Rationale:

* DNS is the root of many network operations and having a consistent naming convention across our products will help manage the complexity.

Alternatives:

* None

Exceptions:

* None

