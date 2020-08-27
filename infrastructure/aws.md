# AWS

### \(AW-100\) Approved AWS Services

The only permitted AWS services for Lambda School Labs projects are listed below:

* Amplify
  * Front-end hosting of Single Page Apps \(SPA\) only
* Elastic Beanstalk
  * Data Science API deployments only
* Sagemaker
  * Data Science only
* S3
  * Public asset storage
  * User uploads via signed URLs
  * Data storage for DS teams

All others are prohibited from use.

Note: These services utilize many underlying services, which are permitted only when provisioned by the orchestration services listed above.

Rationale:

* AWS is _very_ deep, with many different services and components. That complexity needs careful controls to reduce risk and cost.

Alternatives:

* None

Exceptions:

* None

### \(AW-200\) Resource Naming

The following naming conventions must be followed:

* Amplify Application
  * `<Product Name>-<Cohort>-<Team Letter>`
    * bridges-to-prosperity-labs25-a
    * ecosoap-labs26-c
* Elastic Beanstalk Application
  * `<Product Name>-<Cohort>`
    * bridges-to-prosperity-labs25
    * ecosoap-labs26-c
* Elastic Beanstalk Environment
  * `<Product Name>-<Cohort>-<Team Letter>`
    * bridges-to-prosperity-labs25-a
    * ecosoap-labs26-c

{% hint style="info" %}
Please check with your Engineering Manager if you need to name something in AWS that is not in this list.
{% endhint %}

{% hint style="warning" %}
Not following these naming standards _will_ cause your AWS resources to be automatically de-provisioned.
{% endhint %}

Rationale:

* Labs manages dozens of accounts using thousands of distinct resources. Consistent naming is a key to managing this complexity.

Alternatives:

* None

Exceptions:

* None

