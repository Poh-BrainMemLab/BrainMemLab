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

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.7984252891174!2d103.77787097447212!3d1.2955317617490762!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31da1a56c5b19471%3A0x10236dab718a52c!2sMD1%20-%20Tahir%20Foundation%20Building!5e0!3m2!1sen!2ssg!4v1737538787553!5m2!1sen!2ssg" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

{% endcapture %}

{% capture col2 %}

<img src="images/NUSLogo.jpg">

{% endcapture %}


{% include cols.html col1=col1 col2=col2 %}
