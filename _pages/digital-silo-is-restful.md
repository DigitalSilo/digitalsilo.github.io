---
permalink: /digital-silo-is-restful/
title: "Integration with Digital Silo"
---


Digital Silo collects grains’ payloads via a couple of RESTful Web API actions and communicates the processing result asynchronously through web sockets. A couple of web actions have been designated too to be able to terminate the under-process grains.
So, the client applications developed in any programming language only need to integrate these two communication characteristics to send JSON payloads and receive asynchronous responses. 

[Follow this link](https://dsdemogatewayapp.azurewebsites.net/index.html) to take a peek at Digital Silo's Open API documentation.

## We've got .NET developers' back

Digital Silo’s SDK is in .NET to integrate with the silo using programming languages like C# and VB.NET. The SDK provides a robust and easy way to submit grains' payloads and listen to the processing results published by the silo over WebSockets.

Digital Silo's SDK is an open-source C# project that can be cloned from [this Github repo](https://github.com/DigitalSilo/digitalsilosdk). The associated integration test projects found in the repo are great examples in C# to illustrate submitting grains individually or in a batch and terminating them.

## A cool fact

The entire Digital Silo was built using C#!