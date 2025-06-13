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

# About 

👋 Hi, I’m Mingxi Jia. I am a Ph.D. student in Computer Science at Brown University, advised by Professor Stefanie Tellex. I’m interested in building general-purpose learning-based robot manipulation algorithms. Before Brown, I got my master's degree in Robotics (Computer Science concentration) from Northeastern University, Boston, where I was fortunate to work with Professor Robert Platt. I received my Bachelor's degree (in Mechanical Design, Manufacturing, and its Automation) at Beijing University of Chemical Technology (BUCT). Please feel free to send me an email via mingxi_jia@brown.edu if you have any questions!

# 📢 News 
- *2025.06*: Our paper, [**Learning Efficient and Robust Language-conditioned Manipulation using Textual-Visual Relevancy and Equivariant Language Mapping**](Coming Soon!), is accepted by RAL!
- *2023.01.16*: Our paper, [**SEIL: Simulation-augmented Equivariant Imitation Learning**](https://saulbatman.github.io/project/seil/), is accepted by ICRA 2023!

<details>
  <summary> &nbsp; Click to Expand</summary>

  <article markdown="1" class="post-content">
  - *2024.08*: Our paper, "IMAGINATION POLICY: Using Generative Point Cloud Models for Learning Manipulation Policies", is accepted by CoRL!
  - *2023.09.22*: Our paper, [**A General Theory of Correct, Incorrect, and Extrinsic Equivariance**](https://openreview.net/pdf?id=2FMJtNDLeE), is accepted by NeurIPS 2023!
  - *2022.11.23*: Our work, **SEIL: Simulation-augmented Equivariant Imitation Learning**, will be presented in CoRL 2022 Workshop on Sim-to-Real Robot Learning!
  - *2022.09.15*: Our paper, **On-Robot Learning With Equivariant Models**, is accepted by CoRL 2022!
  - *2022.07.15*: Our paper, **BulletArm: An Open-Source Robotic Manipulation Benchmark and Learning Framework**, is accepted by ISRR 2022!
  </article>
</details>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RAL 2025</div><img src='images/gem.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [Learning Efficient and Robust Language-conditioned Manipulation using Textual-Visual Relevancy and Equivariant Language Mapping](https://arxiv.org/abs/2406.15677)

**Mingxi Jia**$$^*$$, Haojie Huang$$^*$$, Zhewen Zhang, Chenghao Wang, Linfeng Zhao, Dian Wang, Jason Xinyu Liu, Robin Walters, Robert Platt, Stefanie Tellex

<span style="color:black">RAL 2025 </span> 

<!-- <span style="color:grey">In Submission</span> -->
[**Paper**](https://arxiv.org/abs/2406.15677) [**Project**](Coming Soon!) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CoRL 2024</div><img src='images/imagination.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [IMAGINATION POLICY: Using Generative Point Cloud Models for Learning Manipulation Policies](https://arxiv.org/abs/2406.11740)

Haojie Huang, Karl Schmeckpeper\*, Dian Wang\*, Ondrej Biza\*, Yaoyao Qian, Haotian Liu, **Mingxi Jia**, Robert Platt, Robin Walters  

<span style="color:black">CoRL 2024 </span> 

<!-- <span style="color:grey">In Submission</span> -->
[**Paper**](https://arxiv.org/abs/2406.11740) [**Project**](https://haojhuang.github.io/imagine_page/) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/equi_theory.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [A General Theory of Correct, Incorrect, and Extrinsic Equivariance](https://arxiv.org/pdf/2303.04745.pdf)

Dian Wang, Xupeng Zhu, Jung Yeon Park, **Mingxi Jia**, Guanang Su, Robert Platt, Robin Walters  

<span style="color:black">NeurIPS 2023 </span> 

<!-- <span style="color:grey">In Submission</span> -->
[**Paper**](https://arxiv.org/pdf/2303.04745.pdf) [**Project**](https://github.com/pointW/ext_theory) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023</div><img src='images/seil.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [SEIL: Simulation-augmented Equivariant Imitation Learning](https://arxiv.org/abs/2211.00194)

**Mingxi Jia**$$^*$$, Dian Wang$$^*$$, Guanang Su, David Klee, Xupeng Zhu, Robin Walters, Robert Platt

<span style="color:black">ICRA 2023 </span> 

<!-- <span style="color:grey">In Submission</span> -->
[**Paper**](https://arxiv.org/abs/2211.00194) [**Project**](https://saulbatman.github.io/project/seil/) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CoRL 2022</div><img src='images/on_robot.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [On-Robot Learning With Equivariant Models](https://arxiv.org/pdf/2203.04923.pdf)

Dian Wang, **Mingxi Jia**, Xupeng Zhu, Robin Walters, Robert Platt  

<span style="color:black">CoRL 2022 </span> 

<!-- <span style="color:grey">In Submission</span> -->
[**Paper**](https://arxiv.org/pdf/2203.04923.pdf) [**Project**](https://github.com/pointW/equi_rl) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISRR 2022</div><img src='images/bulletarm.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [BulletArm: An Open-Source Robotic Manipulation Benchmark and Learning Framework](https://arxiv.org/pdf/2203.04923.pdf)

Dian Wang\*, Colin Kohler\*, Xupeng Zhu, **Mingxi Jia**, Robert Platt    

<span style="color:black">ISRR 2022 </span> 

<!-- <span style="color:grey">In Submission</span> -->
[**Paper**](https://arxiv.org/pdf/2205.14292.pdf) [**Project**](https://github.com/ColinKohler/BulletArm) 

</div>
</div>

# 📖 Educations
- *2023.09 - now*, Ph.D. in Computer Science, Brown University, Providence. 
- *2021.09 - 2023.06*, M.S. in Robotics (CS concentration), Northeastern University, Boston. 
- *2016.09 - 2020.06*, B.Eng. in Mechanical Design, Manufacturing, and its Automation, Beijing University of Chemical Technology (BUCT). 
