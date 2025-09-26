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

I am a Ph.D. candidate in the <a href='https://www.cis.udel.edu/'>Computer & Information Science Department</a> at the <a href='https://www.udel.edu/'>University of Delaware</a>.

I work under the advice of <a href='https://deep-real.github.io/dr_xipeng.html'>Prof. Xi Peng</a> in the <a href='https://deep-real.github.io/'>DeepREAL Lab</a>.

My research interest includes Interpretable Machine Learning, Vision-Language Models, Scientific Machine Learning, and Out-of-distribution Generalization. I have published papers <a href='https://scholar.google.com/citations?user=cwZRdP4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top-tier AI/ML conferences, such as NeurIPS, CVPR, ICML, ECCV, AAAI, etc.



# 🔥 News
- *2025.05*: Passed my Ph.D. Dissertation Proposal defense. &nbsp;🎉🎉
- *2025.03*: I will join the Amazon Science Brand Protection team as summer intern in June. 



# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/Publication/Prostate.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**“Why Is There a Tumor?”: Tell Me the Reason, Show Me the Evidence**

<a href="https://mengmenm.top/" style="color: #494e52; text-decoration: none;">Mengmeng Ma</a>, **Tang Li**, and <a href="https://deep-real.github.io/dr_xipeng.html" style="color: #494e52; text-decoration: none;">Xi Peng</a>

