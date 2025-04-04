---
title: Contact
nav:
  order: 6
  tooltip: Contact information
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the Department of Integrative Structural and Computational Biology at Scripps Research. We are based in La Jolla, CA, though we have many lab members and contributors distributed throughout the US and Canada.

{%
  include figure.html
  image="images/scripps-research-email-logo.png"
  width="300px"

%}

{%
  include button.html
  type="email"
  text="asu@scripps.edu"
  link="asu@scripps.edu"
%}
<!--
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
-->
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/ezXbwnAmZ3QSPHW3A"
%}

{%
  include button.html
  type="directions"
  tooltip="Directions for visitors"
  link="/contact/directions"
%}
{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/scripps_skaggs.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/1600w_la_jolla_campus_09.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% capture col3 %}

{%
  include figure.html
  image="images/1000014768.jpg"
%}

{% endcapture %}

{% capture col4 %}

{%
  include figure.html
  image="images/scripps_aerial.jpg"
%}

{% endcapture %}


{% include cols.html col1=col3 col2=col4 %}
