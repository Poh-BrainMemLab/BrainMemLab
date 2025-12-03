---
title: People
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html %}

<h3 style="text-align:center;"> Interested in joining our team? Click <a href="https://poh-brainmemlab.github.io/BrainMemLab/join/"> here</a> for more information!
</h3>
