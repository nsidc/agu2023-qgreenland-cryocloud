---
title: "🇬🇱 QGreenland &<br/>🌨️ CryoCloud"
subtitle: "An open GIS collaboration for education and research"
---

:::::: {.columns}

::: {.column width="20%"}
![Matt Fisher^1,2^ - [Software Developer](https://github.com/nsidc/)](https://qgreenland.org/sites/default/files/styles/medium/public/2023-08/Matt_Fisher_v2_0.png?itok=xLmAWIfs)
:::

::: {.column width="20%"}
![Trey Stafford^1,2^ - [Software Developer](https://github.com/nsidc/)](https://qgreenland.org/sites/default/files/styles/medium/public/2023-08/TreyStafford_0.jpeg?itok=tU4MgABx)
:::

::: {.column width="20%"}
![Alyse Thurber^2^ - [Education and Outreach](https://cires.colorado.edu/outreach/)](https://qgreenland.org/sites/default/files/styles/medium/public/2023-08/IMG_8099_1.jpeg?itok=vZDLKFqu)
:::

::: {.column width="20%"}
![Twila Moon^1,2^ - [Researcher](https://nsidc.org/about/about-nsidc/what-we-do/our-people/twila_moon)](https://qgreenland.org/sites/default/files/styles/medium/public/2023-08/TwilaMoon_0.jpeg?itok=TqiU0RYQ)
:::

::: {.column width="20%"}
![Tasha Snow^3^ - [Researcher](https://geophysics.mines.edu/project/tasha-snow/)](https://i0.wp.com/geophysics.mines.edu/wp-content/uploads/sites/30/2021/03/T_Snow_2020.jpg?resize=300%2C300&ssl=1)
:::

::::::

<!-- NOTE: Normal footnotes won't work here.
     https://github.com/quarto-dev/quarto-cli/issues/5440 --->

1: [National Snow and Ice Data Center (NSIDC)](https://nsidc.org)

2: [Cooperative Institute for Research in Environmental Sciences
(CIRES)](https://cires.colorado.edu)

3: [Colorado School of Mines](https://www.mines.edu/)


:::{.notes}
_TODO_: What degree of introduction should I provide? How much time to spend?

There will be a QR code at the final slide linking to the webpage for this presentation
where you can follow links!
:::


## QGreenland

What is QGreenland?

<https://qgreenland.org>

:::{.notes}
_TODO: Copy from a previous AGU presentation. Emphasize that community education and
outreach, and therefore workshops, are important parts of our activities._

_TODO: Talk about how we're going in to this with little experience?_

_TODO: Does CryoCloud belong here to? Or is it OK to get to it later?_
:::


# A community problem

Technical training is hard!

:::{.notes}
Planning and administering technical training is hard.

_TODO: Why? All the things..._

In this talk, we're going to focus on variance in user systems as a common distraction
from learning.
:::


## Variance in user systems

An added challenge that distracts from learning.

* Hardware, operating system, and user comfort level

* User configuration
    * Installed programming languages & versions
    * Dependency managers & installed dependency locations

:::{.notes}
_TODO: Step through bullets?_

Hardware, OS: I'm only comfortable with one operating system myself.
:::


## Accessibility

Lack of accessibility can be a distraction[^accessibility-citation].

Hardware and operating systems are a financial barrier to learning!

Mention UDL guidelines[^udl-citation]?

> UDL places responsibility for accessibility on the course designer
> rather than on the learner[^accessibility-responsibility-udl-citation]

[^accessibility-citation]: TODO
[^udl-citation]: <https://udlguidelines.cast.org/>{target="_blank"}
[^accessibility-responsibility-udl-citation]: [Carpentries Instructor Training](https://carpentries.github.io/instructor-training/09-eia.html#universal-design-in-learning-udl){target="_blank"}

:::{.notes}
_TODO: Is this the right place to talk about accessibility? Feels like no_

Hardware is expensive, and operating systems are expensive.

Not everyone has the time to set up their user configuration for a workshop.

Accessibility isn't just about finances; it also means involving people
with disabilities in decision-making. We surveyed our attendees to accommodate
disabilities, but we did not involve people with disabilities in our decision-making.
Important to point out?
:::


## Distractions: :thumbsdown:

:thumbsdown: Distractions contribute to learners' cognitive load and reduce learning
effectiveness[^distractions-citation].

:thumbsdown: Distractions consume teaching time.

:thumbsdown: Distractions consume planning time.

[^distractions-citation]: TODO

:::{.notes}
_TODO: Make text on slide more succinct, move wordy stuff into notes_

Planning: How many helpers do we need? What prep-work do we need participants to do
(installing software, etc.)? Do we need loaner hardware? This time could be better spent
on curriculum.
:::


# QGreenland workshop

:::{.notes}
_TODO: Speaker notes_
:::


## QGreenland workshop

Open source!

<https://qgreenland-workshop-2023-researcher.github.io/>


### Objectives

:satellite: Run a virtual workshop

:unicorn: Minimize or eliminate distractions from participants' unique systems

:::{.notes}
_TODO: Speaker notes_

_TODO: Where to touch on Internet access as a barrier? Here, under "virtual workshop"?
Or next slide? Or both? Set up the requirement here, and then go in to the concern on
the next slide?_
:::


## QGreenland workshop

Open source!

<https://qgreenland-workshop-2023-researcher.github.io/>


### Outcomes

:student: 25 learners

:globe_with_meridians: _TODO: List of countries_

:woman_scientist: Early- and late-career researchers

_TODO: Jupyter blog post_

_TODO: More_



:::{.notes}
Our workshop was able to serve 25 international learners, including `{list of
countries}`, from career levels `{career level range}`, while limiting technical
prerequisites to Internet access and a browser.

_TODO: Better term than late-career?_

_TODO: Talk about cost here?_

Internet access is no small barrier to participation, but enabled international
participation without requiring travel, which we felt was important.
:::


## How we got there

![CryoCloud logo](https://book.cryointhecloud.com/_static/logo.png)

*CryoCloud _JupyterHub_ to the rescue!*

:::{.notes}
Colleagues with the _CryoCloud_ project run a _JupyterHub_ which aims to transition the
NASA research community to cloud and open source work patterns, and this aligns well
with our workshop goals.
:::


## _JupyterHub?_

:memo: _Jupyter Notebook_:
Literate programming file format.

:desktop_computer: _JupyterLab_:
A comprehensive browser-based environment for using _Jupyter Notebooks_.

:partly_sunny: **_JupyterHub_**:
_JupyterLab_ in the cloud, **on demand**.

:::{.notes}
:memo: _Jupyter Notebook_:
Literate programming file format. May be most familiar of these three. Can be edited
and viewed with various tools including the official Jupyter "notebook server" (`jupyter
notebook`), VSCode, PyCharm, and Google Colab.

_TODO: Define literate programming_

:desktop_computer: _JupyterLab_:
A comprehensive browser-based environment for using _Jupyter Notebooks_, including tools
you're used to in your local computing environment, such as file browser, terminal,
package managers, image previewers, and tabular data editors.

:partly_sunny: **_JupyterHub_**:
_JupyterLab_ deployed in the cloud so users can create a _JupyterLab_ on demand with no
prior knowledge.
:::


## A mutually-beneficial arrangement

#### :sparkles: Contributed new functionality to the _CryoCloud_ hub

> :::{.nonincremental}
> * **Open-source desktop GIS in the cloud!**
> * **11** Pull Requests merged; **9** issues opened
> :::


#### :bulb: Inspired other institutions to replicate our advancements

> :::{.nonincremental}
> * [_Jupyter Blog_ post](https://blog.jupyter.org/desktop-gis-software-in-the-cloud-with-jupyterhub-ddced297019a)
> * _TODO: QR_
> :::


#### _TODO: Fragments / incremental display on these slides?_

:::{.notes}
CryoCloud & QGreenland both benefitted from this arrangement.

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

* CryoCloud is operated by 2i2c, a fiscally sponsored non-profit, that operates a large
  number of JupyterHubs.
    * We published a
      [Jupyter Blog post](https://blog.jupyter.org/desktop-gis-software-in-the-cloud-with-jupyterhub-ddced297019a)
      describing our advancements.
    * As a result, 2i2c reported increased requests from their clients for the
      functionality we demonstrated in our blog post.
    * More _JupyterHubs_ adopted QGIS desktop functionality.
:::


## A mutually-beneficial arrangement

#### :chart_with_upwards_trend: Supported _CryoCloud_ community growth & evaluation of impact

> :::{.nonincremental}
> * Our workshop learners joined the _CryoCloud_ community!
> :::


#### :money_with_wings: Reduced costs by collaborating!

> :thumbsdown: ~~2-4 weeks + ~$4500 to set up~~
>
> :thumbsup: 2-3 days to setup + ~$75 cloud costs


:::{.notes}
* Running workshops helps expand the CryoCloud community
* Running workshops helps the CryoCloud team gather data (e.g. surveys) to measure their
  impact.

* Reduced costs benefit our workshop participants by allowing us to focus more on
  teaching
    * Without: $4500 + 2-4 weeks setup
    * With: $0 + 2-3 days setup + $75 cloud operating expenses
:::


# Desktop GIS in the cloud

:::{.notes}
_TODO: Speaker notes_
:::


## Desktop GIS in the cloud

Our Jupyter Blog post[^jupyter-blog] provides the most detail!

_TODO: Short demo here; image(s)? Animation?_

[^jupyter-blog]: https://blog.jupyter.org/desktop-gis-software-in-the-cloud-with-jupyterhub-ddced297019a

:::{.notes}
This talk is more focused on outcomes and how you can reproduce our success; if your
want the most detail on this subject, check out our post!

_TODO: What level of detail/how much time to spend on this?_
:::


# Replication

:::{.notes}
_TODO: Speaker notes_
:::


## Cost is still high

* Collaboration with an existing community was key!
    * We were lucky to have good connections, but...
* You can do that too.
    * _TODO: Link to 2i2c hub listing_
    * _TODO: Other resources to find computing communities_
* _TODO: Suggest operating a hub? How to avoid duplicating work?_

:::{.notes}
As you saw in the previous slide, setting up a cloud _JupyterHub_ with all the features
you need for your workshop can be expensive. Because of this, collaborating with an
existing community was essential if we wanted to pursue this strategy.

We were fortunate to have established connections with _CryoCloud_ to help us get
started, but I think you can "cold call" communities; they are eager for collaborators.

If you're looking to run a workshop, consider an existing community to collaborate with.

If you're looking to fund these type of activities, consider doing it through operating
a _JupyterHub_ community!
:::


# Thank you

:bow:


## Acknowledgements

_TODO_


## :question: Q&A

_TODO: QR code for "references" page of this site_


### Contact

Me: `mfisher87@gmail.com`

QGreenland Team: `qgreenland.info@gmail.com`


# Additional slides

:tada:


## TODO

- [ ] Better structure for intro. "In this presentation, we will talk about ...,
  outcomes, and how you can take advantage of what we learned."
- [ ] Better narrative structure for the workshop. We needed X, Y, Z to do our workshop
  in the cloud. QGIS and QGreenland were of course the most important requirements.
- [ ] Point to CryoCloud's & Openscapes' sessions/tutorials.
    * Twila: Last slide, or slide before conclusion. QR code? Also use the identifier
      for the presentation. Poster number, title.
- [ ] "Outcome" bigger picture.
    * Twila: Highlight how other people can benefit from what we learned.
- [ ] Consider where to use incremental display on slides. E.g. JupyterHub intro slide?
  Mutual benefit slides?
- [ ] Link to our "outcomes" page. "References" page. Other "lessons learned"
  documents/pages?
- [ ] Acknowledgements
- [ ] Logos
