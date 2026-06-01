---
layout: post
title: "The 5 Levels of Infrastructure as Code"
date: 2026-04-28
---

<img width="4000" height="auto" alt="1000006718" src="https://github.com/user-attachments/assets/03f3114f-6449-4042-9820-49078d83d9b0" />

For my final Tech&Meet of the academic year, I attended "The 5 Levels of 
Infrastructure as Code", a talk by Tim Van Roosbroeck and Dimitry Decan from 
Orbid, a RICOH company specialising in cloud infrastructure, modern workspace 
and security. This was probably the most relevant Tech&Meet I attended all 
year, because the content is directly in line with things we cover in our own 
courses.

## About Orbid

Orbid is a cloud and IT services company that builds custom software hosted 
on Azure. They handle 40+ new projects every year, with a baseline 
configuration of around 20 Azure resources per project.

## The 5 levels of Infrastructure as Code

The talk walked us through five levels of maturity when it comes to managing 
infrastructure:

1. **Manual**: clicking through the Azure portal (ClickOps)
2. **Scripted**: using PowerShell or CLI scripts to automate resource creation
3. **Declarative IaC**: using tools like Azure Bicep to describe what 
infrastructure should look like
4. **Modular and reusable**: building standardised templates that can be 
reused across projects
5. **Continuously governed**: full CI/CD pipelines with automated validation 
and governance policies

Orbid explained that most of their current work still sits around levels 1 and 
2, but for new projects they're actively moving towards level 4. That's an 
honest take, it shows that even professional teams are still 
on a journey with this.

## Why Bicep?

The speakers made a strong case for **Azure Bicep** as their tool of choice 
for declarative IaC. The advantages are clear: it's native to Azure, requires 
no licensing costs, has cleaner syntax than raw ARM JSON, and gets day-one 
support for new Azure features. The main downside is that it's Azure-only — 
no multi-cloud support.

## CI/CD

A big part of the talk was also about CI/CD, "continuous integration and 
deployment". The key benefits they highlighted were consistency across 
environments (no more "it works in development but not in production"), faster deployments 
via pipelines, and reduced human error through automated validation before 
anything goes live.

## My reflection

This was the Tech&Meet I enjoyed most. 
Infrastructure as Code, Azure, CI/CD, these are all topics we've touched on 
during our studies, so seeing them applied in a real company context made 
everything clear. It was also great to see that Orbid is a genuinely fun-looking 
place to work, which is always good to know when thinking about where you 
might end up after graduating.
