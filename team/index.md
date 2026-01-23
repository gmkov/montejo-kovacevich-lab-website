---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'master' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'intern' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and group == 'current'" %}
{% include list.html data="members" component="portrait" filter="role == 'visitor' and group == 'current'" %}

{% include section.html background="images/banner.jpg" dark=true %}

{% include section.html %}

## Gone but not forgotten

{% include list.html data="members" component="portrait" filter="group== 'alum'" style="small" %}







