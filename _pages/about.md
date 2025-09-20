---
permalink: /
title: Welcome to my website!
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
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

I am a postdoctoral researcher at [Pacific Northwest National Laboratory (PNNL)](https://www.pnnl.gov/) investigating the complexities of environmental systems with a combined approach of experimental analysis and model simulations. My research combines advanced spectroscopic and spectrometric analysis of soil and water samples with biogeochemical and geochemical modeling to develop better understandings of environmental systems. I am the science point of contact for running samples in [Pyrolysis Gas Chromatography Mass Spectrometry (PyGCMS)](https://www.emsl.pnnl.gov/science/instruments-resources/pyrolysis-gas-chromatography-mass-spectrometry) at [EMSL](https://www.emsl.pnnl.gov/), PNNL's user facility. If you are interested to find the chemical fingerprint of the organic polymers in your samples, please reach out! 

I completed my Ph.D. in Environmental Engineering from the University of Connecticut in 2023, where my dissertation examined reaction kinetics and strength development in lime-stabilized clay soils under the supervision of  [Dr. Maria Chrysochoou](https://engineering.missouri.edu/faculty/marisa-chrysochoou/).



