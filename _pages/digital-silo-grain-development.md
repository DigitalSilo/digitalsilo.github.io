---
permalink: /digital-silo-grain-development/
title: Encapsulating business logic in Digital Silo grains
---

Developers can define Grain classes by deriving them from a provided base class called `Grain`. This base class covers all primary data to declare a grain's behavior, and inheritance brings it down to developers' defined grains. Each grain class is associated with another class deemed as grain processor, where the business logic is implemented and retained. Mediator technology links these two classes together so that Digital Silo discovers this association and runs the business logic.

[This open-source Github repository](https://github.com/DigitalSilo/digitalsiloexamples) hosts a few actual grains that are functional in our demo Digital Silo instance on Azure. The repository also has a few integration test examples that developers can leverage as a pattern to write their tests.