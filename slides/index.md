---
title: "🇬🇱 QGreenland &<br/>🌨️ CryoCloud"
subtitle: "An open GIS collaboration for education and research"
title-slide-attributes:
  data-notes: |
    Welcome to our talk: _read slide_
---


## In this presentation...

* **A problem in our community**: Technical training is hard!
* **(Part of) the solution**: Teaching on a JupyterHub to reduce distractions, improve
  accessibility, and enhance learning. _A [**QGreenland**]{.qgreenland-red}
  workshop collaboration success story._
* **How you can do it to**: Check out [**CryoCloud**](https://cryointhecloud.com)!

:::{.notes}
In this presentation, we're going to talk about a community problem: Technical training
about Earth science data and GIS is difficult, and often requires a complex software
environment for learners.

After gaining some experience this year, we feel that teaching on a JupyterHub is part
of the solution. This enables learners and instructors to focus more of their time on
learning and less of it on troubleshooting.

We think this could be a good option for your next workshop!
:::


---

:::::: {.columns}

::: {.column width="20%"}
![Matt Fisher^1,2^ - [Software Developer](https://github.com/nsidc/)](https://qgreenland.org/sites/default/files/styles/medium/public/2023-08/Matt_Fisher_v2_0.png?itok=xLmAWIfs)
:::

::: {.column width="20%"}
![Twila Moon^1,2^ - [Researcher](https://nsidc.org/about/about-nsidc/what-we-do/our-people/twila_moon)](https://qgreenland.org/sites/default/files/styles/medium/public/2023-08/TwilaMoon_0.jpeg?itok=TqiU0RYQ)
:::

::: {.column width="20%"}
![Alyse Thurber^2^ - [Education and Outreach](https://cires.colorado.edu/outreach/)](https://qgreenland.org/sites/default/files/styles/medium/public/2023-08/IMG_8099_1.jpeg?itok=vZDLKFqu)
:::

::: {.column width="20%"}
![Tasha Snow^3^ - [Researcher](https://geophysics.mines.edu/project/tasha-snow/)](https://i0.wp.com/geophysics.mines.edu/wp-content/uploads/sites/30/2021/03/T_Snow_2020.jpg?resize=300%2C300&ssl=1)
:::

::: {.column width="20%"}
![Trey Stafford^1,2^ - [Software Developer](https://github.com/nsidc/)](https://qgreenland.org/sites/default/files/styles/medium/public/2023-08/TreyStafford_0.jpeg?itok=tU4MgABx)
:::

::::::

<!-- NOTE: Normal footnotes won't work here.
     https://github.com/quarto-dev/quarto-cli/issues/5440 --->

:::{style="font-size:60%;"}
1: [National Snow and Ice Data Center (NSIDC), University of Colorado Boulder](https://nsidc.org)

2: [Cooperative Institute for Research in Environmental Sciences (CIRES), University of Colorado Boulder](https://cires.colorado.edu)

3: [Colorado School of Mines](https://www.mines.edu/)
:::


:::{.notes}
I'm Matt Fisher, and this is the QGreenland and CryoCloud team that authored this talk.

* Software developer for the last 15 years, currently at NSIDC
* Author, with Trey Stafford, of the QGreenland software
* Instructor, with Trey Stafford and Alyse Thurber, of QGreenland Researcher Workshop
  this year. More on that soon!

If anything in this talk goes by too quickly, there will be a QR code at the final slide
linking to the webpage for this presentation where you can find a copy of the slides and
more on the authors.

_TODO: Consider omitting last names in speaker notes._
:::


## ![](/_assets/qgreenland_logo.svg){height="1em" style="margin-bottom: 0px;"} What is [QGreenland]{.qgreenland-red}? {.smaller}

::::::{.columns}

:::{.column width="30%"}
* **All-in-one, open-source, Greenland-focused GIS environment for offline and online
  use** with **QGIS**
* **Curated interdisciplinary data package** for research, learning, decision-making, and
  collaboration.

<https://qgreenland.org>
:::

:::{.column width="70%"}
![](/_assets/qgreenland_overview.png)
:::

::::::


:::{.notes}
An open-source, **Greenland**-focused, interdisciplinary data package and GIS environment
for research, learning, and decision-making.

QGreenland is built for online or offline use, for example in remote field work.

Community education and outreach are important parts of our grant-funded activities, so
we've run several workshops over the last 3 years.
:::


# A problem in our community

Technical training is hard!

:::{.notes}
Planning and administering technical training is hard.

We need to consider our topic carefully, and make sure it's sized right for the time
you have.

We need to build up knowledge in the correct order.

We need to design exercises that will help learners remember their new knowledge.

We need to figure out how breakout rooms in Zoom work even though we thought we knew.

On top of these things, we need to worry about how learners will set up technical
requirements. Question like: For our workshop, do we need loaner laptops? Do we need a
Mac expert and a Windows expert on the teaching team for technical support?
:::


## :desktop_computer: Variance in user systems

:::{.fragment}
* Hardware, operating system, and user comfort level
:::

:::{.fragment}
* User configuration
    * Installed programming languages & versions
    * Dependency managers & installed dependency locations
:::

:::{.fragment}
:point_up: **Takes time away from teaching, planning, and learning.**
:::

:::{.notes}
In this talk, we'll zoom in on variance in user systems as a distraction from all the
other important things we just talked about.

* I'm only comfortable with one **operating system** myself.

* Many learners' **user configurations**, like mine, are customized.

* We all, learners and instructors, only have so much time and attention to give.
:::


## :heart: Accessibility

Hardware, (some) operating systems, and time are expensive.

**Accessibility is our responsibility!**

:::{.notes}
This is also an accessibility and inclusivity problem.

Hardware, operating systems, time, and expertise are expensive.

Not everyone has a laptop with 32GB of RAM, or the free time to set up dependencies for
a workshop.

**This is a barrier to participation!** In our role as educators, we feel responsible to
reduce that barrier.
:::


# [QGreenland]{.qgreenland-red} workshop

:::{.notes}
The QGreenland researcher workshop was a 3-day workshop that occurred earlier this year.

Both Trey and myself are primarily software developers and newer to our role as
educators, so we learned a lot as we went, especially from Alyse Thurber with CIRES
Education & Outreach.
:::


## [QGreenland]{.qgreenland-red} workshop objectives

:::{.fragment}
:satellite: Run a virtual workshop
:::

:::{.fragment}
:test_tube: Follow FAIR open science principles

> :::{.nonincremental}
> * **F**indable
> * **A**ccessible :star:
> * **I**nteroperable
> * **R**eusable :star:
> :::
:::

:::{.fragment}
:unicorn: Minimize or eliminate distractions from system variance
:::

:::{.notes}
We want to run a virtual workshop for a diverse audience of researchers.

Because we want to **teach** FAIR scientific data principles, we want our workshop to
also embody those principles. We gave ourselves a star where we think we did
particularly well.

* **A**: We provided a small stipend to support equitable participation. Anyone can
  learn from our materials on our website, or contribute to our materials on GitHub.
* **R**: We authored administrative documentation to support others re-running our
  workshop.

Our workshop requires users to be able to run QGreenland and install several other
dependencies, including GDAL, and we wanted to avoid supporting all the possible
pitfalls setting those up.

_Extra_ (skip in main reading):

* F: Our workshop is available as a website and as a public Git repository. We're doing
  outreach to share the materials and outcomes.
* I: Our source materials are in a common authoring format: Markdown
:::


## [QGreenland]{.qgreenland-red} workshop outcomes

:::{.fragment}
:woman_scientist: 25 learners from all career stages :de: :poland: :india: :fr: :canada: :us:
:::

:::{.fragment}
:money_with_wings: Reduced costs by *>$4000* by collaborating with CryoCloud
:::

:::{.fragment}
:evergreen_tree: Produced sustainable, re-usable materials
:::

:::{.fragment}
:ringed_planet: Shared lessons learned in
[_Jupyter Blog_ post](https://blog.jupyter.org/desktop-gis-software-in-the-cloud-with-jupyterhub-ddced297019a)
:::


:::{.notes}
25 learners from around the world, and from all career stages joined and completed our
workshop. Our only technical prerequisites were Internet access and a browser.

_EXTRA NOTE: Internet access is no small barrier to participation, but our format enabled
international participation without requiring travel, which we felt was important._

We reduced the costs of the computing infrastructure from an expected $4500 in setup
cost to only $75 in cloud costs for a 3-day workshop by collaborating with the CryoCloud
community.

We produced open-source educational materials that we hope will be useful for a long
time.

And we did outreach activities like a guest post on the _Jupyter Blog_ to share what we
learned.

The QR code on the last slide will take you to that post.
:::


## How we worked around system variance

<p align="center">
[![](https://book.cryointhecloud.com/_static/logo.png){height="300" fig-alt="CryoCloud logo"}](https://cryointhecloud.com)
[![](https://2i2c.org/media/logo.svg){height="300" fig-alt="2i2c Logo"}](https://2i2c.org)
</p>

*CryoCloud _JupyterHub_ to the rescue!*


:::{.notes}
The _CryoCloud_ project aims to transition the NASA research community to cloud and open
source work patterns. Our participants did their work on CryoCloud's _JupyterHub_
instead of on their personal computers.

The CryoCloud JupyterHub is operated by _International Interactive Computing
Collaboration_, a fiscally-sponsored non-profit.
:::


## :ringed_planet: _JupyterHub?_

:::{.fragment}
:memo: _Jupyter Notebook_:
Interactive computing file format.
:::

:::{.fragment}
:desktop_computer: _JupyterLab_:
A comprehensive browser-based environment for using _Jupyter Notebooks_, and more.
:::

:::{.fragment}
:partly_sunny: **_JupyterHub_**:
_JupyterLabs_ managed in the cloud, **on demand**.
:::


:::{.notes}
Hopefully I'm not repeating too much from previous talks. I'll go through this quickly:

:memo: _Jupyter Notebook_:
Interactive computing file format. You can view and edit notebooks with various tools
including the official Jupyter "notebook server" (`jupyter notebook`), VSCode, PyCharm,
and Google Colab.

:desktop_computer: _JupyterLab_:
A comprehensive browser-based environment for _Jupyter Notebooks_, including
desktop-like tools such as file browser, terminal, package managers, image previewers,
and tabular data editors.

:partly_sunny: **_JupyterHub_**:
A system for managing _JupyterLabs_ in the cloud so users can create a _JupyterLab_ on
demand with no prior knowledge.
:::


# :cloud: Desktop GIS in the cloud

![QGIS logo](/_assets/qgis_logo.svg){fig-align="left" height="128"}

:::{.notes}
Now let's look at a quick demo of the GIS experience we set up for our workshop.
:::


---

<iframe
  width="560" height="315"
  title="YouTube video player"
  src="https://www.youtube.com/embed/3mvfxIxx3Hw?si=fAq68sz2T1LtZHvr"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen
  style="display: block; margin: 0 auto;">
</iframe>

:::{.notes}
* Everything you see here is going to happen in the browser.
* First, we're navigating to `CryoInTheCloud.com`.
* We'll navigate to their _JupyterHub_ link and log in.
* We can configure our personal cloud server. I want Python, and 1 CPU.
* This loading part is in real-time. Some parts of this video are sped up, indicated
  with fast-forward icons.
* My JupyterLab is ready!
* Just fast forwarding through pointing out a few cool things JupyterLab can do, like
  previewing GeoJSON, a terminal...
* Let's open the desktop.
* Navigate to and open the QGreenland QGIS project.
* Loading here is sped up to replicate the experience learners had in our workshop. This
  demo was recorded on less optimized and less expensive configuration.
* Let's explore some stuff that looks visually interesting. I'm looking at the "Runoff"
  variable from the RACMO climate model.
* This looks cool, so I want to see satellite imagery of the area.
* I found a neat looking feature, so I decided to measure it, and it's a bit over 4km
  across.
* You can use any other QGIS analysis or processing features with this setup. This is
  just to share how smooth and familiar the desktop experience feels in the cloud!

If you want technical detail on the infrastructure, you can check out our _Jupyter Blog_
post and engage with CryoCloud and 2i2c on GitHub! QR code on the last slide.

_IMPORTANT: When demo is done, click the fullscreen toggle button. DO NOT press escape
or F11._
:::


# 🫵  You can do this too!

:::{.notes}
We think you can also do this for your next workshop.
:::


## :money_with_wings: Cost is still high, so...

:::{.fragment}
#### :handshake: Collaboration with an existing community was key!
:::

:::{.fragment}
#### 🫵  And you can do this too.

> :::{.nonincremental}
> * [Sign up for CryoCloud](https://book.cryointhecloud.com/content/Getting_Started.html)
> * [See a list of 2i2c JupyterHubs](https://infrastructure.2i2c.org/reference/hubs/)
> :::
:::

:::{.notes}
As you saw in a previous slide, setting up a cloud _JupyterHub_ with all the features
you need for your workshop can be expensive.

_Advance_

Because of this, collaborating with an existing community was essential if we wanted to
pursue this strategy.

We were fortunate to have established connections with _CryoCloud_ to help us get
started, but many communities in this space are eager for collaborators. This
arrangement saved our team lots of money, and we also provided value to CryoCloud: all
future users of the hub will have ready access to QGIS and QGreenland, and the
_CryoCloud_ community grew because we onboarded our learners as new users.

_Advance_

If you're looking to run a workshop, consider an existing community to collaborate with,
like _CryoCloud_! Sign up by following the QR code at the end.

2i2c publishes a list of all the JupyterHubs they operate. That's another great place to
find collaborators.

_Extra: If you're looking to fund these type of activities, consider doing it through operating
a_ JupyterHub _community!_
:::


# :bow: Thank you {.smaller}

{{< include "/logos.md" >}}

Also at AGU:

{{< include /other_presentations.md >}}


:::{.notes}
Thank you!

There are some other presentations coming up that you might be interested listed on this
slide. You'll be able to find these by following the QR code at the next slide, too.

**U24B-03** is coming up later today, check it out!
:::


## :question: Q&A

::::::{.columns}

:::{.column width="34%"}
![[https://nsidc.github.io/agu2023-qgreenland-cryocloud/references.html]{style="font-size: 80%;"}](/_assets/qr_references.png)
:::

:::{.column width="66%"}
### Contact

`Matthew.J.Fisher@colorado.edu`

`qgreenland.info@gmail.com`

Join [CryoCloud](https://cryointhecloud.com) and chat with us on [**GitHub
Discussions**](https://github.com/nsidc/qgreenland/discussions/)!
:::

::::::


:::{.notes}
I'm excited to talk with you and hear your questions!

If you follow the QR code, it will take you to the website for this presentation.

There, you'll see a collection of links, including: join us on GitHub Discussions, get
started with CryoCloud, download QGreenland, or learn more about the authors of this
talk.
:::


# :tada: Bonus slides


## :thumbsdown: Distractions

:thumbsdown: Distractions contribute to learners' cognitive load and reduce learning
effectiveness.

:thumbsdown: Distractions consume teaching time.

:thumbsdown: Distractions consume planning time.


:::{.notes}
_TODO: Make text on slide more succinct, move wordy stuff into notes_

Planning: How many helpers do we need? What prep-work do we need participants to do
(installing software, etc.)? Do we need loaner hardware? This time could be better spent
on curriculum.
:::


## :handshake: A mutually-beneficial collaboration

:::{.fragment}
#### :money_with_wings: Reduced costs by collaborating!

> :thumbsdown: ~~2-4 weeks + ~$4500 to set up~~
>
> :thumbsup: 2-3 days to setup + ~$75 cloud costs
:::

:::{.fragment}
#### :sparkles: Contributed new functionality to the _CryoCloud_ hub

> :open_hands: **Open-source desktop GIS in the cloud!**
>
> :tada: **11** Pull Requests merged; **9** issues opened
:::


:::{.notes}
CryoCloud & QGreenland both benefitted from this arrangement.

* Reduced costs benefit our workshop participants by allowing us to focus more on
  teaching
    * Without: $4500 + 2-4 weeks setup
    * With: $0 + 2-3 days setup + $75 cloud operating expenses

* CryoCloud is an inclusive open source project. Running workshops helps expand
  CryoCloud's (and other hubs!) capabilities:
    * We merged **11** PRs and opened **9** issues to help improve CryoCloud.
    * We collaborated with 2i2c and CryoCloud to enable QGIS, an open source desktop GIS
      application that competes with ArcGIS,
      to be used effectively in the cloud by a classroom-sized group, to do real data
      analysis. This involved...
        * MIME type fixes so QGIS project files open when double-clicked.
        * Performance improvements so QGIS projects could load as fast as they do on
          local compute.
        * Demo on upcoming slide.
    * Misc. improvements:
        * Upgrading important dependencies like Git
        * Fixing support for man pages
        * Adding utilities our users and instructors would need
        * Improving documentation
        * Improving CI/CD automations
        * Eliminating warnings that distract from learning
:::


---

#### :chart_with_upwards_trend: Supported _CryoCloud_ community growth & evaluation of impact

> :open_hands: Our workshop learners joined the _CryoCloud_ community!

:::{.fragment}
#### :bulb: Inspired other institutions to replicate our advancements

> :ringed_planet: [_Jupyter Blog_ post](https://blog.jupyter.org/desktop-gis-software-in-the-cloud-with-jupyterhub-ddced297019a)
:::


:::{.notes}
* Running workshops helps expand the CryoCloud community
* Running workshops helps the CryoCloud team gather data (e.g. surveys) to measure their
  impact.

* We published a
  [Jupyter Blog post](https://blog.jupyter.org/desktop-gis-software-in-the-cloud-with-jupyterhub-ddced297019a)
  describing our advancements. There will be a QR code at the end.
    * As a result, 2i2c reported increased requests from their clients for the
      functionality we demonstrated in our blog post.
    * More _JupyterHubs_ adopted QGIS desktop functionality.
:::
