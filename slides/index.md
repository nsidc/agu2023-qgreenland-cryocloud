---
title: "🇬🇱 QGreenland &<br/>🌨️ CryoCloud"
subtitle: "An open GIS collaboration for education and research"
---


## In this presentation...

* **A problem in our community**: Technical training is hard!
* **(Part of) the solution**: Teaching on a JupyterHub to reduce distractions, improve
  accessibility, and enhance learning. _A [**QGreenland**]{.qgreenland-red}
  workshop collaboration success story._
* **How you can do it to**: Check out [**CryoCloud**](https://cryointhecloud.com)!

:::{.notes}
Technical training is hard. Technical training about Earth science data is especially
hard, and often requires a complex software environment.

Teaching on a JupyterHub enables learners and instructors to focus more of their time on
learning and less of it on troubleshooting.

This could be an option for your next workshop!
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
I'm Matt Fisher:

* Mid-career software developer
* Working at NSIDC
* Author, with Trey Stafford, of the QGreenland software
* Instructor, with Trey Stafford and Alyse Thurber, of QGreenland Researcher Workshop
  this year. More on that soon! At the time, both Trey and myself were new to developing
  technical training and acting as instructor, so we learned a lot as we went.

If anything in this talk goes by too quickly, there will be a QR code at the final slide
linking to the webpage for this presentation. There you can find a copy of the slides
(including bonus slides), learn more about authors of this talk, and find several links
we think you might be interested in.
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
_Read the text._

Community education and outreach, and therefore workshops, are important parts of our
grant-funded activities.

_TODO: Talk about how we're going in to this with little experience?_
:::


# A problem in our community

Technical training is hard!

:::{.notes}
Planning and administering technical training is hard.

We need to consider your topic carefully, and make sure it's sized right for the time
you have.

We need to build up knowledge in the correct order.

We need to design exercises that will help learners remember their new knowledge.

We need to figure out how breakout rooms in Zoom work.

On top of these things, we need to worry about how learners will set up technical
requirements. For our workshop, do we need loaner laptops? Do we need a Mac expert and a
Windows expert on the teaching team?
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


## 🦻 Accessibility

Hardware and operating systems are expensive.

Accessibility is our responsibility!

:::{.notes}
Hardware is expensive, and operating systems are expensive.

Not everyone has the time to set up their user configuration and install dependencies
for a workshop.

This is an accessibility barrier!

As course administrators, we have a responsibility to accessibility. The more accessible
our workshop activities and materials are, the more people can learn from them.
:::


# [QGreenland]{.qgreenland-red} workshop

:::{.notes}
This slide is just a separator, skip through it.
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
We want to run a virtual workshop that's accessible to researchers around the world at
all career levels.

Because we're teaching FAIR scientific data principles, we want our workshop to also
embody those principles. We gave ourselves a star where we think we did particularly
well.

* F: Our workshop is available as a website and as a public Git repository. We're doing
  outreach to share the materials and outcomes.
* A: Anyone can contribute to or learn from our materials using open protocols
  (HTTP/Git). We provided a small stipend to support equitable participation.
* I: Our source materials are in a common authoring format: Markdown
* R: We bundled documentation to support others re-running our workshop.

Our workshop requires users to be able to run QGreenland and install several
dependencies, including GDAL and optionally Git. It's important these are all at
versions compatible with the materials. We really don't want this to be a distraction
from learning!
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
25 learners from all career stages, representing Germany, Poland, India, France, Canada,
and the US completed our workshop. Our only technical prerequisites were Internet access
and a browser.

NOTE: Internet access is no small barrier to participation, but our format enabled
international participation without requiring travel, which we felt was important.

We reduced the costs of setting up compute infrastructure from an expected $4500 to only
$75 in cloud costs for a 3-day workshop.

We produced open-source educational materials that will be useful even now that our
workshop is complete.

And we did outreach activities like a guest post on the _Jupyter Blog_ to share what we
learned.

There will be a QR code on the last slide that will include a link to our workshop
materials, details about outcomes, and the _Jupyter Blog_ post.
:::


## How we got there

<p align="center">
[![](https://book.cryointhecloud.com/_static/logo.png){height="300" fig-alt="CryoCloud logo"}](https://cryointhecloud.com)
[![](https://2i2c.org/media/logo.svg){height="300" fig-alt="2i2c Logo"}](https://2i2c.org)
</p>

*CryoCloud _JupyterHub_ to the rescue!*

:::{.notes}
Colleagues with the _CryoCloud_ project run a _JupyterHub_ which aims to transition the
NASA research community to cloud and open source work patterns, and this aligns well
with our workshop goals.

The JupyterHub is operated by _International Interactive Computing Collaboration_, a
fiscally-sponsored non-profit.
:::


## :ringed_planet: _JupyterHub?_

:::{.fragment}
:memo: _Jupyter Notebook_:
Interactive computing file format.
:::

:::{.fragment}
:desktop_computer: _JupyterLab_:
A comprehensive browser-based environment for using _Jupyter Notebooks_.
:::

:::{.fragment}
:partly_sunny: **_JupyterHub_**:
_JupyterLab_ in the cloud, **on demand**.
:::


:::{.notes}
:memo: _Jupyter Notebook_:
Interactive computing file format. May be most familiar of these three. Can be edited
and viewed with various tools including the official Jupyter "notebook server" (`jupyter
notebook`), VSCode, PyCharm, and Google Colab.

:desktop_computer: _JupyterLab_:
A comprehensive browser-based environment for using _Jupyter Notebooks_, including tools
you're used to in your local computing environment, such as file browser, terminal,
package managers, image previewers, and tabular data editors.

:partly_sunny: **_JupyterHub_**:
_JupyterLab_ deployed in the cloud so users can create a _JupyterLab_ on demand with no
prior knowledge.
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
* Look, we're in the browser, starting off on the AGU website, then navigating to
  `CryoInTheCloud.com`
* We'll navigate to their _JupyterHub_ link, click "login"
* We have a few options for our cloud server that'll be provisioned. I want Python, and
  1 CPU.
* This loading part is in real-time
* My JupyterLab cloud instance is ready!
* Just fast forwarding through pointing out a few cool things JupyterLab can do, like
  previewing GeoJSON...
* Let's open the desktop
* Let's navigate to and open QGreenland
* Let's just explore some stuff that looks interesting. I'm looking at the "Runoff"
  variable from the RACMO climate model.
* This looks cool, so I want to see satellite imagery of the area.
* I found a neat looking feature, so I decided to measure it, and it's a bit over 4km
  across.
* You can of course use any other QGIS analysis or processing features. This is just to
  share how smooth the desktop experience feels in the cloud!

This talk is more focused on how this helped us improve learning outcomes; if you want
technical detail on this subject, check out our _Jupyter Blog_ post! QR code on the last
slide.
:::


# 🫵  You can do this too!

:::{.notes}
:::


## :money_with_wings: Cost is still high, so...

#### :handshake: Collaboration with an existing community was key!

#### 🫵  And you can do this too.

> :::{.nonincremental}
> * [Sign up for CryoCloud](https://book.cryointhecloud.com/content/Getting_Started.html)
> * [See a list of 2i2c JupyterHubs](https://infrastructure.2i2c.org/reference/hubs/)
> :::

:::{.notes}
As you saw in a previous slide, setting up a cloud _JupyterHub_ with all the features
you need for your workshop can be expensive. Because of this, collaborating with an
existing community was essential if we wanted to pursue this strategy.

We were fortunate to have established connections with _CryoCloud_ to help us get
started, but I think communities in this space are eager for collaborators. We brought
value to all future users of the hub by making QGIS and QGreenland readily available,
and we helped grow the community by onboarding our learners as new users.

If you're looking to run a workshop, consider an existing community to collaborate with,
like CryoCloud!

On our last slide, follow the QR code to find a link to a list of all 2i2c JupyterHubs,
that's a great starting place! There appear to be around 70 running hubs.

If you're looking to fund these type of activities, consider doing it through operating
a _JupyterHub_ community!
:::


# :bow: Thank you {.smaller}

{{< include "/logos.md" >}}

Also at AGU:

{{< include /other_presentations.md >}}


:::{.notes}
Thank you!

There are some other sessions coming up that you might be interested listed on this
slide. Again, the QR code at the end will take you to a website where you can find these
slides in case you missed a session number. U24B-03 is coming up later today, the others
are on Friday.
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
If you follow the QR code, it'll take you to the website for this presentation.

You'll see a collection of links, including on to join us on GitHub Discussions, and
another to join CryoCloud.
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
