# Clouds, Clusters and You

A <img src="./source/_static/T4D_logo_bw.svg" alt="T4D" width="25" height="25"> seminar providing the required essentials — and more — to leverage shared resources efficiently.

---

### Part 1: Utilization of shared resources

#### Virtualization and "bare-metal"

- Understand the basic terminology (VM, container, hypervisor, server, image).  
- Relate the "X‑as‑a‑Service" principle to virtualization layers and operational responsibility (IaaS, PaaS, FaaS).  

#### Shared compute ecosystems

- Become aware that non‑virtualized approaches exist (bare‑metal provisioning, dedicated nodes).  
- Gain a high‑level overview of common sharing approaches (IaaS, PaaS, SaaS, HPC).  
- Recognize multi‑tenancy implications: quotas, noisy neighbors, resource contention.

#### On cattle and pets

- Learn about stateful and stateless instance designs.
- Appreciate how stateless designs facilitate deployments, reproducibility and scaling.

#### Cloud vs. Cluster

- Understand how cloud infrastructures differ from clusters in terms of:
  - project life-cycle (provision → run → teardown).
  - resource availability and elasticity.
  - (pre‑)configuration and bootstrap requirements.
  - interaction capabilities (interactive APIs vs batch interfaces).
  - monitoring and observability.
  - I/O characteristics (object storage vs POSIX/parallel filesystems).

- Get a decision checklist to choose cloud, cluster, or hybrid for a workload.

---

### Part 2: Cloud/Cluster‑ready projects

#### Primer on software development

- Learn the DRY principle and how it encourages reusable code.  
- Understand orthogonal code organization and why it simplifies computational projects.  
- Learn how to develop a codebase prepared for cluster and/or cloud execution (modularity, tests, environment capture).
- Get a minimal repo template for cluster/cloud-ready project.

#### A word on parallelism

- Learn to classify a workload into levels of parallelism (fine-/coarse-grained, embarrassing).
- Apprehend the implications when working with a high-level language like python.

#### Project structure and management

- Become aware of version control practices for code and data (Git, Git LFS).  
- Gain a practical understanding of how to separate data, parametrization, scripts, and software packages.  
- Capture environments with lockfiles or container recipes for reproducibility.

#### A word on reproducibility

- Recognize how designing projects for cloud & cluster enhances reproducibility (containers, workflows).  
- Use workflow descriptions and container images to make runs repeatable.

#### Picking a side

- Be able to identify cluster‑ or cloud‑friendly properties of a project early on (data gravity, burstiness, parallelism type, compliance, project lifecycle).  
- Produce a simple rubric to score a project and recommend “cluster‑first”, “cloud‑first”, or “hybrid”.


---


### Part 3: In the Clouds

#### Provision and deploy

- Get familiar with the provisioning workflow (project/account → image → network → storage → instance → bootstrap).  
- Be able to generate reproducible deployments using immutable images and cloud‑init/user‑data.


#### Efficient resource usage in a Cloud

- Appreciate the potential cost overhead of sparse or specialized resources (GPUs, large memory).  
- Understand data management best practices in the cloud (prefer object storage for large datasets).  
- Know when to use ephemeral vs persistent VMs (consider startup latency vs job runtime).
- Acknowledge what forms of parallelism are well suited for cloud infrastructures.

#### IaC

- Understand the basic principle of Infrastructure as Code (declarative, idempotent, versionable).  
- Get acquainted with Terraform (provisioning) and Ansible (configuration).  
- Learn to set up a basic IaC‑driven VM lifecycle: plan → apply → change → destroy.

#### On-demand cloud usage (towards a cluster-like usage pattern)

- Learn the pattern of attaching VM/container lifecycles to computational workloads (ephemeral compute).  

---

### Part 4: Clustered computing

#### A primer for a scheduling system

- Identify cluster components and access modes (login/head nodes, scheduler, compute nodes; interactive vs batch).
- Manage secure access (SSH keys, MFA) and follow safe‑login practices.
- Use module systems (Environment Modules/Lmod) to load site software.
- Write correct Slurm job scripts and use sbatch/srun/salloc, job arrays, dependencies, partitions.
- Capture environment and logs reliably in job scripts.

#### Filesystems, storage tiers & I/O pitfalls

- Distinguish storage tiers (home/data, $SCRATCH) and their intended use.
- Stage inputs to fast storage and return outputs to persistent storage with checksums.
- Avoid small‑file and metadata storms by bundling or sharding data.

#### Resource requests, packing & performance optimization

- Learn to profile CPU, memory, and I/O (perf/gprof, sacct, I/O tracers) to find bottlenecks.
- Request CPUs, tasks, threads, memory, GPUs, and walltime appropriately for workload type.
- Get acquainted with advanced job configurations (arrays, co‑location, right‑sizing) to reduce queue time and improve throughput.

#### Customized cluster resources (towards a cloud-like usage pattern)

- Be able to build Singularity images (from Docker) for reproducible execution on clusters.
- Get familiar with live-sessions and web based interfaces (OnDemand, aka. ScienceApps)


---
