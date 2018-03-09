---
layout: post
title: Summer Internships 2018
subheading: 
full_footer: false
header_content: false
---

## Summer Internships 2018

The Whole Tale is inviting Internship applications for 2018!

The act of sharing scientific knowledge is rapidly evolving away from
traditional articles and presentations to the delivery of executable objects
that integrate the data and computational details (e.g., scripts and workflows)
upon which the findings rely. This envisioned coupling of data and process is
essential to advancing science. The WholeTale project aims to connect
computational, data-intensive research efforts with the larger research
process - transforming the knowledge discovery and dissemination process into
one where data products are united with research articles to create "living
publications" or tales.

WholeTale: _Merging Science and Cyberinfrastructure Pathways_ is an NSF-funded
collaboration led by the University of Illinois, Urbana-Champaign, in
partnership with the University of Chicago, the University of Texas at Austin,
the University of California, Santa Barbara, and the University of Notre Dame.
We are pleased to announce the availability of summer research internships for
undergraduates, graduate students and recent postgraduates!


### Schedule

  * **March 8** - Application period opens
  * **March 30** - Deadline for receipt of applications
  * **Apr 16** - Notification of acceptance 
  * **May 21 (~June 4)** - Program begins
  * **June 22 (~July 6)** - Midterm evaluations
  * **July 27 (~Aug 6)** - Program concludes

The exact start date will be determined by the mentor in coordination with the
student to  accommodate academic calendars.

### Program Information

Interns undertake a 10-week program of work centered around one of the projects
listed below. Each intern will be paired with a primary mentor, and possibly
with additional mentors and team members. Interns need not necessarily be at
the same location or institution as any of their mentors. Interns and mentors
are expected to have a virtual or face-to-face meeting at the beginning of the
internship, and maintain regular communication throughout the program. Interns
will be asked to share their work through an open source repository and
communicate weekly updates via a mailing list.  

### Project Descriptions

The proposed internship projects cover a range of topic areas and vary in the
extent and type of prior background required. We expect to fund at least three
of the projects described below; the final determination will also take into
account applicants' interests and expertise.

 1. [The Reproducible Data Wrangler](/internship_projects/2018-reproducible-data-wrangler.html)
 1. [Benchmarking Machine Learning Methods in Materials Science](/internship_projects/2018-benchmarking-machine-learning-matsci.html)
 1. [Analyzing Bias in Machine Learning Research](/internship_projects/2018-analzying-bias.html)
 1. [Reproducibility Study in Biodiversity Informatics](/internship_projects/2018-biodiversity-informatics.html)

### Eligibility

The program is open to undergraduate students, graduate students, and
postgraduates who have received their degree within the past five years. There
are no restrictions on academic backgrounds or field of study (see project
descriptions for prerequisites and desirable skills). **Interns must be at least
18 years of age by the program start date, must be currently enrolled or
employed at a U.S. university or other research institution and must currently
reside in, and be eligible to work in, the United States.** Interns are expected
to be available approximately 40 hours/week during the internship period with
significant availability during normal business hours. _The following student
populations are particularly encouraged to apply:_

 * Students from four-year colleges without significant graduate programs.
 * Students from schools or consortia that have historically served large
   minority student populations. 
 * US veterans pursuing STEM degrees.


### Financial Support

Interns will receive a stipend of $5,000 for participation, paid in bi-weekly
installments, administered by the University of Illinois, Urbana-Champaign.
Participation in the program after the mid-term is contingent on satisfactory
performance. For students who are not US citizens or permanent residents,
complete visa information will be required, and it may be necessary for the
funds to be paid through the student's university or research institution.
In such cases, the student will need to provide the necessary contact
information for their organization.

### To Apply



