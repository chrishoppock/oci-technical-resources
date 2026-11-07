# Terraform & Landing Zones
[Home](README.md) · [Getting started](getting-started.md) · [Networking](networking-interconnects.md) · [Kubernetes](kubernetes-oke.md)
## Build repeatable infrastructure
| Resource | What it does | When it is useful | What you need to try it |
| --- | --- | --- | --- |
| [OCI Terraform provider](https://github.com/oracle/terraform-provider-oci) — provider source & examples | Connects Terraform configuration to OCI infrastructure resources. | Automate deployments and manage configuration in version control. | A supported Terraform/provider version, OCI authentication, IAM permissions, and secure state handling. |
| [OCI Landing Zones](https://github.com/oci-landing-zones) — blueprint & module library | Collects tenancy foundation designs and reusable Terraform modules. | Explore identity, networking, security, and other foundation components. | Select a blueprint and review its documentation, privileges, scope, and costs. |
| [Core Landing Zone](https://github.com/oci-landing-zones/terraform-oci-core-landingzone) — deployment blueprint | Provides an opinionated Terraform foundation for centralized tenancy deployment. | Establish a foundation rather than manually assembling every component. | Review its deployment guide and compatibility with your existing tenancy and policies. |
## Before applying a template
Read the resource plan, policies, supported versions, region assumptions, and teardown instructions. Templates can create billable resources and tenancy-wide changes. Treat state and credentials as sensitive and keep them out of public repositories.
The landing-zone projects reference security benchmarks and practices. A template alone does not establish that your complete environment or workload meets a compliance requirement.
[Back to the resource menu](README.md)
