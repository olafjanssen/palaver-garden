# Initial Project Plan

## Assignment
### Context
After the release of OpenAI's [[GPT-3]] in 2020, there has been a surge in student assignments on working with large Natural Language Generating (NLG) models. These are external internship and graduation projects at small and medium-sized enterprises (SMEs) but also for projects for internal Centres of Expertise (CoEs).

### Goal of the project
Natural language processing and generation can be used in a wide range of applications, such as robot-human interaction, computer aided design, e-healthcare, text analysis, virtual assistants, copywriting and even to assist in programming tasks. While these applications differ in their goals and execution, they share a lot of common knowledge and decisions that need to be made.

The goal of this project is to create an living knowledge base, from now on referred to as a [[digital garden]], combining information about the state and trends in the field of NLG with a collection of ideas and considerations for further research with partners.

Ideally, this digital garden allows anyone that enters to jumpstart their own project, find inspiration and notest to take into consideration, and serves as meeting ground for exchanging new ideas.

Instead of applying NLP/NLG in a project in hindsight or from the perspective of a researcher in a particular non-NLP related field, the digital garden and its tenders can act as consultants to these research groups. In addition, new research proposals can benefit or be based on the ideas and knowledge from this digital garden.

### Scope and preconditions
The digital garden has a specific focus on:
* bringing together NLG related ideas, concepts, and projects within Fontys ICT
* collect best practices, tools and methods
* jumpstart new projects or jump-augment existing ones

It is therefore **not**:
* an exhaustive overview of all possible topics within the field of NLP and NLG
* an exhaustive technical explanation on how the models work
* a collection of technical tutorials on using the language models
* a portfolio site of interesting projects

In addition, to jumpstart small-scale experiments and prototypes a technical base platform will be build.

### Strategy
Creating a digital garden of knowledge is not a goal in itself, but:
* a means to help combine knowledge and jumpstart new projects
* a by-product of exploring a technical prototype

We follow a [[design thinking]] approach to developing a technical prototype for using NLG models in a chatbot setting. Defining the exact use case of this prototype is part of the design thinking process. The related research questions and brainstormed ideas and concepts are planted directly into the digital garden.

Parallel to working on a technical prototype, the current activities within the institute are inventorized and placed into the garden where it can feed both the currente technical prototype as projects that will follow.

### Research questions
The previous is summarized in the following design challenge.

> Design a *knowledge base* and *technical base platform* to enable *students and lecturer-researchers* working in projects that can benefit from using NLG to jumpstart their project and come into contact with stakeholders with the relevant experience.

While the design process for creating the technical prototype elicits its own set of research questions. The following questions are addressed at any rate because of its general nature:

* Which open NLG models are available and how do they compare to each other?
* What platforms are available to run and fine-tune NLG models?
* What are the ethics and responsibilities of a digital garden as a knowledge base?

### End products
Here is a list of intended end products:
* an open access web-based digital garden
* an NLG platform, including:
	* requirements analysis
	* architecture diagram

## Project organisation
### Stakeholders 

- *me* - project leader -  responsible for managing and working on the project
- lector AI - advisor, managing projects related to AI
- lector IXD - managing projects related to interaction design
- lector HTES - managing projects related to robots and sensor networks
- PLOU open learning - responsible for the open learning curiculum where students can take up a variety of projects
- all other PLOUs - where students could do NLG-related projects

Because of the open nature of the digital garden, personal names are left out unless explicit permission is given.

### Communication

No regular communication activities are planned as of yet.

### Activities and time plan

### Configuration management
Both the digital garden as the technical prototype will be under version control.

The digital garden uses a [public git repo](https://github.com/olafjanssen/palaver-garden) and is hosted as [palaver-garden.netlify.app](https://palaver-garden.netlify.app/).

The technical protoype will be an internal gitlab instance. Link will follow #todo.

Managing API keys for the different NLG providers deserves special attention.

### Finances and risk
There is budget for 20 weeks, one day a week. Additional budget for APIs can be requested.