Complete the [online application](https://goo.gl/forms/J3NJipyQDSk9vSBR2) which
also asks you to provide the following information: 

 * a **cover letter** identifying the project(s) you are interested in, the
contributions you expect to make to the project, relevant background, value of
the internship program to your educational and career objectives, and
disclosure of any factors that would affect your ability to participate (e.g.,
other summer employment/commitments, university schedules, etc. 
 * a **resume** that includes educational history, current position, any publications
or honors, and full contact information (including phone number, email address,
and mailing address)

We also encourage you to submit an optional letter of reference from a
professor, supervisor, or other mentor. Please ask your letter-writer to email
the reference letter directly to

 * `wholetale-interns-2018@googlegroups.com` (cc to `ludaesch@illinois.edu`). 
   The Subject should be:  `Summer Internship 2018: <Applicant's Name>`

Applications must be completed and submitted **no later than March 30, 2018**.

### Funding Acknowledgment

Summer Internships are supported by National Science Foundation Award [1541450](
https://www.nsf.gov/awardsearch/showAward?AWD_ID=1541450).

### For more information...

If you have questions or problems about the application process or internship
program in general, please e-mail 
[wholetale-interns-2018@googlegroups.com](wholetale-interns-2018@googlegroups.com).



#### Project #1: Online Materials Science Modeling and Analytics

**Primary Mentor:** Kyle Chard (University of Chicago)

**Additional Mentor:** Ben Blaiszik/Logan Ward (University of Chicago / Argonne National Laboratory)

**Necessary Prerequisites:**

 * Programming experience (Ideally with Python)

**Desirable Skills / Qualifications:**

 * Experience with data analysis toolkits (e.g., Python Pandas, SciPy, R)
 * Some experience with statistical modelling and/or machine learning
 * Basic knowledge of materials science



**Expected Outcomes:**

 * Jupyter notebooks that reproduce published results using data contained in
   MDF
 * Published models, notebooks, and derived data
 * New models created from mixing several MDF datasets
 * Conversion and ingestion of existing materials datasets into MDF

**Project Description:**

There is a vast amount of materials science data (computational or
experimental) available in repositories such as the Materials Data Facility
(MDF), Materials Project, AFLOWLib, Citrination, and NOMAD, among others. While
much of these data has been analyzed in isolation, little have been used
collectively to develop new models and drive new discovery. In this project,
the student will develop methods for accessing data contained within the MDF
and other repositories directly from within Jupyter notebooks. Such a tool will
enable better reproducibility and easier re-use for the increasingly common
machine learning models created from materials data.

After developing a model to access data, the student will then work to recreate
several machine learning methods from the literature to explore these datasets,
and then branch to applying these tools to new data. For example, the student
will implement models that determine whether metallic alloys can be formed as
glasses (see figure below). Having implemented these models and reproduced
published results, the student will apply the underlying model to a wider range
of data contained in the MDF. At this point, there are several possible routes
for continuing the project, including benchmarking several machine learning
methods using the same datasets or exploring how to best mix different data
sources to train a single model. As a result of this work, the student will
publish the resulting notebooks, models, and derived data in the MDF such that
others can discover, reproduce, and build upon their work.

![]({{"assets/images/internships/wt-proj-1_figure.png" | absolute_url}})

Ability of different alloy compositions to form a metallic glass as (a)
measured experimentally and (b) predicted with a machine learning model.
Without being provided any data from the experimental data shown in (a), the
model correctly identifies the locations of the two glass-forming regions in
the Al-Ni-Zr alloy system. Ref: Ward et al. npj Compt. Mater.</span> (2016),
16028.

#### Project #2: Telling the Whole Tale Behind a Paleoclimate Reconstruction based on PaleoCAR

**Primary Mentor:** Timothy McPhillips (UIUC: University of Illinois,
Urbana-Champaign)

**Additional Mentor:** Kyle Bocinsky (Washington State University), Bertram Ludaescher (UIUC)

**Necessary Prerequisites:**

 * R programming experience
 * Interest in developing tools and methods for empowering researchers in the
   data-intensive natural and social sciences

**Desirable Skills / Qualifications:**

 * Competency developing and running software, managing data, and automating
   workflows via scripts on multiple computing platforms (ideally including
   MacOS, Linux, and Windows; cloud-based computing environments in addition
   would be a plus).
 * Modern web development skills for rapid prototyping, e.g., using a
   combination of Javascript-based UIs and REST-based backend services.
 * Experience with one or more of the following:
   * conceptual- and data modeling
   * ontologies and logic-based knowledge representation 
   * database queries and views
   * logic programming such as with Datalog or Prolog
   * electronic scientific notebooks
   * scientific workflow management systems

**Expected Outcomes:**

 * Interactive browser-based environment for browsing, querying, and
   visualizing the comprehensive history of a single PaleoCAR [BK14]
   study.
 * Based on this concrete example, a conceptual template for representing the
   full provenance of any research study carried out using WT tools and
   environments.

**Project Description:**

The goal of this project is to create an integrated representation of all
dimensions of the provenance of the results of particular scientific study. The
study will employ PaleoCAR [BK14] to reconstruct environmental conditions of a
particular paleoenvironment.

The elements of the resulting comprehensive provenance model of this PaleoCAR
study will include:  (1) graphical, queryable representations of each of the
computational workflows enacted as part of the research and corresponding to
the prospective provenance all data products generated during the study; (2)
the retrospective provenance of each such intermediate and final data product
complete with records of the specific program executions involved, the values
of program arguments applied, and--where possible--the values of key variables
within the programs themselves as exposed by YesWorkflow [YW];  (3) the
provenance of all data used by the study but obtained from sources outside the
study including public data repositories; (4) the intellectual and scholarly
lineage of the scientific, computational, and statistical methods employed in
the study; (5) the provenance and dependencies of all software programs,
libraries, and components used in the study; and (6) the network of connections
between the preceding 5 categories of provenance, e.g. the chains of citations
to scientific literature reporting the invention, evaluation, and application
of the methods and software components used in the study.

We expect that this project will yield insights into what new tools researchers
need, and what new capabilities must to be added to the tools and environments
they already use, if we are to make it easy for them to present their studies
in the context of the rich, integrated provenance this project will illustrate.

**References**:

 * [BK14] Bocinsky, R. K. and Kohler, T. A. (2014). [A 2,000-year
   reconstruction of the rain-fed maize agricultural niche in the US
   Southwest](http://www.nature.com/articles/ncomms6618). Nature
   Communications, 5:5618. doi:10.1038/ncomms6618. (see [Science Daily
   article](https://www.sciencedaily.com/releases/2014/12/141204074309.htm) for
   a quick intro)
 * [YW] YesWorkflow toolkit. [github.com/yesworkflow-org/yw-prototypes](https://github.com/yesworkflow-org/yw-prototypes)

#### Project #3: Understanding Requirements for Infrastructure to Promote Reproducible Research

**Primary Mentor:** Peter Darch (University of Illinois at Urbana-Champaign)

**Additional Mentor:** Victoria Stodden (University of Illinois at
Urbana-Champaign)

**Necessary Prerequisites:**

This project is suitable for students in, or graduates of, library and
information science degree programs.

**Desirable Skills / Qualifications:**

 * Academic courses about scientific information (such as data curation, or
   scientific communication practices)
 * Experience with working in scientific information management settings or
   scientific collaboration
 * Experience with conducting qualitative research (interviews, observation)
 * Experience with requirements analysis (particularly use case approaches) for
   software and systems engineering
 

**Expected Outcomes:**

 * Report on information practices and needs of a team of scientific researchers
 * Recommendations for improving information practices within this team
 * A series of use cases representing this team’s requirements for
   infrastructure to promote reproducible research.

**Project Description:**

The task of building infrastructure that supports and promotes reproducible
science involves addressing multiple challenges. One major challenge involves
understanding the existing practices and requirements of the domain researchers
for whom the infrastructure will be built. Developing this understanding is
critical for: identifying where infrastructure development is best targeted;
specifying what features should be incorporated into this infrastructure; and
ensuring that researchers are able to integrate this infrastructure easily into
their work practices.

This project will involve studying a team of researchers from one of the Whole
Tale Science Pathways domains (astronomy, archaeology, material science,
biology/genomics, social science, disaster resilience): the particular domain
will be selected to closely match with your own interests/background.

You will work with the research team to learn about their work and information
practices. These practices include: how they produce, manage, and use data and
software; whether and how they make their data and software accessible to
others; and their associated record-keeping practices. Your work will involve
interviewing team members about their practices, and observing them at
work.

After identifying the team’s existing information practices, you will explore
what infrastructure and practices could make this team’s work more
reproducible. In addition, you may also identify particular barriers and
challenges to introducing new infrastructure and practices into the work
practices of the team.

Based on your findings, you will formulate a series of use cases. These use
cases will represent your findings to software engineers who are building
infrastructure to promote reproducible research.

