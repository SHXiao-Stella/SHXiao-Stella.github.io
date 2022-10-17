---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a Master Candidate in the Department of Finance and Investment at School of Business, Sun Yet-san University.

My primary research interests lie in systemic risk. I've researched how asset securitization causes systemic risk, how banks escape from the regulation by the cross-holding behavior of  securitization, and what is the optimal banking bailout when systemic risk happens. Helping me along the way, I've been learning how to apply recent techniques in machine learning to these practical problems. I have presented a Predict-Gradient-Optimization framework and have applied it to the problem of optimal bank bailout. By using neural networks, I open the black-box formed between the rescue vector and the rescue effect based on the fixed point system under the extended E-N model and make the objective function derivable. I also have interests in macroeconomic modeling and portfolio management.

## Education
======
  + Master of Finance, School of Business, Sun Yat-sen University. Mentor: [Shushang Zhu](https://bus.sysu.edu.cn/en/teacher/ZhuShushang), Professor
  + Bachelor of Financial Management, School of Business, Sun Yat-sen University.

## Research 
======
  + Xiao S.H, [Zhu S.S.](https://bus.sysu.edu.cn/en/teacher/ZhuShushang), [Wu Y](https://www.ying-wu.net/cv). [Asset Securitization, Cross Holdings, and Systemic Risk in Banking](http://dx.doi.org/10.2139/ssrn.4018464).
  + Xiao S.H. [Ma J.L.](https://cbds.gufe.edu.cn/info/1044/2255.htm), [Xia L.](https://bus.sysu.edu.cn/en/teacher/XiaLi), [Zhu S.S.](https://bus.sysu.edu.cn/en/teacher/ZhuShushang) Optimal Systemic Risk Bailout: A PGO Approach Based on Neural Network（Working paper）

## Miscellanea
======
  + My github page can be found [here](https://github.com/SHXiao-Stella).
  + My bilibili page can be found [here](https://space.bilibili.com/388356166/video), which contents my original videos and so on.
  + My personal Wechat Official account is named “言书界”. You can reach it by press this [link](https://mp.weixin.qq.com/mp/profile_ext?action=home&__biz=MzI1NDU0MzI2Nw==&scene=117#wechat_redirect), copy the website and open the website by Wechat.

## Skills
======
  + MATLAB, Python, Stata, Eviews, R
  + Chinese(Native), English, Cantonese

## Contact Information 
======
You can reach me at <sydyx2016@163.com>.


This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).


