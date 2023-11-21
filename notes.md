---
title: "Planning notes"
---

## TODO / raw thoughts

* Use _POP_ method? Appropriate?


## Intro

Lay out the problem...

* Planning & administering technical training is hard

* Variance in user systems can make it harder!
    * Hardware, operating system, and user comfort level
        * I'm personally comfortable with only one very specific operating system
    * User configuration: 
        * Installed programming languages & versions
        * Dependency managers & installed dependency locations
    * Inclusion and accessibility are important for learning; lack of these is a
      distraction or barrier to participation!
        * Accessibility: Hardware is expensive, and operating systems are expensive.
          Not everyone has the time to set up their user configuration for a workshop.
            * [Accommodation vs Universal design](https://carpentries.github.io/instructor-training/09-eia.html#from-accommodation-to-universal-design)
            * [Universal Design in Learning (UDL)](https://carpentries.github.io/instructor-training/09-eia.html#universal-design-in-learning-udl)
                * > UDL places responsibility for accessibility on the course designer
                  > rather than on the learner
                * UDL is more about pedagogy than technology, probably a bad choice of
                  supporting evidence.
            * Accessibility isn't just about finances; it also means involving people
              with disabilities in decision-making. We did not do this, I just thought
              it is important to point out.
        * Inclusion: It doesn't matter what your operating system or hardware
          preferences are. Your user configuration can be totally unique, and as long as
          you have a browser, you can participate.

* Issues caused by system variance are distractions
    * Distractions contribute to cognitive load and reduce learning effectiveness
        * TODO: Cite.
    * Distractions take time to resolve at run time.
    * Distractions take time to plan for: how many helpers do we need?

* *Purpose:* Run a virtual QGreenland workshop for researchers that eliminates
  distractions from system variance

* *Outcome:* Our workshop was able to serve 25 international learners, including
  `{list of countries}`, from career levels `{career level range}`, while limiting
  technical prerequisites to Internet access and a browser.
    * Internet access is no small barrier to participation, but enabled international
      participation without requiring travel, which we felt was important.


## Our solution *(process)*

* *JupyterHub* to the rescue! Colleagues with the _CryoCloud_ project run a JupyterHub
  which aims to transition the NASA research community to cloud and open source work
  patterns, and this aligns well with our workshop goals.

* Explained in layers
    * Jupyter Notebooks: Literate programming file format. Can be edited and viewed with
      various tools.
    * Jupyter Lab: A comprehensive browser-based environment for using Jupyter
      Notebooks, with everything else (terminal, image previewer, tabular data editor,
      ...) you might need.
    * JupyterHub: JupyterLab deployed in the cloud

* Working with an existing commmunity benefitted both:
    * Running workshops helps the CryoCloud team gather data
    * Running workshops helps expand CryoCloud's capabilities (we contributed `{N}` PRs
      to the open-source project)
    * Running workshops helps expand the CryoCloud community
    * Reduced costs benefit our workshop participants by allowing us to focus more on
      teaching
        * Without: $4500 + 2-4 weeks setup
        * With: $0 + 2-3 days setup + $75 cloud operating expenses

* _TODO:_ Point to CryoCloud's & Openscapes' sessions/tutorials.
* _TODO:_ "Sounds like you knew the right people to get this opportunity to use a
  JupyterHub." Yes! There are multiple communities running hubs, however, and I think
  many are looking to similarly exercise their capabilities. Look at the list of hubs
  run by 2i2c for opportunities to collaborate.
