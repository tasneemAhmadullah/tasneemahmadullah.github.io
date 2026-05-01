---
permalink: /
title: Welcome to my website!
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral associate at the Civil and Environmental Engineering department at [Rutgers University](https://cee.rutgers.edu/), I have recently joined [Dr. Nicole Fahrenfeld's](https://www.pnnl.gov/](https://cee.rutgers.edu/nicole-fahrenfeld) lab to investigate microplastics impacted by PFAS bringing with me a strong foundation in spectroscopic analysis. 

Prior to joining Rutgers, I worked at [Pacific Northwest National Laboratory (PNNL)](https://www.pnnl.gov/) to investigate the complexities of environmental systems with a combined approach of experimental analysis and model simulations. My research combined advanced spectroscopic and spectrometric analysis of soil and water samples with biogeochemical and geochemical modeling to develop better understandings of environmental systems. During my time at PNNL I also worked as the science point of contact for running samples in [Pyrolysis Gas Chromatography Mass Spectrometry (PyGCMS)](https://www.emsl.pnnl.gov/science/instruments-resources/pyrolysis-gas-chromatography-mass-spectrometry) at [EMSL](https://www.emsl.pnnl.gov/), PNNL's user facility.

My passion for environmental systems traces back to my PhD in Environmental Engineering which I completed from the University of Connecticut in 2023, where my dissertation focused on reaction kinetics and strength development in lime-stabilized clay soils under the supervision of  [Dr. Maria Chrysochoou](https://engineering.missouri.edu/faculty/marisa-chrysochoou/).

## News

{% if site.news.size > 0 %}
<ul>
  {% for news in site.news reversed %}
  <li><strong>{{ news.date | date: "%B %d, %Y" }}</strong> - {{ news.title }}</li>
  {% endfor %}
</ul>
{% else %}
<p>No news items available.</p>
{% endif %}


