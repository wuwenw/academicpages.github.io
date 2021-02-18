---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Wuwen Wang, an incoming CS Ph.D. student at XXX University. I received my master's degree in Electrical & Computer Engineering from Carnegie Mellon University and my bachelor's degree in Computer Engineering from UIUC.

My research primarily focuses on large-scale high-performance data systems. I’m currently working on the query execution in databases. 

I’m fortunate enough to be a member of [Carnegie Mellon Database Group](https://db.cs.cmu.edu/) and work with [Prof. Andy Pavlo](https://www.cs.cmu.edu/~pavlo/). During my time at CMU DB, I have been a developer for [NoisePage](https://noise.page/), the self-driving in-memory database we developed at CMU. 

If you’re a CMU student interested in database research, talk to Andy when he is back! He is one of the best professors and brilliant people I’ve met. He is in love with DB (Which appears to be the second most important thing in his life : ). He also treats students as friends and always tries his best to help them, either in research or life. He has introduced the beauty of databases to me and, more importantly, made me a better person.

I’m going to work as an intern for the [Apache Pinot](https://pinot.apache.org/) and begin my Ph.D. study in the fall.

Don’t hesitate to contact me if you would like to collaborate or need any information.

[CV](https://wuwenw.github.io/files/cv.pdf)

Publications
======
1. L. Ma, W. Zhang, J. Jiao, **W. Wang**, M. Butrovich, W. Lim, P. Menon, A. Pavlo. “MB2: Decomposed
Behavior Modeling for Self-Driving Database Management Systems” (Submitted to SIGMOD 2021)
2. L. Zhang, M. Butrovich, T. Li, A. Pavlo, Y. Nannapaneni, J. Rollinson, H. Zhang, A. Balakumar, D. Biales, Z.
Dong, E. J. Eppinger, J. E. Gonzalez, W. S. Lim, J. Liu, L. Ma, P. Menon, S. Mukherjee, T. Nayak, A. Ngom, D. Niu, D. Patra, P. Raj, S. Wang, **W. Wang**, Y. Yu, and W. Zhang, "Everything is a Transaction: Unifying Logical Concurrency Control and Physical Data Structure Maintenance in Database Management Systems". Conference on Innovative Data Systems Research, 2021.
3. Liu, C., Das, A., **Wang, W.**, Küchemann, S., Kenesei, P., & Maass, C. R. E. (2019). “Shear-band cavities and strain hardening in a metallic glass revealed with phase-contrast x-ray tomography”. Scripta Materialia, 170, 29-33.

Honors
------
1. The Dean’s List of College of Engineering
2. Earl J. Eckel Scholarship

Teaching
------
1. 15445 [Database Systems](https://15445.courses.cs.cmu.edu/fall2020/)

MISC.
------


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
