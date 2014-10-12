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

Ultimately StackStrap is a strategy for utilizing the three greatest
automation innovations that have ever been offered to the web development
community. StackStrap revolves around the idea that the core of a well oiled
project is little more than a tree of files. Some of those files should be able
to describe how to automate things into a state that just works. Teams should be
enabled to learn a short list of simple commands which enable clear objectives.
This will allow teams to work with simple workflows that offer far more
structure so they can spend more time making the things they love while worrying
less.

## The Goal

Good open-source ideas should effectively build themselves. StackStrap aims to
evolve to be exactly what teams need out of it. It may not be exactly this today,
but the goal is to get a solid groundwork in place to get there. StackStrap is all
about distilling the fundamentals of DevOps and never being perscriptive. Instead
teams should be able to digest these fundamentals and run the way that they feel
works best for them. Having solid developer operations in place is the key to any
successful project. On top of that being able to keep up with emerging standards
is extremely important.

If this project could enable a "DevOps-on-demand" model that freelancers could
sell to companies, that would be viewed as a huge success! Getting off on the
right foot can have huge rewards and is worth the investment.

## The Triumvirate

##### Vagrant

Effectively [Vagrant] distills virtualization to a small subset of rational
commands; be it virtualization on your local machine or on the cloud. Vagrant
enables you to boil down the process of creating/starting/stoping these machines
to simple commands that can be remembered and understood by anyone. Vagrant has
a massive user base contributing to it which is not fixated on any particular
community. This makes Vagrant the perfect choice as the standard gateway to
virtualization and automation. Be it virtualizing a local development
environment or a server to deploy your application to, Vagrant makes it easy for
anyone.

##### Salt

[Salt] is the newest configuration management tool on the market and offers
some key design vartiations that will set it apart from its competitors. It
focuses on the decentralization of operations to cut out the bottlenecks that
occur when dealing with thousands of servers while also being able to easily
setup just a single machine. Salt was designed to be extremley flexible and
enable the process of creatively shaping virtual systems for anything
imaginable. The core idea behind Salt is the process of describing the "State"
of a system as an object of data. This allows you to define a system using YAML,
JSON or whatever else comes along. The process of defining how something will
work as an object is becoming the standard in DevOps, as seen in popular tools
like [Grunt] or [Gulp].

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
