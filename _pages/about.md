---
permalink: /
title "Junxiu Lu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

About me
------
I am a senior undergraduate student from Department of Automation / Xinya College, Tsinghua University, majoring in Automation. 

My research interest includes computational imaging, inverse problem, and the relevant biomedical applications.

I am currently a visiting student at [Hopkins Computational Imaging Group](https://hcig.wse.jhu.edu/), Department of Electrical and Computer Engineering, Johns Hopkins University, working with Professor [Yu Sun](https://sunyumark.github.io/). The goal of my project is to investigate physics-informed generative methods for aberration-aware 3D wide-field fluorescence microscopy, with the goal of extending probabilistic reconstruction toward blind deconvolutions.

Previously, I have been an undergraduate researcher at [the Laboratory of Imaging and Intelligent Technology](https://media.au.tsinghua.edu.cn/), Department of Automation, Tsinghua University, working with Professor [Jiamin Wu](https://media.au.tsinghua.edu.cn/info/1011/1118.htm). Through this experience, I have worked on light field microscopy and retinal imaging, gaining basic knowledge about computational imaging and some hands-on experiences on signal processing, light field reconstruction and digital adaptive optics(DAO).

In my spare time, I enjoy hiking, watercolor painting, as well as visiting museums and exhibitions.

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.