[**Paper**](https://tangli0305.github.io/) \| [**Code**](https://tangli0305.github.io/)
<!-- <strong><span class='show_paper_citations' data='mQFL3DYAAAAJ:2osOgNQ5qMEC'></span></strong> -->
- In Proceedings of the International Conference on Machine Learning, 2025. (acceptance rate 26.9%)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025 Oral</div><img src='images/Publication/failure.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Interpretable Failure Detection with Human-Level Concepts**

<a href="https://nyquixt.github.io/" style="color: #494e52; text-decoration: none;">Kien X. Nguyen</a>, **Tang Li**, and <a href="https://deep-real.github.io/dr_xipeng.html" style="color: #494e52; text-decoration: none;">Xi Peng</a>

[**Paper**](https://arxiv.org/pdf/2502.05275) \| [**Code**](https://github.com/Nyquixt/ORCA)
<!-- <strong><span class='show_paper_citations' data='mQFL3DYAAAAJ:2osOgNQ5qMEC'></span></strong> -->
- In Proceedings of the Annual AAAI Conference on Artificial Intelligence, 2025. (acceptance rate 4.7%)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/Publication/rationale.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Beyond Accuracy: On the Effects of Fine-tuning Towards Vision-Language Model's Prediction Rationality**

<a href="https://wqtwjt1996.github.io/" style="color: #494e52; text-decoration: none;">Qitong Wang</a>, **Tang Li**, <a href="https://nyquixt.github.io/profile/" style="color: #494e52; text-decoration: none;">Kien X. Nguyen</a>, and <a href="https://deep-real.github.io/dr_xipeng.html" style="color: #494e52; text-decoration: none;">Xi Peng</a>

[**Paper**](https://arxiv.org/pdf/2412.13333) \| [**Code**](https://github.com/deep-real/vlm-pred-rationality)
<!-- <strong><span class='show_paper_citations' data='mQFL3DYAAAAJ:2osOgNQ5qMEC'></span></strong> -->
- In Proceedings of the Annual AAAI Conference on Artificial Intelligence, 2025. (acceptance rate 23.4%)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/Publication/Double_correct.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Beyond Accuracy: Ensuring Correct Predictions with Correct Rationales**

**Tang Li**, <a href="https://mengmenm.top/" style="color: #494e52; text-decoration: none;">Mengmeng Ma</a>, and <a href="https://deep-real.github.io/dr_xipeng.html" style="color: #494e52; text-decoration: none;">Xi Peng</a>

[**Paper**](https://arxiv.org/pdf/2411.00132) \| [**Code**](https://github.com/deep-real/DCP) \| [**Video**](https://www.youtube.com/watch?v=c23RWXeI0ok)
<!-- <strong><span class='show_paper_citations' data='mQFL3DYAAAAJ:2osOgNQ5qMEC'></span></strong> -->
- In Proceedings of the  Annual Conference on Neural Information Processing Systems (NeurIPS), 2024. (acceptance rate 25.8%)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024 Strong Double Blind</div><img src='images/Publication/DEAL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DEAL: Disentangle and Localize Concept-level Explanations for VLMs**

**Tang Li**, <a href="https://mengmenm.top/" style="color: #494e52; text-decoration: none;">Mengmeng Ma</a>, and <a href="https://deep-real.github.io/dr_xipeng.html" style="color: #494e52; text-decoration: none;">Xi Peng</a>

[**Paper**](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05615.pdf) \| [**Code**](https://github.com/tangli-udel/DEAL) \| [**Video**](https://www.youtube.com/watch?v=Rd4vFWI2fKw)
<!-- <strong><span class='show_paper_citations' data='mQFL3DYAAAAJ:2osOgNQ5qMEC'></span></strong> -->
- In Proceedings of the European Conference on Computer Vision (ECCV), 2024. ([**Strong Double Blind**](https://eccv.ecva.net/virtual/2024/poster/755), acceptance rate 4.5%)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/Publication/TFL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Beyond the Federation: Topology-aware Federated Learning for Generalization to Unseen Clients**

<a href="https://mengmenm.top/" style="color: #494e52; text-decoration: none;">Mengmeng Ma</a>, **Tang Li**, and <a href="https://deep-real.github.io/dr_xipeng.html" style="color: #494e52; text-decoration: none;">Xi Peng</a>

[**Paper**](https://proceedings.mlr.press/v235/ma24e.html) \| [**Code**](https://github.com/mengmenm/TFL-OOF) \| [**Video**](https://drive.google.com/file/d/1uPGpFzsk_SgV_MA-qnY9k6QlMoyaTqrD/view)
<!-- <strong><span class='show_paper_citations' data='mQFL3DYAAAAJ:2osOgNQ5qMEC'></span></strong> -->
- In Proceedings of the International Conference on Machine Learning, 2024. (acceptance rate 27.5%)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/Publication/DRE.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Are Data-driven Explanations Robust against Out-of-distribution Data?**

**Tang Li**, <a href="https://joffery.github.io/joffery/" style="color: #494e52; text-decoration: none;">Fengchun Qiao</a>, <a href="https://mengmenm.top/" style="color: #494e52; text-decoration: none;">Mengmeng Ma</a>, and <a href="https://deep-real.github.io/dr_xipeng.html" style="color: #494e52; text-decoration: none;">Xi Peng</a>

[**Paper**](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Are_Data-Driven_Explanations_Robust_Against_Out-of-Distribution_Data_CVPR_2023_paper.pdf) \| [**Code**](https://github.com/tangli-udel/DRE) \| [**Video**](https://www.youtube.com/watch?v=4-8zMdB83x8) 
<!-- <strong><span class='show_paper_citations' data='mQFL3DYAAAAJ:2osOgNQ5qMEC'></span></strong> -->
- In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2023. (acceptance rate 25.8%)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPSW 2021 Best Paper Award</div><img src='images/Publication/NeurIPS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Deep Learning for Spatiotemporal Modeling of Urbanization**

**Tang Li**, <a href="https://www.udel.edu/academics/colleges/ceoe/departments/gss/faculty/jing-gao/" style="color: #494e52; text-decoration: none;">Jing Gao</a>, and <a href="https://deep-real.github.io/dr_xipeng.html" style="color: #494e52; text-decoration: none;">Xi Peng</a>

[**Paper**](https://arxiv.org/pdf/2112.09668.pdf) \| [**Video**](https://www.youtube.com/watch?v=3VyVck_gv4g) \| [**Award**](https://sites.google.com/nyu.edu/mlph2021/accepted-papers?authuser=0#:~:text=Deep%20Learning%20for%20Spatiotemporal,Peng%20(University%20of%20Delaware))
<!-- <strong><span class='show_paper_citations' data='mQFL3DYAAAAJ:u5HHmVD_uO8C'></span></strong> -->
- In Proceedings of the Conference on Neural Information Processing Systems (NeurIPS) Workshops on Machine Learning in Public Health (MLPH), 2021. ([**Best Paper Award**](https://sites.google.com/nyu.edu/mlph2021/accepted-papers?authuser=0#:~:text=Deep%20Learning%20for%20Spatiotemporal,Peng%20(University%20of%20Delaware)))
</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🏅 Honors and Awards
- *2025.05* Outstanding Graduate Research Assistant Award 2025, University of Delaware. 
- *2025.01* [**Oral Presentation Award**](https://aaai.org/wp-content/uploads/2025/01/AAAI-25-Oral-Talks-Schedule.pdf), the Annual AAAI Conference on Artificial Intelligence (AAAI).
- *2024.10* **$2,500** CIS Outstanding Conference Travel Award, University of Delaware. 
- *2024.09* [**Strong Double Blind Award**](https://eccv.ecva.net/virtual/2024/poster/755), European Conference on Computer Vision (ECCV).
- *2024.08* **$2,500** CIS Outstanding Conference Travel Award, University of Delaware. 
- *2024.07* **$5,000** API credit from the **OpenAI** Researcher Access Program.
- *2024.05* Distinguished Graduate Student Award 2024, Computer & Information Sciences, University of Delaware. 
- *2023.03* **$1,000** Department Travel Award for Outstanding Conference Publications, University of Delaware. 
- *2022.05* Distinguished Graduate Student Award 2022, Computer & Information Sciences, University of Delaware. 
- *2021.12* [**Best Paper Award**](https://sites.google.com/nyu.edu/mlph2021/accepted-papers?authuser=0#:~:text=Deep%20Learning%20for%20Spatiotemporal,Peng%20(University%20of%20Delaware)), MLPH Workshop, Conference on Neural Information Processing Systems (NeurIPS).

# 📖 Educations
- *2020.08 - present*, Ph.D. in Computer Science, University of Delaware, Newark, DE, USA. 
- *2018.08 - 2020.05*, Master in Computer Science, George Washington University, Washington D.C., USA.
- *2013.09 - 2017.06*, B.Eng. in Software Engineering, East China Normal University, Shanghai, China. 

# 💬 Invited Talks
- *2024.12*, the  Annual Conference on Neural Information Processing Systems (NeurIPS), 2024.  \| [\[video\]](https://www.youtube.com/watch?v=c23RWXeI0ok)
- *2024.09*, the European Conference on Computer Vision (ECCV), 2024.  \| [\[video\]](https://www.youtube.com/watch?v=Rd4vFWI2fKw)
- *2023.05*, the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2023.  \| [\[video\]](https://www.youtube.com/watch?v=4-8zMdB83x8)
- *2021.12*, MLPH Workshop, Conference on Neural Information Processing Systems (NeurIPS), 2021.  \| [\[video\]](https://www.youtube.com/watch?v=3VyVck_gv4g)

<span class='anchor' id='-professional-services'></span>
# 💻 Professional Services
Conference and Journal Reviewer
- Annual Conference on Neural Information Processing Systems (NeurIPS), 2023-2025.
- International Conference on Learning Representations (ICLR), 2025-2026.
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023-2026.
- International Conference on Computer Vision (ICCV) 2025.
- AAAI Conference on Artificial Intelligence (AAAI), 2024.
- IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2022.
- International Conference on Artificial Intelligence and Statistics (AISTATS), 2025-2026.
- British Machine Vision Conference (BMVC), 2024-2025.
- IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2026.
- Remote Sensing (RS), 2022.

DSI Fellow
- *2022.03 - 2025.08, University of Delaware Data Science Institute (DSI), USA.

<span class='anchor' id='-teaching'></span>
# 👨‍🏫 Teaching
- CISC 484 (Introduction to Machine Learning), Teaching Assistant, Fall2022.
- CISC 220 (Data Structure), Teaching Assistant, Fall2023, Spring2024.
- CISC 108 (Introduction to Computer Science), Teaching Assistant, Fall2020, Spring2021, Fall2021.
- CISC 181 (Introduction to Computer Science II), Teaching Assistant, Spring2022, Spring2023.