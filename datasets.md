---
title: Datasets
layout: datasets
filename: datasets.md
---
## Datasets
<!-- STUB PAGE. -->
We overview the datasets released through the FALCON challenge. Technical details and the
dataset itself are provided in the linked DANDI repository and the associated paper. In FALCON, we
release a collection of five datasets spanning a variety of tasks, subjects, and brain areas. Though in our
benchmark we are only evaluating a specific set of metrics for each dataset, we encourage the use of
these datasets beyond FALCON's stated scope.

Note: The FALCON manuscript references the release of additional broadband data for B1 and M2, as well as a second subject's data (M1-B) for M1. These are being prepared and will be released in the coming months.

<hr>

{%- for dataset in site.data.datasets -%}
<div markdown="1">
### {{ dataset.title }}
</div>

<div style="margin-bottom: 1em;">
    <div style="padding-left: 1em; border-left: 2px solid rgb(195, 195, 195)">
        <div>
            {{- dataset.dandi | markdownify -}}
        </div>
        <div style="margin-top: -1.2em">
            <a href="{{ dataset.notebook }}">Demo Notebook</a>
        </div>
    </div>
    <img src="{{ dataset.image }}" alt="{{ dataset.title }} Schematic"/>
    {{- dataset.text | markdownify -}}
</div>
{%- endfor -%}
