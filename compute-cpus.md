# Compute & CPUs
[Home](README.md) · [Networking](networking-interconnects.md) · [Storage](storage.md) · [What's New](whats-new.md)
## Run applications and choose infrastructure
| Resource | What it does | When it is useful | What you need to try it |
| --- | --- | --- | --- |
| [OCI compute shapes](https://docs.oracle.com/en-us/iaas/Content/Compute/References/computeshapes.htm) — documentation | Describes VM and bare-metal configurations across AMD, Intel, and Arm processor options. | Compare CPU, memory, local disk, and network characteristics for your workload. | OCI access, an available shape in your target region, and suitable service limits. |
| [Flexible shapes](https://docs.oracle.com/en-us/iaas/Content/Compute/References/computeshapes.htm) — documentation | Explains choosing CPU and memory allocations for supported VM shapes. | Match resource allocation to application needs and test different sizes. | A supported Flex shape; check the shape guide for allowed configurations. |
| [OCI Terraform provider](https://github.com/oracle/terraform-provider-oci) — code & examples | Provides infrastructure-as-code resources and examples for OCI. | Build repeatable compute and related infrastructure deployments. | Terraform, configured authentication, and IAM permissions. |
| [NVIDIA Vera CPUs on OCI](https://blogs.oracle.com/cloud-infrastructure/nvidia-vera-cpus-oci) — announcement | Describes Oracle's Vera CPU offering and CPU work around agentic systems. | Explore infrastructure for orchestration, tool execution, and other CPU-intensive AI services. | Confirm current shape, region, and capacity details with Oracle before planning a deployment. |
## Questions to answer before sizing
- Is the application compatible with the selected processor architecture?
- Is it limited by CPU, memory, storage I/O, or network traffic?
- Does it need a VM, bare metal, or a container platform?
- What availability, scaling, and recovery requirements apply?
Shape specifications are a starting point. Validate performance and costs with your own workload. See [What's New](whats-new.md) for the dated Vera availability note.
[Back to the resource menu](README.md)
