---
permalink: /
title: "Digital Silo"
author_profile: false
layout: splash
classes:
    - landing
    - wide
header:
  overlay_color: "#000"
  overlay_filter: "0.125"
  overlay_image: /assets/images/splash/splashhomepage.jpg
  actions:
    - label: "Getting started"
      url: "/start"
excerpt: "A mighty serverless solution on Azure to run tasks asynchrnously. Deploy yours just in minutes!" 
intro:
  - excerpt: Digital Silo executes stateless tasks, aka Grains in an asynchronous scalable serverless environment. It accelerates the steps of making an application serverless-ready by helping developers concentrate on business logic only.
feature_row:
  - image_path: /assets/images/splash/developer-250.png
    title: Develop the grains
    excerpt: Download our free **.NET SDK** to implement your business logic tasks aka grains
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/deploy-250.png
    title: Provision the Silo
    excerpt: Download and run the build pipeline to deploy Digital Silo to your Azure subscription
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/upload-250.png
    title: Deploy the grains
    excerpt: Upload your implmemneted .NET grains to Digital Silo's provisioned Azure storage
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/download-250.png
    title: Fire up the Silo
    excerpt: Execute the release pipeline to deploy the infrastructure binaries and make the grains operational
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"    

feature_row_left1:
  - image_path: /assets/images/fast.png
    title: Develop the grains
    excerpt: Download our permanently-free **.NET SDK** to implement your business logic task aka grain
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_right1:
  - image_path: /assets/images/mighty.png
    title: Provision the Silo
    excerpt: Download and run the build pipeline to deploy Digital Silo to your Azure subscription
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_left2:
  - image_path: /assets/images/fast.png
    title: Deploy the grains
    excerpt: Upload your implmemneted .NET grains to Digital Silo's provisioned Azure storage
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"   

feature_row_right2:
  - image_path: /assets/images/mighty.png
    title: Fire up the Silo
    excerpt: Execute the release pipeline to deploy the infrastructure binaries and make the grains operational
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"    
       
---

{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row_left1" type="left" %}
{% include feature_row id="feature_row_right1" type="right" %}
{% include feature_row id="feature_row_left2" type="left" %}
{% include feature_row id="feature_row_right2" type="right" %}
{% include feature_row %}

This is the home page.
