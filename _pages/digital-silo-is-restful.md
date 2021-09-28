---
permalink: /digital-silo-is-restful/
title: "Integration with Digital Silo"
---


Digital Silo collects grains’ payloads via a couple of RESTful Web API actions and communicates the processing result asynchronously through web sockets. A couple of web actions have been designated too to be able to terminate the under-process grains.
So, the client applications developed in any programming language only need to integrate these two communication characteristics to send JSON payloads and receive asynchronous responses. 

[Follow this link](https://dsdemogatewayapp.azurewebsites.net/index.html) to take a peek at Digital Silo's Open API documentation.

## We've got .NET developers' back
Our Digital Silo’s SDK is in .NET, and that’s a popular framework to develop a Digital Silo grain in developers’ favorite programming languages like C# and VB.NET. The SDK provides a robust and easy pattern to follow to implement the business logic in a grain. The entire Digital Silo was built using C#!