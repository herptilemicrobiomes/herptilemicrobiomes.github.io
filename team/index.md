---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

The Herptile Microbiome Research Team - We are an interdisciplinary research team led by Donny Walker (Middle Tennessee State University), Jason Stajich (University of California, Riverside), and Joey Spatafora and Kerry McPhail (Oregon State University)

{% include banner.html image="images/logo_v5.png" %}

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: staff"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/nsf.png"
  link1="https://nsf.gov/"
  tooltip1="National Science Foundation"
%}
