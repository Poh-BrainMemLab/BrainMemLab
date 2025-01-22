---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{%
  include button.html
  type="email"
  text="poh.brainmemlab[at]gmail.com"
  link="poh.brainmemlab@gmail.com"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

<iframe src="https://maps.app.goo.gl/FPYMdeg8BhpKsQnP6"></iframe>

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/NUSLogo.jpg"
%}

{% endcapture %}


{% include cols.html col1=col1 col2=col2 %}
