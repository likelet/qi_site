---
title: "ZHAO Qi Team - Publications"
layout: gridlay
excerpt: "ZHAO Qi Team -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

(For a full list of publications and patents see [below](#full-list-of-publications) or go to [Google Scholar](https://scholar.google.ch/citations?user=j7LCthMAAAAJ), [ReseachGate ID](https://www.researchgate.net/profile/Qi-Zhao-27))

{% assign number_printed = 0 %}
{% for publi in site.data.publist_select %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit><u>{{ publi.title }}</u></pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Selected publications
(See also [Google Scholar](https://scholar.google.com/citations?user=j7LCthMAAAAJ&hl=en); † for equal contribution; \* for corresponding authors)

### 2023
{% for publi in site.data.publist_select %}

{% if publi.year == 2023 %}
[**{{ publi.number }}**].  <u>{{ publi.title }}</u> <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}

### 2022
{% for publi in site.data.publist_select %}

{% if publi.year == 2022 %}
[**{{ publi.number }}**].  <u>{{ publi.title }}</u> <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}


### 2021
{% for publi in site.data.publist_select %}

{% if publi.year == 2021 %}
[**{{ publi.number }}**].  <u>{{ publi.title }}</u> <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}

### 2020
{% for publi in site.data.publist_select %}

{% if publi.year == 2020 %}
[**{{ publi.number }}**]. <u>{{ publi.title }}</u> <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}

### 2019
{% for publi in site.data.publist_select %}

{% if publi.year == 2019 %}
[**{{ publi.number }}**]. <u>{{ publi.title }}</u> <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}

### 2018
{% for publi in site.data.publist_select %}

{% if publi.year == 2018 %}
[**{{ publi.number }}**]. <u>{{ publi.title }}</u> <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}

### 2017
{% for publi in site.data.publist_select %}

{% if publi.year == 2017 %}
[**{{ publi.number }}**]. <u>{{ publi.title }}</u> <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}

### 2014
{% for publi in site.data.publist_select %}

{% if publi.year == 2014 %}
[**{{ publi.number }}**]. <u>{{ publi.title }}</u> <br />
<em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endif %}
{% endfor %}
