---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I'm Chaeyun Lim, a researcher at Dongguk University interested in RF/mmWave Devices, GaN HEMTs.

This website is where I share my research publications, academic presentations, and professional activities.  
I am currently working on advanced modeling and simulation of AlGaN/GaN HEMTs using Silvaco TCAD, with focus on RF performance optimization and thermal management.

A data-driven personal website
======

Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting
  

Research Experiences
======
Jan 2024 – Dec 2024

Analysis of GaN HEMT Device Characteristics According to Dielectric Layer Composition (Jan – Jun 2024)

▪ Investigated the impact of self-heating effects on the electrical and thermal characteristics of GaN HEMTs.

▪ Analyzed the influence of different dielectric materials (Si₃N₄, Al₂O₃, etc.) on DC to RF performance.

▪ Evaluated heat distribution and designed efficient thermal management structures based on dielectric variation.

Thermal Structure Optimization for GaN HEMTs under Self-Heating Conditions
(Jul – Dec 2024)

▪ Proposed high-efficiency heat dissipation structures for GaN HEMTs using Copper-Filled Thermal Vias and Trench Heat Sinks.

▪ Performed thermal simulations to optimize the heat sink structure and minimize hot spots.

▪ Compared DC and RF thermal characteristics with and without optimized thermal structure
![그림4](https://github.com/user-attachments/assets/e12418a9-10f7-48c2-a01b-af6be99365c5)
![그림6](https://github.com/user-attachments/assets/4a78dee9-0c39-417a-ab4c-0fe91105b382)
![그림7](https://github.com/user-attachments/assets/478faeb5-8975-4178-828c-b5706a1bbbdd)
![그림9](https://github.com/user-attachments/assets/579d9472-6a68-4e17-920b-e18db5c82fcf)

![그림10](https://github.com/user-attachments/assets/cc543357-1324-48d5-8da9-3c0cbf74e526)




Research Interests
======
Jan 2024 – Dec 2024

Analysis of GaN HEMT Device Characteristics According to Dielectric Layer Composition
(Jan – Jun 2024)

▪ Investigated the impact of self-heating effects on the electrical and thermal characteristics of GaN HEMTs.

▪ Analyzed the influence of different dielectric materials (Si₃N₄, Al₂O₃, etc.) on DC to RF performance.

▪ Evaluated heat distribution and designed efficient thermal management structures based on dielectric variation.

Thermal Structure Optimization for GaN HEMTs under Self-Heating Conditions
(Jul – Dec 2024)

▪ Proposed high-efficiency heat dissipation structures for GaN HEMTs using Copper-Filled Thermal Vias and Trench Heat Sinks.

▪ Performed thermal simulations to optimize the heat sink structure and minimize hot spots.

▪ Compared DC and RF thermal characteristics with and without optimized thermal structure

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
