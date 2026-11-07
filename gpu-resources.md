# GPU Resources
[Home](README.md) · [Compute](compute-cpus.md) · [Kubernetes](kubernetes-oke.md) · [AI](ai-agentic-workloads.md)
Public material for teams exploring GPU infrastructure. I work alongside Oracle's GPU specialists; this section complements my focus on compute, networking, storage, and application infrastructure.
| Resource | What it does | When it is useful | What you need to try it |
| --- | --- | --- | --- |
| [OCI GPU Quickstarts](https://github.com/oracle-quickstart/oci-gpu-quickstarts) — onboarding guides | Organizes GPU provisioning, initial validation, images, and tooling guidance by GPU family. | Understand the starting steps for a particular GPU offering. | The selected guide's shape, image, driver, permissions, and capacity prerequisites. |
| [GPUs and RDMA on OKE](https://github.com/oracle-quickstart/oci-hpc-oke) — templates & guides | Covers deploying GPU nodes and running RDMA-connected workloads on OKE. | Explore distributed GPU workloads and cluster networking. | Appropriate GPU capacity, service limits, supported images, IAM policies, and Kubernetes access. |
| [OCI AI Blueprints](https://github.com/oracle-quickstart/oci-ai-blueprints) — deployment project | Provides packaged AI workloads on OKE with prescribed infrastructure. | Evaluate a supported stack before designing a custom deployment. | Blueprint-specific infrastructure, model access, and software requirements. |
## Before deploying
A public quickstart is not a capacity reservation. Confirm shape and region availability, approved limits, network/storage requirements, and total deployment cost. Follow each repository's own support and licensing terms.
For CPU resources supporting agents and AI applications, see [Compute & CPUs](compute-cpus.md) and [AI & Agentic Workloads](ai-agentic-workloads.md).
[Back to the resource menu](README.md)
