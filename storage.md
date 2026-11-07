# Storage
[Home](README.md) · [Compute](compute-cpus.md) · [Networking](networking-interconnects.md) · [Kubernetes](kubernetes-oke.md)
## Choose how your applications access data
| Resource | What it does | When it is useful | What you need to try it |
| --- | --- | --- | --- |
| [Object Storage](https://docs.oracle.com/en-us/iaas/Content/Object/Concepts/objectstorageoverview.htm) — documentation | Explains bucket-based object storage and access to stored objects. | Explore storage for datasets, backups, media, or application objects. | An OCI tenancy, bucket permissions, and an access/lifecycle plan. |
| [Block Volume](https://docs.oracle.com/en-us/iaas/Content/Block/Concepts/overview.htm) — documentation | Explains provisioning and managing block storage volumes. | Evaluate persistent disks for compute workloads. | Permissions to create and attach volumes; check instance and placement compatibility. |
| [File Storage](https://docs.oracle.com/en-us/iaas/Content/File/Concepts/filestorageoverview.htm) — documentation | Introduces shared file-system storage and network access. | Explore workloads that need shared file access. | File-system and network permissions, mount connectivity, and a compatible client. |
## Before choosing a service
- **Access pattern:** Does the application use an object API, a block device, or a shared file system?
- **Performance:** What throughput, latency, and concurrency does it require?
- **Protection:** What backup, retention, replication, and recovery policies are needed?
- **Connectivity:** Where will the clients run, and how will they reach the data?
- **Cost:** Review capacity, performance, requests, retrieval, and network charges relevant to the service.
Use the service documentation for current features and limits. A storage choice should follow the application's access pattern and recovery requirements.
[Back to the resource menu](README.md)
