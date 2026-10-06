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

I am a Ph.D. student in Computer and Information Technology at Purdue University, advised by [Prof. Wenhai Sun](https://whsun.org/).

My research focuses on **AI security and privacy**, with current interests in **robust watermarking and provenance for generative language, speech, and audio**. I study how security and privacy mechanisms behave under adversarial manipulation, spanning differential privacy, data poisoning, backdoor attacks, and privacy-preserving machine learning. My current work develops robust watermarking for LLM-generated text, with a focus on improving detection after rewriting while preserving generation quality.

[**CV (PDF)**](/pdf/Xiaolin_Li_CV.pdf)

# 🔥 News
- *Sep 2026*, Our paper **“Your Privacy My Cloak: Backdoor Attacks on Differentially Private Federated Learning”** was accepted to *IEEE S&P 2027*! Grateful to my coauthors for their dedication and support!
- *Aug 2026*, I joined Xmotors AI in Santa Clara as a Machine Learning Engineer Intern, working on audio watermarking and provenance for generative speech and audio.
- *Oct 2025*, Honored to be selected by Purdue University as an RSAC Security Scholar. Grateful for the opportunity and excited to join RSAC 2026 in San Francisco!
- *Apr 2025*, Our paper **“Mitigating Data Poisoning Attacks to Local Differential Privacy”** was accepted to *ACM CCS 2025*! Thanks to all of my collaborators. 

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE S&amp;P 2027</div><img src='images/RING.png' alt="Overview of RING: coordinated perturbations conceal malicious client updates and cancel during server aggregation" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Xiaolin Li`, Ning Wang, Ninghui Li, Wenhai Sun. *Your Privacy My Cloak: Backdoor Attacks on Differentially Private Federated Learning*. **IEEE Symposium on Security and Privacy (S&P), 2027. Accepted.**<br>
[[PDF]](/pdf/RING.pdf) [[arXiv]](https://arxiv.org/abs/2606.17035)

Studies how differential privacy can conceal malicious updates in federated learning, exposing the limits of existing defenses against backdoor attacks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM CCS 2025</div><img src='images/MDPA.png' alt="Overview of poisoning detection and mitigation for local differential privacy" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Xiaolin Li`, Ninghui Li, Boyang Wang, Wenhai Sun. *Mitigating Data Poisoning Attacks to Local Differential Privacy*. **ACM Conference on Computer and Communications Security (CCS), 2025.**<br>
[[PDF]](/pdf/MDPA.pdf)

Develops malicious-report detection and attack-resilient post-processing to mitigate poisoning and recover utility in private frequency estimation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TETC. 2023</div><img src='images/RecPool.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Xiaolin Li`, Qikui Xu, Zhenyu Xu, Hongyan Zhang, Li Xu. *Graph Reconfigurable Pooling for Graph Representation Learning*. *IEEE Transactions on Emerging Topics in Computing*. 2023. 
[[PDF]](/pdf/Recpool.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing. 2023</div><img src='images/DP-DGAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Xiaolin Li`, Li Xu, Hongyan Zhang, Qikui Xu. *Differential privacy preservation for graph auto-encoders: A novel anonymous graph publishing model*. *Neurocomputing*. 2023. 
[[PDF]](/pdf/DP-DGAE.pdf)

</div>
</div>

- Zhenyu Xu, Yifan Li, `Xiaolin Li`, Xinxin Zhang, Li Xu. *Influence Maximization in Partially Observable Mobile Social Networks*. *MobiMedia*. 2023.
[[PDF]](/pdf/Zhenyu_MobiMedia_23.pdf)


- Hongyan Zhang, `Xiaolin Li`, Jiayu Xu, Li Xu, *Graph matching based privacy-preserving scheme in social networks*. *SocialSec*. 2021.  
[[PDF]](/pdf/Hongyan_SocialSec_21.pdf)


# 🔬 Research Experience
**Machine Learning Engineer Intern · Xmotors AI**<br>
Santa Clara, CA · Aug. 2026–Present
- Research audio watermarking and provenance for generative speech and audio, including detection that remains reliable after audio re-encoding.
- Develop evaluation pipelines on open speech and music models to assess robustness to compression, time shifts, and speed changes, alongside detection accuracy and audio quality.

**Research Assistant · Purdue University**<br>
West Lafayette, IN · Sep. 2023–Present
- **Robust LLM watermarking:** Develop watermarking methods for AI-generated text, studying the trade-offs among robustness to rewriting, detection reliability, and generation quality.
- Study security and privacy in machine learning, including poisoning defenses for local differential privacy and backdoor attacks on differentially private federated learning.

**Research Assistant · Fujian Normal University**<br>
Fuzhou, China · Sep. 2020–Jun. 2023
- Studied differential privacy and graph learning for privacy-preserving graph publication and representation learning.

# 🏅 Honors and Awards
- *2025.10*, Selected as an RSAC 2026 Security Scholar, Purdue University.
- *2023.09*, Presidential Doctoral Excellence Award, Purdue University.

<span class='anchor' id='-educations'></span>

# 🎓 Education
- *2023.09–Present*, Ph.D. in Computer and Information Technology, Purdue University, West Lafayette, IN, USA.
- *2020.09–2023.06*, M.S. in Cybersecurity, Fujian Normal University, Fuzhou, China.
- *2016.09–2020.06*, B.E. in Network Engineering, Shandong Agricultural University, Taian, China.
 

# 💬 Professional Service
- Reviewer
  - IEEE INFOCOM 2026.
  - IEEE TIFS 2025; IEEE TDSC 2025/2026; IEEE TKDE 2026; ACM TKDD 2025/2026; Journal of the Chinese Institute of Engineers 2025; The Journal of Supercomputing 2024.

  
