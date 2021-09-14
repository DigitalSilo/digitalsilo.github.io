---
permalink: /
title: "digital://silo"
author_profile: false
layout: splash
classes:
    - landing
    - wide
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash/splashhomepage.jpg
  actions:
    - label: "Sign up"
      url: "/signup"
excerpt: "The excerpt is here" 
intro:
  - excerpt: This is the introduction to the product

feature_row:
  - image_path: /assets/images/splash/feature1.jpg
    title: "Placeholder 1"
    excerpt: "Sample text 1 with **markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/splash/feature2.jpg
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/feature3.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
---
{% include feature_row id="intro" type="center" %}
{% include feature_row %}

This is the home page.
