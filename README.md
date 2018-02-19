Horizontal DevOps
-----------------

Often DevOps considiers a vertical silo of a project, what is the hosting, what is the dev pipeline, what is the QC and deploy pipeline.  That is important, but it is also important to step back and evaluate each of your projects verticals and compare and contrast them.

Differences Should not be the Norm
----------------------------------

When comparing all your projects for the dev, test, and deploy pipelines look to see where they are different and if there is opportunity for considation.  That could be on:

  * Tooling
  * Process
  * Automation

Minimizing differences in tooling, process and automation goes a long way to optimizing your human resources. If team members don't have to waist brain cycles on ramping into a project and can be plugged into the part they are best at with minumal effort you are doing gteat!


Documentation is Critical
-------------------------

Open up your docs!

* [Tandem Docs](https://docs.thinktandem.io/) ~ you can view our docs today and see how we do it.

That doesn't mean you have to do it that way too, but you can get a baseline or comparison for a way forward.

Interfaces Matter; Implementation is Irrelevant
-----------------------------------------------

If you can offer a consistent DX accross all of your projects, then you can reduce ramp up time on getting a developer up and running and productive on a project.

For example you might standardize on:

```bash
lando composer test
```

So the details of implementation here have several layers of complexity, and could even have different details per project, but from the perspective of a developer on there day to day work to run tests on any project you run `lando composer test`.

Needs to be Repeatable
----------------------

Being able to spin up the same stacks, interfaces, and pipelines accross projects needs to be repeatable.  This is where tools like docker come into play.  There are lots of tools to choose from to get the repeatability your team wants or needs. Which tools you pick is less important then the fact that you and your team think about and choose consistent tools across projects where poassible.

This repeatability directly ties into the developers being able to quickly plugin to projects where their expertise is required; hopefully without even noticing the DevOps.

Invest in DevOps
----------------

If you do not have dedicated DevOps people you should. A lot of companies don't know how or if it is worth it to get the ball rolling with DevOps ... the how is this presentation. The answer to is it worth it is YES!

Tool Selection
--------------

Selecting your tools can be a daunting task! Here are some guidelines we find useful:

* Prefer Open Source
* Choose flexible tools over a very specific tool

Don't be Dogmatic
-----------------

It is easy to start this process by saying to yourself every stack is going to be the same: period.

Don't do that.  Give each project the opportunity to be unique. We don't want to choke the project. Every project will have different requirements and some different pieces; Our goal here is to minimize the differences, but still allow for them per project.

Continuously Evaluate
---------------------

DevOps technology and paradigms change. Be flexible! Once you have some docs, tools, and pipelines give your DevOps team time and resources to research the landscape, see the new tools, pick some and evaluate them. Not in isolation, but to hwo they may fit into your pipeline either as a new thing, or a replacement for one or more of your things.

Avoid Bus Problems
------------------
