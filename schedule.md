# Day 1

## Morning

| **Time** | **Section** | **Type** | **Description** |
| --- | :--- | --- | :--- |
| 9:00 | Intro | Presentation | - Present speakers<br>- What is to be expected<br>- Schedule<br>- Requirements to pass this course | 
| 9:15 | Challenges in scientific computing | Presentation | - Resource limitations (Memory & Storage)<br>- Compute limitations (time and power)<br>- Task multiplicity<br>- Transparency & Reproducibility<br> | 
| 9:35 | Challenges in scientific computing | Exercise/Interactive | Go through your past/current and future projects evaluate for each in which category/categories they fall (10')<br> We then count the projects per category to get an overview of the prevalent challenges (10') | 
| 9:55 | Essential terminology | Presentation | Present the most relevant terms to assert a common vocabulary (VM, container, ...) | 
| 10:15 | Basic principles to share resources | Presentation | - Cloud virtualization (_X_ as a Service, ...)<br> - Scheduling systems<br> - Point out some implications that come with multi-tenancy<br> Basically, we present the concepts of "cloud" and "cluster". | 
| 10:25 | A primer on parallelism | Presentation | - Conceptual workflow: Orchestration > multiple individual jobs > aggregation<br> - The workflow can target different levels and happen on multiple levels simultaneously (e.g. multiple machines each running processes on multiple cores)<br> - Distinguish between multiple machines and multiple cores/threads/gpu's<br> - Highlight some advantages/disadvantage of both cases. |
| 10:30 | Break (15') | | |
| 10:45 | Collect what resources participants are using | Interactive | We compile a list of resources that are/were/will be used by the participants |
| 10:50 | Complete & review list of used resources | Interactive | - Complete the list with available resources at UZH (if missing)<br> - Categorize the resources into "cloud"- and "cluster"- based systemd (and others). |
| 11:00 | On cattle and pets | Presentation | - Introduce the concepts of stateful and stateless designs.<br> - Highlight how stateless infrastructure allows simpler scaling<br> - Translate this to the separation of data and tools/functionality. <br> - Present this idea in the light of a scientific project. |
| 11:15 | Basic principles of distributed storage  | Presentation | - Introduce the concepts of distributed network file systems.<br> - Traditionally hardware based, now software based is more common (also at UZH with ceph)<br> - Present some consequences on scalability, availability, security and I/O load distribution<br> - Relate to the stateful and stateless design. |
| 11:30 | Present the cloud | Presentation | - Basic idea.<br> - Typical (abstract) usecase<br> - Most known products<br> - How to interface with (GUI/API)<br> - How it combines with distributed storage<br> - Overview of the Science IT cloud. |
| 12:00 | Present the cluster | Presentation | - Basic idea.<br> - Typical (abstract) usecase<br> - Short intro to SLURM<br> - How to interface with (terminal)<br> - How it combines with distributed storage<br> - Overview of the Science IT cluster. |
| 12:30 | Building a checklist | Presentation/Interactive | _Idea: We define a list of attributes (availability, life-cycle, accessibility, storage requirements, ...) and work out together how each attribute affects the suitability of the cloud/cluster for a project_ |
| 13:00 | Lunch (1h) | | |

## Afternoon

| **Time** | **Section** | **Type** | **Description** |
| --- | :--- | --- | :--- |
| 14:00 | Short intro | Presentation | In the afternoon we focus on project design and coding practices that facilitate the usage of cloud/cluster infrastructures |
| 14:05 | What information belongs into a project? | Presentation/Interactive | _Collect what belongs into a project_<br> - Documentation (about the project: goal, approach, assumptions, etc.)<br> - Scripts (training/analysis)<br> - Data used (either include or declare where to find it)<br> - Environment (functional declaration via requirements.txt or Dockerfile; include hardware specifics) |
| 14:20 | General template for a project structure | Presentation | Present a template structure that allows to include the identified elements of a project<br>_Also provide a link to a project template_|
| 14:30 | Version control | Presentation/Interactive | _We will start with the question "for how long are you using git? a) Less than 1 year, b) 1-2 years, c) more than 2 years_<br> - Short introduction to version control with git (see Git4Acad material). |
| 14:40 | How to include a project documentation | Presentation | - The `README.md` file<br> - Propose a commonly used structure<br> - How to include further docs (e.g. sphinx, refer to project template)|
| 14:50 | How to include data | Presentation | |
| 15:00 | How to declare an environment | Presentation | |
| 15:10 | How to organize your scripts | Presentation | - Separation between reusable code, scripts and parametrization.<br> - Split scripts into orchestration, individual job and aggregation. |
| 15:20 | Cleaning up a toy project 1/3 | Exercise | _We provide a simple ML project with python scripts that do not adhere to a functional split up of scripts._<br> - Identify what is wrong with these scripts. |
| 15:30 | Break (15') | | |
| 15:45 | Primer on software development | Presentation | Short intro with toy examples:<br> - Orthogonal coding<br> - Don't repeat yourself (DRY) principle<br> - Single source of truth (SST) |
| 16:05 | Cleaning up a toy project 2/3 | Exercise | _Go back to the project and identify where it violates orthogonal coding, DRY and/or SST._ |
| 16:20 | Structuring your scripts | Presentation | Have a look at a project template that facilitates following the presented software development principles. |
| 16:30 | Cleaning up a toy project 3/3 | Exercise | _Bring the example ML project into the presented project structure. Clearly separate parametrization, reusable code and scripts. Separate scripts into orchestration, individual job and aggregation._ |
| 17:00 | 1st day end | | |

## Homework
1. **Cleaning up a toy project**

   Finish the started exercise before the 2nd day. Invite one of the instructors to the project.

2. Create a list of your present/past/future projects and identify for each:

   - Short description (just 1 sentence ideally).
   - What computational (cpu/gpu) and storage (rough size; type of data) resources does it require?
   - Does it use parallelism already?

     If yes, what kind (multiple machines, cores/gpus single machine, both)?

     If no, would they benefit from using parallelism and if yes what kind?
   - Did/Will you use special resources in the project?

     If yes, what (cloud (uzh or other), cluster (uzh or other), dedicated machine, etc.?

   We are going to collect this info and discuss it briefly at the beginning of the 2nd day.

# Day 2

## Morning

| **Time** | **Section** | **Type** | **Description** |
| --- | :--- | --- | :--- |
| 9:00 | Intro | Presentation | - Today's schedule<br>- Short recap of content from first day | 
| 9:10 | Homework | Interactive | - General feedback<br>- Discuss exercises | 
| 9:30 | | Presentation| - <br> | 
| 10:30 | Break (15') | | |
| 13:00 | Lunch (1h) | | |

## Afternoon

| **Time** | **Section** | **Type** | **Description** |
| --- | :--- | --- | :--- |
| 14:00 | | | |
| 15:30 | Break (15') | | |

## Homework
