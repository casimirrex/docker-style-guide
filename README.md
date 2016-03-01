# Haufe DOCKER guidelines

![Haufe](images/logo-haufede.png) 
![Docker](images/docker-logo.png)

## Introduction

Docker is a technology, that provides:

- unique way to include a softwarepackage and all its all dependencies into one single package: ** Docker Images **
- a lightweight solution for process-isolation in contrast to the heavier Virtual-Machine approach: ** Docker Containers ** 
- a runtime to decouple the Linux installation inside and outside of a Docker Container (with the exception of the kernel being shared): ** Docker Engine **
- a solution to combine, configure and control multiple containers, networks and hosts: ** Docker Compose** 
- a tool to prepare and manage single or clustered systems running the Docker Engine: **Docker Machine**
- an almost explosively growing system of tools and pre-packaged appplications ... by Docker Inc., other Companies and "The Community": Rancher, Consul, Panamax, ...

The overall architecture is explained in the original Docker documentation in [Understand the architecture](https://docs.docker.com/engine/understanding-docker/)

You find a slightly outdated, but quite good Docker overview at Peter Rossbachs [Docker Basics](https://github.com/rossbachp/docker-basics/blob/master/slides.md)

The [Official Docker Documentation](https://docs.docker.com/) gives a good overview about the main component and its accompanying tools on the [Introduction to Engine user guide](https://docs.docker.com/engine/userguide/intro/)

## The Guidelines

This set of documents called the "Haufe DOCKER Guidelines" represent **mandantory requirements**, recommended best practices and informational resources for using **Docker** in **official (public or internal) Haufe products, services or solutions**.

### When to use the guidelines?

The "Haufe DOCKER Guidelines" **MUST ** be used when you **create**, **modifiy** or ** extend** Docker based solutions.

**Existing** Docker installations and/or components ** might** have to adapt out of specific security or business reasons.

### Who has to use the guidelines?
It is the responsibility of Developers, Release Engineers AND Runtime Operators to apply the Guidelines to a specific project!
	
>	Please follow the guidelines, but don't follow blindly!  
>	You can break the rules with justification.

### How to ask for changes to the guidelines?
This and related documents are "work in progress". We’d love your feedback – whether you agree, disagree, or have some additional practices and tips to add.

>	We encourage you to improve the guidelines with modifications and extensions.
>	Inform the CTO Office (mailto:_CTOLeads@haufe-lexware.com) in this cases.
>
>	Please contribute!

## Guidelines
- [Haufe's Docker Toolset](HaufeDockerToolset.md)
- [Docker Host](DockerHost.md)
- [Docker Machine](DockerMachine.md)
- [Docker Engine](DockerEngine.md)
- [Dockerfile](Dockerfile.md)
	- [Best Practices](BestPracticesDockerfile.md)
- [Docker Image](DockerImage.md)
- [Docker Container](DockerContainer.md)
	- [Best Practices](BestPracticesContainer.md)
- [Docker Compose](DockerCompose.md)
	- [Best Practices](BestPracticesCompose.md)

## To be done ...
- [Network, Service Discovery etc.](.md)
- [Monitoring](.md)
- [Microservices](.md)
- ["Dockerizing" existing solutions](.md)
