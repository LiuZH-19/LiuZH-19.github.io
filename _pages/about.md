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
{% assign url_qwen_music = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:W7OEmFMy1HYC_shieldsio.json" %}
{% assign url_sonar = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:Y0pCki6q_DkC_shieldsio.json" %}
{% assign url_starbech = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:Tyk-4Ss8FVUC_shieldsio.json" %}
{% assign url_songgen = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:2osOgNQ5qMEC_shieldsio.json" %}
{% assign url_songcomposer = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:qjMakFHDy7sC_shieldsio.json" %}
{% assign url_ctrl = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:9yKSN-GCB0IC_shieldsio.json" %}
{% assign url_esg_journal = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:IjCSPb-OGe4C_shieldsio.json" %}
{% assign url_esg = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:u-x6o8ySG0sC_shieldsio.json" %}
{% assign url_ada = gsDataBaseUrl | append: "google-scholar-stats/iELd-Q0AAAAJ:u5HHmVD_uO8C_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
<div style="font-family:Georgia">

Hi👋 nice to meet you!

<br>I am a final-year Ph.D. candidate in the joint Ph.D. program between <a href="https://www.shlab.org.cn/">Shanghai AI Laboratory</a> and <a href="https://www.buaa.edu.cn/">Beihang University</a>, supervised by <a href="http://dahua.site/">Prof. Dahua Lin</a>. At Shanghai AI Laboratory, I work closely with Jiaqi Wang and Yuhang Zang on multimodal LLMs, with a focus on audio-visual understanding and generation.
Before starting my Ph.D., I received my Bachelor’s degree from Beihang University in 2021 and completed two years of master’s study there under the supervision of <a href="https://dbw-buaa.github.io/">Prof. Bowen Du</a>, working on representation learning and forecasting for multivariate time series.

<br><br>I am currently a Research Intern with Alibaba's Qwen Omni team and a core contributor to Video-to-Skill and Qwen-Music. My work spans agentic MLLMs, audio-visual understanding, and audio generation.

<br><br>My current research interests are:
<br><b>◆ Agentic MLLMs: </b><i>multimodal agents, computer-use agents, skill learning from demonstrations, agent harnesses and plugins, and scalable rollout data.</i>
<br><b>◆ Audio-Visual Understanding: </b><i>audio-visual instruction following, deep spatio-temporal reasoning, cross-modal alignment, and reliable evaluation.</i>
<br><b>◆ Audio Generation: </b><i>large-scale autoregressive music models, audio tokenization, controllable song generation and editing, and post-training.</i>

<br><br>
<font style="color: #bf0000"><b>I am on the job market and seeking Research Scientist opportunities that build on my experience in agentic MLLMs, audio-visual understanding, and audio generation. Beyond these core areas, I am also excited about embodied intelligence, interactive multimodal systems, and video generation, and am eager to explore these emerging directions.</b></font>
<br><font style="color: #bf0000"><b>I am always open to research discussions and collaborations.</b></font>
<br><b>Email:</b>&nbsp; <span style="background: #d6eef8">liuzihan@buaa.edu.cn</span>&emsp;&emsp; <b>WeChat:</b>&nbsp; <span style="background: #d6eef8">ZinniaL19</span>
</div>

# Current Focus

<div class="focus-grid">
  <div class="focus-item">
    <b>Agentic MLLMs & Computer-Use Agents</b>
    <span>Developing multimodal agents that acquire reusable skills from human demonstrations and instructional videos, together with scalable rollout pipelines for agentic training data.</span>
  </div>
  <div class="focus-item">
    <b>Audio-Visual Understanding</b>
    <span>Advancing audio-visual instruction following and reasoning across temporal, spatial, and cross-modal evidence, with an emphasis on reliable evaluation.</span>
  </div>
  <div class="focus-item">
    <b>Audio Generation Systems</b>
    <span>Developing music generation systems through tokenizer and model training, controllable song generation and editing, and post-training for Qwen-Music.</span>
  </div>
</div>

# 🔥 News
- *2026.07*: &nbsp;Qwen-Music Technical Report is released on arXiv.
- *2026*: &nbsp;STAR-Bench is accepted by ICLR 2026.
- *2025.05*: &nbsp;SongGen is accepted by ICML 2025.
- *2025.05*: &nbsp;SongComposer is accepted by ACL 2025 main conference.

<span class='anchor' id='internship'></span>
# 💼 Internship

<div class="experience-box" markdown="1">
**Alibaba Cloud Computing Co., Ltd. | Qwen Omni Team, Tongyi Lab**<br>
*Research Intern, 2026.01 - Present*

- **Video-to-Skill (Core Contributor):** I distill reusable and transferable multimodal skills from human demonstrations and instructional videos to guide Computer Use Agents in completing complex customized or out-of-distribution (OOD) tasks. I build the Omni Skill Creator Plugin, spanning 17 categories of office and professional software, and generate high-quality agentic trajectory data for Omni model training and CUA capability enhancement.
- **Qwen-Music (Core Contributor) [[Technical Report](https://arxiv.org/abs/2607.11699)]:** I contribute to the development of Qwen-Music across model training, evaluation, and post-training, with a focus on improving overall generation quality.
</div>

<span class='anchor' id='publications'></span>
# 📝 Publications   <a href='https://scholar.google.com/citations?user=iELd-Q0AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<p><b><sup>*</sup></b> equal contribution.</p>

<span class='anchor' id='audio-visual-understanding'></span>
## Agentic MLLMs, Audio-Visual Understanding and Reasoning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/starbench.png' alt="STAR-Bench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[STAR-Bench: Probing Deep Spatio-Temporal Reasoning as Audio 4D Intelligence](https://arxiv.org/abs/2510.24693) ***[ICLR 2026]***

<b>Zihan Liu<sup>*</sup></b>, Zhikang Niu<sup>*</sup>, Qiuyang Xiao, Zhisheng Zheng, Ruoqi Yuan, Yuhang Zang, Yuhang Cao, Xiaoyi Dong, Jianze Liang, Xie Chen, Leilei Sun, Dahua Lin, Jiaqi Wang

<span>We formalize audio 4D intelligence as reasoning over sound dynamics across time and 3D space, and introduce STAR-Bench to evaluate fine-grained perceptual and spatio-temporal reasoning beyond caption-level semantics.</span>

[**Homepage**](https://internlm.github.io/StarBench/)|
[**Github** ![](https://img.shields.io/github/stars/InternLM/StarBench)](https://github.com/InternLM/StarBench)|
[**arXiv**](https://arxiv.org/abs/2510.24693)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&citation_for_view=iELd-Q0AAAAJ:Tyk-4Ss8FVUC'><img src="https://img.shields.io/endpoint?url={{ url_starbech | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<span class='anchor' id='audio-generation'></span>
## Audio and Music Generation

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/qwen_music_framework.png' alt="Qwen-Music inference framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Qwen-Music Technical Report](https://arxiv.org/abs/2607.11699) ***[arXiv 2026]***

Jin Xu, Kangdi Wang, Ruibin Yuan, Shun Lei, Xiong Wang, Xize Cheng, Xueyao Zhang, Yang Zhang, Yiheng Chen, Yongqi Wang, Yue Wang, Zhifang Guo, <b>Zihan Liu</b>, Zijian Lin, Dake Guo, Hangrui Hu, Lei Xie, Linhan Ma, Wei Xue, Wenxiang Guo, Xinfa Zhu, Xipin Wei, Yangze Li, Yuanjun Lv, Yuxuan Wang, Yunfei Chu, Zhiyong Wu

<span>A large-scale music generation system supporting text-to-music and cover-song generation, with tokenizer/model/render components and post-training for musicality and instruction following.</span>

[**arXiv**](https://arxiv.org/abs/2607.11699)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&citation_for_view=iELd-Q0AAAAJ:W7OEmFMy1HYC'><img src="https://img.shields.io/endpoint?url={{ url_qwen_music | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted</div><img src='images/songgen_x_framework.png' alt="SongGen-X Mixture-of-Adapters framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SongGen-X: Unifying Versatile Editing for Autoregressive Song Generation via Mixture-of-Adapters](https://liuzh-19.github.io/SongGen-X/) ***[Submitted to TASLP]***

<b>Zihan Liu</b>, Ruixing Zhang, Jiaqi Wang, Leilei Sun, Dahua Lin, Yuhang Zang

<span>A unified song editing framework based on Mixture-of-Adapters, supporting fixed- and adaptive-duration inpainting, track-conditioned refinement, style transfer, and lyric editing with a frozen autoregressive backbone.</span>

[**Homepage**](https://liuzh-19.github.io/SongGen-X/)|
[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/SongGen-X)](https://github.com/LiuZH-19/SongGen-X)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/icml2025_songgen.png' alt="SongGen" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SongGen: A Single-Stage Auto-regressive Transformer for Text-to-Song Generation](https://arxiv.org/abs/2502.13128) ***[ICML 2025]***

<b>Zihan Liu</b>, Shuangrui Ding, Zhixiong Zhang, Xiaoyi Dong, Pan Zhang, Yuhang Zang, Yuhang Cao, Dahua Lin, Jiaqi Wang

<span>A fully open-source single-stage autoregressive transformer for controllable song generation, supporting lyric/text control, optional reference voice, and mixed or dual-track output modes.</span>

[**Homepage**](https://liuzh-19.github.io/SongGen/)|
[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/SongGen)](https://github.com/LiuZH-19/SongGen)|
[**arXiv**](https://arxiv.org/abs/2502.13128)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&sortby=pubdate&citation_for_view=iELd-Q0AAAAJ:2osOgNQ5qMEC'><img src="https://img.shields.io/endpoint?url={{ url_songgen | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/acl2025_songcomposer.png' alt="SongComposer" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SongComposer: A Large Language Model for Lyric and Melody Generation in Song Composition](https://arxiv.org/abs/2402.17645) ***[ACL Main 2025]***

Shuangrui Ding<sup>*</sup>, <b>Zihan Liu<sup>*</sup></b>, Xiaoyi Dong, Pan Zhang, Rui Qian, Junhao Huang, Conghui He, Dahua Lin, Jiaqi Wang

<span>A language model that unifies lyric and melody generation in symbolic song representation, enabling multi-task song composition within a single framework.</span>

[**Homepage**](https://pjlab-songcomposer.github.io/)|
[**Github** ![](https://img.shields.io/github/stars/pjlab-songcomposer/songcomposer)](https://github.com/pjlab-songcomposer/songcomposer)|
[**arXiv**](https://arxiv.org/abs/2402.17645)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&sortby=pubdate&citation_for_view=iELd-Q0AAAAJ:qjMakFHDy7sC'><img src="https://img.shields.io/endpoint?url={{ url_songcomposer | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

## Time Series Modeling

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KBS 2025</div><img src='images/kbs2025_egc.jpg' alt="EGC framework with static and evolutionary graph structure learners" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Evolving Graph Structure Learning for Multivariate Time Series Forecasting](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&citation_for_view=iELd-Q0AAAAJ:IjCSPb-OGe4C) ***[Knowledge-Based Systems 2025]***

Junchen Ye<sup>*</sup>, <b>Zihan Liu<sup>*</sup></b>, Bowen Du, Leilei Sun, Weimiao Li, Yanjie Fu, Hui Xiong

<span>The journal version of our graph structure learning work for multivariate time series forecasting.</span>

[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/ESG)](https://github.com/LiuZH-19/ESG)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&citation_for_view=iELd-Q0AAAAJ:IjCSPb-OGe4C'><img src="https://img.shields.io/endpoint?url={{ url_esg_journal | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/ijcai2024.png' alt="CTRL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[An NCDE-based Framework for Universal Representation Learning of Time Series](https://www.ijcai.org/proceedings/2024/0511.pdf) ***[IJCAI 2024]***

<b>Zihan Liu</b>, Bowen Du, Junchen Ye, Xianqing Wen, Leilei Sun

<span>An NCDE-based framework for learning universal time-series representations through reconstruction and contrastive self-supervision across downstream tasks.</span>

[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/CTRL)](https://github.com/LiuZH-19/CTRL)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&citation_for_view=iELd-Q0AAAAJ:9yKSN-GCB0IC'><img src="https://img.shields.io/endpoint?url={{ url_ctrl | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2022</div><img src='images/kdd2022_esg.png' alt="ESG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Learning the Evolutionary and Multi-scale Graph Structure for Multivariate Time Series Forecasting](https://arxiv.org/pdf/2206.13816) ***[KDD 2022]***

Junchen Ye<sup>*</sup>, <b>Zihan Liu<sup>*</sup></b>, Bowen Du, Leilei Sun, Weimiao Li, Yanjie Fu, Hui Xiong

<span>An evolutionary and multi-scale graph learning framework that models dynamic dependencies among multivariate time series.</span>

[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/ESG)](https://github.com/LiuZH-19/ESG)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&sortby=pubdate&citation_for_view=iELd-Q0AAAAJ:u-x6o8ySG0sC'><img src="https://img.shields.io/endpoint?url={{ url_esg | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KBS 2022</div><img src='images/kbs2022.png' alt="Ada-STNet" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Adaptive Spatio-Temporal Graph Neural Network for Traffic Forecasting](https://www.sciencedirect.com/science/article/abs/pii/S0950705122000508) ***[Knowledge-Based Systems 2022]***

Xuxiang Ta, <b>Zihan Liu</b>, Xiao Hu, Le Yu, Leilei Sun, Bowen Du

<span>A dynamic traffic graph learning framework with macro-level self-learning and micro-level self-adaptation for traffic forecasting.</span>

[**Github** ![](https://img.shields.io/github/stars/LiuZH-19/Ada-STNet)](https://github.com/LiuZH-19/Ada-STNet)|
<a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&sortby=pubdate&citation_for_view=iELd-Q0AAAAJ:u5HHmVD_uO8C'><img src="https://img.shields.io/endpoint?url={{ url_ada | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
</div>

{% comment %}
## Other Publications

<div class="other-publications" markdown="1">
- **[The Sonar Moment: An Audio Geo-Localization Benchmark for Audio-Language Models](https://aclanthology.org/2026.findings-acl.1297/)** ***[Findings of ACL 2026]***<br>
  Ruixing Zhang, <b>Zihan Liu</b>, Leilei Sun, Tongyu Zhu, Weifeng Lv<br>
  [**Paper**](https://aclanthology.org/2026.findings-acl.1297/) | <a href='https://scholar.google.com/citations?view_op=view_citation&hl=en&user=iELd-Q0AAAAJ&citation_for_view=iELd-Q0AAAAJ:Y0pCki6q_DkC'><img src="https://img.shields.io/endpoint?url={{ url_sonar | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
</div>
{% endcomment %}

# 🎖 Honors and Awards
- *2021-2025*, 1st Prize, Academic Outstanding Scholarship.
- *2022.10*, National Scholarship, Ministry of Education of PRC.
- *2022.12*, Outstanding Graduate Student.
- *2021.09*, Graduate Entrance Scholarship.
- *2021.06*, Excellent Bachelor’s Thesis; Outstanding Undergraduate Graduate.

# 📖 Education
- *2023.09 - 2027.03*, Ph.D. Candidate, Joint Ph.D. Program between Shanghai AI Laboratory and Beihang University.
- *2021.09 - 2023.06*, M.Sc. in Computer Science and Technology, Beihang University.
- *2017.09 - 2021.06*, B.Sc. in Computer Science and Technology, Beihang University.

<span class='anchor' id='services'></span>
# 🖥️ Services
- **Selected conference reviewing service:** ICLR 2025. [Full reviewing record on OpenReview](https://openreview.net/profile?id=%7EZihan_Liu5).

<!-- # 💬 Invited Talks -->
