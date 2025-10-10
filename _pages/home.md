---
title: "Ronghao Lin - Home"
layout: homelayout
excerpt: "Ronghao Lin - Home"
sitemap: false
permalink: /
---

{% for member in site.data.pi %}

<table>
    <tbody>
        <tr>
            <td width="35%">
              <a id="profile" href="{{site.url}}{{site.baseurl}}/"><img src="{{ site.url }}{{ site.baseurl }}/assets/pi_imgs/{{ member.photo }}" class="img-responsive" width="90%" style="block:inline; margin-left:auto; margin-right:auto; margin-top:20px; margin-bottom:20px;" /></a>
            </td>
            <td>
                <div id="toptitle" style="margin-left: 20px">
                    <h1>{{ member.name }} </h1>
                    <h3>{{ member.identity }} </h3>
                    {{ member.location1 }}  <br>
                    {{ member.location2 }}  <br>
                    <div style="margin-top: 15px;margin-left: -80px">
                        <center>
                            {% if member.website %}<a href="{{ member.website }}" target="_blank" ><i class="fa fa-home fa-2x"></i></a> {% endif %}
                            {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %}
                            {% if member.email2 %}<a href="mailto:{{ member.email2 }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a> {% endif %}
                            {% if member.googlescholar %} <a href="{{ member.googlescholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-2x"></i></a> {% endif %}
                            {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-2x"></i></a> {% endif %}
                            {% if member.semanticscholar %} <a href="{{ member.semanticscholar }}" target="_blank"><i class="ai ai-semantic-scholar-square ai-2x"></i></a> {% endif %}
                            {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-2x"></i></a> {% endif %}
                            {% if member.dblp %} <a href="{{ member.dblp }}" target="_blank"><i class="ai ai-dblp-square ai-2x"></i></a> {% endif %}
                            {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-2x"></i></a> {% endif %}
                            {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-2x"></i></a> {% endif %}
                            {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-2x"></i></a> {% endif %}
                        </center>

                    </div>
                </div>
            </td>
        </tr>
    </tbody>
</table>

{% endfor %}

<div style="margin-top: 35px"></div>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<!-- ------------------------------------------- -->

### 🎓 Profile
I am a highly-motivated Ph.D. student with foundations of computer science, artificial intelligence, physics, and finance. I am a third-year Ph.D. student in Sun Yat-sen University (SYSU) supervised by Prof. [Haifeng Hu](https://seit.sysu.edu.cn/teacher/HuHaifeng).
{: .text-justify}

I am currently working as a joint Ph.D. in Nanyang Technological University (NTU), supervised by Prof. [Yap-peng Tan](https://personal.ntu.edu.sg/eyptan) at [CARTIN](https://www.ntu.edu.sg/cartin).
{: .text-justify}


<!-- ------------------------------------------- -->

<div style="margin-top: 20px"></div>

### 💫 Research
My research interests include: CV & NLP, Multimodal Affective Computing and Emotion Reasoning, Multimodal Empathetic Response with LLM, Digital Human Generation, Video Understanding, World Model and so on. 

I have published 10+ papers at the top AI conferences / journals <a href='https://scholar.google.com/citations?user=xm6apUEAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=&https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FRH-Lin%2Frh-lin.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
{: .text-justify}

My long-term goal is to build human-centric multimodal understanding and generation. 

<!-- 我的研究兴趣包括：计算机视觉与自然语言处理，多模态情感计算与推理，大模型共情回复，数字人生成，视频理解，世界模型等。 -->

I also extensively explore the application of AI for science, cognitive computing, social and economics studies.

<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 1.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;">

- **Multimodal Affective Computing**:

&nbsp;&nbsp; MTMD, MMCL, MSG-MBA

</div>

<div style="margin-top: 10px"></div>

<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 1.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;">

- **Robust Multimodal Learning**:

&nbsp;&nbsp; M3ixup, [CyIN](https://github.com/RH-Lin/CyIN), [MMPDA](https://github.com/RH-Lin/MMPDA), [MissModal](https://github.com/RH-Lin/MissModal)

</div>

<div style="margin-top: 10px"></div>

<div style="border-radius: 0.7em;background-color: rgba(0,0,0,3%);padding-bottom: 1.0pt;padding-left: 4.0pt;padding-right: 4.0pt;padding-top: 4.0pt;">

- **Multimodal Empathetic Response**:

&nbsp;&nbsp; [E3RG](https://github.com/RH-Lin/E3RG)

</div>


<!-- ------------------------------------------- -->

<div style="margin-top: 20px"></div>

### 📢 Advertising

XXX
