---
permalink: /get-started/
title: "Get started with Digital Silo"
---

Please ensure that you have read the [documentation](https://github.com/DigitalSilo/digitalsilodocs) to learn about developing Digital Silo grains.

## Development environment

1) [Clone this repository](https://github.com/DigitalSilo/digitalsiloexamples.git) to use its test project as a template to test and verify your under-development grains. There are several working examples found in the repository that can help understand developing Digital Silo grains.

2) Ensure that you have added the necessary NuGet packages to your C# grain projects.

3) Download this Docker container and spin it off to run an instance of Digital Silo on your development machine.

4) Upload your grains to the Azure storage emulator hosted in the docker's container manually. It is available at `http://localhost:20001/blah/`. Restart your docker container to get Digital Silo to pick up the grains and integrate them.

Happy Coding!

## Production environment

Please send us an email at `start@digitalsilo.io` to obtain the Terraform script and Azure DevOps pipeline's YAML file to run Digital Silo on your Azure subscription.