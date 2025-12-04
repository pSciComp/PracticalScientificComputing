# Cloud/Cluster-ready projects

## What belongs into a project?

_The take-home message here will be that a project is not simply defined by a bunch of scripts._
_An integral part of each project is a declaration of the environment - ideally in a functional form (e.g. requiremnts.txt, pyproject.toml or/and Dockerfile) - and a documentation of the workflow._

## Stick to conventions

Adhering to best practices when it gets to project structure make not just your life easier, it facilitates also sharing and developing your projects with others.

_We will provide a general template for a python project, go through the different elements in order to make sure that we understand their purpose._

## Version control

_This will be but a short introduction to git and how to use it._

- Short introduction to git
- Direct answer to the question: Why git is beneficial for a scientific project?
- Refer to the online material of the Git4Acad course
- Intro to git LFS and linking git modules with `git submodules`

## Project documentation

Following the structure of a template `README.md` we step through what essential information belong into a documentation.

_We want to keep this short; focus on documenting where to find what and how to execute/run the analysis/training._

## Related data

The goal here is to make the participants aware:

1. In any project that relies on data it must be clearly documented, where the data can be found, how it should be accessed and integrated into the project.
2. Data should always be decoupled from scripts and parametrization (remember the stateful and stateless.
