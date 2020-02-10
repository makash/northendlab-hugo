+++
author = "Akash Mahajan"
categories = ["On Training"]
date = 2020-02-09T18:30:00Z
description = ""
image = "/images/man-in-black-reebok-shoes-about-to-carry-barbell-949129.jpg"
title = "The almost impossible challenge of training security teams"
type = "post"

+++

Training people is a challenging problem. There are no two ways about it. It is especially so in the world of information security because of the constantly changing nature of threats, landscape and what needs protecting. As more and more information systems get meshed in the very fabric of society the challenge keeps getting tougher. For example, there are different sector specific legal compliance for industry sectors of Finance (Sarbanes Oxley), Health Care, Payment Card Industry.

Just to give you a sense of why training is a complicated endeavour for a security testing team in my company, have a look at what a typical security analyst ends up doing as part of their job.

![Appsecco's Security Analyst has cross functional capabilities](/images/what-security-analyst-needs-to-know.png "A typical security analyst should know all of this")

That does seem like a lot of things!

You may be wondering from where do we find people who are so capable and familiar with so many knowledge areas. The reality is that we don’t find people with all these skills.

Since we would like all our security analysts to be able to do all of that once they are working, we need to separate based on

1. What we can hire for
2. What we can train on

This is the journey each security analyst ends up undertaking in our company.

![Security Learning Journey undertaken by a new hire at Appsecco](/images/training-of-security-analyst.png "Security Learning Journey undertaken by a new hire at Appsecco")

Usually the talent pool we can access gives us people who have a grounding of concepts in application security and passing familiarity with OWASP Top 10 application risks framework.

Most of the people we hire are also familiar with ideas on how to use OSINT, Kali Linux and rudimentary scripting in Python.

![We hire keeping in mind the following skills](/images/security-analyst-t-shape.png "We hire keeping in mind the following skills")

If you strain your eyes you will be able to discern a ‘T’ shape. I wrote about how we hire in my previous post [On Hiring](https://securitypost.in/hiring-for-security-teams-akash-mahajan/ "Hiring for security teams"). Just to recap we look for people who are

1. Self starters
2. Willing to take initiative
3. Open to learning always and kind to themselves about failing

Assuming that we managed to hire the people based on these attributes. Now comes the part about training and guidance. We try and do this by dividing on what and how we train in four buckets.

1. Stuff we can teach by training
2. Stuff that we can teach by guiding during the work they are doing
3. Stuff that they learn when they get to collaborate with others or give talks at conferences
4. Stuff that they learn when we nudge and prod and mentor them to build tools and vulnerable applications

![Four ways to train and guide security analysts](/images/four-buckets.png "Four ways to train and guide security analysts")

## So why exactly is training an almost impossible challenge

Most people who have a testing background can attest to the fact that ensuring test coverage is one of the most difficult aspects of functional testing. On top of that when it comes to application security testing ensuring discovery, proper identification and if possible exploitation of weaknesses should be done. Once it has been established that there is indeed a security weakness it needs to be mapped to the OWASP Top 10 application risk framework. This sets the agenda for the security analyst and the developer of the application to be able to have a discussion based on common language and terms.

### Typical steps for doing a security testing project

1. Understand the application and its features
2. Find weaknesses and report themselves
3. Make sense of all the parts of the system like back-end, front-end, database, authentication, servers 3rd party services
4. At the close of the project try and understand what worked, what didn’t, what else can be automated

![Steps for executing a security testing project](/images/security-project-lifecycle.png "Steps for executing a security testing project")

In the cycle of finding bugs, we can zoom in to get a better sense of each step

![Simple cycle followed for finding bugs](/images/finding-bug-cycle.png)

To add to this there are scores of server side back-end frameworks, tens of databases, scores of front-end frameworks and new 3rd party services keep cropping up. Using these modular components developers codify business logic which again needs to be looked at by the analyst. This logic could be using variety of access control mechanisms (most popular being Role Based Access Control) which can be complicated to understand beyond a number of roles and the resources those roles have access to.

> Therefore the biggest challenge for a security tester is to find out if a certain pattern of weakness is present or not. Even if the analyst may have seen it earlier, due to the bespoke nature of applications it may not be apparent.

So how does one train for such a scenario? Wherein we are combining known knowledge, capability, application of skill, ability to draw inferences from available data to find security issues within a fixed amount of time. Phew!

## Building a capability maturity framework

There are no easy solutions but we can try and build a maturity framework to tackle some of the challenging aspects. A maturity framework looks at the problem in stages and breaks down anything that is difficult to address.

1. Start with a baseline matrix on minimal knowledge areas and abilities required
2. Create training practice playgrounds tailored to what needs to be covered as per the baseline
3. Create training labs that allow the trainee analyst to target one specific kind of weakness
4. Use data generated by the previous activity (application logs/instrumented code) to ascertain what are the gaps remaining
5. I guess was rinse repeat as the practice playgrounds and labs can become more complex as the trainee analysts graduate to the next level of maturity

### Martial Arts Belts

Many process and training plan frameworks borrow the belt nomenclature to indicate gradients in maturity. Going from variety of colours to black which indicates mastery.

[Karate Belt Colours and what they mean](https://medium.com/@stefanogiovannihala/understanding-the-meaning-of-karate-belts-colors-648248d8a630 "Understanding the Meaning of Karate Belts Colors")

### Resources that can be used right now

For creating baselines OWASP Application Security Verification Standards (Web and Mobile) and the Cybok Knowledge Areas is good enough to cover almost all aspects of security testing areas.

1. [OWASP ASVS 4.x](https://owasp.org/www-project-application-security-verification-standard/ "OWASP Application Security Verification Standard")
2. [OWASP Mobile ASVS ](https://mobile-security.gitbook.io/masvs/ "OWASP Mobile Application Security Verification Standard")
3. [CyBOK Knowledgebase](https://www.cybok.org/knowledgebase/ "The Cyber Security Body Of Knowledge")

The security testing guides by OWASP, the Web Application Hackers Handbook are all great for creating a list of capabilities that trainee analysts can practice to become skilled in the techniques and tools for doing such security testing.

1. [OWASP Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
2. [Web Application Hacker's Handbook Testing Checklist](https://gist.github.com/jhaddix/6b777fb004768b388fefadf9175982ab "Web Application Hacker's Handbook Testing Checklist")

### Future Roadmap

Nobody can predict the future. This is one area where a lot of unknown unknowns cause training and continuous learning to derail. New technologies, newer applications of known technologies, uptake in usage of certain developer tools and frameworks all of this can mean that experienced security testers need to keep up with the times. This may not require learning more security but practising methods around learning how to learn and more.

#### Some more resources

* [Learning how to learn](https://www.coursera.org/learn/learning-how-to-learn "Coursera Course - Learning How to Learn") - Great course on learning the techniques to be able to learn and grasp faster
* [Accelerating your security learning](https://github.com/makash/accelerating-your-security-learning-in-2017-null-Bangalore-Jan2017 "Accelerating Your Security Learning") - A bit dated but a methodology for keeping up new things to learn and making a system for learning about security. This one is best done in a group.
