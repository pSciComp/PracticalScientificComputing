# Utilization of shared resources

## Challenges in scientific computing

- Processing large amounts of data (inference or/and statistical analysis - video data, genomic data, large matrices, etc).
  
  In practice this boils down to:
  - Finding/managing storage solutions
  - Make data available to computational resources
  - Configure computational resources to digest data properly

- Produce large amounts of synthetic data (statistical bootstrapping, Monte Carlo simulations, many-body-simulations).
- Develop and evaluate machine learning models (hyperparameter tuning, deep learning)
- Transparency and Reproducibility.

Framed differently we can define 4 categories:

1. Resource limitations (Memory & Storage)
   - Storage quotas
   - Logistical challenges to move data
   - Handling datasets (RAM usage)
2. Compute limitations time and computing power (CPU & GPU)
   - Job run-times
   - Specialized hardware (GPU/TPU) and architecture requirements
3. Task multiplicity
   - Massive parallelisms
   - Data aggregation
4. Transparency & Reproducibility
   - Environment consistency (hardware & software)
   - Data transparency (pre-trained models, )
   - Workflow documentation


## Virtualization and "bare-metal"

- Understand the basic terminology both for cloud infrastructure (VM, container, hypervisor, server, image) and for the cluster.

  In case of the cluster the focus should be on data storage, and the different slurm components (login, compute).

  The goal is to define the concepts and clarify how they relate to the underlying hardware infrastructure.

- Relate the "X‑as‑a‑Service" principle to virtualization layers and operational responsibility (IaaS, PaaS, FaaS).  

## Shared compute ecosystems

- Become aware that non‑virtualized approaches exist (bare‑metal provisioning, dedicated nodes).  
- Gain a high‑level overview of common sharing approaches (IaaS, PaaS, SaaS, HPC).  
- Recognize multi‑tenancy implications: quotas, noisy neighbors, resource contention.

## On cattle and pets

- Learn about stateful and stateless instance designs.
  
  - Define the terms (traditionally used in IT) and the underlying idea (separation of data and functionality/tools).
  - Present this idea in the context of a scientific project: decouple data and code, be mindful about how you bring them together (i.e. how to run your analysis/training etc.) 

- Appreciate how stateless designs facilitate deployments, reproducibility and scaling.

## Cloud vs. Cluster

- Understand how cloud infrastructures differ from clusters in terms of:
  - project life-cycle (provision → run → tear-down).
  - resource availability and elasticity.
  - (pre‑)configuration and bootstrap requirements.
  - interaction capabilities (interactive APIs vs batch interfaces).
  - monitoring and observability.
  - I/O characteristics (object storage vs POSIX/parallel filesystems).

- Get a decision checklist to choose cloud, cluster, or hybrid for a workload.


## Decision guide

We point out some clear characteristics of a project the can be used to identify whether cloud or cluster based approaches (or a combination) are better suited.
