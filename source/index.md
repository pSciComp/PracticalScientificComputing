```{include} ../README.md
:end-before: <!-- readme-include -->
```

A <img src="./_static/T4D_logo.svg" alt="**T4D**" width="35" height="35"> seminar providing the required essentials — and more — to leverage shared resources efficiently.

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

### Content

```{toctree}
:caption: About
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:hidden:
{% endif %}

content/about/index
```

{% if slide %}
#### Utilizing Shared Resources
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
#### Research Software Engineering
{% endif %}
```{toctree}
:caption: Part 2: Research Software Engineering
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:numbered:
:hidden:
{% endif %}

content/researchSoftwareEngineering/source/content/index
```

{% if slide %}
#### Efficient Cluster Computation
{% endif %}
```{toctree}
:caption: Part 3: Efficient Cluster Computation
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:numbered:
:hidden:
{% endif %}

content/efficientClusterComputation/source/content/index
```

{% if slide %}
#### Efficient Cloud Usage 
{% endif %}
```{toctree}
:caption: Part 4: Efficient Cloud Usage
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:numbered:
:hidden:
{% endif %}

content/efficientCloudUsage/source/content/index
```

```{toctree}
:caption: Outro
:maxdepth: {% if slide %}1{% else %}2{% endif %}
{% if slide %}:hidden:
{% endif %}

content/outro/index
```
