---
title: Improving software quality in bioinformatics through teamwork
keywords:
- software quality
- bioinformatics
- teamwork
lang: en-US
date-meta: '2024-02-19'
author-meta:
- Katalin Ferenc
- Ieva Rauluseviciute
- Ladislav Hovan
- Vipin Kumar
- Marieke Kuijjer
- Anthony Mathelier
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Improving software quality in bioinformatics through teamwork" />
  <meta name="citation_title" content="Improving software quality in bioinformatics through teamwork" />
  <meta property="og:title" content="Improving software quality in bioinformatics through teamwork" />
  <meta property="twitter:title" content="Improving software quality in bioinformatics through teamwork" />
  <meta name="dc.date" content="2024-02-19" />
  <meta name="citation_publication_date" content="2024-02-19" />
  <meta property="article:published_time" content="2024-02-19" />
  <meta name="dc.modified" content="2024-02-19T18:54:53+00:00" />
  <meta property="article:modified_time" content="2024-02-19T18:54:53+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Katalin Ferenc" />
  <meta name="citation_author_institution" content="Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway" />
  <meta name="citation_author_orcid" content="0000-0002-3006-4297" />
  <meta name="citation_author" content="Ieva Rauluseviciute" />
  <meta name="citation_author_institution" content="Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway" />
  <meta name="citation_author_orcid" content="0000-0001-9253-8825" />
  <meta name="citation_author" content="Ladislav Hovan" />
  <meta name="citation_author_institution" content="Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway" />
  <meta name="citation_author_orcid" content="0000-0001-8847-9295" />
  <meta name="citation_author" content="Vipin Kumar" />
  <meta name="citation_author_institution" content="Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway" />
  <meta name="citation_author" content="Marieke Kuijjer" />
  <meta name="citation_author_institution" content="Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway" />
  <meta name="citation_author_orcid" content="0000-0001-6280-3130" />
  <meta name="citation_author" content="Anthony Mathelier" />
  <meta name="citation_author_institution" content="Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway" />
  <meta name="citation_author_institution" content="Department of Medical Genetics, Institute of Clinical Medicine, University of Oslo and Oslo University Hospital, Oslo, Norway" />
  <meta name="citation_author_orcid" content="0000-0001-5127-5459" />
  <link rel="canonical" href="https://ferenckata.github.io/SQSeminarPaper/" />
  <meta property="og:url" content="https://ferenckata.github.io/SQSeminarPaper/" />
  <meta property="twitter:url" content="https://ferenckata.github.io/SQSeminarPaper/" />
  <meta name="citation_fulltext_html_url" content="https://ferenckata.github.io/SQSeminarPaper/" />
  <meta name="citation_pdf_url" content="https://ferenckata.github.io/SQSeminarPaper/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://ferenckata.github.io/SQSeminarPaper/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://ferenckata.github.io/SQSeminarPaper/v/657c186e695f8689bce87e8f48e30e5834be3963/" />
  <meta name="manubot_html_url_versioned" content="https://ferenckata.github.io/SQSeminarPaper/v/657c186e695f8689bce87e8f48e30e5834be3963/" />
  <meta name="manubot_pdf_url_versioned" content="https://ferenckata.github.io/SQSeminarPaper/v/657c186e695f8689bce87e8f48e30e5834be3963/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://ferenckata.github.io/SQSeminarPaper/v/657c186e695f8689bce87e8f48e30e5834be3963/))
