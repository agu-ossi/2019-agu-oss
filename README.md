# Best Practices for Developing and Sustaining Your Open-Source Research Software

Material for the workshop at the AGU 2019 Fall Meeting.

**Conveners:**
Rene Gassmoeller,
Lindsey Justine Heagy,
Lion Krischer,
Leonardo Uieda,
Christopher Bane Sullivan

|    |Info|
|---:|:---|
|Location|Grand Hyatt / Room: Conference Theatre (Theatre level)|
|Time|Wednesday, 11 December 2019 / 08:00 - 12:20|
|Workshop ID|SCIWS5|
|Shared notes| [Google Docs](https://docs.google.com/document/d/1aeyE4ojd16W5nkIb25Nzvzl86aV0JWNHcuNh0BzVC_Y/edit?usp=sharing)|
|Slides| [Slides](https://docs.google.com/presentation/d/1Ar6ymeBkP2BJ41xEt2H5XRXBh0vjn2oQJrmY_1vXExg/edit#slide=id.p)|
|Feedback| [Mentimeter](https://www.menti.com/2jc4ixza4o)

## Description

Modern research software is the basis of scientific progress in geophysics by supporting data collection, data analysis, and numerical simulation. These codes span the range from small one-off scripts developed by individual researchers up to large packages with thousands of users. While there is increasing awareness about best programming practices, scientists are rarely prepared to scale their codes into team projects developed by  larger communities. However, growing a sustainable software project and the community of practice that surrounds it is a prerequisite to make scientific software development more efficient and research more reproducible.

The open-source community has established modern best-practices for developing reliable software, publishing that software, forming communities around the code, and finding sustainable ways to maintain them over time. This hands-on half-day workshop is aimed at scientists currently developing their own software of any size. The participants will apply a workflow for developing and managing open-source research codes following best-practices. We will discuss licensing and privacy considerations for open-source projects in a scientific context, briefly review version control with git and hosting projects online, and teach how to automatically test and efficiently document code. Furthermore, we will discuss how to grow projects and manage communities around it. The course material is independent of programming language or scientific discipline. By the end of this workshop participants will be able to apply the gained knowledge directly to their own projects and create more sustainable research software. 

## Learning Objectives

Our aim with this workshop is for participants to:

1. Learn about modern best-practices for developing, testing, documenting, and publishing research software that promote accessibility, reusability, and reproducibility.
2. Gain hands-on experience with open-source software development tools available to researchers including Jupyter (for sharing, http://jupyter.org/), git (versioning, https://git-scm.com/), GitHub (collaboration, https://github.com/), ReadTheDocs (documentation, https://readthedocs.org/), and Travis CI (testing, https://travis-ci.org/).
3. Learn basic concepts of software project management like the life cycle of scientific software, defining a target audience, developing a project mission and vision, building a welcoming community, and approaching scientists uncomfortable with sharing their research software.

## Tentative Agenda

During the workshop, we'll introduce these topics by working through an example.
The goal is to convert a notebook (or script) that does some data analysis into a 
Python library that is tested, documented, and can be reused. The final version 
of the library and a history of each step in the conversion process can be found at
https://github.com/opengeophysics/2018-agu-oss-example-repo

| Duration (min) | Topic | Tools |
|:--------------:|:------|:------|
| 15 | Motivations for community research software and its technical and social challenges. Software as a project, not a collection of files| |
| 15 | Discussion with presenters and participants about prior experiences with technical and social challenges | |
| 15 | Define target audience, mission, vision, and life cycle of the participant’s software projects | |
| 5 | Break | |
| 20 | Introduce the example we will work through and provide the Jupyter notebook | |
| 20 | Practical review of version control with git and setting up an online repository on GitHub with the provided example project (a small python library, participants are encouraged to instead use their own research code in whichever language) | |
| 15 | Managing communication and building a welcoming community | |
| 15 | Including a Code of Conduct and Contributing Guidelines | [Contributor Covenant](https://www.contributor-covenant.org/) |
| 15 | Coffee Break |  |
| 15 | Introduction to open-source and how to choose an open-source license | [Choose a license](https://choosealicense.com/), [OSI Licenses](https://opensource.org/licenses) |
| 30 | Why and how to write tests | |
| 15 | How to set up continuous integration services to automate tests | |
| 5 | Break | |
| 15 | Importance of documentation and naming conventions. How to write and publish documentation. | [ReadTheDocs](http://readthedocs.org) |
| 15 | Q&A this time block will be distributed over sessions as necessary | |
| 15 | Overview on further resources available within the open source community (best-practice guides, developer communities, software organizations) | |

## *Before* the workshop

If you would like to follow along interactively during the course, please do the following before the course starts:

- Download and install [Anaconda](https://www.anaconda.com/download/). Use the latest version of Python 3 and be sure to check the box that says "Add Anaconda to my PATH environment variable" if on Windows.

![AnacondaPath](http://toolkit.geosci.xyz/_images/AnacondaPath.png)
- Download and install git. The easiest way to do this is to follow the instructions on the [Software Carpentry website](https://carpentries.github.io/workshop-template/#git).
- If you do not already have one, set up a free [GitHub account](https://github.com/).

## *After* the workshop

Since the time allocated for the workshop does not allow to cover scientific
software development in its entirety, we provide links to some alternatives and
guides to extend and deepen some of the taught concepts.

### Further reading

- **Version control with Git**
  - [Git - the simple guide](http://rogerdudler.github.io/git-guide/)
  - [Git Cheat Sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
- **Software packing**
  - [The Hitchhiker's Guide to packaging](https://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/)
  
### Alternatives to the tools presented

- **Version control**
  - [GitLab](https://www.gitlab.com): Version control for with private repositories and for your own server

- **Continous Integration**
  - [CircleCI](https://circleci.com): Alternative to Travis (https://circleci.com/circleci-versus-travisci/).
  - [Jenkins](https://github.com/jenkinsci/jenkins): Continuous integration on your own server. Might come in handy, for computationally more demanding software tests.

- **Documentation**
  - [MkDocs](https://www.mkdocs.org): Fast and simple project documentation using Markdown.

## Recording of AGU 2018 (slightly different focus)

[![recording-AGU](https://img.youtube.com/vi/Ck3f8Dbk98U/0.jpg)](https://youtu.be/Ck3f8Dbk98U)

Workshop - AGU 2019

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
