---
layout: page
permalink: /
title: about
---

<div class="text-center mt-5">
  <img class="profile-img" src="{{ 'prof_pic.jpg' | prepend: '/assets/img/' | prepend: site.baseurl }}">
</div>

<div class="col mt-4">
  <h1 class="title text-center font-weight-bold">Eleftherios Mylonas</h1>
  <div class="row mt-3 mb-3">
    <div class="col-sm-6">
      <h6 class="mt-1 text-left text-sm-left" style="font-family: monospace; font-stretch: ultra-condensed;">
        <br/>Applied Electronics Laboratory<br/>
        <a href="http://www.ece.upatras.gr/" target="_blank">Electrical and Computer Engineering Department</a><br/>
        <a href="https://www.upatras.gr/" target="_blank">University of Patras</a><br/>
        Patras, Greece 26500
      </h6>
    </div>
    <div class="col-sm-6">
      <img class="img-responsive" style="width: 100%;" src="{{ 'up_2017_logo_en.jpg' | prepend: '/assets/img/' | prepend: site.baseurl }}" alt="University of Patras Logo">
    </div>
  </div>
</div>

<!-- Introduction -->

<div class="col text-justify p-0">
  <span class="font-weight-bold">Eleftherios Mylonas</span> received his Diploma degree in 2019 from the <a href="http://www.ece.upatras.gr/" target="_blank">Electrical and Computer Engineering Department</a> of University of Patras. He holds research experience in the area of 5G communications for smart grid and Industry 4.0 applications from participating in Horizon 2020 projects. He is currently pursuing a PhD degree at University of Patras. His main research topic is Special purpose edge processors for digital twin applications. His research interests include Next Generation IoT, Digital twins, Cyber-Physical Systems, Intelligent Edge / AI-enabled Edge Computing.
</div>

<!-- News 
<div class="news mt-3 p-0">
  <h1 class="title mb-4 p-0">news</h1>
  {% assign news = site.news | reverse %}
  {% for item in news limit: site.news_limit %}
    <div class="row p-0">
      <div class="col-sm-2 p-0">
        <span class="badge danger-color-dark font-weight-bold text-uppercase align-middle date ml-3">
          {{ item.date | date: "%b %-d, %Y" }}
        </span>
      </div>
      <div class="col-sm-10 mt-2 mt-sm-0 ml-3 ml-md-0 p-0 font-weight-light text">
        <p>{{ item.content | remove: '<p>' | remove: '</p>' | emojify }}</p>
      </div>
    </div>
  {% endfor %}
</div>
-->