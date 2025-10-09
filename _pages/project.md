---
title: "Ronghao Lin - Project"
layout: textlay
excerpt: "Ronghao Lin - Project"
sitemap: false
permalink: /project
---

# Participated / Led Project

<div style="margin-top: 35px"></div>

<script async defer src="https://buttons.github.io/buttons.js"></script>

{% for proj in site.data.project %}
<div class="row">
<h3>&#9654; {{ proj.topic }}</h3>
<div  style="margin-top: -15px" >
  <center><img src="{{ site.url }}{{ site.baseurl }}/assets/proj_imgs/{{proj.photo.name}}" class="img-responsive" width="{{proj.photo.scale}}" alt="centered image"  style="margin-left: 20px" /></center>
</div>
  
<div  style="margin-left: 20px;margin-top: -20px">
  {% if proj.paper %}<span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;"><a href="{{proj.paper.link}}">{{proj.paper.name}}</a></strong><br />{% endif %}
  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;"><a href="{{proj.site.link}}">Project site</a>{% if proj.site.note %} ({{proj.site.note}}){% endif %}</strong> &nbsp; &nbsp; &nbsp; 
  <br>
  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">Description: </strong>{{ proj.desc}}


</div>
</div>

<div style="margin-top: 45px"></div>
{% endfor %}






