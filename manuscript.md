---
title: Improving software quality in bioinformatics through teamwork
keywords:
- software quality
- bioinformatics
- teamwork
lang: en-US
date-meta: '2024-04-25'
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
  <meta name="dc.date" content="2024-04-25" />
  <meta name="citation_publication_date" content="2024-04-25" />
  <meta property="article:published_time" content="2024-04-25" />
  <meta name="dc.modified" content="2024-04-25T13:51:08+00:00" />
  <meta property="article:modified_time" content="2024-04-25T13:51:08+00:00" />
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
  <meta name="citation_author_institution" content="Centre for Bioinformatics, Faculty of Mathematics and Natural Sciences, University of Oslo, Ooslo, Norway" />
  <meta name="citation_author_orcid" content="0000-0001-5127-5459" />
  <link rel="canonical" href="https://ferenckata.github.io/SQSeminarPaper/" />
  <meta property="og:url" content="https://ferenckata.github.io/SQSeminarPaper/" />
  <meta property="twitter:url" content="https://ferenckata.github.io/SQSeminarPaper/" />
  <meta name="citation_fulltext_html_url" content="https://ferenckata.github.io/SQSeminarPaper/" />
  <meta name="citation_pdf_url" content="https://ferenckata.github.io/SQSeminarPaper/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://ferenckata.github.io/SQSeminarPaper/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://ferenckata.github.io/SQSeminarPaper/v/b8ed99caaabb85b03f26c78efb955ea83c2cffd4/" />
  <meta name="manubot_html_url_versioned" content="https://ferenckata.github.io/SQSeminarPaper/v/b8ed99caaabb85b03f26c78efb955ea83c2cffd4/" />
  <meta name="manubot_pdf_url_versioned" content="https://ferenckata.github.io/SQSeminarPaper/v/b8ed99caaabb85b03f26c78efb955ea83c2cffd4/manuscript.pdf" />
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
([permalink](https://ferenckata.github.io/SQSeminarPaper/v/b8ed99caaabb85b03f26c78efb955ea83c2cffd4/))
was automatically generated
from [ferenckata/SQSeminarPaper@b8ed99c](https://github.com/ferenckata/SQSeminarPaper/tree/b8ed99caaabb85b03f26c78efb955ea83c2cffd4)
on April 25, 2024.
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
     Centre for Molecular Medicine Norway (NCMM), Nordic EMBL Partnership, University of Oslo, 0318 Oslo, Norway; Department of Medical Genetics, Institute of Clinical Medicine, University of Oslo and Oslo University Hospital, Oslo, Norway; Centre for Bioinformatics, Faculty of Mathematics and Natural Sciences, University of Oslo, Ooslo, Norway
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/ferenckata/SQSeminarPaper/issues)
or email to
Katalin Ferenc \<k.t.ferenc@ncmm.uio.no\>, 
Anthony Mathelier \<anthony.mathelier@ncmm.uio.no\>.


:::


## Abstract {.page_break_before}

Since high-throughput techniques became a staple in science laboratories, computational algorithms and scientific software boomed.
However, scientific software, specifically bioinformatics software, usually lacks software development quality standards.
It results in software code that is hard to test (or independently verify), reuse, and maintain.
We believe the root of inefficiency in implementing the best software development practices in academic settings is the individualistic approach, which has traditionally been the norm for recognizing scientific achievements and, by extension, for developing specialized software.
Software development is a collective effort in most software-heavy endeavors.
Indeed, the literature suggests teamwork directly impacts code quality through knowledge sharing, collective software development, and established coding standards.
In our computational biology research groups, we explored ways to sustainably involve all group members in learning, sharing, and discussing software development while maintaining the personal ownership of research projects and related software products.
We found that through weekly meetings, within a year, regular members improved their coding skills, became more efficient bioinformaticians, and obtained detailed knowledge about the work of their peers, triggering new collaborative projects.
Each member learned about advanced concepts through within-group knowledge transfer without investing significant time.
We can now quickly identify and access each other's expertise and have established standards to which new members must comply.
We strongly advocate for improving software development culture within bioinformatics through local collective effort in computational biology groups or institutes with three or more bioinformaticians.
This manuscript provides the necessary overview of the best coding practice literature.
It describes how we improved our software development culture through three pillars: (1) software quality seminars, (2) code reviews, and (3) resource sharing.
We hope that our shared experience and suggestions will boost the implementation of similar initiatives for improved academic training and a more sustainable environment for academic software practice.


## Introduction ##

Bioinformatics and computational biology are indispensable and integral components of research in biology.
About 90% of researchers rely on results produced by scientific software [@doi:10.1109/MIC.2014.88].
In turn, scientists heavily rely on computer science and software engineering innovations, such as programming languages, programming paradigms, or container solutions.
However, adopting practices from other fields is complex, and scientific software development in the academic setting tends to lag.
One implication of using outdated or poor software engineering practices is that incorrect software may result in invalid scientific findings [@doi:10.1109/MIC.2014.88; @doi:10.7717/peerj-cs.839].
Even when the software performs as intended, researchers can spend significant time on software building using suboptimal practices.
Such practice results in the accumulation of technical debt, which translates to increased future time investments in extra efforts, refactoring, and rework [@doi:10.1016/j.jss.2020.110848; @{https://c2.com/doc/oopsla92.html}; @doi:10.1145/2160718.2160733].

Good software development practices (e.g., pair programming and code reviews) are established in other software-heavy fields to mitigate the risk of incorrect software solutions and save development time.
However, scientists, such as bioinformaticians, who work with scientific software often lack formal education in computer science and software development [@doi:10.1109/SECSE.2009.5069155; @doi:10.7717/peerj-cs.839; @doi:10.1371/journal.pcbi.1005412]. This lack of or limited training hinders the adoption of good coding practices.
Moreover, the current funding and academic evaluation frameworks often restrict research projects to being primarily driven by a single trainee.
As a consequence, the limitations of an individual's skills restrict academic software development, which often fails to follow software development guidelines and remains poorly maintained beyond the end of the project [@doi:10.1101/2022.03.10.483804; @doi:10.1371/journal.pone.0205898; @doi:10.1371/journal.pcbi.1005412; @doi:10.1145/1852786.1852802].
One way to expand the knowledge and application of good software quality practices is to rely on other experts and leverage complementary knowledge.
We suggest that practices from the field of software development, such as code reviews, can be repurposed as learning opportunities.

In research-oriented environments, what defines a "team" is perceived differently than in software development.
Group members generally discuss and help each other with scientific suggestions.
Still, a single person often drives the code base's design and implementation process to address specific scientific questions.
Since adhering to or disregarding software development guidelines typically depends on personal judgment, proper software engineering practice is often considered secondary.
However, when multiple group members develop software, researchers tend to appreciate software engineering concepts [@doi:10.1109/SECSE.2009.5069155].
Notably, larger development teams often enhance communication and software documentation, which are crucial to the success of high-profile code bases. [@doi:10.1371/journal.pone.0205898].
The systematic adoption of team coding practices homogenizes the software engineering competence of individuals across the research group and contributes to the dynamism of the research environment.
To summarize, organizing individual bioinformatics in a team structure results in increased validity and reproducibility of scientific findings and improved maintenance of the computational resources for the community [@doi:10.1093/nar/gkad1059; @doi:10.1186/s13059-023-02877-1].

This paper first reviews relevant literature on the individual and team coding practices suggested within and outside scientific research groups.
To overcome the obstacles limiting researchers from adopting good practices, we present our groups' approaches, where we learn, teach, and apply concepts to improve the quality of our software products in a team setting.
We created weekly meetings where group members discuss aspects of software quality relevant to computational biology.
Code review sessions complement these meetings to discuss and review the code of our peers.
We suggest that our team-based activities result in shared standards and an overall better code quality with a reduced effort on an individual level.
Furthermore, we offer a framework for initiating collective software development involving members of a bioinformatics group, with and without formal training in software engineering.

We emphasize that collaborative efforts provide a suitable environment to improve software quality in an academic setting.
More specifically, the discussions and reflections we developed in those settings accelerated the adoption of software engineering skills in our teams.
We draw a visual metaphor where improving software quality is similar to a rock climbing exercise, with the top of the rock representing our goal of good quality software (**Figure 1**).
To reach this goal, one needs to become proficient in the various concepts depicted by the holds.
These concepts are selected from the literature and our professional experience but are not exhaustive, and each group can tailor them to their specific needs.
The higher they are on the wall, the more advanced we consider the concepts to be.
As the progress is cumulative, we show the holds representing related concepts that build upon each other in the same color.
This way, we mimic traditional computer science education.
The order of visiting the topics can vary between groups, but reiterating certain core concepts (e.g., modularization and testing) is valuable.
Nevertheless, the most crucial point is that rock climbing requires a partner to belay you, just as we believe that other people's input helps us become better programmers.

![***Figure 1:*** **An illustration comparing the improvement process in software writing to rock climbing.**
DSA: data structures and algorithms, OOP: object-oriented programming, UML: Unified Modelling Language, CI: continuous integration, SCA: static code analysis](content/images/wall_climbing.png "Wall climbing"){height="700px"}


## Overview of suggested coding practices #

Bioinformaticians often use error-prone development practices to create software or pipelines.
This practice leads to poor quality and solutions that fall short of ideal due to the insufficient application of proper software engineering methods [@doi:10.1109/MS.2007.155].
In the past two decades, software engineering researchers have surveyed and discussed the limitations and caveats of scientific software development practices and products (e.g., see [@doi:10.1016/j.jss.2020.110848; @doi:10.1109/SECSE.2009.5069155; @doi:10.1109/CSEET.2009.44; @doi:10.1145/1852786.1852802; @doi:10.1109/MIC.2014.88]).
Moreover, online learning and support resources are vital for bioinformaticians who are self-taught programmers.
These include peer blog posts, open-source lecture materials from universities, forums, and published guidelines for improved coding and data analysis.
The encouraged practices are plenty.
However, the current coding practices relevant to bioinformatics software development vary and depend on factors such as prior training in computer science and specific scientific research fields.
Finally, the suggested practices do not necessarily include a consistent view in line with mainstream software standards.

Thus, we selected articles as entry points for bioinformaticians who aim to improve their programming skills.
We provide an overview of the suggestions presented in these papers in **Table 1** (**Supplementary Methods**).
While this type of article usually targets early career researchers with minimal coding experience (e.g., first-time terminal users), they often encourage using state-of-the-art software solutions (e.g., containers), which seem contradictory.
Therefore, these guidelines represent a mix of primary and advanced concepts usually provided as lists of rules or "tips & tricks."
The large spectrum of guidelines to follow highlights the unique challenges emerging in bioinformatics, even for routine pipelines and software development for data analysis.

**Table 1** might initially intimidate due to the extensive list of recommendations.
This complexity reflects how the bioinformatics community struggles to implement these guidelines [@doi:10.7717/peerj-cs.839].
Recognizing that the widespread adoption of these standards will prove complicated through individual efforts, we considered a more collaborative strategy.
Indeed, we aimed to revise our techniques and methods to ensure the successful integration of these guidelines into our practices.
More specifically, our experience indicated a greater likelihood of adopting these critical practices and working collectively towards better software engineering proficiency.

Updating software development practices or gaining a good understanding of new concepts is not trivial.
For instance, Arvanitou _et al._ noted that a scientific software developer must choose between various good practices depending on developing a software tool or a data analysis pipeline [@doi:10.1016/j.jss.2020.110848].
The authors argue that the selection of practices should follow the software quality attributes to prioritize [@{https://iso25000.com/index.php/en/iso-25000-standards/iso-25010?limit=3%20}].
Importantly, it implies that priorities will vary between software products based on the trade-offs between these attributes (e.g., performance vs security).
As bioinformaticians are rarely familiar with the meaning and importance of these attributes [@doi:10.1109/CSEET.2009.44, @doi:10.48550/arXiv.1804.01954; @doi:10.1109/MS.2008.85], we present an overview and short descriptions in **Supplementary Table 1**.
Within bioinformatics, attributes such as functional suitability and performance are implicitly prioritized, while other attributes, such as maintainability, portability, and reliability, are often neglected.
Through implicit prioritization, most software is developed as a prototype, even when the goal is to create a long-term product [@doi:10.1038/d41586-022-01901-x].
This report focuses on three target quality attributes as our learning goals: reliability, performance, and extensibility (see also **Figure 1**).

The hardship of systematic, automated testing of scientific software has been discussed in detail [@doi:10.48550/arXiv.1804.01954; @doi:10.1109/MS.2008.85; @doi:10.1109/MIC.2014.88].
Scientific software development requires dedicated testing methods to maintain scientific integrity since unexpected discoveries can confound expected outcomes and error detection.
Scientists tend to assess the model's validity but do not thoroughly test the code that implements it, which betrays the common confusion of a model and its implementation as a single entity [@doi:10.48550/arXiv.1804.01954].
Uncovered faults can, and sometimes do, lead to incorrect scientific insights, as shown in multiple examples [@doi:10.1126/science.314.5807.1856].
These observations highlight the importance of considering unit testing and verification for scientific software (**Figure 1**, **Supplementary Table 2**).

A fundamental aspect of bioinformatics software development involves the integration of functionalities from various software packages -- a concept referring to collections of code that perform specific tasks.
This approach of combining packages from several resources has several implications [@doi:10.1371/journal.pcbi.1005412; @doi:10.1016/j.jss.2020.110848; @doi:10.1109/MIC.2014.88; @doi:10.1101/2022.03.10.483804].
Among these, we focus on two critical issues.
First, over time, the software may become increasingly challenging to maintain.
Indeed, the complexity, size, age, and code's change-proneness heavily affect its maintainability [@doi:10.1109/CSEET.2009.44].
One can address this increased complexity through a shared understanding and implementation of functions and modularization (**Figure 1**, **Supplementary Table 2**).
Second, package management (including versioning) is crucial to ensure maintenance and ease of development, reproducibility, and reusability.
Frameworks [@doi:10.12688/f1000research.29032.1; @doi:10.1038/nbt.3820] and package management solutions [@{https://www.anaconda.com/}; @{https://docs.docker.com/}; @{https://apptainer.org/}] are required to achieve these qualities (**Figure 1**, **Supplementary Table 2**).

We found that the literature mainly targeted towards bioinformaticians rarely covers the topic of coding as a team or using multiple people's expertise in software development.
Usually, the advice encourages beginners to ask for help when facing problems with their code, not to work together from the start.
Such advice includes consulting with colleagues, finding a mentor, or participating in online communities (e.g., Stack Overflow or Biostars) [@doi:10.1371/journal.pcbi.1008645].
However, the described framework primarily focuses on individual practices, calls upon a specific (often scientific) issue, and insufficiently recognizes unknown unknowns.
This scheme contradicts software engineering-oriented literature, where the main focus is on practices for coding in teams [@https://faculty.washington.edu/ajko/books/cooperative-software-development; @doi:10.1007/s10664-012-9205-0].
The only counterexample we found is the Code Clubs described by Hagan et al. [@doi:10.1371/journal.pcbi.1008119].
In their research group, members collectively engage in software development through code reviews, coding in pairs, and software engineering education through workshops or seminars [@doi:10.1371/journal.pcbi.1008119].
The authors of Code Clubs present tips on organizing meetings to receive the best support and learn new software-related concepts.
Sharing coding experiences with others helps minimize isolation, allows individuals to learn from their peers, and maintains standards for writing better-quality software.
Therefore, we also established a learning club called software quality seminars, regular code reviews, and a resource-sharing platform to foster team effort (**Figure 1**).
In the following sections, we illustrate the merit of developing a learning community that enables the adoption of good software engineering practices by reflecting on our own code production.

***Table 1:*** **Collection of recommendations for improving scientific software quality.** Some guidelines are vague, have a varied scope, and target different stakeholders. Therefore, finding individual responsibility and actionable points from the literature may be challenging.
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
            <td>Do not require superuser privileges for installation and usage</td>
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
            <td>Description of the software version used, its configurations, and parameters in publications</td>
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
            <td>Support for developer community for long-term maintenance (when applicable)</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.1109/MIC.2014.88]</td>
        </tr>
        <tr>
            <td>Financial support for software development and maintenance</td>
            <td>[@doi:10.5281/zenodo.1172970; @doi:10.1109/MIC.2014.88]</td>
        </tr>
    </tbody>
</table> 




## Coding in teams #

Beyond the brief mention of getting support in the guidelines for bioinformaticians, specialized literature examines how to organize team coding activities effectively.
Indeed, programming as a collective practice is a critical notion in software engineering.
Maximizing team cohesion while minimizing code coupling represents a central theme  [@{http://www.jstor.org/stable/40539129}].
From the code's perspective, the adoption of sound software design enforcing modularity and extensibility ensures the viability of a software project [@ISBN:0932633420].
Nevertheless, from a software development perspective, one should prefer team management practices centered around communication and collective governance [@ISBN:0932633420].

We generally understand management as performing specific tasks: planning, monitoring resources, and tracking progression [@{https://www.wrike.com/project-management-guide/faq/what-is-software-project-management/}].
Typically, a single individual, referred to as the "manager" of the project, takes on these functions.
In this context, manager is a role rather than a particular person's title.
In the specific context of academic computational projects, one rarely finds a strict division of labor when considering software project management.
Some tasks, such as risk assessment, budget, and time management, are discussed at the project's conception (e.g., during grant application) and thus decoupled from the actual software development phase.
The remaining management tasks would often fall on the developer(s).
Implicit decision-making is one of the critical challenges current bioinformatics projects face.

As agile is the primary recommendation for team management in these guidelines (**Table 1**), its relevance to academic settings is worth discussing.
Agile methodologies, which emphasize iterative development, regular feedback, and flexibility, could significantly improve the way teams handle the evolving demands and rapid changes typical in academic computational projects.
Through more team communication, one outstanding aim of agile is the aspiration for more autonomy in organizing the work of software developers.
Practices and methods aligned with agile prescriptions include planning a minimum viable product, documenting requirements, organizing stand-up meetings, defining and assigning tasks, pair programming, and code reviews.
Many of these practices do not require the manager's presence but assume a collegial work culture and standardized procedures.
The additional overhead in terms of time and resources needed when developing is offset by the benefits mentioned above regarding software resilience and improved team capabilities.

Incentivizing collective ownership and governance promotes the adoption of software engineering best practices among developers contributing to a software project [@doi:10.1016/j.infsof.2009.11.004].
Indeed, by aspiring to make any developer within the team interchangeable across the various ongoing tasks, we create the need for robust testing, comprehensive documentation, and coherence across the project's different parts @{http://www.jstor.org/stable/40539129}.
Furthermore, by exposing every developer to various tasks throughout the project development, one strengthens the knowledge and skill base of the team as a whole, as well as creates an improved mutual awareness of team member expertise.
This mutual awareness, the transactive memory system, is linked to increased team performance @doi:10.1177/1046496420967764.
These merits further improve the team's capacity to overcome technical challenges that will arise throughout the development process.

We do not believe that all the software engineering guidelines employed in the industry are necessarily relevant to producing scientific software in academia.
Indeed, the circumstances differ significantly, mainly due to the outcomes of research projects (papers, tools, protocols, etc.), and we need to credit the particular individual researchers for their career progression.
However, this should not prevent interactions between developers of distinct projects, as these interactions will ensure compliance with the rules and increase quality.
Our proposition of building a learning community centered on coding is our attempt to bridge the gap between the merits of coding in teams and the reality of individually credited projects in the academic setting.

In our research groups, we have implemented the environment in which we, as a group, learn about and implement the software quality practices discussed above.
We want to share this experience and propose how simple additions, such as weekly code review sessions or seminars, can improve the quality of collective or personal software.


## Our experience in improving development processes as a team ##

Our team (composed of members from several academic research groups) adopted improved software development practices by implementing three pillars: 1 - software quality seminars, 2 - code review sessions, and 3 - resource sharing.
We describe our experience and recommendations for implementing these pillars.

### Software quality seminars ###

Within the context of our software quality seminars, we have implemented a system for transferring knowledge among participants.
Such seminars substitute for a more formal computer science education, which most bioinformaticians lack [@doi:10.7717/peerj-cs.839].
Each seminar is structured to build a shared vocabulary among members to facilitate discussions on implementation details and code structures. 
These seminars include presentations and demonstrations covering basic concepts.
Beyond this, we also use this platform to introduce new techniques and showcase tools not limited to specific projects.
It helped in three ways: broadening our collective knowledge, serving as an opportunity to look at those more theoretical concepts in practice, and building a community by encouraging all members to present their topics of interest.
While preparing the lectures can represent a significant time investment, this effort is rewarded by the substantial knowledge gained from attending others' presentations.
Finally, the investment pays off in the long run since acquiring knowledge leads to greater efficiency and expertise in future projects.

### Code reviews ###

The benefits of code reviews have been reviewed [@doi:10.5334/jors.35; @doi:10.1371/journal.pcbi.1008119; @{https://logicmag.io/clouds/agile-and-the-long-crisis-of-software/}, @ISBN:9780201616224].
Some benefits, such as implementing consistent coding standards and detecting bugs/errors, are obvious.
In contrast, others represent less expected outcomes, such as diverse learning, fostering a positive environment, or enhancing efficiency.
Before a scheduled code review, the developer writes their code in a way that others will understand, which enforces improved code readability and structuring.
This expectation is largely self-inflicted as each person feels pressure to expose their weaknesses - even within a friendly environment.
During a code review session, the developer must clearly explain some aspects of their code (e.g., structure, algorithm implementation, or performance-related decisions).
We recommend that the developer decide the aspect of the code they want to focus on during these sessions.
While code review sessions generally focus on implementation details, they can trigger discussion on any aspect of the code, including user interface design, documentation, and architectural considerations.

The other participants may not be deeply familiar with the project addressed explicitly by the code, but they bring their complementary knowledge and viewpoint.
The feedback obtained can help fix existing or potential future issues, improve the implementation, and produce cleaner and more concise code.
Our experience indicates a broader adoption of theoretical aspects and good software engineering practices.
We highlighted these during code review sessions.
We found that the implicit soft peer pressure derived from these code review sessions successfully addressed most goals: standardization of practices, improved code quality, and enhanced software usability.

As a beneficial side effect, we observed an enhanced understanding of the members' projects that naturally resulted from scrutinizing the code.
It gave a deeper understanding of the underlying scientific questions and led to more insightful comments during subsequent group meetings.
Additionally, a hands-on analysis of everyone's code revealed the repetitiveness of certain coding elements across the projects.
To address this redundancy, we recommend implementing a system to share resources.

### Resource sharing ###

Resource sharing fundamentally involves ensuring that valuable resources are readily accessible to all participants.
We efficiently implemented resource sharing through two perspectives: external open-access resources (forums, repositories, packages, and libraries) and internal resources (including within-group tools).
The internal aspect is crucial as it fosters team contributions that enhance individual project development.
For instance, consider a shared repository containing various computational tools developed by group members.
These tools are universal and aligned with the group’s research questions.
For example, a module that performs a gene set enrichment analysis and summarizes the results can be incorporated into different pipelines without rewriting the code that applies particular packages.
A set of modules with standardized documentation and API becomes a toolkit available for reuse by all group members.
Furthermore, the group collectively develops and reviews the underlying codebase, enhancing utility and quality.

We believe these three pillars are the minimum requirement for achieving lasting improvement in software development within research teams.
Still, bioinformaticians of other groups should tailor the content and the frequency of these meetings to their specific needs.
As a concrete example, many regular attendees of our sessions have extensively implemented various software development methods discussed (such as object-oriented programming, user stories for documenting requirements and assumptions, using Jira for feature additions and bug reporting, and continuous integration with Git) while collaboratively working on the same codebase for the latest JASPAR database release [@doi:10.1093/nar/gkad1059].
Additionally, it is worth noting that this article was successfully written using Manubot, a tool based on continuous integration [@doi:10.1371/journal.pcbi.1007128].

In the following sections, we discuss how software quality seminars and code reviews helped with the examples of three specific software engineering notions: modularization, testing, and dependency management.

### Examples of improved development processes ###

From our experience, we observed that it might be challenging to adopt the listed practices.
Therefore, instead of providing rules, we aim to encourage a mindset of mastering software engineering through an iterative process.
We illustrate it by discussing our example concepts from different angles, levels, and formats in the software seminars and in practice at code reviews.
We share specific examples from our projects to highlight how these concepts changed how we produce software (**Supplementary Figures**).

#### Modularization ####

Modular design is one of the most common approaches for team programming, ensuring the maintainability and extensibility of a software product.
We understood from the guidelines and experiences of the team that moving from unstructured scripts to organized code with functions brings several benefits at a low cost.
Consequently, this topic was covered several times during our software quality seminars and code review sessions.

Specifically, we dedicated software quality seminars to the following topics to improve modularization (**Supplementary Table 2**): object-oriented programming, class diagrams and unified modeling language in general, design patterns, software architecture, Snakemake [@doi:10.12688/f1000research.29032.1], S4 objects, R package development, a case report from the organization of the JASPAR database project [@doi:10.1093/nar/gkad1059], and a review of the book titled The Pragmatic Programmer [@ISBN:9780135957059].
We understood that modularization can take form on many levels. On a small scale, it means naming and organizing parts of the code into functions.
Once a code grows, one can start refactoring into classes and focus on the coherence and coupling of the parts (**Supplementary Figure 1-2**).
When building a pipeline of scripts, one can identify coherent modules that would translate to rules in Snakemake [@doi:10.12688/f1000research.29032.1] (**Supplementary Figure 3-4**.)
Modularization means continuously monitoring the code, recognizing a code that grew too much, and re-structuring it into smaller parts.
It involves an understanding that the code is not a static entity but an ever-growing, ever-changing organism.

A recurring question is whether a script needs refactoring or can remain a prototype.
Taschuk and Wilson [@doi:10.1371/journal.pcbi.1005412] suggest a cut-off at which one reuses a script, shares it with others, or uses it to produce findings in a publication.
This definition would potentially include most code written by bioinformaticians.
Still, we should weigh the time spent on improving the scripts against the time required to deal with suboptimal code on a case-by-case basis.
With practice and exposure to a lot of code, modularization becomes the norm, which reduces the distance between a prototype and a refactored code.

#### Testing ####

As highlighted in the literature [@doi:10.48550/arXiv.1804.01954], testing is complex for scientific software.
However, it is a central concept in team programming, as test coverage increases trust and allows the safe addition of new features by any member.
We revisited testing multiple times in our session through discussion around debugging tools, how to write unit tests in Python (```pytest``` and ```unittest```) and R (```testthat```), the type of functions to test, and the automation of tests via continuous integration (e.g., GitHub Actions) (**Supplementary Table 2**).
The main challenge usually lies in viewing software testing as more than just validating the scientific features of the software on a small test dataset.
Similarly to modularization, a recurring question was when to start adding tests.
We view testing not as a form of quality control that acts as a sort of checkpoint but as part of an iterative development process.
Therefore, we advise testing early, departing from the mindset: "I will start tomorrow after implementing this new idea."
Peer reviews challenge the implementation, while code reviews provide an optimal platform to discuss tests.
One can view this aspect as a scientific endeavor when we envision the edge cases and discuss the properties of the biological question.

#### Dependency management ####

Given the large number of dependencies and the entire ecosystem of tools involved in scientific software development, managing these dependencies is crucial for ensuring the reproducibility of findings.
In a team setting, it is natural to create identical environments for all developers to ensure they can run the code identically. 
In the software quality seminars related to dependency management, we covered the following topics: container solutions [@{https://docs.docker.com/}; @{https://apptainer.org/}], R package development, and Anaconda [@{https://www.anaconda.com/}] (**Supplementary Table 2**).
We established a DockerHub account for our group [@{https://hub.docker.com/u/cbgr}] to share our custom containers (**Supplementary Figures**).
This resource enables easy installation of our Snakemake pipelines across different servers.

In sum, we view the implementation of software quality seminars, code reviews, and shared resources in the academic setting as critical tools to improve coding and to better trust the resulting scientific discoveries.
Nevertheless, we recognize that scientists can choose to implement all or any of them as independent activities.
We observed that even a single activity benefits the members' coding experience and the resulting code quality.
As good practices become routine, the required time investment will decrease, and the benefits will become more apparent.
Finally, the shared knowledge base and standards allow us to make new group members adopt good coding practices more quickly.

## Conclusions and Future Perspectives ##

As bioinformatics becomes a more and more software-heavy field, we believe a good direction is to collectively lower the barrier to adapting to new technologies.
Working in a team and following standards is not an option for large software projects that support many researchers and contribute to novel findings.
We argue that following good software quality practices and mimicking team structure also benefit small projects.
The overall performance increases when team members are familiar with each other and together build problem-solving routines through cumulative experience [@{http://www.jstor.org/stable/40539129}].
In a group, the knowledge of who knows what speeds up problem-solving [@doi:10.1177/1046496420967764]; time spent together, and social factors ease technical knowledge transfer [@{http://www.jstor.org/stable/40539129}].
Therefore, we motivate all group leaders with a computational component, be it small or not, to build an environment for their trainees to communicate and discuss software quality aspects.

We envision a future where scientific software for core applications is appreciated, reliable, and actively maintained.
All scientists would benefit from a strong backbone of software solutions that would support quick and efficient prototyping and the maturation of working solutions.
Unfortunately, we recognize that the lack of funding for software maintenance prevents achieving a level of software quality that would inspire confidence in the results [@doi:10.1109/MIC.2014.88].
Funding agencies, often through peer reviewers, emphasize "novelty" by enforcing new software development.
This focus can make it difficult to justify dedicating time to the maintenance of software or computational resources that offer limited scientific output, especially when considering journal publications as the only token of success.
As Alexander Szalay puts it, "the funding stops when researchers develop the software prototype" [@doi:10.1038/d41586-022-01901-x].
Researchers want to build on each other's findings and use published novel software as tools, but they might need to spend a significant amount of time adopting or maintaining that software [@doi:10.1371/journal.pcbi.1005412; @doi:10.1016/j.jss.2020.110848; @doi:10.1109/MIC.2014.88].
The scientific ecosystem would benefit from funding earmarked for maintenance and dedicating time to it in project proposals.
On a positive note, a few agencies, such as the Chan Zuckerberg Initiative Essential Open Source Software for Science fund @{https://chanzuckerberg.com/eoss/} and the Schmidt Futures through their Virtual Institute of Scientific Software [@doi:10.1038/d41586-022-01901-x], have recognized this missed opportunity. They are starting to address the lack of funding in this aspect.
The scientific community and funding agencies should welcome the efforts of maintaining original software and encourage its updates instead of the development of replacement software with the risk of remaining unmaintained.

To summarize, it is of utmost importance for the scientific community to recognize the limitations of the software it produces and to acknowledge the flaws in the coding process.
To harness the potential for substantial improvement, we recommend that scientific groups and institutions organize three pillar activities: software quality seminars, code review sessions, and the implementation of resource sharing.
These initiatives will engage members of research groups in one another’s projects, facilitating the practical exchange of knowledge and feedback on code and beyond.
Finally, we strongly advocate for sustainable funding to maintain existing scientific software and recognize software that adheres to best practices.

## Acknowledgements ##

The authors acknowledge the contributions made by all the participants of our code reviews and software quality seminars at the Centre for Molecular Medicine Norway (NCMM), University of Oslo, and the helpful feedback on an early version of the manuscript provided by Ine Bonthuis, Nolan Newman, and Romana Pop.
The authors were supported by funding from The Norwegian Research Council \[187615\], Helse Sør-Øst, and the University of Oslo through the Centre for Molecular Medicine Norway (NCMM) (to Mathelier and Kuijjer groups); the Norwegian Cancer Society \[197884, 245890\] (to Mathelier group), the Research Council of Norway \[288404\] (to Mathelier group), the Norwegian Research Council \[313932\] (to M.L.K.), the Norwegian Cancer Society \[214871, 273592\] (to M.L.K.), the European Union’s Horizon 2020 research and innovation program under the Marie Sklodowska-Curie grant agreement \[801133\] (to L.H.)


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

