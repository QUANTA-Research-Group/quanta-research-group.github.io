---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our group is made up of a team of highly committed and collaborative researchers. We recognize that diverse teams do better research. We foster an environment where team members are treated equally and where we respect and admire our differences. The team includes students and staff at all levels.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

We work with a wide range of leading groups around the world, and are always on the lookout for new and unique perspectives. We want to push the frontiers of quantum computing and train the next generation of scientists.

{%
  include button.html
  text="Join Us"
  link="https://forms.gle/kZnTtzyNYcTYFBBL7"
  new_tab=true
%}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
