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
{% assign url_starbech = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:Tyk-4Ss8FVUC_shieldsio.json" %}
{% assign url_songgen = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:2osOgNQ5qMEC_shieldsio.json" %}
{% assign url_songcomposer = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:qjMakFHDy7sC_shieldsio.json" %}
{% assign url_ctrl = gsDataBaseUrl | append: "google-scholar-stats/ELd-Q0AAAAJ:9yKSN-GCB0IC_shieldsio.json" %}
{% assign url_esg = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:u-x6o8ySG0sC_shieldsio.json" %}
{% assign url_ada = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:u5HHmVD_uO8C_shieldsio.json" %}





<span class='anchor' id='about-me'></span>
<div style="font-family:Georgia">

Hi👋 nice to meet you!

<br>I am a third-year Ph.D. student in the joint Ph.D. program between <a href="https://www.shlab.org.cn/">Shanghai AI Laboratory</a> and <a href="https://www.buaa.edu.cn/">Beihang University</a>, supervised by <a href="http://dahua.site/">Prof. Dahua Lin</a>. 
Prior to that, I obtained my Bachelor’s degree in 2021 and completed two years of master’s study at Beihang University under the supervision of <a href="https://scholar.google.com/citations?user=QVHvhM4AAAAJ">Prof. Leilei Sun</a>, where my research focused on spatio-temporal data mining and time series analysis.

<br><br>Since beginning my Ph.D., I have been focusing on:
<br><b>◆ Multimodal Large Language Models (MLLMs): </b><i>Large Audio-Language Models (LALMs), Omni Language Models (OLMs), Audio-Visual Alignment / Perception / Reasoning, ... </i>
<br><b>◆ Audio Generation: </b><i>Text-to-Song Generation, Controllable Song Generation & Editing, Spatial Audio Generation, ...</i>

<br><br>
<font  style="color: #bf0000"><b>I am always open to research discussions and collaborations!</b></font>
 <br><font style="color: #bf0000"><b>I expect to graduate in 2027 and am currently seeking internship opportunities. 
Please feel free to contact me if you believe my background and interests align with your work! 
 </b></font> <!-- #0016bfff -->
 <br><b>Email:</b>&nbsp; <span style="background: #d6eef8">liuzihan@buaa.edu.cn</span>&emsp;&emsp; <b>WeChat:</b>&nbsp; <span style="background: #d6eef8">ZinniaL19</span> 
</div>

# 🔥 News
- *2025.05*: &nbsp;🎉🎉 SongGen is accepted by ICML 2025.
- *2025.05*: &nbsp;🎉🎉 SongComposer is accpeted by ACL 2025 main conference.

# 📝 Publications  <a href='https://scholar.google.com/citations?user=iELd-Q0AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<!-- <p>（<b>*</b> equal contribution, <b>&dagger;</b> corresponding authors） </p> -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/starbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[STAR-Bench: Probing Deep Spatio-Temporal Reasoning as Audio 4D Intelligence](https://arxiv.org/abs/2510.24693) ***[arXiv]***

**Zihan Liu**, Shuangrui Ding, Zhixiong Zhang, Xiaoyi Dong, Pan Zhang, Yuhang Zang, Yuhang Cao, Dahua Lin, Jiaqi Wang

<span>We formalize audio 4D intelligence, defined as reasoning over sound dynamics across time and 3D space, and introduce STAR-Bench to measure it, with a focus on linguistically hard-to-describe acoustic cues. </span>

[**Homepage**](https://internlm.github.io/StarBench/)|
[**Github** ![](https://img.shields.io/github/stars/InternLM/StarBench)](https://github.com/InternLM/StarBench)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&citation_for_view=iELd-Q0AAAAJ:Tyk-4Ss8FVUC'><img src="https://img.shields.io/endpoint?url={{ url_starbech | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/icml2025_songgen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SongGen: A Single Stage Auto-regressive Transformer for Text-to-Song Generation](https://arxiv.org/abs/2502.13128) ***[ICML 2025]***

**Zihan Liu**, Shuangrui Ding, Zhixiong Zhang, Xiaoyi Dong, Pan Zhang, Yuhang Zang, Yuhang Cao, Dahua Lin, Jiaqi Wang

<span>A single-stage auto-regressive transformer for text-to-song generation that offers versatile control via lyrics, descriptive text, and an optional reference voice while supporting both mixed and dual-track modes to meet diverse requirements</span>

[**Homepage**](https://liuzh-19.github.io/SongGen/)|
[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/SongGen)](https://github.com/LiuZH-19/SongGen)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&sortby=pubdate&citation_for_view=iELd-Q0AAAAJ:2osOgNQ5qMEC'><img src="https://img.shields.io/endpoint?url={{ url_songgen | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/acl2025_songcomposer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SongComposer: A Large Language Model for Lyric and Melody Generation in Song Composition](https://arxiv.org/abs/2402.17645) ***[ACL main 2025]***

Shuangrui Ding*, **Zihan Liu***, Xiaoyi Dong, Pan Zhang, Rui Qian, Junhao Huang, Conghui He, Dahua Lin, Jiaqi Wang

<span>A language large model that understands and generates melodies and lyrics in symbolic song representations.</span>

[**Homepage**](https://pjlab-songcomposer.github.io/)|
[**Github** ![](https://img.shields.io/github/stars/pjlab-songcomposer/songcomposer)](https://github.com/pjlab-songcomposer/songcomposer)｜
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&sortby=pubdate&citation_for_view=iELd-Q0AAAAJ:qjMakFHDy7sC'><img src="https://img.shields.io/endpoint?url={{ url_songcomposer | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/ijcai2024.png' alt="sym" width="100%"></div></div>   
<div class='paper-box-text' markdown="1">
[An NCDE-based framework for universal representation learning of time series](https://www.ijcai.org/proceedings/2024/0511.pdf) ***[IJCAI 2024]***

**Zihan Liu**, Bowen Du, Junchen Ye, Xianqing Wen, Leilei Sun

<span>Built on a NCDE backbone, the model learns general time-series representations via joint reconstruction and contrastive self-supervision, delivering strong performance across diverse downstream tasks and showing notable robustness to missing data. </span>


[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/CTRL)](https://github.com/LiuZH-19/CTRL)｜
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&citation_for_view=iELd-Q0AAAAJ:9yKSN-GCB0IC'><img src="https://img.shields.io/endpoint?url={{ url_ctrl | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2022</div><img src='images/kdd2022_esg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Learning the evolutionary and multi-scale graph structure for multivariate time series forecasting](https://arxiv.org/pdf/2206.13816) ***[KDD 2022]***

Junchen Ye*, **Zihan Liu***, Bowen Du, Leilei Sun, Weimiao Li, Yanjie Fu, Hui Xiong

<span>We propose an evolutionary and multi-scale graph learning framework that models dynamic dependencies among multivariate time series, achieving superior forecasting performance across domains such as transportation, energy, and finance.</span>

[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/ESG)](https://github.com/LiuZH-19/ESG)｜
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&sortby=pubdate&citation_for_view=iELd-Q0AAAAJ:u-x6o8ySG0sC'><img src="https://img.shields.io/endpoint?url={{ url_esg | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KBS 2022</div><img src='images/kbs2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Adaptive spatio-temporal graph neural network for traffic forecasting](https://arxiv.org/pdf/2206.13816) ***[KDD 2022]***

Xuxiang Ta, **Zihan Liu**, Xiao Hu, Le Yu, Leilei Sun, Bowen Du

<span>We propose a dynamic traffic graph structure with macro-level self-learning and micro-level self-adaptation, demonstrating strong interpretability and effectiveness in traffic forecasting. </span>

[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/Ada-STNet)](https://github.com/LiuZH-19/Ada-STNet)｜
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&sortby=pubdate&citation_for_view=iELd-Q0AAAAJ:u5HHmVD_uO8C'><img src="https://img.shields.io/endpoint?url={{ url_ada | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>


# 🎖 Honors and Awards
- *2023, 2024, 2025*, 1st Prize, Academic Outstanding Scholarship.
- *2022.10*, National Scholarship, Ministry of Education of PRC.
- *2021.09*, Graduate Entrance Scholarship.
- *2021.06*, Excellent Bachelor’s Thesis; Outstanding Undergraduate Graduate. 

# 📖 Educations
- *2023.09 - Present*,  Ph.D. Candidate, Joint Ph.D. Program between Shanghai AI Laboratory and Beihang University.
- *2021.09 - 2023.06*, M.Sc. in Computer Science and Technology, Beihang University (later transferred to the Ph.D. program).
- *2017.09 - 2021.06*, B.Sc. in Computure Science and Technology, Beihang University.
 
# 🖥️ Services
- Conference reviewer for ICLR’25
<!-- # 💬 Invited Talks -->

<!-- # 💻 Internships -->



