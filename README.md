# Solution Templates

![image](images/google_cloud_logo.png)

### Looking for pre-built Google Cloud solutions?
This repository contains links to different end-to-end templates built with Google Cloud products which cover common use cases for Startups and Digital Natives. Most of them can be deployed in **just one click** and are easily integrated into your existing Google Cloud environment. If you're new to Google Cloud, we recommend you first follow [this guide](https://cloud.google.com/docs/enterprise/setup-checklist) to set up your Google Cloud environment. 

## Solutions
These solutions are implemented using Infrastructure as Code with different tools like [Cloud Build](https://cloud.google.com/build) and [Terraform](https://www.terraform.io/), which enable repeatable and seamless deployments. Click on the link for the solution and follow the instructions in the README to deploy.

Last update: 23/01/2023
### Data Management and Analytics
- [Build a Foundation Data Pipeline with Google Cloud](https://goo.gle/c-GCStoBQ)
- [Cloud SQL for PostgreSQL disaster recovery: A complete failover and fallback process](https://goo.gle/c-CloudSQLMR)

### Security, Logging and Monitoring
- [HTTP Load Balancer with Cloud Armor](https://goo.gle/c-LBandArmor)
- [Ingestion and analysis of audit logs for a Workspace / Google Cloud organization](https://goo.gle/c-AuditLogsBQ)

### Application Modernization
- [Serverless Web Hosting Wordpress](https://goo.gle/c-AuditLogsBQ)

We are constantly updating our portfolio with new use cases and looking to improve our solutions, so we really value feedback. Please feel in [this form](https://https://goo.gle/startupTemplateFeedback) if there's anything you'd like to share.

## Infrastructure as Code
Infrastructure as Code (IaC) is the management of infrastructure through a descriptive model that enables the provisioning and deployment of cloud resources. It enables more efficient change management by supporting environment changes in a way that can be tested (prior to actual deployment), automatically applied and audited as per business-defined process policies. DevOps teams can store these defined configurations in source control and leverage Continuous Integration and Continuous Deployment (CI/CD) pipelines to deploy infrastructure as needed. It supports the recommended best practices of keeping configurations repeatable, trackable and visible across the organisation.

### Benefits
There are several benefits of using Infrastricutre as Code including:
- **Automation**: deploy resources much faster and more reliably than manual processes so more time can be invested in developing business logic and applications. 
- **Declarative**: specify and capture the state of your infrastructure in source files and increase visibility across the organisation to track changes more easily. 
- **Roll back**: built-in version control to capture changes in commit logs so it is easy to roll out and roll back changes just like a regular application.
- **Validate**: automated testing and code reviews allow precise assessment of desired vs current infrastructure state.
- **Scale**: leverage library of reusable, documented and battle-tested infrastructure code to scale and evolve as per business needs.

Under the hood, Infrastructure as code uses the Google Cloud API to provision cloud services, examples of which include:
- Launch a virtual machine (VM) with user-specified configurations.
- Creating a Google Kubernetes Engine cluster and node pool.
- Creating a BigQuery dataset.
