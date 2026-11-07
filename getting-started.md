# Getting started
[Home](README.md) · [Compute](compute-cpus.md) · [Networking](networking-interconnects.md) · [Storage](storage.md)
## Before you deploy
You do not need an OCI account to read the documentation and examples in this collection. To run a deployment, check:
1. **Account and access:** An OCI tenancy and IAM permissions for the resources you will create. Multicloud examples also require the relevant account and permissions in the other cloud.
2. **Region and capacity:** The services and compute shapes must be available in your chosen region. A published example does not guarantee capacity or an approved service limit.
3. **Tools:** Follow the project's requirements for Terraform, CLI, SDKs, Kubernetes tools, or local runtimes.
4. **Costs and cleanup:** Deployment can create billable compute, storage, networking, and other services. Read the resource list and teardown instructions before starting. Removing an application does not necessarily remove its infrastructure.
## Useful starting points
| Resource | What it helps with | When to use it | What you need |
| --- | --- | --- | --- |
| [OCI documentation](https://docs.oracle.com/en-us/iaas/Content/home.htm) — documentation | Find service guides and configuration references. | You need the owning service's instructions. | No account to read; tenancy access for deployments. |
| [Compute shapes](https://docs.oracle.com/en-us/iaas/Content/Compute/References/computeshapes.htm) — documentation | Compare processor, CPU, memory, and network configurations. | You are sizing a VM or bare-metal workload. | Workload requirements and a target region. |
| [OCI Terraform provider](https://github.com/oracle/terraform-provider-oci) — code & examples | Manage infrastructure as code. | You want repeatable deployments. | Terraform and configured OCI authentication and permissions. |
| [OCI Landing Zones](https://github.com/oci-landing-zones) — templates & design guidance | Explore tenancy foundations and reusable deployment modules. | You are planning an environment for a team. | Review the selected blueprint's scope and IAM requirements. |
## Choose a path
- **Application infrastructure:** [Compute](compute-cpus.md) → [Networking](networking-interconnects.md) → [Storage](storage.md).
- **Containers:** [Kubernetes & OKE](kubernetes-oke.md) → [Terraform & Landing Zones](terraform-landing-zones.md).
- **AI applications:** [AI & Agentic Workloads](ai-agentic-workloads.md) → [Compute](compute-cpus.md), with [GPU Resources](gpu-resources.md) where required.
- **Multicloud:** [Networking & Interconnects](networking-interconnects.md).
[Back to the resource menu](README.md)
