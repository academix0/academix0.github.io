---
title: Contact
nav:
  order: 6
  tooltip: Contact information
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Info Lab is a part of the College of Computing and Informatics, Sungkyunkwan University (SKKU), and members of the Lab are leading research activities in several areas of biomedical and information security.

    
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
  link="https://maps.app.goo.gl/q38WE96JXtx5wSny9"
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
