{% if page %}
# Syllabus
{% else %}
# Schedule
{% endif %}

{% if page %}
```{include} ../../../README.md
:start-after: <!-- syllabus-include -->
:end-before: <!-- syllabus-exclude-->
```
{% else %}
:::{card} Day 1
1. Part: **[Utilizing Shared Resources](https://github.com/t4d-gmbh/utilizingSharedResources)**

---
Lunch (12:30-13:30). 

---
2. Part: **[Research Software Engineering](https://github.com/t4d-gmbh/researchSoftwareEngineering)**

:::
:::{card} Day 2
3. Part: **[Efficient Cluster Computation](https://github.com/t4d-gmbh/efficientClusterComputation)**

---
Lunch (12:30-13:30). 

---

4. Part: **[Efficient Cloud Usage](https://github.com/t4d-gmbh/efficientCloudUsage)**
:::
{% endif %}

