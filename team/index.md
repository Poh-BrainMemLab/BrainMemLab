---
title: People
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html %}

<h4 style="text-align:center;"> Interested in joining our team? Check our <a href="https://poh-brainmemlab.github.io/BrainMemLab/join/">Join Us!</a>
 page for available positions!</h4>
