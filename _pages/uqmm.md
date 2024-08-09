---
layout: lab
title: UQMM Lab
permalink: /uqmm/ 
description: 
nav: true
order: 1
profile:
  align: left
  image: uqmm-color.png
---




# Lab Members

<style>
table {
    border-collapse: collapse;
}
table, th, td {
   border: 1px solid white;
}
blockquote {
    border-left: solid blue;
    padding-left: 10px;
}
</style>



#### Graduate Students
<div class ="image-gallery">
  <div class="box"><a href="https://www.linkedin.com/in/zi-xin-wang-6307811ab/?originalSubdomain=au" title="Zixin Wang">
         <img src="/assets/img/student_preview/zixin.jpg" alt="Zixin"  class="img-gallery" />
         <div class ="textbox" style="margin-top:10px;"> <b> Zixin Wang </b> </div>
         <div class ="textbox" style="margin-top:3px;"> Ph.D. <br> 2021.04-Present<br> </div></a>
  </div>


  <div class="box"><a href="https://zhuoxiao-chen.github.io/" title="Zhuoxiao Chen">
         <img src="/assets/img/student_preview/ivan.jpg" alt="Aniket"  class="img-gallery" />
         <div class ="textbox" style="margin-top:10px;"> <b> Zhuoxiao Chen </b> </div>
         <div class ="textbox" style="margin-top:3px;"> Ph.D. <br> 2022.01-Present<br> </div></a>
  </div>

  <div class="box"><a href="https://www.linkedin.com/in/djamahl-etchegaray-888873140/?originalSubdomain=au" title="Djamahl Etchegaray">
         <img src="/assets/img/student_preview/djamahl.png" alt="Djamahl"  class="img-gallery" />
         <div class ="textbox" style="margin-top:10px;"> <b> Djamahl Etchegaray </b> </div>
         <div class ="textbox" style="margin-top:3px;">  Ph.D. <br> 2023.01-Present </div></a>
  </div>

  <div class="box"><a href="https://www.linkedin.com/in/jason-lim-a10a7a189/?originalSubdomain=au" title="Jia Syuen Lim">
         <img src="/assets/img/student_preview/jason-headshot.jpg" alt="Jia"  class="img-gallery" />
         <div class ="textbox" style="margin-top:10px;"> <b> Jia Syuen Lim </b> </div>
         <div class ="textbox" style="margin-top:3px;">  Ph.D. <br> 2023.07-Present </div></a>
  </div>
  <div class="box"><a href="" title="Yuxia Fu">
         <img src="/assets/img/student_preview/yuxia.jpg" alt="Yuxia"  class="img-gallery" />
         <div class ="textbox" style="margin-top:10px;"> <b> Yuxia Fu </b> </div>
         <div class ="textbox" style="margin-top:3px;">  Ph.D. <br> 2024.01-Present </div></a>
  </div>
  <div class="box"><a href="" title="Fengyi Zhang">
         <img src="/assets/img/student_preview/fengyi.jpg" alt="Fengyi"  class="img-gallery" />
         <div class ="textbox" style="margin-top:10px;"> <b> Fengyi Zhang </b> </div>
         <div class ="textbox" style="margin-top:3px;">  Ph.D. <br> 2024.07 </div></a>
  </div>
  <div class="box"><a href="" title="Huitong Yang">
         <img src="/assets/img/student_preview/huitong.jpg" alt="Huitong"  class="img-gallery" />
         <div class ="textbox" style="margin-top:10px;"> <b> Huitong Yang </b> </div>
         <div class ="textbox" style="margin-top:3px;">  Ph.D. <br> 2024.07 </div></a>
  </div>
    <br>
 </div>

#### Visiting Students / Data Science Capstone / Placement Supervision

| **Jacques Serfontein**, *Optimising Lithium Refinery Filtration with Machine Learning*, Feb '24 -- July '24|

| **Junjie Meng, Ziniu Zhang**, *Test-time Domain Adaptation for 3D Object Detection*, Aug '23 -- Nov '23|

| **Yuxia Fu, Zhuo Cao**, *Dataset Distillation for Object Detection*, Feb '23 -- Nov '23|

<br>

# Lab Notes

#### Conference Memo

| 🥐 **[ICCV 2023](https://uqmm.gitbook.io/iccv23-notes/)** (Yadan) - covering tutorials, posters on generalization & 3D vision

| 🏰 **ICLR 2024** (coming soon)


<br>


# Lab News

#### 2024

[Jul '24] 1 paper accepted by IJCV 2024

[Jul '24] 1 paper accepted by MM 2024

[Jul '24] 1 paper accepted by ECCV 2024

- **[Find n' Propagate: Open-Vocabulary 3D Object Detection in Urban Environments](https://arxiv.org/abs/2403.13556)**. ***Djamahl Etchegaray**, Zi Huang, Tatsuya Harada, **Yadan Luo**.* 📝[Paper Link](https://arxiv.org/abs/2403.13556), 🛠️[Github](https://github.com/djamahl99/findnpropagate)



#### 2023


[Nov '23] 🥇 **[Best Student Paper Award](https://www.acmmm2023.org/)**, **Zixin Wang**, **Yadan Luo**, Zhi Chen, Sen Wang, Zi Huang, *Cal-SFDA: Source-Free Domain-adaptive Semantic Segmentation with Differentiable Expected Calibration Error*, 📝[Paper Link](https://arxiv.org/pdf/2308.03003), 🛠️[Github](https://github.com/Jo-wang/Cal-SFDA), ACM Multimedia 2023.

[Nov '23] 🏆 **[Best Demo Award](https://www.acmmm2023.org/)**, **Djamahl Etchegaray**, **Yadan Luo**, Zachary FitzChance, Anthony Southon, Jinjiang Zhong, *Open-RoadAtlas: Leveraging VLMs for Road Condition Survey with Real-Time Mobile Auditing*, ACM Multimedia 2023.


<!-- ### Research Projects
<div class="projects grid">

  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h2 class="card-title text-lowercase">{{ project.title }}</h2>
          <p class="card-text">{{ project.description }}</p>
          <div class="row ml-1 mr-1 p-0">
            {% if project.github %}
            <div class="github-icon">
              <div class="icon" data-toggle="tooltip" title="Code Repository">
                <a href="{{ project.github }}" target="_blank"><i class="fab fa-github gh-icon"></i></a>
              </div>
              {% if project.github_stars %}
              <span class="stars" data-toggle="tooltip" title="GitHub Stars">
                <i class="fas fa-star"></i>
                <span id="{{ project.github_stars }}-stars"></span>
              </span>
              {% endif %}
            </div>
            {% endif %}
          </div>
        </div>
      </div>
    </a>
  </div>
{% endfor %} -->

