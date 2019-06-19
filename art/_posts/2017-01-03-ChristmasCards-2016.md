---
layout: post
title: Christmas Card Art!
category: art
year: 2017
description: Some artwork for Christmas Cards, 2016
images:
  - image_path: art/images/2017/ChristmasCards/One.jpg
    title: Coffee Fox
  - image_path: art/images/2017/ChristmasCards/Two.jpg
    title: Candle Dragon
  - image_path: art/images/2017/ChristmasCards/Three.jpg
    title: Wassail Fish
  - image_path: art/images/2017/ChristmasCards/Four.jpg
    title: Lady Carrot Cake
  - image_path: art/images/2017/ChristmasCards/Five.jpg
    title: Sad Raccoon
  - image_path: art/images/2017/ChristmasCards/Six.jpg
    title: Fire Salamander
---

{% for image in page.images %}
  ![{{image.title}}]({{site.baseurl}}/{{image.image_path}}){: class="img-block"}
{% endfor %}
