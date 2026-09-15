---
title: "Projects (The Fun Stuff)"
layout: splash
permalink: /splash/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/moon.jpg
intro: 
#  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
# feature_row:
#  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
#    alt: "placeholder image 1"
#    title: "Placeholder 1"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
#  - image_path: /assets/images/-gallery-image-2-th.jpg
#    alt: "placeholder image 2"
#    title: "Placeholder 2"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
#  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
#    title: "Placeholder 3"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row1:
  - image_path: /assets/images/ACS.png
    alt: "ACS Image"
    title: " Planetary Rover Active Suspension System"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: /ACS/
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/LINK1.png
    alt: "Link Image"
    title: "Limbed Interface for Natural Kinetics (LINK)"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    # alt: "placeholder image 2"
    # title: "Placeholder Image Center Aligned"
    excerpt: "**'There is nothing impossible for those who try'**"
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row1" type="right" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="center" %}

# {% include feature_row id="feature_row4" type="center" %}
