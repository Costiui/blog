---
layout: page
header:
  image_fullwidth: costiui2020.jpg
sidebar: right

image_sliders:
  - slider1
  - slider2
  - slider3
permalink: /index.html 
homepage: true 
---
{% include slider.html selector="slider1" %}

{% include alert info='Filmari cu drona Costiui' %}

{% include video_costiui.html %}

<div class="row t60">
    <div class="medium-6 columns b30">
    <a href="/monument-istoric/castelul-apaffi">
<img src="{{ site.urlimg }}castel-apaffi-costiui.jpg"  alt="monument istoric castelul apaffi"></a>
	    <div align="center">Castelul Apaffi</div>
	    <a class="button tiny radius" href="https://blog.costiui.ml/monument-istoric/castelul-apaffi/">{{ site.data.language.read2 }}</a>
    </div><!-- /.medium-6.columns -->

    <div class="medium-6 columns b30">
    <a href="/video/filmari-cu-drona">
        <img src="{{ site.urlimg }}ronaszek-tajkep.jpg" alt="filmare cu dron costiui"></a>
       <div align="center">Filmare cu drona Costiui</div>
	<a class="button tiny radius" href="https://blog.costiui.ml/video/filmari-cu-drona/">{{ site.data.language.read2 }}</a>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

{% include alert info='Ultimul Articol' %}
{% include newpost.html %}
