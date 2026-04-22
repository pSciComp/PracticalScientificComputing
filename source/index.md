```{include} ../README.md
:end-before: <!-- readme-header -->
```
:::{div} text-center bg-light text-body p-3 rounded font-monospace

<small>A course provide by</small>

```{image} https://raw.githubusercontent.com/t4d-gmbh/.github/main/static/logo/bw/T4D_discover.svg
:class: only-light
:width: 220px
:alt: T4D logo
:target: https://github.com/t4d-gmbh
```
```{image} https://raw.githubusercontent.com/t4d-gmbh/.github/main/static/logo/wb/T4D_discover.svg
:class: only-dark
:width: 220px
:alt: T4D logo
:target: https://github.com/t4d-gmbh
```
:::

{% if slide %}
:::{admonition} Authors
:class: note, margin
**Dr. [Jonas I. Liechti](https://github.com/j-i-l)**  
**Dr. [Matteo Delucchi](https://github.com/matteodelucchi)**
:::
{% else %}
### Authors

**Dr. [Jonas I. Liechti](https://github.com/j-i-l)**  
**Dr. [Matteo Delucchi](https://github.com/matteodelucchi)**  
{% endif %}

## Content

```{toctree}
:caption: About
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:hidden:
{% endif %}

content/about/index
```

{% if slide %}
### Utilizing Shared Resources
{% endif %}
```{toctree}
:caption: Part 1: Utilizing Shared Resources
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:numbered:
:hidden:
{% endif %}

content/utilizingSharedResources/source/content/index
```

{% if slide %}
### Research Software Engineering
{% endif %}
```{toctree}
:caption: Part 2: Research Software Engineering
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:numbered:
:hidden:
{% endif %}

./content/researchSoftwareEngineering/source/content/index
```

{% if slide %}
### Recap; Containers, Clouds & Objects
{% endif %}
```{toctree}
:caption: Part 3: Recap; Containers, Clouds & Objects
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:numbered:
:hidden:
{% endif %}

./content/recapCloudsObjects/source/content/index
```

{% if slide %}
### Cluster - Workflow & Profiling
{% endif %}
```{toctree}
:caption: Part 4: Cluster - Workflow & Profiling
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:numbered:
:hidden:
{% endif %}

content/workflowClusterProfiling/source/content/index
```

```{toctree}
:caption: Outro
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:hidden:
{% endif %}

content/outro/index
```
