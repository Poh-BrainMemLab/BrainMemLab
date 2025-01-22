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

<iframe src="[https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d306141.380212437!2d126.3453416664724!3d33.3711157139061!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x350ce3544cc84045%3A0x66bc36d2981ebf31!2sJeju-do%2C+South+Korea!5e0!3m2!1sen!2sus!4v1473136714592](https://www.google.com/search?q=national+university+of+singapore+logo&sca_esv=92b12e7e59cf2f55&rlz=1C5CHFA_enUS965US965&udm=2&biw=1440&bih=695&sxsrf=ADLYWIKXDsmcgJeYzxYM4lr569jefah2ZQ%3A1737536633362&ei=ebSQZ72hFZ3m4-EP59_KkQE&ved=0ahUKEwj9wcKu_IiLAxUd8zgGHeevMhIQ4dUDCBE&uact=5&oq=national+university+of+singapore+logo&gs_lp=EgNpbWciJW5hdGlvbmFsIHVuaXZlcnNpdHkgb2Ygc2luZ2Fwb3JlIGxvZ28yBRAAGIAEMgUQABiABDIEEAAYHjIEEAAYHjIGEAAYBRgeSNwkUIUGWJEjcAN4AJABA5gB0wGgAagXqgEGMjguNi4zuAEDyAEA-AEBmAIloAKFFMICBhAAGAcYHsICBBAjGCfCAgsQABiABBixAxiDAcICDhAAGIAEGLEDGIMBGIoFwgIKEAAYgAQYQxiKBcICCBAAGIAEGLEDwgIEEAAYA5gDAIgGAZIHBjMxLjQuMqAH-OsB&sclient=img#vhid=d6WKyIFUKmJXWM&vssid=mosaic)" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/NUSLogo.jpg"
%}

{% endcapture %}


{% include cols.html col1=col1 col2=col2 %}
