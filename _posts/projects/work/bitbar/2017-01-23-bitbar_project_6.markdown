---
name: Bitbar Inc - OSX Infrastructure Automation with Ansible
when: 01/2017-05/2017
role: DevOps Engineer
keywords: Ansible, Jenkins Pipeline, Vagrant

layout: col-1
category: work
---

The goal of this project was to create a reliable way of automatically provisioning new OSX hosts and upgrading old ones. Previously this had been done using Chef, but the decision was made to start from scratch as the deployments were rather error-prone and unreliable.

I was responsible for designing the project structure, CI-pipeline and also the actual deployment workflow. In addition, I wrote down the development guidelines for the project and implemented majority of the Ansible-roles. An important success criterion in this project was to make the upgrade and setup process reliable, but at the same time support multiple environments allowing them to contain some differences but still keeping the configurations as consistent as possible. In addition, when designing the CI-pipeline and development guidelines, high priority was given to ensuring that the deployments will stay reliable also in the future when the project evolves and more people start working on it.
