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
  - image_path: /assets/images/splash/developer.svg
    title: 1. Develop the grains
    excerpt: Download our free **.NET SDK** to implement your business logic tasks aka grains
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/deploy.svg
    title: 2. Provision the Silo
    excerpt: Download and run the build pipeline to deploy Digital Silo to your Azure subscription
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/launch.svg
    title: 3. Deploy the grains
    excerpt: Upload your implemented .NET grains to your Digital Silo's provisioned Azure storage
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"   


feature_row_right1:
  - image_path: /assets/images/cloud.svg
    title: Digital Silo is serverless
    excerpt: Whatever Digital Silo does is not running on a dedicated server or server farm. The sky is the limit, and the grain processing kernel resides on serverless infrastructure. What happens behind the scene stays there without getting developers involved with managing that spectrum.
    url: digital-silo-is-serverless
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_left2:
  - image_path: /assets/images/fast.png
    title: It's RESTful, integration made easy!
    excerpt: Digital Silo's integration gate is a simple RESTful Web API that allows developers to integrate their applications regardless of their adopted coding technology to submit or terminate grains effortlessly. Responses are communicated back over WebSockets asynchronously as soon as they become ready.
    url: digital-silo-is-restful
    btn_label: "Read More"
    btn_class: "btn--primary"  
   
feature_row_left2:
  - image_path: /assets/images/coding.svg
    title: Easy-to-develop grains
    excerpt: A grain is a stateless component that encapsulates a specific business logic that runs throughout Digital Silo. Introducing a grain is as simple as following a few key steps.
    url: digital-silo-grain-development
    btn_label: "Read More"
    btn_class: "btn--primary"    

feature_row_right2:
  - image_path: /assets/images/send.svg
    title: Submit and forget!
    excerpt: Just activate the grains by submitting their respective payloads, aka requests in JSON format, via a single entry point. Digital Silo will notify your client application promptly once the grain processing result becomes available.
    url: digital-silo-submit-forget
    btn_label: "Read More"
    btn_class: "btn--primary"    

feature_row_left3:
  - image_path: /assets/images/secure.svg
    title: Secure and flexible
    excerpt: Digital Silo is a collection of independent tasks. It is flexible enough to accommodate the fulfillment instructions by facilitating running grains in any order, lining them up, or deferring each grain's process to the future.
    url: digital-silo-grain-processing
    btn_label: "Read More"
    btn_class: "btn--primary"     
 
  
# feature_row_techs:
#   - image_path: assets/images/splash/azure100x100.png
#   - image_path: assets/images/splash/NET_logo.png
#   - image_path: /assets/images/splash/angular100.png
#   - image_path: assets/images/splash/ts-logo-100.png
#   - image_path: assets/images/splash/terraform_logo.png
       
---

{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row_right1" type="right" %}
{% include feature_row id="feature_row_left2" type="left" %}
{% include feature_row id="feature_row_right2" type="right" %}
{% include feature_row id="feature_row_left3" type="left" %}
{% include feature_row %}

This is the home page.
