# AI & Agentic Workloads
[Home](README.md) · [Compute](compute-cpus.md) · [Kubernetes](kubernetes-oke.md) · [GPU Resources](gpu-resources.md)
## Build agents and AI applications
| Resource | What it does | When it is useful | What you need to try it |
| --- | --- | --- | --- |
| [OCI Agent Development Kit](https://docs.oracle.com/en-us/iaas/Content/generative-ai-agents/adk/api-reference/introduction.htm) — documentation, quickstart & source links | Introduces the client-side toolkit for applications using OCI Generative AI Agents Service. | Explore agent tools, orchestration patterns, and application integration. | Follow the quickstart for the runtime, authentication, service access, and IAM setup. |
| [Oracle AI Developer Hub](https://github.com/oracle-devrel/oracle-ai-developer-hub) — examples & workshops | Collects resources for applications, agents, and systems using Oracle AI Database and OCI services. | Find a concrete example relevant to your use case. | Read the chosen app's README; dependencies and required services vary. |
| [OCI AI Blueprints](https://github.com/oracle-quickstart/oci-ai-blueprints) — deployment project | Provides packaged AI workload stacks on OKE. | Explore supported inference and other AI deployment patterns. | Appropriate cluster, compute/GPU resources, permissions, and any model or software licenses. |
| [NVIDIA Vera CPUs on OCI](https://blogs.oracle.com/cloud-infrastructure/nvidia-vera-cpus-oci) — announcement | Describes CPU infrastructure for agent orchestration, code/tool execution, and related services. | Evaluate the CPU side of an AI system alongside model-serving choices. | Confirm current offering and regional capacity; see the [availability note](whats-new.md). |
## Match infrastructure to the application
Agentic applications can include APIs, tool execution, retrieval, state, storage, and model calls. Not every agent application requires a dedicated GPU cluster. Start with the application's requirements and the selected model/service deployment approach.
Before running an example, review its data access, tool permissions, credential handling, model terms, and resource costs. The linked projects are examples, not a substitute for application-specific security and operational review.
[Back to the resource menu](README.md)
