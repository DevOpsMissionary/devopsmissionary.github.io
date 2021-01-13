
---
date: 2020-12-21
title: "Inside Containers"
linkTitle: "Inside Containers"
description: >
  Containerization is a very important new tool for any DevOps missionary to know
author: Billy Foss ([@BillyFoss](https://twitter.com/BillyFoss))
---

One of the recent changes in technology is containers.  From a DevOps context, they enable packaging of applications and dependencies into a nice package that can be easily distributed.  Containers can also be combined within orchestration tooling to build larger applications and platforms.

Sometimes you want to package a set of applications into an easy to use environment.  Consider a development environment that needs specific versions of the build tools.
The purpose of this post is to demonstrate one method of packaging applications into a container while enabling usage an interaction from your laptop.

## Tools
I'm going to use the following tools:

- [Virtual Box](https://www.virtualbox.org/) - provides the ability to run a virtual machine locally.
- [Vagrant](https://www.vagrantup.com/) - provides automation and management of virtual machine images.
- [Terraform](https://www.terraform.io/) - enables provisioning and management of infrastructure across multiple cloud and server providers.
- [Ansible](https://www.ansible.com/) -  enables automation of all kinds of things.
