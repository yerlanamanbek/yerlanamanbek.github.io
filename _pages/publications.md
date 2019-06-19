---
#layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Recent Posters
====
* [Best Poster Award:](https://www.ices.utexas.edu/about/news/494/){:target="_blank"}{:target="_blank"} "Adaptive Numerical Homogenization for Upscaling Single Phase Flow and
Transport", Y. Amanbek, G. Singh and M. F. Wheeler, Texas Applied Mathematics
and Engineering Symposium (TAMES), September 21-23, 2017, Austin, Texas. [Link](https://figshare.com/articles/Adaptive_Numerical_Homogenization_for_Upscaling_Single_Phase_Flow_Transport/5414203){:target="_blank"}
 
* "Selective Time-stepping adaptivity for Non-Linear Reactive Transport Problems",
Y. Amanbek, G. Singh and M. F. Wheeler, SIAM Conference on Computational
Science and Engineering (CSE17), February 26-March 3, 2017, Atlanta, Georgia. [Link](https://figshare.com/articles/poster_siam_cse17_adaptive_time_print_version_pdf/4702549){:target="_blank"}
