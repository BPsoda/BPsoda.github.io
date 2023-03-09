---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a junior student at Shanghai Jiao Tong University, majoring in automation(IEEE class). I love to study how the digital world percepts and controls the physical world. So, I have interest in computer vision, robotics and deep learning.  

Currently, I am researching deep-learning-based visual mapping and localization, advised by Prof. Hesheng Wang. I am looking forward to a Ph.D degree in control science or computer science.

Favored programming language: Python, C++, Matlab. Like to program in an organized way: understandable variable names, clean comments, good file structure and git commit logs. Hate functions that written by other programmer but have no comments or docs.

# 🎖 Honors and Awards
- *2022.11* CUMCM, Provincial Second Prize
- *2022.10* Suzhou Yu Cai Scholarship
- *2022.10* SJTU Scholarship, Grade B
- *2022.4* COMAP, M Prize
- *2021.10* COSCO Scholarship, Third Award
- *2021.10* SJTU Scholarship, Grade B

# 📖 Educations
- *2020.06 - now*, Undergraduate, Shanghai Jiao Tong University, Shanghai.  
  **Score**: 91.02/100 **Rank**: 1/28

# 💬 Language
- *CET6* 660
- *TOEFL* 104 (Reading 29, Listening 29, Speaking 22, Writing 24)


# 💻 Projects
## Make Illustrator Relationship Visible
[github](https://github.com/BPsoda/ICE2604-illustrator-knowledge-grapgh)  
The final project for course ICE2604(电类工程导论). It is a cooperation project led by me. This project includes:  
- *Scraper* We implemented a data scraper with Python and get information of illustrators and illustrations from [pixiv](https://www.pixiv.net)
- *Database* The data are stored and organized in mysql.
- *Analyze & Visualization* We analyze the relationship among illustrators by tags attached to their works and followers. Then, we visualized these results as charts and a huge relation map.
- *Website* We designed an interactive website where users can look into statistics, search for illustrators and browse illustrations.

## A P2P BBS
[github](https://github.com/BPsoda/ComputerNetHomework)  
A BBS based on P2P network. Final project for Computer Network.

## Fundus Images Processing
Final project for Digital Image Processing.   
We first localize the macula lutea with CNN, the align and normalize the image. Next, the vessels are segmented with U-Net and are removed to get clean images with Fast Marching Method (FMM).