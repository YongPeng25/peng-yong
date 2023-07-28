---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My general research interests lie in the development of seismic waveform inversion and modeling
methodologies to effectively derive high-resolution parameter models aimed at subsurface discovery and
utilization. My primary focus is on mitigating the cycle-skipping and reducing inter-parameter crosstalk issues 
in full-waveform inversion (FWI) with misfit function design, regularization techniques, and
optimization methods. I am also interested in numerical PDE solvers for wave propagation problems.
Figure 1 gives a review of my research topics up to now. In short, finite difference and spectral element
methods are used for wavefield simulation in my research. To tackle the local minima issue, I and
collaborators have developed optimal transport distance and local matching filters to capture time shifts
in the seismic data, and total variation regularization is developed for salt body reconstruction. For
multiparameter FWI, I have proposed a parsimonious truncated Newton method to reduce cross-talk
issues from the mathematical point of view. In addition, I am working on the Q estimation, in which I
utilize the peculiar physical features of spectral modification of the waveform related to attenuation to
improve the inversion results. More details about my previous PhD, current postdoc work, and research
plan are presented in the next three sections.

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

 
