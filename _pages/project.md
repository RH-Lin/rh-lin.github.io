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

<span style="padding-left: 10px;"></span><h3> {{ proj.topic }}</h3>

{% if proj.photo %}
<table>
  <tbody>
      <tr>
        <td width="25%">
          <div  style="margin-top: -15px" >
            <center><img src="{{ site.url }}{{ site.baseurl }}/assets/project_imgs/{{proj.photo.name}}" class="img-responsive" width="{{proj.photo.scale}}" alt="centered image"  style="margin-left: 20px" /></center>
          </div>
        </td>
        <td>
          <div  style="margin-left: 20px;margin-top: -20px">
            <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{proj.title.name}}</strong> {% if proj.title.link %}&nbsp;<a href="{{proj.title.link}}">\[link\]</a>{% endif %} <br />
            <strong style="font-size: 17px;">Leader: </strong>{{proj.title.leader}},&nbsp;{{proj.title.time}}
            <br/>
            <strong style="font-size: 17px;">Intro: </strong>{{ proj.desc}}
          </div>
        </td>
      </tr>
    </tbody>
  </table>
{% else %} 


{% endif %}
    
</div>

<div style="margin-top: 45px"></div>
{% endfor %}

