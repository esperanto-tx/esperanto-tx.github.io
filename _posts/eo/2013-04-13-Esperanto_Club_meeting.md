---
layout: page
#subheadline:  "Templates"
title:  "2013 Aprila Monata kluba kunveno"
teaser: "Dum la aprila klub-kunveno ni lernis ludi novan kart-ludon."
categories:
    - eo
tags:
    - post format
header:
   image_fullwidth: "gallery-eknt-blank-header.jpg"
sidebar: left
breadcrumb: true
image:
   title: "2013-04-13 -- Esperanto Club meeting/IMG_20130413_172402.jpg"
   thumb: "2013-04-13 -- Esperanto Club meeting/IMG_20130413_172402-thumb.jpg"
   caption: Fotoj de Ron Wolf
gallery:
    - image_url: "2013-04-13 -- Esperanto Club meeting/IMG_20130413_172402.jpg"
      caption: "Ni ludas novan kart-ludon"
    - image_url: "2013-04-13 -- Esperanto Club meeting/IMG_20130413_172540.jpg"
      caption: ""
    - image_url: "2013-04-13 -- Esperanto Club meeting/IMG_20130413_172626.jpg"
      caption: ""
---
<!--more-->
--------------------------
Klaku suben por spekti la fotoj (Click below to view the photos)
{% include gallery %}


## Aliaj Artikoloj en Esperanto

<ul>
    {% for post in site.categories.eo %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>