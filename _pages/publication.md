---
title: "Ronghao Lin - Publication"
layout: textlayout
excerpt: "Ronghao Lin - Publication"
sitemap: false
permalink: /publication
---

# Publications

`#` denotes equal contribution, `*` denotes correspondence. Jump to [\[Preprint\]](#preprint), [\[Survey\]](#survey), [\[Benchmark\]](#benchmark), [\[Conference\]](#conference), [\[Journal\]](#journal), [\[Others\]](#others).

<!-- See full publications in [\[Google Scholar\]](https://scholar.google.com/citations?user=YGDX46AAAAAJ). <br> -->

<div style="margin-top: 35px"></div>

{% if site.data.pub_preprint %}
### Preprint<a name="preprint"></a>

{% for publi in site.data.pub_preprint %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>{{ publi.authors }} </em><br />
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>{{ publi.venue.name }}</strong> &nbsp;&nbsp; {{ publi.year }} &nbsp;&nbsp; <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[code\]</a>{% endif %}&nbsp;{% if publi.promote %}<a href="{{ publi.promote.link }}">\[{{ publi.promote.name }}\]</a>{% endif %}

{% endfor %}
{% endif %}

<!-- ------------------------------------------- -->

<div style="margin-top: 30px"></div>

{% if site.data.pub_survey %}
### Survey<a name="survey"></a>

{% for publi in site.data.pub_survey %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>{{ publi.authors }} </em><br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>{{ publi.venue.name }}</strong> {% if publi.venue.note %} ({{ publi.venue.note }}){% endif %} &nbsp;&nbsp; {{ publi.year }}&nbsp;&nbsp;
  <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[data\]</a>{% endif %}

{% endfor %}
{% endif %}

<!-- ------------------------------------------- -->

<div style="margin-top: 30px"></div>

{% if site.data.pub_benchmark %}
### Benchmark<a name="benchmark"></a>

{% for publi in site.data.pub_benchmark %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>{{ publi.authors }} </em><br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>{{ publi.venue.name }}</strong> {% if publi.venue.note %} ({{publi.venue.note}}){% endif %} &nbsp;&nbsp; {{ publi.year }}&nbsp;&nbsp;
  <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[data\]</a>{% endif %}

{% endfor %}
{% endif %}

<!-- ------------------------------------------- -->

<div style="margin-top: 30px"></div>

{% if site.data.pub_conference %}
### Conference<a name="conference"></a>

{% for publi in site.data.pub_conference %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em>{{ publi.authors }} </em><br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>{{ publi.venue.name }}</strong> {% if publi.venue.note %} ({{publi.venue.note}}){% endif %} &nbsp;&nbsp; {{ publi.year }} {% if publi.highlight %}&nbsp;&nbsp; <strong style="color:#DE426B;">{{ publi.highlight }}</strong>  {% endif %} &nbsp;&nbsp; <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[code\]</a>{% endif %}&nbsp;{% if publi.promote %}<a href="{{ publi.promote.link }}">\[{{ publi.promote.name }}\]</a>{% endif %}

{% endfor %}
{% endif %}

<!-- ------------------------------------------- -->

<div style="margin-top: 30px"></div>

{% if site.data.pub_journal %}
### Journal<a name="journal"></a>

{% for publi in site.data.pub_journal %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em>{{ publi.authors }} </em><br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ publi.venue.full }} {% if publi.venue.short %}(<strong>{{publi.venue.short}}</strong>){% endif %} &nbsp;&nbsp; {{ publi.year }}&nbsp;&nbsp;
  <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[code\]</a>{% endif %}&nbsp;{% if publi.promote %}<a href="{{ publi.promote.link }}">\[{{ publi.promote.name }}\]</a>{% endif %}

{% endfor %}
{% endif %}

<!-- ------------------------------------------- -->

<div style="margin-top: 30px"></div>

{% if site.data.pub_other %}
### Others (Tutorials，Books)<a name="others"></a>

{% for publi in site.data.pub_other %}

  <span style="font-size: 20px;">&#8226;</span> &nbsp; <strong style="font-size: 17px;">{{ publi.title }}</strong> <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<em>{{ publi.authors }} </em><br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>{{ publi.venue.name }}</strong> {% if publi.venue.note %} ({{publi.venue.note}}){% endif %} &nbsp;&nbsp; {{ publi.year }}&nbsp;&nbsp;
  <a href="{{ publi.link.paper }}">\[paper\]</a>&nbsp;{% if publi.link.code %}<a href="{{ publi.link.code }}">\[code\]</a>{% endif %}

{% endfor %}
{% endif %}

<div style="margin-top: 15px"></div>

