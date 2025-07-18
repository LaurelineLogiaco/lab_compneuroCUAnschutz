---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

<center>
Our group is hosted at the Colorado University Anschutz medical campus, in the Health Sciences Building.
</center>

{%
  include button.html
  type="email"
  text="laureline.logiaco@cuanschutz.edu"
  link="laureline.logiaco@cuanschutz.edu"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Anschutz+Health+Sciences+Building/@39.7454721,-104.8444678,17z/data=!3m1!4b1!4m6!3m5!1s0x876c633a9c45be13:0x85f675e778fce18c!8m2!3d39.7454721!4d-104.8418929!16s%2Fg%2F11pzx9tmvh?entry=ttu&g_ep=EgoyMDI1MDcxMy4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
