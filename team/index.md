---
title: Team
nav:
  order: 2
  tooltip:
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a growing team of people who value each other's unique expertise and perspective, and are united in our efforts to study how the brain generates movement.

If you are interested in joining us, please contact [Laureline Logiaco](mailto:laureline.logiaco@cuanschutz.edu) and include a CV and a statement of research interests. Laureline is affiliated with the [Neuroscience](https://www.cuanschutz.edu/graduate-programs/neuroscience/home), [Bioengineering](https://engineering.ucdenver.edu/bioengineering/graduate-programs/phd-in-bioengineering) and [Computational Bioscience](https://www.cuanschutz.edu/graduate-programs/computational-bioscience/home) graduate programs.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role != 'pi'" %}
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include section.html %}

{% capture col1 %}


{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/team_pic.png"
  caption=""
%}

{% endcapture %}

{% capture col3 %}


{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

