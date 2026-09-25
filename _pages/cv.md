---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-nav {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin: 1.25rem 0 2rem;
}

.cv-nav-label {
  flex-basis: 100%;
  margin-bottom: 0.2rem;
  font-size: 0.85em;
  font-weight: 600;
}

.cv-nav a,
.cv-nav a:visited {
  display: inline-block;
  padding: 0.45rem 0.8rem;
  border: 1px solid #1765ad;
  border-radius: 6px;
  background: #f0f7ff;
  color: #155a9c;
  font-size: 0.85em;
  font-weight: 600;
  text-decoration: none;
}

.cv-nav a:hover,
.cv-nav a:focus-visible {
  background: #155a9c;
  color: #ffffff;
  text-decoration: underline;
}

.cv-nav a:focus-visible,
a.cv-download:focus-visible,
a.cv-more:focus-visible {
  outline: 3px solid #155a9c;
  outline-offset: 3px;
}

a.cv-download,
a.cv-download:visited {
  display: inline-block;
  padding: 0.65rem 1rem;
  border: 1px solid #155a9c;
  border-radius: 6px;
  background: #155a9c;
  color: #ffffff;
  font-weight: 600;
  text-decoration: none;
}

a.cv-download:hover {
  background: #104779;
  text-decoration: underline;
}

a.cv-more,
a.cv-more:visited {
  color: #155a9c;
  font-weight: 600;
  text-decoration: underline;
  text-underline-offset: 3px;
}

h2[id] {
  scroll-margin-top: 5rem;
}

@media print {
  .cv-nav,
  .cv-download {
    display: none !important;
  }
}
</style>

**Assistant Professor**  
School of Computing and Artificial Intelligence (SCAI)  
Nazarbayev University, Astana, Kazakhstan

[Download full CV (PDF)]({{ base_path }}/files/documents/CV_Yerlan.pdf){: .cv-download target="_blank" rel="noopener"}

<nav class="cv-nav" aria-label="CV sections">
  <span class="cv-nav-label">Jump to a section:</span>
  <a href="#recognition">Recognition</a>
  <a href="#education">Education</a>
  <a href="#research">Research</a>
  <a href="#publications">Publications</a>
  <a href="#teaching">Teaching</a>
  <a href="#talks">Talks</a>
  <a href="#service">Service</a>
</nav>

