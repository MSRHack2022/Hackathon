# MSR Virtual Hackathon 2022

Today, software is developed with the help of many supporting systems, which provide help for source code management, code review, issue tracking, synchronous or asynchronous interpersonal communication, continuous integration, and many other tasks. Many of these systems store a wealth of data about how software is being developed, allowing for detailed studies and exploration tools that could be used to better understand software development.

[GrimoireLab](https://chaoss.github.io/grimoirelab/) is a toolset designed to help retrieve, analyze, and visualize such data. It has components for gathering data from about 30 different software development supporting systems, and enriching, analyzing, and visualizing it, including modules for identity management. GrimoireLab is mainly written in Python, available for use as [Python packages][https://pypi.org/project/grimoirelab/] or with [docker-compose](https://github.com/chaoss/grimoirelab#using-docker-compose). There is also some documentation: a [paper](https://peerj.com/articles/cs-601/), a [tutorial](https://chaoss.github.io/grimoirelab-tutorial/), and detailed instructions in each of the [source code repositories](https://github.com/chaoss/grimoirelab#grimoirelab-components). To have a glimpse of the kind of analysis and visualizations that GrimoireLab provides out of the box, check the [CHAOSS GrimoireLab dashboard](https://chaoss.biterg.io) (GrimoireLab is a [CHAOSS](https://chaoss.community) project). A simplified version of the data in any collection of GitHub and GitLab repositories can also be obtained via [Cauldron.io](https://cauldron.io), which is powered by GrimorieLab.

Hackathons are effective ways to explore research and product ideas by teaming up with others on intense but limited in duration tasks. We propose a GrimoireLab online hackathon to explore problems and solutions in software development that require data collection from software development repositories. Examples for these are the analysis of developer activities in specific software projects, the study of the developers involved in building all the components of a certain system (including dependencies), the tracking of some parameters of all components in a [Software Bill of Materials](https://www.ntia.gov/SBOM), visualizing how people are joining and leaving a certain project, or how people from the many companies participating in a large project communicate with each other. All of these could be implemented as singular studies, or as generic tools for automatically performing a study, analysis, or visualization of any random project.

The GrimoireLab MSR Virtual Hackathon will provide activities typical of the in-person hackathon virtually. For example, defining research questions, forming teams, and scoping problems. Organizers will provide advice on the best ways to conduct data processing and improve performance. The hackathon will also provide the opportunity for participants to work with world-class researchers on relevant problems and research questions.

Please join if you are concerned about better understanding software development and building tools to help researchers and stakeholders better understand how specific software projects perform. Also, if you are interested in adding another tool to your toolbox, the hackathon may help you in your future research. In this hackathon, we will focus on the analysis of free, open source software (FOSS) projects providing free access to their development data, but results will be of potential interest to the industry at large, and of course, to the research community.

The descriptions of the projects selected by the PC will be published at the Hackathon track of [MSR’2022](https://conf.researchr.org/track/msr-2022/), and given publicity in the CHAOSS community.

Any topics related to conducting research, building tools, or improving infrastructure that supports software development, helps industry in their use of or production of software, or educational/training aspects related to work in the retrieval, analysis, or visualization of software development data are within the scope of the hackathon. For example:

* Applications that analyze software development communities and help to detect problems in the onboarding process, in the mentoring of new developers, in the resolution of conflicts, in the participation in processes such as code review or bug fixing.

* Applications that increase transparency by helping development communities to be self-aware of how they work together, where they have bottlenecks or underattended areas, or in general, process or communication problems.

* Applications that increase understanding of software supply chains and ecosystem: how and why they function and how to manage risks, especially as related to industry use of FOSS components.

* Any infrastructure work that does data fusion or data quality improvements beyond what is directly available from software development repositories.

* Visualizations of software development data, which helps better understand how large software development communities work, and identify patterns that could be linked with good practices or bad smells.

Participants in the hackathon should use GrimoireLab components, or data obtained with GrimoireLab (e.g., via Cauldron.io).

Key Dates

* The intent for participation (including potential project ideas) will be collected until October 18, 2021. The intent should be submitted via email to organizers (jesus.gonzalez.barahona@urjc.es, gregorio.robles@urjc.es, dizquierdo@bitergia.com, Maelick.Claes@oulu.fi)

* November 11: One day online training sessions, defining research questions, scoping problems, and team formation. People who did not submit any intent before this date can still join at this point. During the period of October 18 to November 11, the organizers will help the participants to formulate the ideas to prepare for project pitches presented on November 11.

* Over the period of November 11 - December 10: multiple “hacking” days that include dedicated hackathon times and checkpoints to share, assess each team’s progress, and provide support if necessary.

* December 10: team presentations to the PC. PC will provide feedback to the presenters on the originality of the idea, the potential impact of the proposed solution, and how to communicate the project ideas

* January 27: Submission of a description of the team projects (up to two pages) for the submission to the MSR2021 Hackathon track.

* February 28: Notification of the acceptance to MSR Hackathon Track published in the MSR proceedings. The PC will judge submissions based on the clarity of the description, the originality of the idea, the potential impact of the proposed solution, and the sophistication of the artifacts produced during the hackathon.

Organizers will provide support in the form of mentors that can help with technical issues. The hackathon will also provide the opportunity for participants to work with world-class researchers on relevant problems and research questions. In addition to its organizers and the program committee, the hackathon will be supported by [Bitergia](https://bitergia.com), the company leading the development of GrimoireLab, and CHAOSS, the community in which GrimoireLab is maintained.

A [dedicated HitHub repository](https://github.com/MSRHack2022/Hackathon) is provided with some information about the hackathon. Its issue tracker will be used as the preferred mechanism to answer questions and solve issues for the participants of MSR Hackathon. [Matrix](https://matrix.org/) (for example, via [Element](https://element.io/)) will be suggested as the main means of asynchronous communication during the hackathon between teams, mentors, and organizers, with a dedicated room maintained during the entire duration of the event. When needed, videoconferencing will be done via a dedicated [Teams](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software/) room.
