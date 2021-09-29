---
permalink: /digital-silo-grain-processing/
title: Flexibility in defining the performance
---


When putting the system's design together, flexibility in processing tasks or grains has always been a top priority.

Digital Silo allows developers to define their grains' execution behavior by populating specific fields in the submitted grains' payloads, and Digital Silo adopts the instructed pattern accordingly. As a result, the system will run some grains without any particular order, queue some of them, or defer processing another batch to the future. 

Such flexibility is hugely beneficial for real-world scenarios like sending deferred emails in a digital marketing campaign, or controlling the sequence of saving data to a database, and so forth.

Please refer to this section of the documentation for further technical details.

## Security

All components and tiers of Digital Silo, starting from the client application, are secured by Microsoft Azure's Active Directory system. Digital Silo rejects requests made without a valid authorization token to ensure that the trusted origins are served only.