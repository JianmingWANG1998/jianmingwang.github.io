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

I am currently a Ph.D. student in the CSE department of the Hong Kong University of Science and Technology (HKUST). My advisors are [Prof. Nevin L. Zhang](https://www.cse.ust.hk/faculty/lzhang/) and [Prof. Zhihong Li](https://ic.pku.edu.cn/szdw/zzjs/L1/lzh/index.htm). My research interests mainly include Brain-Computer Interface (BCI) and Machine Learning, aiming at building intelligent BCI systems.  
**Currently, I am working on: 1) EEG Representation Learning (Self-Supervised Learning); 2) Evaluation of Clinical Solutions using EEG.**

<span class='anchor' id='-news'></span>

# 🔥 News
- *2025.12*: &nbsp;🎉 HKUST PQE Pass!
- *2024.09*: &nbsp;🎉 HKUST New Semester Begins!

<span class='anchor' id='-publications'></span>

# 📝 Publications

## 📄 Conference / Journal Papers

<table style="width:100%; border:none; border-collapse:collapse; margin-top: 20px; border-style: hidden;">
  <tr>
    <td style="width:40%; vertical-align:middle; border:none; padding-right: 25px;">
      <img src="images/deltagatenet_arch.png" alt="DeltaGateNet Architecture" style="width:100%; height:auto; border-radius:8px; box-shadow: 0 4px 8px rgba(0,0,0,0.15);">
    </td>
    <td style="width:60%; vertical-align:middle; border:none; text-align:justify;">
      <div style="font-size: 1.1em; font-weight: bold; line-height: 1.4; margin-bottom: 8px;">
        Bidirectional Temporal Dynamics Modeling for EEG-based Driving Fatigue Recognition
      </div>
      <div style="font-size: 0.95em; color: #444; margin-bottom: 10px;">
        YIP Tin Po*, <strong>Jianming WANG*</strong>, Yutao Miao, Jiayan Zhang, Yunxu Zhao, Xiaomin Ouyang, Zhihong Li, Nevin L. Zhang
      </div>
      <div style="margin-bottom: 12px;">
        <a href="https://jianmingwang1998.github.io/DeltaGateNet/" target="_blank" style="text-decoration:none; font-weight:bold;">[Project]</a> 
      </div>
      <ul style="margin: 0; padding-left: 20px; font-size: 0.92em; line-height: 1.6; color: #222;">
        <li>Proposed <strong>DeltaGateNet</strong>, featuring a <strong>Bidirectional Delta module</strong> to capture asymmetric neural activation and suppression.</li>
        <li>Utilized <strong>Gated Temporal Convolution</strong> with residual learning to extract robust long-term temporal dependencies.</li>
      </ul>
    </td>
  </tr>
</table>

## 📜 Patents
<table style="width:100%; border:none; border-collapse:collapse; margin-bottom: 30px; border-style: hidden;">
  <tr>
    <td style="width:40%; vertical-align:middle; border:none; padding-right: 25px;">
      <div style="background-color:#2c3e50; color:white; display:inline-block; padding:2px 10px; border-radius:20px; font-size:0.75rem; margin-bottom: 8px;">Patent 2024</div>
      <img src="images/Nerve_Tissue_Transmission_Bioelectric_Signal_Processing_Method_and_Equipment.png" alt="patent" style="width:100%; height:auto; max-height:120px; object-fit:contain; border-radius:8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
    </td>
    <td style="width:60%; vertical-align:middle; border:none; text-align:justify;">
      <div style="font-size: 1.02em; font-weight: bold; margin-bottom: 5px;">
        <a href="https://patents.google.com/patent/CN118177838B/en" target="_blank" style="text-decoration:none;">Nerve tissue transmission bioelectric signal processing method and equipment</a>
      </div>
      <div style="font-size: 0.92em; color: #444; margin-bottom: 5px;">
        <strong>Jianming WANG</strong>, Jiapeng He, Yifan Yin, Junshi Li, Dong Huang
      </div>
      <div style="font-size: 0.88em; color: #555; font-style: italic; margin-bottom: 8px;">
        China National Intellectual Property Administration, 2024.
      </div>
      <ul style="margin: 0; padding-left: 20px; font-size: 0.9em; line-height: 1.5;">
        <li>Method and equipment for processing bioelectric signals from nerve tissue transmission.</li>
      </ul>
    </td>
  </tr>
</table>

<table style="width:100%; border:none; border-collapse:collapse; margin-bottom: 30px; border-style: hidden;">
  <tr>
    <td style="width:40%; vertical-align:middle; border:none; padding-right: 25px;">
      <div style="background-color:#2c3e50; color:white; display:inline-block; padding:2px 10px; border-radius:20px; font-size:0.75rem; margin-bottom: 8px;">Patent 2023</div>
      <img src="images/Determination_Method_and_Apparatus_for_Wake_promoting_Electrical_Stimulation_Protocol_in_Disorders_of_Consciousness_Rehabilitation.png" alt="patent" style="width:100%; height:auto; max-height:120px; object-fit:contain; border-radius:8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
    </td>
    <td style="width:60%; vertical-align:middle; border:none; text-align:justify;">
      <div style="font-size: 1.02em; font-weight: bold; margin-bottom: 5px;">
        <a href="https://patents.google.com/patent/CN116712672A/zh" target="_blank" style="text-decoration:none;">Determination Method and Apparatus for Wake‑promoting Electrical Stimulation Protocol in Disorders of Consciousness Rehabilitation</a>
      </div>
      <div style="font-size: 0.92em; color: #444; margin-bottom: 5px;">
        <strong>Jianming WANG</strong>, Jiapeng He, Hao Kang, Yifan Yin, Xianghua Lin, Junshi Li
      </div>
      <div style="font-size: 0.88em; color: #555; font-style: italic; margin-bottom: 8px;">
        China National Intellectual Property Administration, 2023.
      </div>
      <ul style="margin: 0; padding-left: 20px; font-size: 0.9em; line-height: 1.5;">
        <li>A wake-promoting system for rehabilitation of consciousness disorders.</li>
      </ul>
    </td>
  </tr>
