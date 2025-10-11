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
### {{ proj.topic }}<a name="topic"></a>

{% if proj.photo %}
<table>
  <tbody>
    <tr>
      <td width="25%">
        <div  style="margin-top: -5px" >
          <img src="{{ site.url }}{{ site.baseurl }}/assets/project_imgs/{{proj.photo.name}}" class="img-responsive" width="{{proj.photo.scale}}" alt="centered image"  style="margin-left: 10px;margin-right: 10px; border: 2px solid #ccc; border-radius: 8px;" />
        </div>
      </td>
      <td>
        <div  style="margin-left: 20px;margin-top: -5px">
          <strong style="font-size: 17px;">{{ proj.title }}</strong> {% if proj.link %}&nbsp;&nbsp;<a href="{{ proj.link }}">[link]</a>{% endif %} <br />
          <strong style="font-size: 17px;">Leader: </strong>{{ proj.leader }}<strong style="font-size: 17px;">&nbsp;&nbsp;|&nbsp; Time: </strong>{{ proj.time }}<br/>
          <strong style="font-size: 17px;">Intro: </strong>{{ proj.desc }}
        </div>
      </td>
    </tr>
  </tbody>
</table>
{% else %} 
  <strong style="font-size: 17px;">{{ proj.title }}</strong> {% if proj.link %}&nbsp;&nbsp;<a href="{{ proj.link }}">[link]</a>{% endif %} <br />
  <strong style="font-size: 17px;">Leader: </strong>{{ proj.leader }}<strong style="font-size: 17px;">&nbsp;&nbsp;|&nbsp; Time: </strong>{{ proj.time }}<br/>
  <strong style="font-size: 17px;">Intro: </strong>{{ proj.desc }}
{% endif %}

<div style="margin-top: 20px"></div>
{% endfor %}

<div style="margin-top: 15px"></div>