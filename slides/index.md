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
This is only one of the things that makes technical training hard. In this talk,
we'll focus on variance in user systems as a distraction from all the things we just
talked about in the previous slide..

* I'm only comfortable with one **operating system** myself.

* Many learners' **user configurations**, like mine, are customized.

* We all, learners and instructors, only have so much time and attention to give.
:::


## 🦻 Accessibility

Hardware and operating systems are expensive.

Accessibility is our responsibility!

:::{.notes}
Hardware is expensive, and operating systems are expensive. This is an accessibility
barrier!

Not everyone has the time to set up their user configuration and install dependencies
for a workshop.

As course administrators, we have a responsibility to accessibility. The more accessible
our workshop activities and materials are, the more people can learn from them.
:::


# [QGreenland]{.qgreenland-red} workshop

:open_hands: Open source! _TODO: Can/should we say our workshop is FAIR?_

<https://qgreenland-workshop-2023-researcher.github.io/>

:::{.notes}
There will be a QR code on the last slide that will include this link.
:::


## [QGreenland]{.qgreenland-red} workshop

### Objectives

:satellite: Run a virtual, open, accessible workshop

:unicorn: Minimize or eliminate distractions from participants' unique systems

:::{.notes}
We want to run a workshop that's accessible to researchers around the world at all
career levels.

Our workshop requires users to be able to run QGreenland and install several
dependencies, including GDAL and optionally Git. It's important these are all at
versions compatible with the materials. We really don't want this to be a distraction
from learning!
:::


## [QGreenland]{.qgreenland-red} workshop

### Outcomes

:student: 25 learners :de: :poland: :india: :fr: :canada: :us:

:woman_scientist: Researchers from all career stages

:money_with_wings: Reduced costs by *>~$4000* by collaborating with CryoCloud

:ringed_planet: Shared lessons learned in
[_Jupyter Blog_ post](https://blog.jupyter.org/desktop-gis-software-in-the-cloud-with-jupyterhub-ddced297019a)


:::{.notes}
Our workshop was able to serve 25 learners from all career stages, representing Germany,
Poland, India, France, Canada, and the US. Our only technical prerequisites
were Internet access and a browser.

NOTE: Internet access is no small barrier to participation, but our format enabled
international participation without requiring travel, which we felt was important.

We reduced the costs of setting up compute infrastructure from an expected $4500 to only
$75 in cloud costs for a 3-day workshop.

We shared our lessons learned in a post on the _Jupyter Blog_. Our last slide will have
a QR code that will take you to a page with links, including to this post.
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

_TODO: QGIS logo_

:::{.notes}
_TODO: Speaker notes_
:::


---

_TODO: Image(s) or very short animation_

:::{.notes}
This talk is more focused on outcomes and how you can reproduce our success; if you
want the most detail on this subject, check out our _Jupyter Blog_ post! QR code on the
last slide.
:::


# 🫵  You can do this too!

:::{.notes}
_TODO: Speaker notes_
:::


## :money_with_wings: Cost is still high, so...


#### :handshake: Collaboration with an existing community was key!

#### 🫵  And you can do this too.

* _TODO: Link to 2i2c hub listing_
* _TODO: Other resources to find computing communities_
* _TODO: Suggest operating a hub? How to avoid duplicating work?_

:::{.notes}
As you saw in a previous slide, setting up a cloud _JupyterHub_ with all the features
you need for your workshop can be expensive. Because of this, collaborating with an
existing community was essential if we wanted to pursue this strategy.

We were fortunate to have established connections with _CryoCloud_ to help us get
started, but I think communities in this space are eager for collaborators.

If you're looking to run a workshop, consider an existing community to collaborate with.

If you're looking to fund these type of activities, consider doing it through operating
a _JupyterHub_ community!
:::


# :bow: Thank you

{{< include "/logos.md" >}}

Other sessions:

_TODO: Fill out CryoCloud & Openscapes sessions/tutorials. Use the identifier
 for the presentation. Poster number, title._

:::{.notes}
Thank you!
:::


## :question: Q&A

::::::{.columns}

:::{.column width="34%"}
![[https://nsidc.github.io/agu2023-qgreenland-cryocloud/references.html]{style="font-size: 80%;"}](/_assets/qr_references.png)
:::

:::{.column width="66%"}
### Contact

`mfisher87@gmail.com`

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


## TODO

- [ ] Better narrative structure for the workshop. We needed X, Y, Z to do our workshop
  in the cloud. QGIS and QGreenland were of course the most important requirements.
- [ ] Acknowledgements
