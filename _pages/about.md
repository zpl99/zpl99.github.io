---
permalink: /
title: "Zeping Liu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year Ph.D. student in the Department of Geography and the Environment at the University of Texas at Austin, advised by Dr. Gengchen Mai. My research focuses on Geospatial AI and Intelligent Earth Observation, with particular emphasis on geo-foundation models, spatial representation learning, and efficient large-scale, high-resolution remote sensing mapping.

You can access my curriculum vitae here.

Publication
======
<span style="color: #13baf0; font-size: 20px;"><b>Torchspatial: A location encoding framework and benchmark for spatial representation learning</b></span>  
_Nemin Wu, Qian Cao, Zhangyu Wang, **Zeping Liu**, Yanlin Qi, Jielu Zhang, Joshua Ni, Xiaobai Yao, Hongxu Ma, Lan Mu, Stefano Ermon, Tanuja Ganu, Akshay Nambi, Ni Lao, Gengchen Mai_  
arXiv preprint arXiv:2406.15658, 2024  
[paper](https://arxiv.org/abs/2406.15658)

<span style="color: #13baf0; font-size: 20px;"><b>Four seasonal composite Sentinel-2 images for the large-scale estimation of the number of stories in each individual building</b></span>  
_Siqing Lyu, Chao Ji, **Zeping Liu**, Hong Tang, Liqiang Zhang, Xin Yang_  
Remote Sensing of Environment, 2024  
[paper](https://www.sciencedirect.com/science/article/pii/S0034425724000282)

<span style="color: #13baf0; font-size: 20px;"><b>CALIPSO-based aerosol extinction profile estimation from MODIS and MERRA-2 data using a hybrid model of Transformer and CNN
</b></span>  
_Yang Zhen, Xin Yang, Hong Tang, Haoze Shi, **Zeping Liu**_  
Science of The Total Environment, 2024  
[paper](https://www.sciencedirect.com/science/article/pii/S0048969724065793)

<span style="color: #13baf0; font-size: 20px;"><b>China Building Rooftop Area: the first multi-annual (2016–2021) and high-resolution (2.5 m) building rooftop area dataset in China derived with super-resolution segmentation from Sentinel-2 imagery</b></span>  
_**Zeping Liu**, Hong Tang, Lin Feng, Siqing Lyu_  
Earth System Science Data, 2023  
[paper](https://essd.copernicus.org/articles/15/3547/2023/essd-15-3547-2023.html)

<span style="color: #13baf0; font-size: 20px;"><b>National-scale mapping of building footprints using feature super-resolution semantic segmentation of Sentinel-2 images</b></span>  
_Lin Feng, Penglei Xu, Hong Tang, **Zeping Liu**, Peng Hou_  
GIScience & Remote Sensing, 2023  
[paper](https://www.tandfonline.com/doi/pdf/10.1080/15481603.2023.2196154)






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
