+++
author = "Akash Mahajan"
categories = ["On Product Mindset"]
date = 2020-07-11T18:30:00Z
description = "The way software is done has evolved. Security teams need to evolve to. "
image = ""
title = "How to offer Security as a product? When all we have are pen-testers."
type = "post"

+++
In today’s day and age users expect their software to be always available, snappy with no lag over variety of Internet connections ranging from broadband to 2G, should work for 2 screens at least their mobile and laptop. A lot of services provided by software and humans are considered ubiquitous and have become commoditised.

1. Email
2. Calendars
3. File sharing

15 years ago (writing this in 2020) all of the above required complex setups and constant maintenance to ensure they were available, didn’t corrupt our data and kept our information safe. While there was server software that was installed the key ingredient in the mix was service operators.

**![Users ](/images/collaboration-software-1.png)**

> As the collaboration software has moved a lot of wizardry and magic required to maintain such software moved from the operator to the software itself. As software and the service it provides becomes more reliable, users adapt their workflow around this reliability and other non functional promises made by such software.

If you are old like me, you will remember a time mailbox storage used to be so low that it was a ritual to save email attachments on to the disk. Important emails were saved to disk because searching the inbox was painful. Have you ever needed to do that? Or if you did it must have been ages ago.

### User experience matters because users matter

Nowadays users expect _polish_ and _value_ from whatever it is they use to get their job done (product).

> Value is about all the good things considered by the user while polish makes it enjoyable to do.

Now consider what usually happens in a modern engineering team

| Job To Be Done | Product to use |
| --- | --- |
| Store my source code and let me collaborate while coding | Github, Gitlab, Gitea |
| Pull a container to use as a base | Docker Hub |
| Copy the source from repo, build the app, run some tests | Jenkins, Circle CI, Github Actions |
| Start a server for hosting my app | AWS EC2, Digital Ocean Droplet, GCP Compute VM |
| Pull all the logs from app/server | Splunk, ELK Stack |

![](/images/collaboration-software-2-1.png)	
_Operators got replaced with Managed Software As A Service_

It isn't surprising to me, that currently a lot of folks find traditional security teams blockers and gatekeepers and don’t like them one bit for that. That is primarily due to the difference in perception different teams have about what is the primarily responsibility to their business.

**![](/images/pentesters-saying-no.png)**

_From the point of view of engineering teams security teams tend to speak like this._

## Business want their engineering to do Continuous Deployments

All businesses exist to make profits. To be able to do that they rely on paying attention to market conditions, upcoming opportunities, listening to their paying customers. The operationalise this by prioritising new features which they would like to be added to production and A/B tested etc. This cycle of experimentation is meant to continue and improve iteratively with measurement tweaks and other external factors.

> The traditional function of the security team providing security "services" such as PenTesting, Vulnerability Assessments has become opposite of what the business wants and needs.

It is untenable for security teams to offer services that don't offer value to their internal customers nor do they make their job easy (polish) by giving lots of findings without context in hard to parse binary formats such as MS Word, Excel or Adobe PDF files.

![Engineers are used to DevOps speeds](/images/engineers-want-stuff-at-devops-speed-1.png "Engineers are used to DevOps speeds")

_Engineers are used to DevOps speeds_

### Security teams need to evolve

They need to think in terms of a product mindset. In a product mindset you want to solve for problems. Not  solve for solutions. Examples of solving for solutions include

| Solutions Mindset is about fitting tools to generic problems | Product Mindset is about asking questions |
| --- | --- |
| Running vulnerability scanning tools to find servers that need patching | What can we do so that developers always have updated base images to start with |
| Static analysis scanning tools that check for generic security issues | What can we do to ensure that insecure code may never reach our production |
| Elaborate checklists and guidelines for hardening production servers | What can we do to ensure that no human needs to login to production servers but still enable troubleshooting of issues if required |

Agreed that this is an opinionated list. But this should give you a good idea on the switch that is required.

The question still remains. How can we start thinking about offering security as a product when our teams are full of pentesters.  Now that you are in problem mindset, welcome to the journey. 😀😀

![](/images/patrick-tomasso-5hvn-2ww6ry-unsplash.jpg)

_Photo by_ [_Patrick Tomasso_](https://unsplash.com/@impatrickt?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) _on_ [_Unsplash_](https://unsplash.com/s/photos/journey?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

## Easy answers are usually a symptom of solutions mindset

As you may be aware that I run a well known and respected [Application Security Company](https://appsecco.com). For us the idea of being of service which adds value and polish is enshrined in our mission statement itself. To ensure that everyone who is going to join our team starts their journey we ask them to read [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](https://itrevolution.com/book/the-phoenix-project/) even before they have officially joined us.

![The Phoenix Project - Book](https://itrevolution.com/wp-content/uploads/2017/01/TPP_3rd_3D_layered_010318-e1553022345260-488x700.jpg "The Phoenix Project - Book")

> Albeit anecdotal 100% of the team members who joined read the book that we suggested and shared that this was an eye opening book for them.

Another place I think you should start is to understand the whole DevOps Movement and what it entails https://en.wikipedia.org/wiki/DevOps. The best way to get into problem mindset is to understand the philosophy your primary customers (engineering teams) are following.