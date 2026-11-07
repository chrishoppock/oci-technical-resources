# Networking & Interconnects
[Home](README.md) · [Compute](compute-cpus.md) · [Storage](storage.md) · [Terraform](terraform-landing-zones.md)
## Build an OCI network or connect existing environments
| Resource | What it does | When it is useful | What you need to try it |
| --- | --- | --- | --- |
| [OCI networking overview](https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/overview.htm) — documentation | Introduces VCNs, subnets, gateways, routing, and related networking components. | Plan application connectivity and network boundaries. | An address plan, OCI IAM permissions, and a target region. |
| [FastConnect overview](https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/fastconnectoverview.htm) — documentation | Explains dedicated connectivity between an existing network and OCI. | Evaluate private connectivity for hybrid workloads or data movement. | A supported connection model, routing design, and network/provider arrangements. |
| [FastConnect requirements](https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/fastconnectrequirements.htm) — documentation | Lists prerequisites for the available connectivity models. | Check what you and your connectivity provider must supply. | Network team involvement and the requirements for your selected model. |
| [Multicloud interconnect](https://docs.oracle.com/en-us/iaas/Content/multicloud/interconnect.htm) — documentation hub | Links to AWS, Azure, and Google Cloud interconnect guidance. | Evaluate architectures spanning OCI and another cloud. | Accounts and permissions on both sides; review the specific service's supported locations and prerequisites. |
| [Azure interconnect architecture](https://docs.oracle.com/en/solutions/oci-azure/index.html) — reference architecture | Explains an Azure VNet and OCI VCN connected through ExpressRoute and FastConnect. | Explore private cross-cloud application patterns. | Compatible regions, networking resources, and permissions in both clouds. |
| [Google Cloud interconnect setup](https://docs.oracle.com/en-us/iaas/Content/multicloud/interconnect-gcp.htm) — deployment guide | Walks through the Google Cloud and OCI networking requirements and connection setup. | Plan a private connection between the two clouds. | Subscriptions, routing components, and IAM permissions in both clouds. |
## Plan the connection
Check address overlap, BGP/routing, redundancy, DNS, traffic inspection, and encryption requirements. Private connectivity and encryption are separate design considerations; see [FastConnect security](https://docs.oracle.com/en-us/iaas/Content/Network/Concepts/fastconnectsecurity.htm).
Supported regions and pricing depend on the connection type and provider. Review both sides' charges rather than assuming all cross-cloud traffic or connectivity is free.
[Back to the resource menu](README.md)
