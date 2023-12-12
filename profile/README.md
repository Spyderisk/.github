# Welcome to the Spyderisk Open Project on GitHub

Here you will find all of the code that makes up
[Spyderisk](https://spyderisk.org), the automated risk assessment tool. The most important Spyderisk repositories for users are pinned
below, and are:

* Spyderisk System Modeller - the main Spyderisk application. This repository is for technical software developers. This app contains a mathematical model of the world (the "Domain Model") over which a user can graphically add the specifics of their particular use case (the "System Model"). Spyderisk then calculates the risk of various scenarios happening, for example, a large cloud service becoming unavailable following an electrical outage that affects a critical datacentre. The Spyderisk System Modeller can be provided as a hosted service, an example being the training installation available at spyderisk.org.
* Spyderisk System Modeller Deployment - This contains the tools which allow a more technical user (but not necessarily a software developer) to install System Modeller themselves, either on their own laptop or on cloud servers they own.
* Spyderisk Adaptor - For users who want to do automated risk assessment from their own [Python](https://python.org) code. A running instance of the Spyderisk application has APIs that the Spyderisk Adaptor can call. 

There are many other respositories here, varying from project administration tools to deeply technical code that operates on Domain Models.
