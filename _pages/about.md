---
permalink: /
title: "About me"
author_profile: true 
redirect_from: 
  - /about/
  - /about.html
---

I received my Ph.D. degree in Computer Science and Technology from Zhejiang University under the supervision of Professor [Jinsong Han](https://person.zju.edu.cn/en/hanjinsong#0). Previously, I received my B.Eng in Computer Science and Technology from Wuhan University (Outstanding Engineer Class) in 2019.

More details can be found in my [CV](https://person.zju.edu.cn/en/hanjinsong#0).

Research Interests
======
Mobile Computing, Wireless Sensing, IoT Security, Millimeter Wave


Publications
======
**[USENIX Security 2025, CCF-A]** DiskSpy: Exploring a Long-Range Covert Channel via mmWave Sensing of 𝜇m-level HDD Vibrations. Proceedings of USENIX Security Symposium, 2025.  
***Weiye Xu***, Danli Wen, Jianwei Liu, Zixin Lin, Yuanqing Zheng, Jinsong Han  
[Paper]()  [Slides]()  [Video]()


**[MOBICOM 2022, CCF-A]** Mask Does Not Matter: Anti-Spoofing Face Authentication using mmWave Without On-site Registration. Proceedings of the 28th Annual International Conference on Mobile Computing And
 Networking, 2022.  
***Weiye Xu***, Wenfan Song, Jianwei Liu, Yajie Liu, Xin Cui, Yuanqing Zheng, Jinsong Han, Xinhuai
 Wang, Kui Ren  
 [Paper]()  [Slides]()  [Video]()


**[INFOCOM 2021, CCF-A]** RFace:Anti-Spoofing FacialAuthentication Using COTS RFID. Proceedings of IEEE International Conference on Computer Communications, 2021.  
***Weiye Xu***, Jianwei Liu, Shimin Zhang, Yuanqing Zheng, Feng Lin, Jinsong Han, Fu Xiao, Kui Ren  
[Paper]()  [Slides]()  [Video]()


**[TMC 2023, CCF-A]** Anti-Spoofing FacialAuthentication Based on COTS RFID. IEEE Transactions on Mobile Computing, 2023. 
***Weiye Xu***, Jianwei Liu, Shimin Zhang, Yuanqing Zheng, Feng Lin, Fu Xiao, Jinsong Han 
[Paper]() 

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
