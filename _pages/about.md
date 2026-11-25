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

<span class='anchor' id='about-SynXR Lab'></span>
The **SynXR (Synesthesia XR) Lab** explores Human-Computer Interaction (HCI) at the intersection of synesthetic experiences and performance art in extended reality (XR) environments. Through an interdisciplinary approach combining Design, Computer Science, Psychology, and Performing Arts, the lab investigates how multi-sensory integration and cross-reality interactions can enhance human perception, creativity, and artistic expression in digital spaces.

<span class='anchor' id='about-me'></span>

Hi, I am **Shuo Yan**, an Associate Professor at [School of New Media Art & Design](https://art.buaa.edu.cn/index.htm) / [State Key Laboratory of Virtual Reality Technology and Systems](https://vrlab.buaa.edu.cn/index.htm) in [Beihang University](https://www.buaa.edu.cn/). I received my Ph.D. in Intelligent Digital Performance from Beijing Institute of Technology, during which I was a visiting Ph.D. student in the Fluid Interfaces at [MIT Media Lab](https://www.media.mit.edu/). I received the Outstanding Doctoral Dissertation Award from China Simulation Federation, the Outstanding Graduation Project Supervisor Award from Beijing Higher Education Institutions, and the Xiaomi Young Scholar Award.

My research focuses on creating novel immersive XR experiences. I have published more than 30 papers and 20 artworks at the top international HCI/XR conferences.

⭐ Looking for highly motivated students and research interns. 招收硕士生及暑期/日常学生科研，有意请联系本人邮箱

# 👩🏻‍🏫 Teaching
- VR Interaction Design 虚拟现实交互设计（本科）
- Information Visualization Design 信息可视化设计（本科）
- Human-Computer Interaction and User Experience Design 人机交互与用户体验设计（研究生）
- Fundamentals of Digital Media Design 数字媒体设计基础（本科）

# 🧪 Research Foundations
- Humanities and Social Science Fund of Ministry of Education of China, Project: **XR-Based Intelligent Performance Perception Generation and Interaction Collaboration**(2022-2025) 教育部人文社会科学基金规划项目
- National Natural Science Foundation of China, Project: **Research on Affective Evaluation and Content-Based Adaptive Feedback for Intelligent Interactive Performance from Audience Perception**(2019-2021) 国家自然科学基金青年项目
- China National Arts Fund, Project: **Construction of Digital Promotion Platform for Intangible Culture Heritage (ICH) ‘Hua er’** (2018-2020) 国家艺术基金传播推广项目
- National Key Research and Development Program of China, Project: **Yunnan Minority Dance Digital Performance Creativity and Display System Based on VR** (2019-2024) 云南省科技厅重点研发项目（子课题）
- Independent Project of the State Key Laboratory of Virtual Reality Technology and Systems, Project: **Research on Innovative Design of Immersive Performance under Human-AI Collaboration**(2024-2026) 虚拟现实技术与系统全国重点实验室自主课题

# 🔔 News 
- Dec, 2026 · SIGGRAPH Asia 2026, Educators Forum Talk, 📍Kuala Lumpur, Malaysia
- Nov, 2026 · ICXR 2026 Conference, <a href="https://icxr.net/2026/ProgramXRGallery.html">**XR Gallery Chair**</a>, 📍Guangzhou, China
- Oct, 2026 · Pacific Graphics 2026 Conference, Demo Presentation, 📍Singapore
- Jan, 2026 · Visiting Researcher in Immersive Reality Lab, National University of Singapore, 📍Singapore

# 📖 Selected Publications

{% assign sel = site.data.publications | where: "selected_pub", true %}
{% for p in sel %}{% include pubs/card.html item=p %}{% endfor %}

<p class="more-link"><a href="{{ '/publications/' | relative_url }}">→ Full publication list ({{ site.data.publications | where_exp: "p", "p.kind != 'work'" | size }} items)</a></p>

# 😈 Selected XR Demos and Artworks

{% assign selw = site.data.publications | where: "selected_work", true %}
<div class="work-grid">
{% for p in selw %}{% include pubs/tile.html item=p %}{% endfor %}
</div>

<p class="more-link"><a href="{{ '/works/' | relative_url }}">→ All XR demos and artworks ({{ site.data.publications | where_exp: "p", "p.kind != 'paper'" | size }} items)</a></p>

# 🏆 Honors and Awards
- 2024 Mentor Award
- 2023 Winner, Second Prize of Outstanding Innovation Cases of Aesthetic Education in Beijing Universities，Beijing Education Commission
- 2023 Mentor Award, BUAA Excellent Master's Thesis BUAA
- 2022 Grant, $14000 Research Funding from Xiaomi Youth Scholarship Xiaomi
- 2022 Grant, $7000 Research Funding from Social Science Youth Scholarship BUAA
- 2021-2022 Mentor Award, Outstanding Undergraduate Graduation Design (Thesis)，Beijing Education Commission
- 2019 Winner, Third Prize of "Teaching Design" in the 7th National Collegiate and Universities Digital Art and Design Competition Ministry of Industry and Information Technology (MIIT)
- 2017 Winner, Outstanding Doctoral Dissertation Award of China Simulation Federation(CSF)
- 2015 Fellowship, National PhD Scholarship in China Ministry of Education of China

# 📚 Educations
- 2013.09 - 2014.09, Visiting PhD Student, MIT Media Lab. 
- 2012.09 - 2017.06, PhD in Software Engineering, Intelligent Digital Performance, BEIJING INSTITUTE OF TECHNOLOGY 
- 2006.09 - 2010.06, Bachelor of DESIGN, Industrial Design / Business Administration (Double Degree), BEIJING INSTITUTE OF TECHNOLOGY

# 💬 Invited Talks
- 2025.11, <a href="https://mp.weixin.qq.com/s/Im6Z4NIer50IrrRqCpHwpA" style="text-decoration: none; color: #00369F;">**Research on Innovative Design of Human-Computer Collaborative Intelligent Performance**</a>, , Dance Research Institute, China National Academy of Arts.  
- 2019.09, <a href="https://www.ted.com/talks/shuo_yan_tedxchengdu" style="text-decoration: none; color: #00369F;">**从"观众"到"创造者"**</a>, TEDxChengdu