</table>

<!-- 专利4 -->
<table style="width:100%; border:none; border-collapse:collapse; margin-bottom: 30px; border-style: hidden;">
  <tr>
    <td style="width:40%; vertical-align:middle; border:none; padding-right: 25px;">
      <div style="background-color:#2c3e50; color:white; display:inline-block; padding:2px 10px; border-radius:20px; font-size:0.75rem; margin-bottom: 8px;">Patent 2023</div>
      <img src="images/Bruxism_Event_Detection_System_and_Bruxism_Data_Processing_Method.png" alt="patent" style="width:100%; height:auto; max-height:120px; object-fit:contain; border-radius:8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
    </td>
    <td style="width:60%; vertical-align:middle; border:none; text-align:justify;">
      <div style="font-size: 1.02em; font-weight: bold; margin-bottom: 5px;">
        <a href="https://patents.google.com/patent/CN115844337B/zh" target="_blank" style="text-decoration:none;">Bruxism Event Detection System and Bruxism Data Processing Method</a>
      </div>
      <div style="font-size: 0.92em; color: #444; margin-bottom: 5px;">
        <strong>Jianming WANG</strong>, Junshi Li, Dong Huang
      </div>
      <div style="font-size: 0.88em; color: #555; font-style: italic; margin-bottom: 8px;">
        China National Intellectual Property Administration, 2023.
      </div>
      <ul style="margin: 0; padding-left: 20px; font-size: 0.9em; line-height: 1.5;">
        <li>System and method for detecting bruxism events and processing related data.</li>
      </ul>
    </td>
  </tr>
</table>

<!-- 专利5 -->
<table style="width:100%; border:none; border-collapse:collapse; margin-bottom: 30px; border-style: hidden;">
  <tr>
    <td style="width:40%; vertical-align:middle; border:none; padding-right: 25px;">
      <div style="background-color:#2c3e50; color:white; display:inline-block; padding:2px 10px; border-radius:20px; font-size:0.75rem; margin-bottom: 8px;">Patent 2023</div>
      <img src="images/Method_and_System_for_Detecting_Bruxism_Movements.png" alt="patent" style="width:100%; height:auto; max-height:120px; object-fit:contain; border-radius:8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1);">
    </td>
    <td style="width:60%; vertical-align:middle; border:none; text-align:justify;">
      <div style="font-size: 1.02em; font-weight: bold; margin-bottom: 5px;">
        <a href="https://patents.google.com/patent/CN115813351A/zh" target="_blank" style="text-decoration:none;">Method and System for Detecting Bruxism Movements</a>
      </div>
      <div style="font-size: 0.92em; color: #444; margin-bottom: 5px;">
        <strong>Jianming WANG</strong>, Junshi Li, Dong Huang
      </div>
      <div style="font-size: 0.88em; color: #555; font-style: italic; margin-bottom: 8px;">
        China National Intellectual Property Administration, 2023.
      </div>
      <ul style="margin: 0; padding-left: 20px; font-size: 0.9em; line-height: 1.5;">
        <li>Method and system specifically for detecting bruxism movements.</li>
      </ul>
    </td>
  </tr>
</table>

<span class='anchor' id='-honors-and-awards'></span>

# 🎖 Honors and Awards
- *2023.12*: Member, HKUST SENG-BICI Entrepreneurship PhD Program [[Link](https://okt.hkust.edu.hk/hkust-collaborative-innovation-center)]
- *2023.06*: Jingjinji National Center of Technology Innovation Excellent Graduate [[Link](https://www.jingjinji.cn/xwzx/ywbb/bf2ab611b35f428e8d0237488557d28b.htm)]
- *2023.06*: Jingjinji National Center of Technology Innovation Cyan Innovatician [[Link](https://mp.weixin.qq.com/s/yKj6PmVAXVBgj0dv0kURmg)]
- *2020.09*: Member, HKUST Innovation Leaders Program [[Link](https://calendar.hkust.edu.hk/events/2020-pilot-scheme-innovation-leaders-program-call-application)]
- *2019.12*: China Unicom Big Data Scholarship

<span class='anchor' id='-educations'></span>

# 📖 Educations
- *2024.08 - Now*: Ph.D. student in Computer Science and Engineering, HKUST.
- *2020.08 - 2023.08*: MSc in Big Data Technology, HKUST.
- *2018.07 - 2018.08*: Summer Exchange Student, Cornell University.
- *2016.08 - 2020.08*: BSc in Computer Science, BNU-HKBU UIC.

<span class='anchor' id='-internships'></span>

# 💻 Internships
- *2020.09 - 2021.01*: Machine Learning Engineer, WeBank.
- *2019.07 - 2019.08*: Big Data Intern, China Unicom.

<span class='anchor' id='-teaching-assistant'></span>

# 👨‍🏫 Teaching Assistant
- *2025 Fall*: **CSIT5910 & MSBD5012: Machine Learning**, *Head TA*, HKUST  
- *2025 Spring*: **COMP 5212: Machine Learning**, *Head TA*, HKUST  
