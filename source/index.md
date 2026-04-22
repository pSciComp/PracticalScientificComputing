```{raw} html
<div align="center">
<img src="https://raw.githubusercontent.com/pSciComp/.github/main/_static/pSciComp_logo.png" alt="pSciComp Logo" width="400">
</div>
<div align="center">
<p>
  <a href="https://pscicomp.courses.t4d.ch/slides/index.html">
    <img src="https://img.shields.io/badge/Course-Slides-green.svg" alt="online handout">
  </a>
  <a href="https://pscicomp.courses.t4d.ch/index.html">
    <img src="https://img.shields.io/badge/Course-Handout-purple.svg" alt="online handout">
  </a>

</p>
<h1>Practical Scientific Computing</h1>
<p>A practical guide to mastering
  <br>
  modern compute infrastructure
</p>
<br><br>
<pre><small>A course provided by</small>
<br>

<a href="https://github.com/t4d-gmbh"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/t4d-gmbh/.github/main/static/logo/wb/T4D_discover.svg"><source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/t4d-gmbh/.github/main/static/logo/bw/T4D_discover.svg"><img alt="T4D Logo" src="https://raw.githubusercontent.com/t4d-gmbh/.github/main/static/bw/T4D_discover.svg" width="220" style="vertical-align: middle;"></picture></a>
</pre>
</div>
```

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
