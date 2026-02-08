```{include} ../README.md
:end-before: <!-- readme-include -->
```
{% if build == "slides" %}
<!-- <p style="font-size: 0.9em;"><strong>Dr. Jonas I. Liechti</strong><br>
<strong>Dr. Matteo Delucchi</strong></p> -->
:::{admonition} Authors
:class: note, margin
Dr. Jonas I. Liechti  
Dr. Matteo Delucchi
:::

{% else %}
### Authors

**Dr. Jonas I. Liechti**  
**Dr. Matteo Delucchi**  
{% endif %}

### Content

```{toctree}
:caption: About
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}
{% if build == "slides" %}:hidden:
{% endif %}

content/about/index
```

{% if slide %}
#### Utilizing Shared Resources
{% endif %}
```{toctree}
:caption: Part 1: Utilizing Shared Resources
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}
{% if build == "slides" %}:numbered:
:hidden:
{% endif %}

content/utilizingSharedResources/source/content/index
```

{% if slide %}
#### Research Software Engineering
{% endif %}
```{toctree}
:caption: Part 2: Research Software Engineering
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}
{% if build == "slides" %}:numbered:
:hidden:
{% endif %}

content/researchSoftwareEngineering/source/content/index
```

{% if slide %}
#### Efficient Cluster Computations
{% endif %}
```{toctree}
:caption: Part 3: Efficient Cluster Computations
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}
{% if build == "slides" %}:numbered:
:hidden:
{% endif %}

content/efficientClusterComputations/source/content/index
```

{% if slide %}
#### Efficient Cloud Computations
{% endif %}
```{toctree}
:caption: Part 4: Efficient Cloud Computations
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}
{% if build == "slides" %}:numbered:
:hidden:
{% endif %}

content/efficientCloudComputations/source/content/index
```

```{toctree}
:caption: Outro
:maxdepth: {% if build == "slides" %}1{% else %}2{% endif %}
{% if build == "slides" %}:hidden:
{% endif %}

content/outro/index
```