## Honors, Awards & Recognition
{: #recognition }

<!-- Verify the exact ICCSA award title and add the awarded paper title/link. -->

| Year | Recognition |
|:-----|:------------|
| **2026** | **Fellow of the Higher Education Academy (FHEA)**, Advance HE |
| **2025** | **[Best Paper Award]({{ base_path }}/posts/2025/07/blog-post-9/)**, International Conference on Computational Science and Its Applications (ICCSA), shared with coauthors. [NU award record](https://research.nu.edu.kz/en/prizes/the-best-paper-award-at-iccsa-2025/){:target="_blank" rel="noopener"} |
| **2024** | **[Best Researcher 2023 Award](https://ssh.nu.edu.kz/tpost/6lc62pydc1-ssh-professors-win-best-researcher-of-th){:target="_blank" rel="noopener"}**, Ministry of Science and Higher Education, Kazakhstan |
| **2018** | Graduate School Summer Fellowship, The University of Texas at Austin, USA |
| **2017** | **[Best Poster Award](https://oden.utexas.edu/news-and-events/news/csems-amanbek-receives-top-poster-award-at-tames/){:target="_blank" rel="noopener"}**, Texas Applied Mathematics and Engineering Symposium (TAMES), USA |
| **2017** | Research Experience in Carbon Sequestration (RECS) Program Award, USA |
| **2017** | SIAM Travel Award, USA |
| **2016** | CIME Foundation and CIRM Grant, Italy |

## Education
{: #education }

**Ph.D. in Computational Science, Engineering & Mathematics**  
[The University of Texas at Austin](https://www.utexas.edu/){:target="_blank" rel="noopener"}, USA · 2018

**M.Sc. in Information Technology**  
[Nanyang Technological University](https://www.ntu.edu.sg/){:target="_blank" rel="noopener"}, Singapore · 2009

**B.Sc. in Applied Mathematics and Computer Science**  
[Al-Farabi Kazakh National University](https://kaznu.kz/en){:target="_blank" rel="noopener"}, Kazakhstan · 2006

## Research Interests
{: #research }

- **Numerical analysis and scientific computing:** finite element methods,
  domain decomposition, multiscale methods, and a priori and a posteriori
  error analysis.
- **Flow and transport in porous media:** numerical modeling of multiphase
  flow, heterogeneous media, and coupled processes.
- **Computational mechanics:** CFD–DEM modeling, fracture processes,
  and sand production.
- **Scientific machine learning:** physics-informed neural networks
  and data-driven modeling for flow and transport.

## Recent Publications
{: #publications }

The six most recent publications are listed below.

{% assign recent_publications = site.publications | sort: "date" | reverse %}

<ul>
{% for post in recent_publications limit:6 %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

[View all publications →]({{ base_path }}/publications/){: .cv-more }

## Teaching & Supervision
{: #teaching }

My teaching includes numerical methods, scientific computing, calculus,
differential equations, and finite element methods.

[View teaching experience and courses →]({{ base_path }}/teaching/){: .cv-more }

[View research students and supervision →]({{ base_path }}/students/){: .cv-more }

## Talks & Presentations
{: #talks }

{% assign recent_talks = site.talks | sort: "date" | reverse %}

<ul>
{% for post in recent_talks limit:3 %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

[View all talks →]({{ base_path }}/talks/){: .cv-more }

## Academic Leadership & Service
{: #service }

- **Deputy Chair**, Republican Student Subject Olympiad in Mathematics
  (6B054), Nazarbayev University, 2026.

- **Journal reviewing:** reviewer for
  [Journal of Computational Physics](https://www.journals.elsevier.com/journal-of-computational-physics){:target="_blank" rel="noopener"}
  (2019).

- **Team Leader**, Nazarbayev University team at the Al-Khorezmi
  International Mathematical Olympiad, Urgench, Uzbekistan, 2018.

- **Team Leader**, Nazarbayev University teams at the 19th and 20th
  International Mathematics Competition for University Students,
  Blagoevgrad, Bulgaria, 2012 and 2013. Responsibilities included
  coordinating selection with faculty, mentoring students, and
  organizing team participation. Team achievements included
  [competition medals](https://nu.edu.kz/news/nazarbayev-university-students-won-a-silver-medal-at-international-mathematical-competition){:target="_blank" rel="noopener"}.

---

*Last updated: September 2026.*


<!-----
#layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
Also full CV is available in [pdf format](/files/documents/CV_Yerlan.pdf){:target="_blank"}.

Education
=====
* Ph.D in Computational Science, Engineering & Mathematics, [The University of Texas at Austin](https://www.utexas.edu/){:target="_blank"}, USA, 2018
* M.Sc. in  IT, [Nanyang Technological University](http://www.ntu.edu.sg){:target="_blank"}, Singapore, 2009
* B.Sc. in Applied Mathematics and Computer Science, [Al-Farabi Kazakh National University](http://kaznu.kz/en){:target="_blank"}, Kazakhstan, 2006

Research Interests
======
_Numerical modeling_: domain decomposition, discretization schemes, multiscale methods,
a posteriori and a priorri error analysis, robust and efficient solution algorithms.

Recent Awards
======
* [Best Paper Award](https://ssh.nu.edu.kz/tpost/6lc62pydc1-ssh-professors-win-best-researcher-of-th){:target="_blank"}{:target="_blank"}, Ministry of Science and Higher Education, Kazakhstan, 2024
* [Best Researcher 2023 award](https://ssh.nu.edu.kz/tpost/6lc62pydc1-ssh-professors-win-best-researcher-of-th){:target="_blank"}{:target="_blank"}, Ministry of Science and Higher Education, Kazakhstan, 2024
* Graduate School Summer Fellowship, the University of Texas at Austin, 2018
* Texas Applied Math & Eng Symposium (TAMES) [Best Poster Award](https://oden.utexas.edu/news-and-events/news/csems-amanbek-receives-top-poster-award-at-tames/){:target="_blank"}{:target="_blank"}, USA, 2017
* Research Experience Carbon Sequestration Program Award, USA, 2017
* SIAM Travel Award, USA, 2017
* CIME-Foundation and CIRM Grant, Italy, 2016

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Recent Talks
======
  <ul>{% for post in site.talks reversed limit%}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Service
======
* Reviewer for peer-reviewed journals: [Journal of Computational Physics](https://www.journals.elsevier.com/journal-of-computational-physics){:target="_blank"} 2019
* Leader of the Nazarbayev University Team at  Al-Khorezmi International Mathematical Olympiad 2018, Urgench, Uzbekistan
* Leader of the Nazarbayev University Team at 19th and 20th International Mathematics
Competition for University Students, Blagoevgrad, Bulgaria 2012 and 2013
  * Organized selection process with Professors from different schools.
  * Mentored students during preparation, coordinated the process team trip and
performance of team.
  * As result, the most participations were awarded with [medals](https://nu.edu.kz/news/nazarbayev-university-students-won-a-silver-medal-at-international-mathematical-competition){:target="_blank"}.

<!--- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3  

  
Work experience
======
  * 2014-: Research Assistant Center for Subsurface Modeling, Institute for Computational Engineering
and Sciences(ICES)
    * Developed adaptive numerical homogenization method for 
ow and transport
model at reduced computational cost. Poster of this work was awarded in the
Texas Applied Math & Eng Symposium.
    * Derived and conducted a priori error analysis for slightly compressible 
ow
using EVMFEM in continuous and discrete time cases.
    * Time domain decomposition methods for 
ow and transport in heterogeneous
porous media problems. Poster was presented in SIAM Conference on Computational
Science and Engineering at Atlanta.
    * Developed a posteriori error estimate for EVMFEM. This is a great in practical
applications in adaptive mesh refinement.
    * Presented research outcomes to industry professionals.
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

  
  Center for Subsurface Modeling, Institute for Computational Engineering
and Sciences(ICES)
* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
 --> 