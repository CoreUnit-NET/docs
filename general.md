#### **rights and limitations**  
*This document and its intellectual property belong to CoreUnit.NET and more precisely [NobleMajo](https://github.com/noblemajo).*  
*The forwarding, use, modification or copying of individual sections is prohibited without the direct authorisation of NobleMajo.*

- [Docs](#docs)
- [Application](#application)
- [A cunet project](#a-cunet-project)
  - [About](#about)
  - [License](#license)
  - [Target user](#target-user)
  - [Goal](#goal)
  - [Thoughts](#thoughts)
  - [Tec](#tec)
  - [Data](#data)
  - [Steps](#steps)
  - [Future](#future)

# Docs
Cunet (aka CoreUnit.NET) uses this kind of markdown files for docs and project definitions.

# Application
The application consists of 5 parts:
1. [Google Forms *introduction*](https://forms.gle/Jo4hYGeW8ZCQRBES7)
2. Join the [cunet discord server](https://discord.com/invite/GJSbyJ5Jpe) and create a support ticket there. **Please** mention in the ticket that you would like to apply and that you have filled in the form. On the discord server you can also find some more infos about cunet.
3. Cunet project *definition* (see below)
4. Project *implementation* (see below)
5. Project *presentation & talk* (after our response)

You can choose from 4 simple example application projects: (or use a similar existing, see below)
- [cmd tool](./basic-cmd-tool.md)
- [discord bot](./basic-discord-bot.md)
- [web service](./basic-web-service.md)
- [docker compose stack](./basic-docker-compose-stack.md)

**Or** if you have an existing project, you can send a git repo link to instand.  
For your own git repo, please provide a `cunet` branch with a `project.md` using one of the 4 templates above!


# A cunet project
The following are some of the key points of a cunet project that define the purpose, benefits, structure, work steps and future of a project.
You will always find these points in a finished and ready cunet project definition.

If you want to define your own project, you don't always have to fill in all of them and you can also ask cunet developers for help.

Test and development eepos, service account/bot credentials and servers are provided by cunet.

## About
The main heading of a project document that is never "about": Always use the name of the project as heading.

Make notes for the following things:
- What is the benefit?
- Which technologies are used?
- Who is the target group?
- What problem is to be solved?

From the answers to the questions you can now put together a short/nice name or create an nice 3-6 letter acronym.

## License
The licence part of a project defines the licence framework under which the project should be created, developed and, if applicable, published.  
Cunet always licences as CoreUnit.NET or NobleMajo to keep created works in the network ecosystem and prevent stealing of ideas and work.

All participating cunet developers must always be listed as contributors and authors.  
No one is favoured here unless it is a sole development at the time.

## Target user
This defines the target group of the project.
here you first define who can/should use/host/provide the software itself.
In addition, it can be defined which platform users could have the already hosted software.
For example, cunet internal could be the provider and the platform users could be the developers or the mods of cunet.
Or the target group could be defined as cunet internal/external and enterprise companies.
Then the platform users could be, for example, cunet users, members and enterprise customers or platform users.

## Goal
Defines the goal and what is to be achieved.

Ask yourself the following questions to find your goal:
- What problem do you want to solve?
- Who will use it and how will it benefit them?
- How did you come up with the idea? What was your idea, problem, vision and benefit?

## Thoughts
Thoughts and reasons that explain certain decisions in your project.

If during the definition or the project duration someone asks why a problem should/would be solved in a certain way and this is not explained here, this can always be extended.

## Tec
Defines technical data such as frameworks used, programming interface, programming language, planned/used libraries and tools that help.

The planned runtime environment can also be defined, for example as a linux container, ubuntu server or modular system.

## Data
Like a glossary for certain project components.
Can contain data structures, existing or project-specific word definitions.

## Steps
Defines the rough steps required to achieve the goal.

These should be logical and build on each other.
The first steps should define the basic project structure.
the last steps should define the basic functionality without extras.

Extra features will be defined in the next future part.

## Future
Defines extra features based on the last step.

Future features are extra features that do not describe the basic functionality and extend the project.
