# Kubernetes & OKE
[Home](README.md) · [Compute](compute-cpus.md) · [AI](ai-agentic-workloads.md) · [GPU Resources](gpu-resources.md)
## Deploy containerized applications
| Resource | What it does | When it is useful | What you need to try it |
| --- | --- | --- | --- |
| [Kubernetes Engine overview](https://docs.oracle.com/en-us/iaas/Content/ContEng/Concepts/contengoverview.htm) — documentation | Introduces OKE and its Kubernetes deployment and node options. | Evaluate managed Kubernetes for applications or AI workloads. | OCI permissions, a network design, and the relevant cluster/node resources. |
| [OCI Terraform provider](https://github.com/oracle/terraform-provider-oci) — code & examples | Includes resources for automating OCI infrastructure. | Manage cluster infrastructure through versioned configuration. | Terraform, authentication, and the selected example's prerequisites. |
| [GPUs and RDMA workloads on OKE](https://github.com/oracle-quickstart/oci-hpc-oke) — deployment templates & guides | Provides GPU cluster deployment material and RDMA workload guidance. | Explore GPU-backed Kubernetes and distributed workload networking. | Suitable GPU capacity, service limits, IAM policies, and supported images; follow the repository requirements. |
| [OCI AI Blueprints](https://github.com/oracle-quickstart/oci-ai-blueprints) — deployment project | Provides packaged AI workload deployment and management examples on OKE. | Evaluate a supported AI stack with the project's prescribed components. | An OCI tenancy, appropriate OKE/GPU resources, and blueprint-specific prerequisites. |
## Design decisions
Start with node type, Kubernetes compatibility, private/public endpoint access, workload identity, persistent storage, ingress, and observability. The OKE documentation explains responsibilities and behavior for each node option.
For general applications, start with the OKE overview. GPU and AI templates are more specialized and may provision substantial infrastructure.
[Back to the resource menu](README.md)
