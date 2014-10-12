---
permalink: /
layout: page
---

There is an incredible wealth of open-source DevOps tools available today, all
with their own growing communities. With the recent surge in popularity of command
line centric open source, a wave of newcomers are working with the UNIX command
line for the first time. Patterns that were long only the territory of hackers are
being optioned by the folks who have learned development from a media first
perspective. There is an incredible opportunity to normalize and grow the patterns
we use to build things.  The problem is that into order to utilize all of this
goodness you need an awful lot of background knowledge to get to the point where
it works effectively. StackStrap seeks to mitigate these issues.

StackStrap is decentralized in nature and could be described as a [PaaS] that
companies can run for themselves. The project aims to simplify the process of
building and deploying web based applications and services using existing
open-source. By building up around existing projects StackStrap becomes little
more than an evolving strategy. The project is geared towards smaller operations
which employ a wide range of skill levels and may not be able to afford in house
developer operations. The idea is to offer the simplicities of services like
[Heroku] while allowing companies to leverage the costs savings of root cloud
services like [AWS].

<!--
I don’t like Heroku & AWS being called out directly. I think you should describe
what value Heroku adds and remove the name reference. Same with AWS. For all we
know someone may way to use this with private cloud and custom automation.
-->

Ultimately StackStrap is a strategy for utilizing some of the greatest automation
innovations that have been offered to the modern web development community.  It
revolves around the idea that the core of a project well suited for rapid and
collaborative development is little more than a specifically laid out tree of
files containing meta-data to describe and coordinate these automation tools in a
way that "just works". Teams should be enabled to learn a short list of simple
commands that enable clear objectives.  This will allow them to utilize simple
work-flows that offer well defined structure so they can spend more time writing
code while worrying less about low level details about the environment that they
will run in.

## The Goal

StackStrap is about distilling the fundamentals of DevOps and providing a concise
framework to apply these fundamentals in whichever way works best for the specific
team and project at hand.

## The Triumvirate

##### Vagrant

[Vagrant] reduces the hugely complex subject of virtualization to a small subset
of uniform and rational commands; be it virtualization on your local machine or on
the cloud.  Vagrant enables you to take the process of creating, starting, and
stopping these instances to simple commands that can be remembered and understood
by anyone.

Vagrant has a massive user base contributing to it which is not fixated on any
particular community. This makes Vagrant the perfect choice as the standard
gateway to virtualization and automation. 

##### SaltStack

[Salt] is infrastructure management software that is easy enough to get running in
seconds, scalable enough to manage tens of thousands of servers, and fast enough
to control and communicate with them in milliseconds.

Salt was designed to be extremely flexible and enable the process of creatively
shaping virtual systems for anything imaginable. The core idea behind Salt is the
process of describing the "State" of a system as an object of data. This allows
you to define your desired configuration for systems using YAML, a straight
forward markup language that is easy to read and write. The process of defining
how something will work as an object is becoming the standard in DevOps, as seen
in popular tools like [Grunt] or [Gulp].

##### Docker

[Docker] is the evolution of how applications will run and be deployed.
Essentially it allows you to isolate all the the system processes that your
application depends on within a sandboxed container. You can run this container
on any system with a modern Linux kernel. The process of "docking" to a running
Linux kernel means that a Docker container will boot in next to no time. This
means that you could verify your application is running as expected on your
local machine and then deliver it to a remote server.  It also means that you
can have one powerful machine that runs all of your environments (staging,
production...) as proxies to a single web server. This offers serious cost and
preformance benefits while reducing a great deal of redundancies.

[PaaS]: http://en.wikipedia.org/wiki/Platform_as_a_service
[Heroku]: https://www.heroku.com/
[AWS]: http://aws.amazon.com/
[Vagrant]: http://vagrantup.com/
[Salt]: http://saltstack.com/
[Grunt]: http://gruntjs.com/
[Gulp]: http://gulpjs.com/
[Docker]: https://www.docker.com/
