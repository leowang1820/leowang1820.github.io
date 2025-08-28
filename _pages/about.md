---
permalink: /
title: ":closed_book: About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! My name is Chengye Wang, and i am a graduate student at the [School of Mechanical Engneering](https://me.bit.edu.cn/) of 
[Beijing Institute of Technology](https://www.bit.edu.cn/) under the supervision of Assoc.Prof.[Yechen Qin](https://me.bit.edu.cn/szdw/jsml/jlgcx/zdyzskzyjs/sssds3/5ba2e729d2ac4afb866e576ffdd0c7c0.htm).

I got my Bachelor's degree at the [College of Automotive Engneering](https://auto.jlu.edu.cn/) of [Jilin University](https://www.jlu.edu.cn/) under the supervison of Prof.[Nan Xu](https://auto.jlu.edu.cn/info/1306/5519.htm) in 2024.

My research interests focuse on path planning and stability control of CAVs especially under extreme scenarios. Based on traditional vehicle dynamic method, i am now thrilled to try to apply the advanced technology such as machine learning into improving the motion performance under complex envrionments. 

I am very motivated and passionate about wheeled robot especially the use of learning-based methods. I am now open to PhD positions especially in decions-making and control of autonomous vehicle. Please feel free to reach out!

:exclamation: News
======
- **[2025.8]** Our article [“基于动态稳定边界的智能车辆路径跟踪控制方法”](http://leowang1820.github.io/files/2025-0035-revised.pdf)（Dynamic Region of Stability Integrated Path-tracking Control for Intelligent Vehicles）has been accepted by **机械工程学报**（Chinese Journal of Mechanical Engineering, **IF=4.5, Q1**）！I provide a stable domain estimation method based on Lyapunov function(LF) for the path-tracking controller.
  
- **[2025.7]** Our team designed a Four-wheel independent drive electric vehicle. I designed the algorithm architecture of steering, driving and braking modules which can be controlled either via a remote control or manually. Despite weighing only 300kg, we achieved a speed of over 50 km/h and the ability to climb a steep slope of 30°！[Here]() is part vedio.
  
- **[2025.5]** Our group won the 4th prize in **City and High-Speed**, [Onsite Autonomous Driving Algorithm Challenge 2025](https://www.onsite.com.cn/#/dist/home), the part vedio can be seen in [here](https://github.com/Daigo111111/2-Onsite-). 

- **[2024.12]** I completed the dual-vehicle state communication based on Ubuntu/ROS, and this algorithm was used in path planning-related research and we provide a [interesting video](https://www.bilibili.com/video/BV1r8RqYJEyP/?vd_source=ae14150a937c3eb3565526f568721c64) based on [BYD,Shenzheng,China](https://www.byd.com/cn) test platfrom. 

- **[2024.9]** I was recommended for admission to Beijing Institute of Technology for graduate studies with the top 5% academic performance at Jilin University.

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

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
