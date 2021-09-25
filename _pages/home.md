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
    title: 1. Develop the grains
    excerpt: Download our free **.NET SDK** to implement your business logic tasks aka grains
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/deploy-250.png
    title: 2. Provision the Silo
    excerpt: Download and run the build pipeline to deploy Digital Silo to your Azure subscription
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"
  - image_path: /assets/images/splash/upload-250.png
    title: 3. Deploy the grains
    excerpt: Upload your implemented .NET grains to your Digital Silo's provisioned Azure storage
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--secondar"   

feature_row_left1:
  - image_path: /assets/images/fast.png
    title: Digital Silo is mighty!
    excerpt: Digital Silo harnesses the power of the Azure cloud to supercharge the execution of the business logic encapsulated in submitted grains. It can well scale-out when additional horsepower is needed or provide a close to real-time processing time and throughput. Digital Silo can accommodate hundreds or thousands of grains simultaneously without any compromise!
    url: digital-silo-is-mighty
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_right1:
  - image_path: /assets/images/mighty.png
    title: Digital Silo is serverless
    excerpt: Whatever Digital Silo does is not running on a dedicated server or server farm. The sky is the limit, and the grain processing kernel resides on serverless infrastructure. What happens behind the scene stays there without getting developers involved with managing that spectrum.
    url: digital-silo-is-serverless
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row_left2:
  - image_path: /assets/images/fast.png
    title: It's RESTful, integration made easy!
    excerpt: Digital Silo collects grains' payloads via a single RESTful Web API POST action and communicates the processing results asynchronously via web sockets. The client applications developed in any language, e.g., typescript, C#, etc., need to integrate these two communication features to send JSON payloads and receive asynchronous responses.
    url: digital-silo-is-restful
    btn_label: "Read More"
    btn_class: "btn--primary" 

feature_row_right2:
  - image_path: /assets/images/fast.png
    title: We've got .NET developers' back
    excerpt: Digital Silo's SDK is in .NET, and that's a popular framework to put together a Digital Silo grain in developers' favorite programming languages like C# and VB.NET. The SDK provides a robust and easy pattern to follow to implement the business logic in a grain. The entire Digital Silo was built using C#!
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"   

feature_row_left3:
  - image_path: /assets/images/mighty.png
    title: Submit and forget!
    excerpt: Just have the grains activated by submitting their respective payloads aka requests in JSON format via a single entry point. Digital Silo will notify your client application promptly once the grain processing result becomes available.
    url: digital-silo-submit-forget
    btn_label: "Read More"
    btn_class: "btn--primary"    

feature_row_right3:
  - image_path: /assets/images/fast.png
    title: Flexible performance
    excerpt: Digital Silo is a collection of independent tasks. It is flexible enough to accommodate the fulfillment instructions by facilitating running grains in any order, lining them up, or deferring each grain's process to the future.
    url: digital-silo-grain-processing
    btn_label: "Read More"
    btn_class: "btn--primary"     

feature_row_left4:
  - image_path: /assets/images/fast.png
    title: It's secure
    excerpt: DAll components and tiers of Digital Silo, starting from the client application, are secured by Microsoft Azure's Active Directory system. Digital Silo rejects requests made without a valid authorization token to ensure that the trusted origins are served only.
    url: digital-silo-is-secure
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
{% include feature_row id="feature_row_left1" type="left" %}
{% include feature_row id="feature_row_right1" type="right" %}
{% include feature_row id="feature_row_left2" type="left" %}
{% include feature_row id="feature_row_right2" type="right" %}
{% include feature_row id="feature_row_left3" type="left" %}
{% include feature_row id="feature_row_right3" type="right" %}
{% include feature_row id="feature_row_left4" type="left" %}
{% include feature_row %}

This is the home page.
