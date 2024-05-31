# Welcome to the Spyderisk Open Project on GitHub

Spyderisk exists because complex socio-technical computer systems are too vast
and intricate for any human to understand or predict. Society is rightly is
concerned about them, and we are addressing that concern.

The [Spyderisk Open Project Strategy](https://github.com/Spyderisk/system-modeller/blob/dev/docs/Spyderisk-Open-Project-Strategy.md) explains our aim:

> revolutionise understanding of the trustworthiness of socio-technical systems
> by establishing an international Open Community supporting the research,
> development, use and support of open, effective, and accessible risk
> assessment methods, knowledge and tools.

The Spyderisk Open Project started in 2023, building on
[15 years of history in risk assessment](https://github.com/Spyderisk/system-modeller/blob/dev/HISTORY.md).

All our work is published and maintained under open licenses - software
source code, ontologies, domain model database, online training, documentation,
and academic papers. The Spyderisk Open Project was founded by the University
of Southampton, England, but we welcome all collaborators and contributors. You
can contact us at [team@spyderisk.org](mailto://team@spyderisk.org).

## Who is Spyderisk for?

Spyderisk at present in 2024 is for people who are familiar with the field of risk
assessment, such as risk researchers, academics, ethicists or policymakers.

Focus areas of the Spyderisk Open Project are:

* the ethics of risk assessment
* ontologies of harm, risk and misbehaviour
* mathematical modelling of risk assessment
* software tools to calculate risk in models of complex systems

While the Spyderisk software is currently for the more technically-inclined,
as we make clear in our
[guide for Spyderisk System Modeller contributors](https://github.com/Spyderisk/system-modeller/blob/dev/CONTRIBUTING.md)
there is likely a way for anyone passionate about risk assessment to become involved.
Even explaining what risk assessment is about is a skill in itself,
and if you have that skill we would love to hear from you.

Our introductory online course 
[Cybersecurity Risk Assessment & Modelling: Core Priniciples](https://training.spyderisk.org/courses/course/view.php?id=2)
is a good place to start for those who are not already in the field of risk assessment. 

## What is Spyderisk?

Spyderisk is for assessing risk in complex socio-technical systems. By *complex systems* we
mean "systems of systems that humans are unable to fully understand, debug or
predict, typically socio-technical-physical systems." In other words, humans
build critical systems that are unknowable, and so we need to apply mathematics
to delineate the risks in these unknowable systems.

"Socio-technical" relates to the interconnectedness of the modern world.
*Social* aspects include legal and policy requirements and aspects of human
psychology while *technical* components include information technology networks
and machine learning/artificial intelligence. This also includes physical
systems such as handheld devices, train station information zones, and human
guards at country frontier checkpoints. Put together, these kinds of complex
systems decide our everyday privacy, the safety of our medical records, and
that airports function smoothly and safely.

The Spyderisk team has written many
[papers and reports related to risk assessment](https://github.com/Spyderisk/system-modeller/blob/dev/docs/papers/README.md),
including some of the first on ontological approaches to concepts such as biomedical burden
and cybersecurity aspects of systems composed of IoT systems. Spyderisk starts from an
[ontological approach](https://github.com/Spyderisk/system-modeller/blob/dev/docs/ontology.md)
although end users of the Spyderisk software do not require an understanding of ontology.

As of Mid-2024, the Spyderisk software is in early release, fully available but only working
in quite specific circumstances. To get a feel for what the software can do once it is running,
the course [Getting Hands on with Spyderisk](https://training.spyderisk.org/courses/course/view.php?id=3) explains
how to model systems using the Spyderisk software.

If you are a researcher in the area of risk modelling including ontologies of
risk, or if you have a specific problem domain you need to examine
(particularly in cybersecurity or privacy) then you are already part of our
community and Spyderisk could be for you. 

# The Spyderisk GitHub repositories

There are many repositories, of which the central four are:

* [Spyderisk System Modeller](https://github.com/Spyderisk/system-modeller) - the web service software, for people comfortable dealing with computer source code
* [Spyderisk System Modeller Deployment](https://github.com/Spyderisk/system-modeller-deployment/) - the tools which allow a user familiar with installing software to get Spyderisk running, either on their own laptop or on cloud servers they own.
* [Spyderisk Adaptor](https://github.com/Spyderisk/system-modeller-adaptor/) - for users of the [Python programming language](https://python.org) commonly used in science and academia, who want to do automated risk assessment using the Spyderisk reasoner but from their own code. A running instance of the Spyderisk application has APIs that the Spyderisk Adaptor calls.
* [Spyderisk Domain Network](https://github.com/Spyderisk/domain-network) - the most complete and advanced Spyderisk knowledgebase, describing a complex computing/IoT/cloud network in very general terms such as "server computer" or "database". Users of the Spyderisk software can then load in this model and use it as a palette for drawing their own real-world network in order to explore their particular risk profiles.

Other repositories vary from project administration tools to very specific
technical code that operates on Domain Models.

We look forward to seeing you around the risk assessment community.
