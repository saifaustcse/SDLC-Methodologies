# SDLC Methodologies

A concise guide to the **Software Development Life Cycle (SDLC)** and its core **methodologies**, explained with plain-language descriptions, use cases, and pros and cons.

## Table of Contents

| No. | Topic                                                                       |
| --- | --------------------------------------------------------------------------- |
| 1   | [What Is the SDLC?](#1-what-is-the-sdlc)                                    |
| 2   | [The Phases of the SDLC](#2-the-phases-of-the-sdlc)                         |
| 3   | [SDLC Methodologies: An Overview](#3-sdlc-methodologies-an-overview)        |
| 4   | [Waterfall Model](#4-waterfall-model)                                       |
| 5   | [V-Model](#5-v-model)                                                       |
| 6   | [Prototyping Model](#6-prototyping-model)                                   |
| 7   | [Spiral Model](#7-spiral-model)                                             |
| 8   | [Rapid Application Development (RAD)](#8-rapid-application-development-rad) |
| 9   | [Incremental Model](#9-incremental-model)                                   |
| 10  | [Iterative Model](#10-iterative-model)                                      |
| 11  | [Agile Model](#11-agile-model)                                              |
| 12  | [Comparison of SDLC Methodologies](#12-comparison-of-sdlc-methodologies)    |
| 13  | [Selecting the Right Methodology](#13-selecting-the-right-methodology)      |
| 14  | [References](#14-references)                                                |

## 1. What Is the SDLC?

> **The Software Development Life Cycle (SDLC) is a methodology with clearly defined processes for creating high-quality software.**

## 2. The Phases of the SDLC

The SDLC consists of the following phases of software development:

<p align="center">
    <img src="images/sdlc.png" alt="Phases of SDLC" width="600" height="500">
</p>

**Phase 1 – Analysis/Planning**

The planning stage is the most important phase of the entire SDLC from the perspective of project managers and stakeholders. It is performed by the senior members of the team with inputs from the customer, sales, market surveys and domain experts.

It consists of three sub-phases:

- **Requirement Analysis** – defines how the software will be used, the data it takes in and produces, and who will use it.
- **Feasibility Study** – evaluates the project's economic, legal, operational, technical and schedule feasibility, so that executives can decide whether to proceed.
- **Defining Requirements** – documents and gets approval for the product requirements in an SRS (Software Requirements Specification) document.

**Phase 2 – Design**

This phase translates the SRS into a system architecture. Based on the SRS, one or more design approaches are proposed and documented in a DDS (Design Document Specification). The DDS is reviewed by all important stakeholders, and the best design is selected based on risk, robustness, modularity, budget and time constraints. The chosen design defines all architectural modules along with their communication and data flow with external and third-party modules (if any).

**Phase 3 – Development/Implementation**

In this phase the actual development starts and the product is built. Code is generated and the database is designed as per the DDS. Developers follow the coding guidelines defined by their organization, using tools such as compilers, interpreters and debuggers.

**Phase 4 – Testing/Quality Assurance**

In this phase, systems integration and system testing are carried out by a Quality Assurance (QA) professional to determine whether the proposed design meets the initial set of business goals. Testing is repeated to check for errors, bugs and interoperability, and continues until the end user finds it acceptable. Functional testing (acceptance, integration, system and unit) as well as non-functional testing are carried out.

**Phase 5 – Deployment/Release**

This phase follows successful testing and delivers the software to the end user or installs it onto the customer's system(s). Once the product is delivered, beta testing begins and all bugs and enhancements are reported to the development team. Once the changes are complete, the final deployment takes place.

**Phase 6 – Maintenance**

The final phase involves maintenance and regular updates. End users can fine-tune the system to boost performance, add new capabilities or meet additional user requirements.

**[⬆ Back to Top](#table-of-contents)**

## 3. SDLC Methodologies: An Overview

```
SDLC Approaches
│
├── Predictive / Plan-Driven
│   ├── Waterfall
│   └── V-Model
│
├── Evolutionary / Iterative
│   ├── Prototyping
│   ├── Spiral
│   └── RAD
│
├── Iterative & Incremental
│   ├── Incremental
│   └── Iterative
│
└── Agile
    ├── Scrum
    ├── Kanban
    ├── Extreme Programming (XP)
    ├── Lean
    ├── Crystal
    ├── Feature-Driven Development (FDD)
    └── DSDM
```

## 4. Waterfall Model

> **Waterfall is a sequential and linear flow for developing a software application.**

The project moves through a series of finite stages, and each stage must be fully completed before the next one begins.

<p align="center">
    <img src="images/waterfall.png" alt="Waterfall Model" width="800" height="450">
</p>

**Use cases:**

- Requirements are very well known, clear and fixed, with no ambiguity
- The technology stack is predefined
- The project is small or mid-sized

**Pros:**

- Each stage is clearly defined
- Process and results are well documented
- Simple, easy to understand and manage

**Cons:**

- Cannot accommodate changing requirements
- Later-stage requirement changes are costly, as all phases are affected
- No working software is produced until late in the life cycle
- Progress is hard to measure while a stage is still in development

**[⬆ Back to Top](#table-of-contents)**

## 5. V-Model

> **The V-Shaped model expands the classic Waterfall model by pairing each development activity with a testing phase. It is also known as the Verification and Validation (V) model.**

The V-Model places Verification phases on one side and Validation phases on the other, joined by the coding phase at the bottom to form a V-shape.

<p align="center">
    <img src="images/v-model.png" alt="V-Shaped Model" width="800" height="450">
</p>

**Verification:** A static analysis method (review) done without executing code. It evaluates the development process to check whether the specified requirements are met.

**Validation:** A dynamic analysis method (functional and non-functional) done by executing code. It evaluates the completed software to check whether it meets the customer's expectations and requirements.

<details>
<summary><b>V-Model – Verification Phases</b></summary>

1. **Business Requirement Analysis:** The first step, where product requirements are understood from the customer's side through detailed communication to capture their expectations.
2. **System Design:** System engineers analyze and interpret the business requirements by studying the user requirements document.
3. **Architecture Design:** The architecture covers the list of modules, their functionality, interface relationships, dependencies, database tables, diagrams and technology details. Integration testing is planned during this phase.
4. **Module Design:** The system is broken down into small modules, and the detailed Low-Level Design of each module is specified.
5. **Coding Phase:** A suitable programming language is decided based on the requirements, following the organization's coding guidelines and standards. The final build is optimized for performance and passes through code reviews.

</details>

<details>
<summary><b>V-Model – Validation Phases</b></summary>

1. **Unit Testing:** Unit test plans developed during the module design phase are executed to eliminate bugs at the code or unit level.
2. **Integration Testing:** After unit testing, integrated modules are tested to verify their communication with each other.
3. **System Testing:** The complete application is tested for functionality, interdependency and communication, covering functional and non-functional requirements.
4. **User Acceptance Testing (UAT):** Performed in a user environment resembling production, UAT verifies that the delivered system meets the user's requirements and is ready for the real world.

</details>

**Use cases:**

- Requirements are well known, clear, fixed and precisely documented
- Accurate product testing is required

**Pros:**

- Each stage is clearly defined and well documented
- Defects are found early through proactive defect tracking
- Testing and verification occur early, leading to a high-quality product
- Enables project management to track progress accurately

**Cons:**

- Cannot accommodate changing requirements
- Even more rigid and less flexible than Waterfall
- Requirement and test documents must be updated for any mid-development change
- No working software is produced until late in the life cycle
- Not a good fit for large, complex or object-oriented projects

**[⬆ Back to Top](#table-of-contents)**

## 6. Prototyping Model

> **A prototype is built, tested and reworked iteratively until it is accepted by the customer.**

Customer feedback and refined requirements are used to modify the prototype, which is then re-presented for evaluation. Once approved, the prototype serves as the requirements for building the actual software using the Waterfall approach.

<p align="center">
    <img src="images/prototype.png" alt="Prototype Model" width="800" height="450">
</p>

**Use cases:**

- Requirements are incomplete or unclear
- Early customer feedback on the requirements is needed

**Pros:**

- Adaptive — easily accommodates updates and new requirements
- Prototypes can be changed or even discarded
- Increases user involvement before implementation
- Mitigates or eliminates risks before the actual product is built
- Quicker client feedback leads to better solutions
- Identifies complex or difficult functions early

**Cons:**

- Time-consuming and comparatively costly
- Prototype effort may be wasted, as it is ultimately thrown away
- Poor documentation, since customer requirements are insufficient
- May encourage excessive change requests and requirement variations
- Customers may confuse the prototype with the actual system or expect early delivery
- Developers may rush prototypes or reuse them for the final system when not feasible

**[⬆ Back to Top](#table-of-contents)**

## 7. Spiral Model

> **An evolutionary model combining the Iterative and Prototyping models with the systematic, controlled aspects of Waterfall, placing very high emphasis on risk analysis.**

Each loop of the spiral is a phase that allows incremental releases of the product through each iteration around the spiral.

<p align="center">
    <img src="images/spiral.png" alt="Spiral Model" width="800" height="400">
</p>

Each phase of the Spiral Model is divided into four quadrants:

1. **Determine objectives, alternatives and constraints:** Requirements are gathered, objectives identified, constraints evaluated and alternative solutions proposed.
2. **Evaluate alternatives, identify and resolve risks:** Solutions are evaluated and the best one is selected. Its risks are identified and resolved, and a prototype is built for the chosen solution.
3. **Develop and verify the next level of the project:** Features are developed and verified through testing, producing the next version of the software.
4. **Review and plan the next phase:** Customers evaluate the developed version, and planning for the next phase begins.

**Use cases:**

- Requirements are unclear or complicated and need continuous clarification
- Frequent releases of modules are required
- Customer evaluation and feedback are required in each increment
- Significant changes are expected during the development cycle
- Continuous risk evaluation is needed, especially for large and complex projects

**Pros:**

- Requirement changes are easily adopted, even at later stages
- Requirements are captured more accurately through customer feedback
- Risk analysis in every phase mitigates the chances of breakages
- Users see the system early, and features are added in a systematic way

**Cons:**

- Complex to understand, manage and implement
- Requires high risk-analysis expertise
- Number of iterations is unknown, so the end date remains uncertain
- Takes longer and is more expensive to develop
- High risk of falling behind schedule or going over budget
- Excessive documentation across the many intermediate stages

**[⬆ Back to Top](#table-of-contents)**

## 8. Rapid Application Development (RAD)

> **A concurrent process model based on the prototyping approach, used to complete software development in a very short time.**

The project is divided into small modules; each module is developed in parallel by a different party, and then all modules are combined into the final project.

<p align="center">
    <img src="images/rad.png" alt="RAD Model" width="800" height="400">
</p>

RAD consists of four basic phases:

1. **Requirement Analysis:** Planning and designing each module, using approaches such as brainstorming, task analysis, form analysis and user scenarios.
2. **Customer Evaluation:** Developers deliver the prototype and take customer reviews. If satisfied, implementation begins.
3. **Construction:** The prototype is refined, and all modifications, corrections and improvements convert the modules into the final working product.
4. **Cut Over:** All independent modules are evaluated separately. The tools and sub-parts of the product make testing very easy.

**Use cases:**

- Requirements are clearly specified and well known
- The system can be modularized and delivered incrementally within 2–3 months
- Technical risk is limited
- Designers, domain experts and a budget for automated code generation tools are available

**Pros:**

- Changing requirements can be accommodated at any time
- Development time and cost are drastically reduced
- Reviews are quick and customer feedback is encouraged
- Prototypes are delivered early, so the customer is satisfied
- Component reusability speeds up development
- Integration from the beginning solves many integration issues

**Cons:**

- Only systems that can be modularized can be built this way
- High dependency on modeling skills and strong technical teams
- Not suitable when technical risk is high
- Requires user involvement throughout the life cycle
- A slight complexity in modularizing can fail the entire project
- Not applicable to small-budget projects — modeling and automated code generation are expensive

**[⬆ Back to Top](#table-of-contents)**

## 9. Incremental Model

> **The incremental methodology is designed to overcome the shortcomings of the Waterfall methodology.**

The whole system is divided into various builds. Each build goes through the requirements, design, implementation and testing phases, and each subsequent release adds function to the previous one until the complete system is ready.

<p align="center">
    <img src="images/incremental.png" alt="Incremental Model" width="800" height="450">
</p>

**Use cases:**

- Requirements of the complete system are clearly defined and understood
- A functional module needs to reach the market early

**Pros:**

- Supports changing requirements at a lower cost
- Results are obtained early — an operational product is delivered with every increment
- Progress can be measured, and parallel development can be planned
- Testing and debugging each smaller iteration is easy
- Issues and risks from each increment are resolved in the next one

**Cons:**

- Needs a clear and complete definition of the whole system before it can be broken down
- Each iteration is rigid, and change costs remain higher than iterative approaches
- Requires more resources, skilled risk analysis and management attention

**[⬆ Back to Top](#table-of-contents)**

## 10. Iterative Model

> **An evolutionary approach in which the software is developed and delivered in small pieces, called iterations.**

Each iteration goes through its own planning, design, coding and testing phases and produces a working version of the software. This version is refined in the next iteration based on feedback until the complete system meets the requirements.

<p align="center">
    <img src="images/iterative.png" alt="Iterative Model" width="800" height="450">
</p>

**Use cases:**

- Requirements are not fully known at the start and are expected to evolve
- A working version of the product is needed early to gather customer feedback

**Pros:**

- Supports changing requirements
- A working version is delivered with every iteration
- Customer feedback from each iteration leads to better solutions
- Risks are identified early and resolved in the next iteration

**Cons:**

- Requires active customer involvement throughout the project
- Scope can keep expanding, delaying the final product
- More resources and management attention may be required

**[⬆ Back to Top](#table-of-contents)**

## 11. Agile Model

> **An iterative and incremental approach that delivers working software in small, frequent releases called sprints or iterations.**

Agile emphasizes collaboration, customer feedback and adaptability to change rather than a rigid, pre-planned process. Common Agile frameworks include Scrum, Kanban and Extreme Programming (XP).

<p align="center">
    <img src="images/agile.png" alt="Agile Model" width="500" height="500">
</p>

**Use cases:**

- Requirements are expected to change frequently
- The customer wants to see working software early and often
- Continuous feedback and collaboration are required
- Small to medium projects with cross-functional teams

**Pros:**

- Adapts quickly to changing requirements
- Delivers working software early and frequently
- Improves customer satisfaction through continuous feedback
- Reduces risk through regular testing and reviews
- Provides transparency through regular demos and stand-ups

**Cons:**

- Less emphasis on detailed documentation
- Requires active customer involvement throughout the project
- Difficult to estimate total cost and timeline up front
- Can be hard to manage for large, complex projects

**[⬆ Back to Top](#table-of-contents)**

## 12. Comparison of SDLC Methodologies

| Methodology     | Requirements   | Change      | Risk       | Delivery            | Best When                                     |
| --------------- | -------------- | ----------- | ---------- | ------------------- | --------------------------------------------- |
| **Waterfall**   | Fixed          | Low         | High       | End                 | Requirements are stable                       |
| **V-Model**     | Fixed          | Low         | Medium     | End                 | Testing and verification are critical         |
| **Prototyping** | Unclear        | High        | Medium     | Early prototype     | Requirements need validation                  |
| **Spiral**      | Evolving       | High        | High       | Iterative cycles    | Risk is the primary concern                   |
| **RAD**         | Flexible       | High        | Medium     | Very fast           | Speed is the priority                         |
| **Incremental** | Mostly defined | Medium–High | Low–Medium | Feature increments  | Features can be delivered independently       |
| **Iterative**   | Evolving       | High        | Medium     | Repeated refinement | The solution needs continuous refinement      |
| **Agile**       | Changing       | Very High   | Low        | Frequent increments | Requirements and priorities change frequently |

## 13. Selecting the Right Methodology

There is no single "best" methodology — the right choice depends on the project, its requirements, risks, constraints and delivery needs. Use the comparison table in Section 12 and the decision tree below to narrow down the options.

```
Requirements / Solution
│
├── Stable and well-defined
│   ├── Rigorous verification & validation → V-Model
│   └── Otherwise → Waterfall
│
├── Need to discover or refine the solution
│   ├── Need a prototype mainly to understand/validate requirements
│   │      └── Prototyping
│   │
│   ├── High technical/business risk
│   │      └── Spiral
│   │
│   └── Need short cycles, rapid construction,
│       reusable components, and frequent user feedback
│          └── RAD
│
├── Need to develop progressively
│   ├── Add functionality piece by piece → Incremental
│   ├── Repeatedly refine functionality → Iterative
│   └── Both → Iterative + Incremental
│
└── Requirements and priorities change continuously
    ├── Fixed-length iterations → Scrum
    ├── Continuous flow → Kanban
    ├── Engineering practices → XP
    ├── Waste reduction → Lean
    ├── Lightweight/team-focused → Crystal
    ├── Feature-driven → FDD
    └── Timeboxed/business-focused → DSDM
```

**[⬆ Back to Top](#table-of-contents)**

## 14. References

- [tutorialspoint](https://www.tutorialspoint.com/sdlc/index.htm)
- [tatvasoft](https://www.tatvasoft.com/blog/top-12-software-development-methodologies-and-its-advantages-disadvantages/)
- [scnsoft](https://www.scnsoft.com/blog/software-development-models)
- [visual-paradigm](https://www.visual-paradigm.com/guide/software-development-process/what-is-a-software-process-model/)
- [w3schools.in](https://www.w3schools.in/sdlc-tutorial/software-development-life-cycle-sdlc/)
- [melsatar](https://melsatar.blog/2012/03/21/choosing-the-right-software-development-life-cycle-model/)

**[⬆ Back to Top](#table-of-contents)**

## Author

**Md. Saiful Islam**
_A Software Engineer interested in Software Design & Architecture_

**GitHub:** [@saifaustcse](https://github.com/saifaustcse)
**LinkedIn:** [Md. Saiful Islam](https://www.linkedin.com/in/saif-aust-cse/)
