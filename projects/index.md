---
title: Projects
nav:
  order: 1
  tooltip: Working experiments
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include section.html %}

{% capture text %}

{%
  include button.html
  link="projects"
  text="Learn more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Motivation, Curiosity, and Learning"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}


{%
  include button.html
  link="team"
  text="Learn more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Brain states and information processing"
  text=text
%}

{% capture text %}


{%
  include button.html
  link="team"
  text="Learn more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Enhancing human cognition with neurofeedback"
  text=text
%}


