# beezy-cloud
Build a Private Cloud, the Open Way! 

## Introduction
When discussing with customers and partners about building a new infrastructure, everyone agrees to address the backlog and technical debts from the past. And yet, all funnels down quickly to the legacy world while dreaming about a usuable cloud experience.  
  
Sounds familiar? This is a common outcomes from our time limited linear thinking linked to existing experience and knowledge. In other words, we naturally feel time pressured to deliver a finite outcome which creates a natural tunnel vision towards a given solution made of elements that we master. This is also the root cause of limited innovation within company cruising the enterprise segment who lost their start-up genes (and leadership). 

This repo/essay is about addressing rethinking our current so-called legacy infrastructure by introducing a true private cloud experience for on-prem infrastructure embracing the cloud native and open-source ways.

The process will leverage the fail fast learn fast principle. 

## Problem identification
Beezy Inc is a development start-up helping customers and partners to create new solutions for diverse industries. While their core business is not building infrastructure, they are in need of rock solid, performant, and elastic environments to empower their teams to quickly deliver business value to their customers. 
While having their HQ in Brussels, Beezy Inc is a remote first workplace meaning that building a traditional stack would require space colocation in a data centre. Neither is to fully host their infrastructure in the cloud due to some of their specific customer industry. But they would appreciate the on-demand elasticity of the cloud. 
When discussing with the developers, they fully embrace containers but yet they still need time to time some virtual machines. 
Although, the traditional stack of compute, virtualization, storage, backup, networking, ... seems to be the obvious choice, but clearly out of budget.
The last requirements is about managing the overall solution. The SRE team has 2 team members and embracing the dev ways of working would ease the self-support. 

Let's list the requirements:
- a compact setup to reduce colocation costs
- hybrid cloud solution for elasticity 
- a compact setup to reduce colocation costs
- containers and virtual machines
- DevOps model 

## Solutioning
The SRE teams went with the Devs to KubeCon in Amsterdam and discover the flexibility of Kubernetes to orchestrate both the platform and the applications. Browsing the talks and booths, they discovered projects like Kubervirt to deal with virtual machines as-code on Kubernetes which addresses the second big needs. 
While watching a big crowd movement towards one of the booth, they discovered a company called Red Hat offering an enterprise version of Kubernetes. Could this be the solution to their needs?  

## Roadmap


## MVP 


## 