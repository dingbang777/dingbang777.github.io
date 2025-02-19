---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi, I am a third-year undergraduate student at Shanghai Jiao Tong University, advised by [Prof. Cewu Lu](https://www.mvig.org/) and [Prof. Yong-Lu Li](https://dirtyharrylyl.github.io/) at MVIG-RHOS. I also intern at Shanghai AI Laboratory, advised by [Prof. Bo Dai](https://daibo.info/) and [Yanhong Zeng](https://zengyh1900.github.io/). Previously, I was a research intern at IRMV, advised by [Prof. Hesheng Wang](https://irmv.sjtu.edu.cn/wanghesheng).

My research interests mainly lies in **Generative Models** and **Embodied AI**. I have background in image generation, 3D human-object interaction and robotic navigation. Now I am pretty interested in **human motion modeling**, **its interaction with object and scene** and its application in **robotics**.

**I am actively looking for internship opportunity during the summer of 2025!**

Education
======
**Shanghai Jiao Tong University**   
* Undergraduate Student
* Major in Physics, Minor in Computer Science and Technology 
* Overall GPA: 3.99, Average score: 91.65, **Rank: 2/54**


Publication
======
**Memorize My Movement: Efficient Sensorimotor Navigation with Self-motion-based Spatial Cognition.**  
Qiming Liu, <u>Dingbang Huang</u>, Zhe Liu, and Hesheng Wang.  
IEEE Transactions on Automation Science and Engineering **(T-ASE)**  

**Reconstructing In-the-Wild Open-Vocabulary Human-Object Interactions.**  
Boran Wen, <u>Dingbang Huang</u>, Zichen Zhang, Jiahong Zhou,Jianbin Deng,Jingyu Gong,Yulong Chen,Lizhuang Ma,Yong-Lu Li.  
Conference on Computer Vision and Pattern Recognition 2025 **(CVPR)** under review



Research Experience
======
**Shanghai AI Laboratory - IDC group & Embodied AI Center**   
* Research Intern – Supervisor: Prof. Bo Dai & Yanhong Zeng
* Research topic: Image generation and editing.
* Layered Image Synthesis with Diffusion Models. Preparing for ICCV2025.

**Shanghai Jiao Tong University - MVIG-RHOS**   
* Undergraduate Research Intern – Supervisor: Prof. Yong-Lu Li & Prof. Cewu Lu
* Research topic: 3D human-object-interaction reconstruction
* Designed a novel 3D HOI optimizer based on 3D Gaussian Splatting and contact optimization to reconstruct the spatial interactions between humans and objects from single images.
* Utilized SOTA 3D reconstruction tools to develop a 3D HOI annotation and reconstruction pipeline, and build a new and scalable in-the-wild 3D HOI dataset Open3DHOI consisting of 2.5k+ images with rich 2D and 3D annotations.

**Shanghai Jiao Tong University - IRMV**   
* Undergraduate Research Intern – Supervisor: Prof. Hengsheng Wang
* Research topic: Robotic navigation
* Developed an efficient memory-enhanced navigation framework called MENEO, which builds spatial cognition of historically explored areas by memorizing the self-movements of mobile robots, thereby eliminating the need to store and process redundant raw scene features as previous methods did. 

Selected Awards
======
* First Prize of Wangban Scholarship, SJTU 
* Foresight&Sequoia Scholarship for Talent Development, SJTU
* Silver Medal Winner in International University Physics Competition
* Third Class Scholarship, SJTU
* Second Prize in National College Student Mathematics Competition

Skills
======
**Skills**  Python(Numpy, Pytorch, Diffusers...), Linux, LaTex, Git&Github, C++, Matlab, RISC-V, SQL, ROS, Habitat
**Languages** English(CET4: 648), Mandarin(native), Cantonese(native)




Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
