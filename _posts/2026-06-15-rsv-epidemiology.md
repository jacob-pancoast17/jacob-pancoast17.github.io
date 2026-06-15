---
title: "RSV Epidemiology Analysis"
date: 2026-06-15T13:10:30-04:00
---

While exploring the National Respiratory and Enteric Virus Surveillance System (NREVSS) [dashboard][nrevss] in late April, I noticed RSV positivity rates were elevated in Vermont compared to other states. This provoked me to investigate further, as I found that Vermont's RSV season this year started later, peaked later, and was still ongoing as of mid-May.

Using methodologies spanning epidemiology, biostatistics, data science, and public health, this analysis uncovers temporal trends in RSV epidemiology in Vermont from 2023-26 and discusses implications on public health policy and practices in R Markdown.

{% capture fig_img %}
[![RSV particles](/assets/images/rsv-banner.jpg)](https://jacob-pancoast17.github.io/epi-analysis)
{% endcapture %}

{% capture fig_caption %}
Read more here.
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>

[nrevss]: https://www.cdc.gov/nrevss/php/dashboard/index.html
