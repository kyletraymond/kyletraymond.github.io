---
layout: post
title: More Christmas Cards, 2016
category: art
year: 2017
description: A typical Christmas card game at the Raymonds, in Christmas cards.
images:
  - image_path: art/images/2017/ChristmasCards/wolf.jpg
    title: The wolf lays down
  - image_path: art/images/2017/ChristmasCards/bear.jpg
    title: The bear passes
  - image_path: art/images/2017/ChristmasCards/moose.jpg
    title: The moose passes
  - image_path: art/images/2017/ChristmasCards/loon.jpg
    title: The loon lays down, goes out, floats up to the top

---

{% for image in page.images %}
  ![{{image.title}}]({{site.baseurl}}/{{image.image_path}}){: class="img-block"}
{% endfor %}
