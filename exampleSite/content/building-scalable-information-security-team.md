+++
author = "AMol NAik"
categories = ["On Hiring"]
date = 2019-12-22T18:30:00Z
description = ""
draft = true
image = ""
title = "Building Scalable Product Security Team"
type = "post"

+++
In a startup environment, Infosec team need to cater to all the things related to information security. This includes, but not limited to Product security, Data Security, Compliance, Incident response, etc. It is very important to plan for a diverse team who can comfortably serve to all such queries. This post is trying to shed light on Infosec responsibilities, technical skill sets & personal qualities needed and how you can stand out of the crowd.

## InfoSec Responsibilities

On a brief view, I divide Information Security team’s responsibilities as follows:

![](/images/post2.png)

### Audit

The major role for infosec team is to audit. This team audit Web applications, Mobile Apps, APIs, Infrastructure, etc to check for security loopholes. They also review the product designs at an early stage of software development to uncover security misconfiguration. Data audit is another important thing as companies collect sensitive data of customers, drivers, merchants, etc and need to secure in terms of unauthorised access. Risk will be calculated for each loophole considering impact & likelihood of the flaw. Risk matrix helps team to identify the severity of the bug and help to prioritize the patching.

### Patch

Most of the DevOps teams develops automation to fulfil heavy requirements for infrastructure provisioning. The infrastructure will be provisioned mainly in Cloud using Docker & Kubernetes. Most of the infrastructure security issues arises from misconfigurations of the tools & the source will be templates used like terraform, Cookbooks & Docker files, etc.

To mitigate the flaws at source, following the principle of “Secure By Default”, these templates need to be audited & fixed to provide secure infrastructure.

### Monitor

Monitoring the infrastructure & business applications is one of the important responsibilities of infosec team. Things like Firewall changes, User access, Functionality abuse are few areas which need continuous monitoring for insecure changes. Real-time monitoring helps close issues as & when it happens.

## Technical Skills

With the brief idea about the responsibilities of Information Security team, let’s look at the core technical skills required to fulfil each of the above responsibility.

### Pentesters

Pentesters are the hardcode security personnel whose main aim is to break stuff. These people have a wide variety of knowledge on infrastructure, programming, applications, etc which helps them audit for security bugs. There are specialised tools & techniques which help them audit. These people are always evolving as more & more tech is added to the landscape.

### DevOps

With the agile mindset, most companies are adopting devops practices. This will be achieved with using wide range of devops tools. For this, it is very important to have a team which is well versed with toolset being used. With the help of pentesters, this team will be fixing templates & development pipeline so that “Secure By Default” principle will be followed.

### Developers

With all the responsibilities, Infosec team heavily depends on automation to scale. Be it building automated scanner or developing alerting mechanism, development is the biggest chunk of the work involved in setting up secure practices. Having team specialised in such skills come in handy where the quality of work & speed for deliveries will be maintained.

## Personal Qualities

Having listed down the core technical skills, let’s looks at personal qualities I look for people while hiring.

### Passion

Passion is the biggest driver for the success of any task. If you are not passionate enough, the job becomes mundane for you and you end up being a tool junkie. Sadly there are many people in information security who solely rely on tools to audit and these are the majority of them available now.

### Empathy towards other teams

Most of the security professionals feels that they do the most important job in the organization. One of my community friends call this as "Ego". What they fail to realise that everyone in the company is important for running the business. This leads to fights between security & other teams, mainly dev teams, when they need to collaborate for security work.

When you start empathising with other teams, you will learn the challenges faced by those teams. Security team is always adding more work to other teams as security bugs need to be patched which disturb their product plans. With empathy, we can figure out a middle path to fulfil both team’s jobs.

### Being Responsible

Many of times, teammates assumes there will be always someone in team to address issues, specially managing security alerts. We have to understand, security is our responsibility & we need to be active on addressing every security. In my current job, during production issues, product teams wants help from security team to eliminate the possibility of attack. In such cases, timely response is needed. Even if you don’t possess the skills to address the issue, you can reach out to other team mates to let them know that someone is waiting for our help.

### Stand out of the Crowd

As there are so many candidates looking for new job opportunities, few of the following will make you different from others:

* Have a technical blog discussing attacks, proactive controls, research, etc
* Code repository having your automation tools
* Community presence to showcase your skills