
class: center, middle

# Reproducibility and Open Science

<small>Follow along at: <a href="XXX">XXX</small>

---

<img src="images/escience.png" width=350>

### UW eScience Institute

Major funding from:

 - Gordon and Betty  Moore  Foundation,<br>
 - Alfred P. Sloan Foundation, <br>
 - Washington Research Foundation, <br>
 - National Science Foundation

#### Data Science Environments project with Berkeley and NYU

Reproducibility and Open Science Working Group:

 - https://reproduciblescience.org/

 - Mailing list: reproducible@uw.edu

---

layout: true

<div style="position: absolute; left: 650px; top: 370px;">
<image src="images/escience-network.png" width=500px style="opacity:0.4;filter:alpha(opacity=40);"> </div>

---

# What does Reproducible Research mean?

### .blue[Ability to determine exactly how scientific results were obtained.]

 - Basis of scientific method.

 - Required for confidently building on past results.

 - Critical for accountability in engineering analysis / decision making.

---

template: meaning1

### .red[Standards and best practices in computational/data science are not yet well codified.]

 - Experimental science: Lab notebooks, methodology section of publications, etc.

 - Mathematics: Proofs are required in publications.

---

name: crotty1

Quote from .blue[Reproducible Research: A Cautionary Tale]

By David Crotty, March 26, 2014 on the [scholarly kitchen blog](??)


.red["If your experiment consists of running numerical data through an algorithm,
then releasing your data and your code allows others to quickly verify that
you’ve done what you’ve said you’ve done.]
But when it comes to other types of research,
wet bench experiments or observational
work for example, reproduction is not quite so simple."

---

template: crotty1

#### .red[If only it were so easy in computational/data science!]
---

## Outline

 - .blue[Goal:] Stimulate discussion and share ideas  

     - Types of reproducibility
     - Tools for reproducibility

 - .blue[Data:] archiving, curation, sharing
 - .blue[Code:] scripting, versioning, collaborating, sharing

---

name: private1

## Private reproducibility...

Use scripts, not GUIs, for data analysis and visualization.

Use version control / provenance tracking tools.

Archive code and data used for published results.

.blue[Why?]

 - Ability to check results in prior publication,

 - Ability to build on your own past research of your own
   (or students / collaborators).

 -  Easily modify tables/figures to satisfy referees, etc.

---

template: private1

#### .red[Auditable Research:]
Even if code and data are not shared, there should be a
permanent record that can be checked.

.blue[Analogous to lab notebooks.]

---

### Version control does *not* mean...

<img src="images/PhDcomics-final.png" width=350>

http://www.phdcomics.com/comics/archive.php?comicid=1531

---

## Public Reproducibility...

Allowing others to reproduce your results.

(Readers, referees, researchers down the hall...)


.blue[Why?]

 -  Verifying scientific integrity of results.

 -  Aids in understanding ideas, implementing methods

 -  Increases impact of work.

---

## Data Curation

### [Ten Simple Rules for the Care and Feeding of Scientific Data](http://dx.doi.org/10.1371/journal.pcbi.1003542)

by Alyssa Goodman, Alberto Pepe , Alexander W. Blocker, Christine L.
Borgman, Kyle Cranmer, Merce Crosas, Rosanne Di Stefano, Yolanda Gil, Paul
Groth, Margaret Hedstrom, David W. Hogg, Vinay Kashyap, Ashish Mahabal,
Aneta Siemiginowska, Aleksandra Slavkovic,

PLOS Computational Biology 10(2014), e1003542.
http://dx.doi.org/10.1371/journal.pcbi.1003542

---

## Data Curation

### [Ten Simple Rules for the Care and Feeding of Scientific Data](http://dx.doi.org/10.1371/journal.pcbi.1003542)

 - Rule 2.  Share Your Data Online, with a Permanent Identifier

 - Rule 4. Publish Workflow as Context

 - Rule 5. Link Your Data to Your Publications as Often as Possible

 - Rule 6. Publish Your Code (Even the Small Bits)

 - Rule 7. State How You Want to Get Credit

 - Rule 8. Foster and Use Data Repositories


---

## Data Repositories

 -  .blue[DesignSafe:] https://www.designsafe-ci.org/ <br>

 -  .blue[Community Surface Dynamics Modeling System]<br>
    (CSDMS): http://csdms.colorado.edu Data and model repositories,<br>
    Web interface to some models

 -  .blue[Open Science Framework:] https://osf.io/ <br>
    Ex: April 12 talk by Kara Woo in
    eScience Reproducibility and Open Science Seminar

 - .blue[UW ResearchWorks:] https://researchworks.lib.washington.edu/ <br>
   Ex: Ocosta School tsunami study,
   https://digital.lib.washington.edu/researchworks/handle/1773/24054

 - .blue[figshare:] https://figshare.com/ <br>
   Ex: Search for tsunami

 - .blue[Zenodo:] https://zenodo.org/ <br>
   Ex: Data and code for journal article on PTHA, <br>
   http://dx.doi.org/10.5281/zenodo.12406

---

## Some Git references

 -  [List of 10 recommended tutorials](http://sixrevisions.com/resources/git-tutorials-beginners/)

 -  https://help.github.com/categories/bootcamp/

 -  http://git-scm.com/book/en/Getting-Started-Git-Basics

 -  [Github online tutorial](http://try.github.com/)


### More general resources, including Git:

 -  [Software Carpentry](http://software-carpentry.org/)

 -  [Code Academy](https://www.codecademy.com/)
