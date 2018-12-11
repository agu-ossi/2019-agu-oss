# Best practices for modern open-source research codes
Material for the workshop at the AGU 2018 Fall Meeting.

**Conveners:**
Leonardo Uieda,
Lindsey Heagy,
Lion Krischer,
Florian M. Wagner

|    |Info|
|---:|:---|
|Location|Grand Hyatt / Room: Penn Quarter|
|Time|Wednesday, 12 December 2018 / 13:40 - 18:00|
|Workshop ID|WS24|

## Description

Modern science increasingly relies on code, ranging from small scripts to workflows with
many interacting parts. Reproducibility and extension of studies employing these codes
require that they are accessible. The open-source community has established modern
best-practices for making software available, usable, and maintainable. In this
workshop, we will demonstrate a workflow for publishing research code following these
best-practices. We will cover open-source licenses, version control, automated testing,
documentation, and continuous integration. The workshop will be hands-on: participants
will work to set up a project using sample code provided by the instructors. By the end,
participants will have the knowledge needed to continue learning independently and apply
these practices to their own research code. These resources can be applied to any
programming language or scientific discipline.


## Learning Objectives

Our aim with this workshop is for participants to:

1. Gain awareness of tools available to researchers within the open-source ecosystem
   including [Jupyter](http://jupyter.org/), [git](https://git-scm.com/), 
   [ReadTheDocs](http://readthedocs.org), continuous integration services (for testing), etc
2. Learn modern best-practices for structuring a repository for research software that
   promotes accessibility, reusability, and reproducibility
3. Learn about the tools available for testing, publishing documentation, and versioning
   that can be immediately applied to their own codes


## Tentative Agenda

During the workshop, we'll introduce these topics by working through an example.
The goal is convert a notebook (or script) that does some data analysis into a 
Python library that is tested, documented, and can be reused. The final version 
of the library and a history of each step in the coversion process can be found at
https://github.com/opengeophysics/2018-agu-oss-example-repo

| Duration (min) | Topic | Tools |
|:--------------:|:------|:------|
| 15 | Introduce the motivations and problems that the workshop will address | TODO: link notebook we will use |
| 30 | Describe the example we will working through and provide an overview of the Jupyter notebook | [Jupyter notebook](https://jupyter-notebook.readthedocs.io/en/stable/) |
| 45 | Overview of version control with git and setting up an online repository | [GitHub](https://github.com/) |
| 45 | How to setup a small Python library (though the example is in python, participants are encouraged to use their own research code in whichever language they prefer) | [Scientific Python Cookiecutter](https://nsls-ii.github.io/scientific-python-cookiecutter/index.html) |
| 15 | Discussion on choosing an open-source license | [Choose a license](https://choosealicense.com/), [OSI Licenses](https://opensource.org/licenses) |
| 15 | Including a Code of Conduct and Contributing Guidelines | [Contributor Covenant](https://www.contributor-covenant.org/) |
| 30 | How to write automated tests in Python | [Pytest](https://docs.pytest.org/en/latest/contents.html) |
| 30 | Setup continuous integration services to check that the code is tested on every update | [TravisCI](https://docs.travis-ci.com/user/languages/python/) |
| 30 | Write and publish documentation on ReadTheDocs, a free hosting service for open source software projects | [ReadTheDocs](http://readthedocs.org) |
| 15 | Overview of other resources available within the open source community | |


## Before you come

If you would like to follow along interactively during the course, please do the following before the course starts:

- Download and install [Anaconda](https://www.anaconda.com/download/). Use the latest version of Python 3 and be sure to check the box that says "Add Anaconda to my PATH environment variable" if on Windows.
![AnacondaPath](http://toolkit.geosci.xyz/_images/AnacondaPath.png)
- Download and install git. The easiest way to do this is to follow the instructions on the [Software Carpentry website](https://carpentries.github.io/workshop-template/#git).
- If you do not already have one, set up a free [GitHub account](https://github.com/).

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