was automatically generated
from [ferenckata/SQSeminarPaper@657c186](https://github.com/ferenckata/SQSeminarPaper/tree/657c186e695f8689bce87e8f48e30e5834be3963)
on February 19, 2024.
</em></small>



## Authors



+ **Katalin Ferenc**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0002-3006-4297](https://orcid.org/0000-0002-3006-4297)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [ferenckata](https://github.com/ferenckata)
    <br>
  <small>
     Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway
  </small>

+ **Ieva Rauluseviciute**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-9253-8825](https://orcid.org/0000-0001-9253-8825)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [ievarau](https://github.com/ievarau)
    <br>
  <small>
     Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway
  </small>

+ **Ladislav Hovan**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-8847-9295](https://orcid.org/0000-0001-8847-9295)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [ladislav-hovan](https://github.com/ladislav-hovan)
    <br>
  <small>
     Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway
  </small>

+ **Vipin Kumar**
  <br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [princeps091-binf](https://github.com/princeps091-binf)
    <br>
  <small>
     Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway
  </small>

+ **Marieke Kuijjer**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-6280-3130](https://orcid.org/0000-0001-6280-3130)
    <br>
  <small>
     Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway
  </small>

+ **Anthony Mathelier**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-5127-5459](https://orcid.org/0000-0001-5127-5459)
    <br>
  <small>
     Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway; Department of Medical Genetics, Institute of Clinical Medicine, University of Oslo and Oslo University Hospital, Oslo, Norway
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/ferenckata/SQSeminarPaper/issues)
or email to
Katalin Ferenc \<k.t.ferenc@ncmm.uio.no\>, 
Anthony Mathelier \<anthony.mathelier@ncmm.uio.no\>.


:::


## Abstract {.page_break_before}

Ever since the high-throughput techniques became a staple in science laboratories, the generation of computational algorithms and scientific software boomed.
However, it has been noted that scientific software, and specifically bioinformatics software, lacks the quality standards of software development.
The consequence of this is code hard to test (or independently verify), reuse, and maintain.
We believe the root of inefficiency in implementing the best software development practices in the academic settings is the individualistic approach, which has traditionally been the norm for recognition of scientific achievements and by extension for software development.
Software development is a collective effort in most software-heavy endeavours.
The literature suggests that team work directly impacts code quality through knowledge sharing, collective software development, and established coding standards.
In our computational biology research groups, we explored ways to sustainably involve all group members in learning, sharing, and discussing software, while maintaining the personal ownership of research projects and related software products.
We found that through weekly meetings, within a year, regular members improved their coding skills, became more efficient bioinformaticians, and obtained a detailed knowledge about the work of their peers.
Through within-group knowledge transfer, each member obtained knowledge about advanced concepts without investing significant amount of time.
We can now quickly identify and access the expertise of each other, and we established standards to which new members are also required to comply.
We advocate for improvement of software development culture within bioinformatics through local collective effort in computational biology groups or institutes with 3 or more bioinformaticians.
Our three pillars of improving coding culture are: 1 - software quality seminars, 2 - code reviews, and 3 - resource sharing.

## Introduction ##

Bioinformatics and computational biology are indispensable components of research in biology.
About 90% of researchers rely on results produced by scientific software [@doi:10.1109/MIC.2014.88].
In turn, scientists are heavily relying on inventions of computer science and software engineering, such as programming languages, programming paradigms, or container solutions.
However, adopting practices from other fields is not without difficulties and scientific software development tends to lag behind.
One implication of using outdated or poor software engineering practices is that incorrect software results in invalid scientific findings [@doi:10.1109/MIC.2014.88; @doi:10.7717/peerj-cs.839].
Beyond that, even when the software performs as intended, researchers spend significant amount of time on software building using suboptimal practices which can further increase the necessary time investment in the future [@doi:10.1016/j.jss.2020.110848; @{https://c2.com/doc/oopsla92.html}; @doi:10.1145/2160718.2160733].

Good software development practices (e.g. pair programming, code reviews) have been established in other software-heavy endeavours to mitigate the risk of incorrect software solutions and save development time.
However, bioinformaticians or more generally scientists working with scientific software often lack formal education in computer science or software development [@doi:10.1109/SECSE.2009.5069155; @doi:10.7717/peerj-cs.839; @doi:10.1371/journal.pcbi.1005412].
This hinders the adoption of good coding practices (e.g. unit tests, continuous integration).
In addition, historically research projects are often carried by a single trainee and are part of academic degree evaluation.
Thus, software developed for a particular project is mostly limited to the skills of an individual person, does not follow many software development guidelines, and can remain poorly maintained after the end of the project [@doi:10.1101/2022.03.10.483804; @doi:10.1371/journal.pone.0205898; @doi:10.1371/journal.pcbi.1005412; @doi:10.1145/1852786.1852802].
One way to expand the knowledge and application of good software quality practices is to rely on people around and make use of redundancy of the knowledge.
We suggest that software development practices, such as pair programming or code reviews, can be repurposed as learning opportunities.

Currently, a team is perceived differently in research-oriented environments compared to the software development projects.
In research groups, members of the group discuss and help each other with scientific suggestions, but most often a single person is designing and implementing the code base to answer scientific questions.
Without shared standards, the available guidelines on coding practices are only suggestive and often anecdotal.
As following or ignoring these guidelines is up to individual judgment, the actual craft of software engineering is often treated as an afterthought.
However, when software is developed by multiple group members, researchers tend to appreciate software engineering concepts [@doi:10.1109/SECSE.2009.5069155].
High-profile code bases often feature larger development teams and their activities indicates better communication and documentation of the software [@doi:10.1371/journal.pone.0205898].
To summarize, systematic adoption of team coding practices homogenizes software engineering competence of individuals across the research group and contributes to the dynamism of the research environment.
We hypothesize that a form of team structure organized around individual software products could improve the quality of our scientific code.
According to the literature, we expected an increased validity and reproducibility of scientific findings, as well as better maintenance of our computational resources for the community [@doi:10.1093/nar/gkad1059; @doi:10.1186/s13059-023-02877-1].

In this work we first review relevant literature on the individual and team coding practices that are currently suggested within and outside scientific research groups.
To overcome the obstacles limiting researchers to adopt good practices, we present our groups' approach, where in a team setting we learn, teach, and apply concepts to improve the quality of our software products.
We have created weekly meetings and code review sessions where group members discuss aspects of software quality relevant for computational biology and show their own code for the rest of the group to discuss and review.
We suggest that our team-based activities result in shared standards and an overall better code quality of the members with a reduced effort on an individual level.
Furthermore, we provide a framework on how to get started with collective software development by directly or indirectly involving all bioinformatician group members, with or without formal training in software engineering.


## Overview of currently suggested coding practises for bioinformaticians ##

The current coding practices in the field of bioinformatics is extremely variable and depends on the background of individual scientists, the research field they are in and others.
It can be overviewed from two perspectives: how bioinformatics software products are evaluated and what coding guidelines and suggestions are currently available.
Already almost two decades ago, Diane F. Kelly wrote that scientific computations keep on being performed using error-prone development practices and reaching suboptimal solutions and poor software quality due to lack of appropriate software engineering practices [@doi:10.1109/MS.2007.155].
Since then, limitations and caveats of scientific software development practices and products has been surveyed and discussed by software engineering researchers [@doi:10.1016/j.jss.2020.110848; @doi:10.1109/SECSE.2009.5069155; @doi:10.1109/CSEET.2009.44; @doi:10.1145/1852786.1852802; @doi:10.1109/MIC.2014.88].
To increase the consistency in how bioinformaticians code and the quality of their code, data analysis and coding guidelines are fairly consistently published.
Furthermore, since bioinformaticians are often self-taught programmers and only a small fraction have formal training in computer science and software engineering, the online learning and support resources become vital.
These include blog posts from peers, open-source lecture materials from universities, forums or articles that propose guidelines on how to code or analyse data in a better way.
Therefore, the encouraged practices are plenty, however they vary a lot and do not necessarily include a consistent view of the mainstream software standards.

We selected articles which would be the entry point for bioinformatician who aim to improve their programming skills (**Supplementary Methods**, **Table 1**).
These papers focus on specific suggestions, often referred to as rules or “tips & tricks”, or they more broadly direct the readers towards good practices of coding, which are put together into guidelines.
While their targets are early career researchers with minimal coding experience (e.g. first time terminal users), they also encourage the usage of state-of-the-art software solutions (e.g. containers).
Therefore, the guidelines are often a mix of basic and advanced concepts, especially from the perspective of a standard computer science and software engineering curriculum, highlight the unique challenges emerging in bioinformatics even for routine analyses.
Furthermore, the characteristically varied backgrounds among bioinformaticians adds to the challenge of establishing broadly adopted and effective guidelines or standards.
The first impression **Table 1** might give is being intimidating due to the sheer amount of recommendations.
Many of these guidelines are struggling to establish themselves within the bioinformatics community [@doi:10.7717/peerj-cs.839].
This muddled transmission prompts us to re-think our strategies and methods to realize the effective adoption of these software engineering notions.
More specifically, our own experience indicated a greater likelihood of adoption for these notions when engaged as part of a collective effort towards better software engineering proficiency.

Updating development practices, or even gaining a good understanding of new concepts is not a trivial task.
Beyond understanding, Arvanitou et al. note that a scientific software developer, depending on the application of the software (e.g. whether it is a tool or a data analysis pipeline), needs to make choices among the good practices [@doi:10.1016/j.jss.2020.110848].
The authors argue that selection can be done via the prioritization of software quality attributes [@{https://iso25000.com/index.php/en/iso-25000-standards/iso-25010?limit=3%20}].
Due to the trade-offs between these attributes (e.g. performance vs security), priorities needs to be set for each software product.
However, bioinformaticians are rarely familiar with the meaning and importance of these attributes [@doi:10.1109/CSEET.2009.44, @doi:10.48550/arXiv.1804.01954; @doi:10.1109/MS.2008.85].
We list these attributes and provide short descriptions for them in the Supplementary Materials.
Some, such as functional suitability and performance are implicitly prioritized within bioinformatics.
Others, such as maintainability, portability, and reliability, are neglected in most bioinformatics endeavour.
Through implicit prioritization bioinformaticians develop all software as a prototype, even when the goal is to create a long-term product.
Therefore, we decided to set three target quality attributes as our learning goals that we have neglected in the past: reliability, performance, and extensibility (**Figure 1**).

The hardship of systematic, automated testing of scientific software has been discussed in detail [@doi:10.48550/arXiv.1804.01954; @doi:10.1109/MS.2008.85; @doi:10.1109/MIC.2014.88].
Uncovered faults can and do lead to incorrect scientific insights as shown in multiple examples [@doi:10.1126/science.314.5807.1856], which prompted us to investigate this issue further.
Often in science we use software to find new knowledge and do not know *a priori* the exact output a software should give for a new input dataset.
Furthermore, according to the Kanewala and Bieman [@doi:10.48550/arXiv.1804.01954], scientists view their scientific model and the implementation as a single entity.
Therefore, scientists tend to test the validity of the model but not verify the code which produces it.
In our sessions, we covered unit testing and discussed verification for scientific software (**Figure 1**).

Another insight is about the complexity of bioinformatics software.
In bioinformatics analysis it is common to combine the functionalities that are coming from various packages.
This has several implications [@doi:10.1371/journal.pcbi.1005412; @doi:10.1016/j.jss.2020.110848; @doi:10.1109/MIC.2014.88; @doi:10.1101/2022.03.10.483804], here we highlight two of them.
First, over time the software becomes increasingly hard to maintain.
The complexity, size, age, and the change-proneness of a code heavily affect maintainability [@doi:10.1109/CSEET.2009.44].
However, as bioinformatics software developers view their code as "means to an end", they care less about the future of their software.
To address this question, we built a shared understanding of functions and modularization (**Figure 1**), and expect the members of our code reviews to organize their code into modules.
Second, package management (including versioning) is a crucial aspect to ensure not only maintenance, but also ease of development, reproducibility, and reusability.
Frameworks [@doi:10.12688/f1000research.29032.1; @doi:10.1038/nbt.3820] and package management solutions [@{https://www.anaconda.com/}; @{https://docs.docker.com/}; @{https://apptainer.org/}] are required to achieve these qualities.
Similarly to modularization, we first learnt about version control and container solutions (**Figure 1**), so that we can expect members to follow these practices.

Interestingly, throughout our literature review we found only one instance of suggestions on how to code in a team setting and utilize multiple people's expertise on software development.
Often guidelines for starting bioinformaticians encourage reaching out to others, but mostly to seek help when encountering a problem with their code.
This could include consulting with colleagues, finding a mentor or participating in online communities (for example, Stack Overflow or Biostars) [@doi:10.1371/journal.pcbi.1008645].
However, it is still mainly focused on individual practices, does not involve peer-pressure, and insufficient to recognize unknown unknowns.
The one counter example is the Code Clubs described by Hagan et al. [@doi:10.1371/journal.pcbi.1008119].
In their research group, members are collectively engaged in software development through code reviews and pair coding and software engineering education through workshops or seminars [@doi:10.1371/journal.pcbi.1008119].
It is in contrary to software engineering-oriented literature, where the main focus is on practices when coding in a team [@https://faculty.washington.edu/ajko/books/cooperative-software-development; @doi:10.1007/s10664-012-9205-0].
Sharing your coding experience with others helps minimize the isolation, allows individuals to learn from their peers, helps to establish and maintain standards, and helps to write a better quality software.
We therefore established a learning club called software quality seminars, regular code reviews, and a resource sharing platform to foster team effort (**Figure 1**).

In a later section (Our experience of development processes involving teams) we will illustrate with concrete examples how notions like design patterns, standardised documentation or data structures got incorporated in our daily software development practice and thinking through regular instances of collective learning.
But first let us turn to the dedicated literature for team-based software development to demonstrate the merit of a collective approach to software development.

***Table 1:*** **Collection of recommendations for improving scientific software quality.** Some guidelines are more vague than others, they also have varied scope, and they target different stakeholders. Therefore, it may be hard to find individual responsibility and actionable points from the literature.
<table>
    <thead>
        <tr>
            <th>Category</th>
            <th>Recommendation</th>
            <th>References</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=3>Software development 101</td>
            <td>Sanity check on input parameters</td>
            <td>[@doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td>Do not hard-code changeable parameters and paths</td>
            <td>[@doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td>Do not require superuser privileges</td>
            <td>[@doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td rowspan=3>Advanced software development</td>
            <td>Usage of design patterns</td>
            <td>[@doi:10.1016/j.jss.2020.110848]</td>
        </tr>
        <tr>
            <td>Adoption of international best practice standards of software quality</td>
            <td>[@doi:10.5281/zenodo.1172970]</td>
        </tr>
        <tr>
            <td>Regular refactoring</td>
            <td>[@doi:10.1016/j.jss.2020.110848]</td>
        </tr>
        <tr>
            <td rowspan=7>Software development process</td>
            <td>Continuous integration</td>
            <td>[@doi:10.1016/j.jss.2020.110848]</td>
        </tr>
        <tr>
            <td>Agile software development methodology</td>
            <td>[@doi:10.7717/peerj-cs.839; @doi:10.1016/j.jss.2020.110848]</td>
        </tr>
        <tr>
            <td>Educated choice of software development methodology</td>
            <td>[@doi:10.1109/CSEET.2009.44]</td>
        </tr>
        <tr>
            <td>Independent review of source code</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.1109/CSEET.2009.44; @doi:10.1109/MIC.2014.88]</td>
        </tr>
        <tr>
            <td>Code quality monitoring</td>
            <td>[@doi:10.1016/j.jss.2020.110848]</td>
        </tr>
        <tr>
            <td>Inclusion of appropriate license</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td>Cooperation between developers and users</td>
            <td>[@doi:10.5281/zenodo.1172970]</td>
        </tr>
        <tr>
            <td rowspan=4>Testing and validation</td>
            <td>Establish validation and acceptance procedures</td>
            <td>[@doi:10.5281/zenodo.1172970]</td>
        </tr>
        <tr>
            <td>Provide a small test set</td>
            <td>[@doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td>Standardized tests</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.7717/peerj-cs.839; @doi:10.1109/CSEET.2009.44; @doi:10.1371/journal.pcbi.1005412; @doi:10.1016/j.jss.2020.110848]</td>
        </tr>
        <tr>
            <td>Ensure reproducibility of results</td>
            <td>[@doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td rowspan=5>Reproducibility</td>
            <td>Standardized working environment and automation</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.7717/peerj-cs.839]</td>
        </tr>
        <tr>
            <td>Version control</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.7717/peerj-cs.839; @doi:10.1371/journal.pcbi.1005412; @doi:10.1016/j.jss.2020.110848]</td>
        </tr>
        <tr>
            <td>Rely on package managers</td>
            <td>[@doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td>Containerization for portability</td>
            <td>[@doi:10.7717/peerj-cs.839; @doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td>Tagging of software version for reproducibility</td>
            <td>[@doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td rowspan=3>Documentation</td>
            <td>User (and developer) documentation</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.7717/peerj-cs.839; @doi:10.1109/CSEET.2009.44; @doi:10.1371/journal.pcbi.1005412]</td>
        </tr>
        <tr>
            <td>Requirements gathering</td>
            <td>[@doi:10.7717/peerj-cs.839; @doi:10.1109/CSEET.2009.44]</td>
        </tr>
        <tr>
            <td>Description of the software version used, its configurations and parameters in publications</td>
            <td>[@doi:10.5281/zenodo.1172970]</td>
        </tr>
        <tr>
            <td rowspan=8>Community effort</td>
            <td>Contribute to open-source development</td>
            <td>[@doi:10.1109/MIC.2014.88]</td>
        </tr>
        <tr>
            <td>Reuse existing (reliable) software</td>
            <td>[@doi:10.1371/journal.pcbi.1005412; @doi:10.1016/j.jss.2020.110848]</td>
        </tr>
        <tr>
            <td>Preferentially selecting freely available open-source software</td>
            <td>[@doi:10.5281/zenodo.1172970]</td>
        </tr>
        <tr>
            <td>Encourage user participation in the software development process</td>
            <td>[@doi:10.5281/zenodo.1172970]</td>
        </tr>
        <tr>
            <td>Recognition and assignment of adequate time for quality-assured development</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.1109/CSEET.2009.44]</td>
        </tr>
        <tr>
            <td>Recognition of software development as academic achievement</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.1109/MIC.2014.88]</td>
        </tr>
        <tr>
            <td>Support for developer community for long term maintenance (when applicable)</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.1109/MIC.2014.88]</td>
        </tr>
        <tr>
            <td>Financial support for software development and maintenance</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.1109/MIC.2014.88]</td>
        </tr>
    </tbody>
</table> 



![***Figure 1:*** **An illustration comparing the process of improvement in software writing to rock climbing.**
DSA: data structures and algorithms, OOP: object-oriented programming, UML: Unified Modelling Language, CI: continuous integration, SCA: static code analysis](content/images/wall_climbing.png "Wall climbing"){height="700px"}


## Coding in teams ##

Beyond the brief mention of getting support or coding in a team in guidelines for bioinformaticians, specialized literature exists that examines how to effectively organize coding activities in a team.
Programming as a collective practice is a key notion in software engineering.
A central theme in this literature is maximizing team cohesion while minimizing code coupling [@{http://www.jstor.org/stable/40539129}].
Authors argue that the viability of a software project along its successive development phases is largely determined by the adoption of sound software design enforcing modularity and extensibility, coupled with team management practices centred around communication and collective governance [@ISBN:0932633420].

In general, we understand management as the set of tasks ensuring the viability of a software project.
These tasks revolve around planning, monitoring resources, and tracking progression [@{https://www.wrike.com/project-management-guide/faq/what-is-software-project-management/}].
Typically, the oversight of these functions would be taken up by a single individual referred to as the “manager” of a project, where manager is a role rather than a title of a particular person.
In the particular context of computational projects in academia, a strict division of labour is rarely found in regard to the management of software projects.
Furthermore, some tasks, such as risk, budget and time management, and maintenance are discussed at the conception of the project (e.g. during grant application) and thus decoupled from the actual software development phase.
The remaining management tasks would often be deliberated by the developer(s), eventually, and often implicitly, reaching a consensus on the desired way forward and acted upon.
Implicit decision making is one of the key challenges current bioinformatics projects face.
As agile is the only recommendation about team management present in these guidelines (**Table 1**), we discuss it here in detail.

Through more team communication, one outstanding aim of agile is the aspiration for more autonomy in organizing the work of software developers.
Incentivizing a collective ownership and governance of the codebase as a whole, promotes the adoption of software engineering best practices among developers contributing to a software project [@doi:10.1016/j.infsof.2009.11.004].
Indeed, by aspiring to make any developer within the team interchangeable across the various ongoing tasks, we create the need for robust testing, comprehensive documentation and coherence across the difference parts of the project [@{http://www.jstor.org/stable/40539129}].
Furthermore, by exposing every developer to a variety of tasks over the course of the project development, we strengthen the knowledge and skill base of the team as a whole, as well as create a better mutual awareness of team member expertise.
This mutual awareness is known as transactive memory system, and has been linked to increased team performance [@doi:10.1177/1046496420967764].
Taken together these merits further improve the team's capacity to overcome technical challenges that will arise over the course of the development process.

Reaping the benefits from agile-like practices requires the effective adoption of a variety of methods.
Practices and methods aligned with agile prescriptions include planning a minimum viable product, document requirements, organize stand-up meetings, assign tasks, do pair-programming, or code reviews.
Note that many of these practices do not require the presence of the manager, but assume a collegial work culture and standardized procedures.
This constitutes an additional overhead in terms of time and resources needed when developing, but this is offset by the aforementioned benefits in terms of coding practice, software resilience and improved team capabilities.

We do not believe that all the software engineering guidelines employed in the industry are necessarily relevant to the production of scientific software.
The circumstances differ significantly, mainly due to how the outcomes of research projects (papers, tools, protocoles, etc.) need to be credited to paricular individual researchers for their career progression.
Regardless of the optimality of this situation, personal projects remain the norm, and it would be futile to expect another group member to achieve an equal level of familiarity with one's project.
However, this should not prevent interactions between the people in the group, as it is through these interactions that rules are enforced and quality increased.

In our research groups, we have practically implemented the environment in which we, as a group, learn about and implement software quality practices that have been discussed in literature.
We want to share this experience and propose how simple additions, such as weekly code review sessions or seminars, can lead to the improved quality of collective or personal software.


## Our experience of development processes involving teams ##

In our professional careers, we have experienced hardships with scientific software - both from the user and from the developer's perspective.
We have seen a variety of suggestions in the literature aiming to improve the status of bioinformatics software.
We recognized that for a single person achieving a good understanding of them all, and subsequently prioritizing, and adopting them would require a substantial amount of time.
Paradoxically, researchers in academia, especially trainees, often work under time pressure, since projects, such as doctoral thesis, have pressing deadlines.
Even basic software development standards (e.g. standardized environment, independent review of source code) might seem out of scope and impossible to implement for a single researcher.
On the other hand, we also have seen that the industry standard approach heavily relies on a team structure and team management.
Therefore, within our groups, we aimed to create a system where the individual scientific software projects are supported through collective learning, understanding, and discussions.
In this section we describe the practices that we have settled on.

In order to illustrate our thinking with regards to improvement in software writing, we compare it to the exercise of rock-climbing (**Figure 1**).
At the top of the rock is our goal of good quality software.
Specifically, we identified reliable, performant, and extensible software as our aim, as we wished to improve our skills in creating and maintaining a lasting piece of software as is the scope of our teams [@doi:10.1093/nar/gkad1059 ; @doi:10.1186/s13059-023-02877-1].
In order to reach it, we need to become proficient in the various concepts depicted by the holds.
These concepts were selected from the literature and our professional experience, but are not exhaustive and can be tailored to the specific needs of each group.
The higher they are on the wall, the more advanced we consider the concepts to be.
As the progress is cummulative, we have chosen to show the holds in the same colour if they represent related concepts that build upon each other.
This way, we mimic traditional CS education, compared to the guidelines of a mixture of concepts.
The most important point, however, is the fact that rock climbing requires a partner to belay you, just as we believe the input of other people helps us become better programmers.

The software development practices that we have adopted can be broadly separated into three categories: 1 - software quality seminars, 2 - code reviews, and 3 - resource sharing.
Here we describe and illustrate the work done in these ways.
We believe these three pillars are the minimum requirement for achieving lasting improvement in software development within research teams, but bioinformaticians of other groups should tailor the content and the frequency of these meetings to their specific needs.

### Software quality seminars ###

Within the framework of software quality seminars, we have established a large-scale knowledge transfer system between the participants.
Presentations and demonstrations of basic concepts, new techniques and tools that are not necessarily tied to a specific project help broaden our knowledge base and awareness.
In this sense, they form almost a substitute for a more formal computer science education, which most bioinformaticians lack [@doi:10.7717/peerj-cs.839].
Topics can arise from literature recommendations, previous education, own projects, code reviews, or effectively be a reproduction of a useful talk or seminar given elsewhere.
The presenters benefit as well by having to research the topic further and present it coherently.
We recommend keeping these meetings regular, e.g. at least once a month, given the amount of knowledge that can be learnt together (see **Table 1**).

The outcomes of these sessions are manifold.
A few examples:

1) a shared vocabulary that enables quick discussion about implementation details and code structures (e.g. object-oriented programming, design patterns, data structures and algorithms);
2) awareness of previously unknown packages or technical solutions, improving software performance and quality (e.g. bioframe, S4 object system, R Markdown);
3) a kind of toolkit and set of recordings we can sample from and build on in our own research projects (e.g. containerization, git features to ease and quicken software development, planning with UML diagrams).

We also wanted to experiment with some of the collaborative practices common in the industry to tailor it to our situation.
Therefore, we have explored the possibility of collaborative projects and pair programming.
Within the limitations of our busy schedules, we have experimented with collaboration on different software tools that are available for all members of the research group and developed by multiple people in the group (see section on Resource sharing).
We have not proceeded to adopt these practices routinely, but they represent an interesting concept that others who want to follow in our footsteps might want to explore.
Although not explicitly a project conceived during the meetings, many regular attendees have extensively applied software quality features (object-oriented programming style, user stories when documenting the requirements and assumptions, Jira to add features and report bugs, continuous integration with Git) when working on the same codebase as a team for the latest release of JASPAR database [@doi:10.1093/nar/gkad1059].
We also want to note that this article in fact was successfully written using a continuous integration based tool Manubot [@doi:10.1371/journal.pcbi.1007128].

### Code reviews ###

The benefits of code reviews have been reviewed in the past [@doi:10.5334/jors.35; @doi:10.1371/journal.pcbi.1008119; @{https://logicmag.io/clouds/agile-and-the-long-crisis-of-software/}].
In this text we will briefly summarize how presenting your code and receiving feedback leads to improvement in the process of creating software.
We found that during these meetings implicit peer-pressure helps us achieve most goals: standardization of practices, improved code quality, and enhanced usability of the software.
We would like to note, that the efficiency of these meetings are improved with a shared understanding of the concepts covered during the software quality seminars.
Therefore, we advise starting with learning before discussing the code.

Prior to a scheduled code review, the author is expected to write their code in a way that it will be explainable and understood by others.
This expectation is largely self-inflicted as each person feel the pressure of exposing their weaknesses - even within a friendly environment.
In a large distributed project clean coding style may be trivial, but because the bioinformatic projects are often handled by a single person, it is very possible to make the code complex and obfuscated.
We observed that during data analysis parts of the code are re-run in an ad-hoc manner (e.g. by commenting out or re-writing parts), making it increasingly difficult to explain the code or reproduce the same analysis.

During the code review, the author has to explain some aspect of their code clearly (e.g. structure, algorithm implementation, performance related decisions), which depends on them understanding it.
Trying to explain your code to someone is shown to help with understanding, as with the rubber duck method [@ISBN:9780201616224].
The feedback obtained can help fix existing or potential future issues, improve the implementation, and produce cleaner, more concise code.
The other participants may not be deeply familiar with the particular project, but they have their unique knowledge and point of view.
We agree with the ten simple rules described by Hagan et al. [@doi:10.1371/journal.pcbi.1008119], and note that many of those naturally emerged as a code of conduct after a few rounds of trial and error.
In our settings, it is entirely up to the author to choose which aspect of the code, or software product to discuss.
Although it is implied that participants of code reviews are intended to discuss implementation details, we accept and enjoy discussions about any other aspect of the code, such as user interface design, documentation, or architecture considerations.

After the review, the received suggestions, if crucial, should be implemented swiftly to improve the code before advancing the project.
Some other suggestions (e.g. coding style) do not require instant refactoring, these may be viewed as suggestions for future projects.
At the start of implementation of regular meetings, the recurring comments were about modularization, documentation, and variable declarations, until these became standard among the members.
For example, after about half a year, it was trivial for everyone involved that code organized into functions is preferred over the so-called "spaghetti code".
It is important to note that the success of code review is highly dependent on its frequency.
A long time between reviews means a lot of new code, difficulty to cover all changes in a single session, and potentially a lot of rewrite post review.
Our group of 5-10 people settled for weekly code review sessions.

A recurring question is whether a script needs refactoring or can remain a prototype.
Taschuk and Wilson [@doi:10.1371/journal.pcbi.1005412] suggest a cut-off where a script is being reused, shared with others or used to produce findings in a publication.
This definition would potentially include the majority of code written by bioinformaticians, but the time spent on improving the scripts should be weighed against the time required to deal with suboptimal code.
Overall, as good practices become routine, the required time investment will be reduced and the benefits will become more apparent.

Our experience indicates a broader adoption of theoretical aspects and good practices of software engineering highlighted during these code review sessions.
A couple examples will illustrate how code reviews incentivized coding practices and team self-managements aligned with agile prescriptions.
Code review involves some elements of problem-solving, often revisiting fundamental notions of design patterns, algorithms or data structures.
Recurrently we would examine the best strategies to modularize the presented code and discuss what would constitute effective and self-contained computational task and elaborate collectively possible design patterns.
This strengthens the team's overall competency as well as promoting some form of standardization regarding the mental models to use for common tasks and objects solicited in many computational projects.
An important part of the code review process focuses on the compliance with good code practices, and constitutes an explicit attempt at standardization.
This is particularly well illustrated with the review of documentation which goes beyond simple linting.
Effectively this process promotes the adoption of a shared and systematic manner to describe and document the behaviour of the considered tool, which facilitates its intelligibility for a wider audience.
The shared knowledge base and standards also allow us to make new group members adopt good coding practices more quickly.

As a positive additional outcome, we noticed an increasing understanding in each other’s projects that naturally emerged through talking about the examined code.
This enabled us to give more involved comments during subsequent group meetings too, where we would naturally discuss each other's scientific projects.
Additionally, seeing and analysing everyone's code on a more hands-on level showed us how repetitive some pieces of code can be in different projects.
This redundancy can be removed by implementing a system to share resources.

### Resource sharing ###

Resource sharing boils down to making sure that useful online resources are brought to the attention of all participants easily.
It can be discussed from two perspectives: external open-access resources (forums, repositories, packages and libraries) and internal (within-group resources with tools).
The latter is very important as it allows for team contribution that can benefit the individual project development.
A simple example of this could be a shared repository of various computational tools that were developed by members of the group.
Such tools are universal enough and fit the group’s research questions, so all people in the group can re-use them.
In addition, each tool can be potentially developed and reviewed by multiple group members.

In sum, software quality seminars, code reviews and shared resources in the research group can be implemented as separate activities choosing all or any of them.
We observed that even a single activity is benefiting members' coding experience and the resulting code quality.


## Conclusions and future perspectives ##

Software engineering emerged and has been developing to address issues naturally arising from poorly planned software development, such as project failures, delays, incorrect functionality or defects [@doi:10.1145/3084225], none of which is unknown to the scientific community.
Indeed, the crisis of scientific software in general is widely discussed [@doi:10.1038/d41586-023-00053-w; @doi:10.1038/d41586-022-01516-2].
It is only natural that the bioinformatics community learns from those more experienced, and focuses on solving problems that have been identified.
In this case, it is both the software engineering research community and the industry experts on software and team management.

In our computational biology groups, we introduced regular seminars to learn about software solutions, and code reviews that fit our specific needs and context.
Through these meetings, we learnt about and adopted various concepts that achieve a better quality software.
Furthermore, we have established coding standards within our groups, which ease within-group support and collaborative projects.
We note that the usage of these tools is not necessarily aligned with industry practices, due to the experimental nature of scientific software.
Nevertheless, as bioinformatics becomes a more and more software-heavy field, we believe a good direction is to collectively lower the barrier to adapting to new technologies.

When discussing our approach, it is implied that team dynamic is important, especially for such bottom-up approaches.
The overall performance increases when team members are familiar with each other and build problem-solving routines together through cumulative experience [@{http://www.jstor.org/stable/40539129}].
In a group the knowledge on who knows what speeds up the problem-solving [@doi:10.1177/1046496420967764]; time spent together and social factors ease technical knowledge transfer [@{http://www.jstor.org/stable/40539129}].
We therefore motivate group leaders of groups with even a small computational component to build an environment for their trainees to communicate and discuss software quality aspects.

For large software project which supports many researchers and contributes to novel findings, working in team and following standards is a necessity and not an option.
While this may not be necessary for smaller projects, we argue that following good software quality practices is still very beneficial.
If single-person projects survive the original developer, deposited on platforms like GitHub, they might be overly cryptic and poorly documented so that no other scientist can take over [@doi:10.1038/d41586-022-01901-x].
Over time a project might be taken over by another person, thus accidentally becoming a sort of team project with (by definition) insufficient communication.
Lack of standards and good practices thus undermine maturation, addition of new features, and general maintainability.

We envision a future where scientific software for core applications is appreciated, reliable, and actively maintained.
All scientists would benefit from a strong backbone of software solutions, that would support quick and efficient prototyping, as well as maturation of working solutions.
The lack of funding for the maintenance of software, prevents achieving a level of software quality that would inspire confidence in the results [@doi:10.1109/MIC.2014.88].
Funding is typically provided for the development of novel software, and it can be hard to justify spending time on maintenance which provides no output in terms of articles.
Currently, as Alexander Szalay puts it "the funding stops when they [researchers] actually develop the software prototype" [@doi:10.1038/d41586-022-01901-x].
Researchers want to build on each other's findings, use published novel software as tools, but they might need to spend quite some time adopting or maintaining that software [@doi:10.1371/journal.pcbi.1005412; @doi:10.1016/j.jss.2020.110848; @doi:10.1109/MIC.2014.88].
The infrastructure would benefit from funding earmarked for maintenance, and from dedicating time to it in project proposals.
Fortunately in recent years, the lack of funding is being recognized and addressed by a few agencies, such as the Chan Zuckerberg Initiative Essential Open Source Software for Science fund [@{https://chanzuckerberg.com/eoss/}].
Scientific community and funding agencies should welcome the efforts of maintaining original software and encourage its updates instead of the development of a replacement software that risks remaining unmaintained.

To summarise, today it is important for the scientific community to recognize the limitations of the software we are producing.
This includes acknowledging the flaws in the process of coding.
As a potential great improvement we propose organizing activities, such as software quality and code review seminars, that would involve the whole research group in each other's projects, therefore allowing the sharing of knowledge and feedback on the code practically.
We also advocate for sustainable funding for the maintenance of existing and newly developed scientific software.

## Acknowledgements ##

The authors would like to acknowledge the helpful feedback on an early version of the manuscript provided by Ine Bonthuis, Nolan Newman, and Romana Pop.
We would also like to acknowledge the contributions made by all the participants of our code reviews and software quality seminars.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

