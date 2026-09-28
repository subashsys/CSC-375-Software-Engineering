# CSC375: Software Engineering
---

## Table of Contents

1. [Course Overview](#course-overview)
2. [Unit 1: Introduction to Software Engineering](#unit-1-introduction-to-software-engineering)
3. [Unit 2: Software Processes](#unit-2-software-processes)
4. [Unit 3: Agile Software Development](#unit-3-agile-software-development)
5. [Unit 4: Requirements Engineering](#unit-4-requirements-engineering)
6. [Unit 5: System Modeling](#unit-5-system-modeling)
7. [Unit 6: Architectural Design](#unit-6-architectural-design)
8. [Unit 7: Design and Implementation](#unit-7-design-and-implementation)
9. [Unit 8: Software Testing](#unit-8-software-testing)
10. [Unit 9: Software Evolution](#unit-9-software-evolution)
11. [Unit 10: Project Management](#unit-10-project-management)
12. [Unit 11: Software Quality Management](#unit-11-software-quality-management)
13. [Unit 12: Configuration Management](#unit-12-configuration-management)
14. [Glossary of Key Terms](#glossary-of-key-terms)
15. [Exam Preparation Tips](#exam-preparation-tips)
16. [Recommended Books and References](#recommended-books-and-references)

---

## Course Overview

**Definition:** Software Engineering (SE) is the systematic, disciplined and quantifiable application of engineering principles to the development, operation and maintenance of software.

| Item | Detail |
|---|---|
| Course Code | CSC375 |
| Course Title | Software Engineering |
| University | Tribhuvan University, Nepal |
| Program | BSc CSIT |
| Nature | Theory + Practical (project work) |
| Main Text | *Software Engineering* by Ian Sommerville |

### Course Objectives

**Definition:** Statements describing what a student should be able to do after completing the course.

- Understand how software is developed as an engineered product.
- Apply process models, requirements, design, testing and management techniques.
- Work in teams to plan and deliver a software project.

### Prerequisites

**Definition:** Knowledge a student should already have before taking a course.

- Programming (C / C++ / Java), Data Structures, Database Systems, basic Object-Oriented concepts.

---

## Unit 1: Introduction to Software Engineering

**Definition:** The foundation unit that explains what software is, why engineering discipline is needed, and the ethical and professional context of the field.

### 1.1 Software

**Definition:** Software is a collection of computer programs, associated data, and documentation (requirements, design, user manuals, test plans) that together perform a specific function.

#### 1.1.1 Software Characteristics

**Definition:** Properties that distinguish software from physical products.

- **Intangible:** Software is logical, not physical.
- **Engineered/developed, not manufactured:** Cost lies in design, not production.
- **Does not wear out:** It degrades through change, not physical aging.
- **Custom-built:** Most software is built for specific needs rather than assembled from standard parts.

#### 1.1.2 Software Product Types

- **Generic products:** *Definition:* Stand-alone systems produced by a company and sold to any customer (e.g., MS Word). The developer owns the specification.
- **Customized (bespoke) products:** *Definition:* Systems commissioned by a specific customer and developed for them (e.g., a bank's core system). The customer owns the specification.

#### 1.1.3 Software Categories

**Definition:** Groupings of software by application domain.

- System software, Application software, Engineering/scientific software, Embedded software, Web/mobile applications, Artificial intelligence software, Product-line software.

### 1.2 Software Engineering

**Definition:** An engineering discipline concerned with all aspects of software production, from early specification to maintenance after deployment.

#### 1.2.1 Importance of Software Engineering

**Definition:** The reasons the discipline exists: individuals and society rely on advanced software, and it is cheaper in the long run to use engineering methods than to write programs ad hoc.

#### 1.2.2 Software Crisis

**Definition:** The historical situation (1960s onward) in which projects ran over budget and schedule, were unreliable and hard to maintain, which motivated the birth of software engineering.

#### 1.2.3 Software Engineering vs Computer Science vs System Engineering

- **Computer science:** *Definition:* Theory and fundamentals of computation.
- **Software engineering:** *Definition:* Practical problems of producing software.
- **System engineering:** *Definition:* All aspects of developing complex systems including hardware, software and processes.

#### 1.2.4 Software Engineering Diversity

**Definition:** The wide range of application types (embedded, batch, entertainment, data collection, systems of systems) that require different engineering approaches.

#### 1.2.5 Fundamental Software Engineering Activities

- **Specification:** *Definition:* Defining what the system should do.
- **Development:** *Definition:* Designing and programming the system.
- **Validation:** *Definition:* Checking that the system is what the customer wants.
- **Evolution:** *Definition:* Changing the system in response to change.

#### 1.2.6 Attributes of Good Software

**Definition:** Non-functional qualities expected of a product beyond its features.

- **Maintainability:** Ease of changing for new needs.
- **Dependability and security:** Reliability, safety, and protection from malicious use.
- **Efficiency:** Responsible use of memory and processor time.
- **Acceptability:** Usable and compatible with the systems users already have.

### 1.3 Professional and Ethical Responsibility

**Definition:** The moral obligations of software engineers toward clients, employers, the public and the profession.

#### 1.3.1 Software Engineering Ethics

**Definition:** Principles guiding professional conduct such as confidentiality, competence, intellectual property rights and computer misuse avoidance.

#### 1.3.2 ACM/IEEE Code of Ethics

**Definition:** A joint code with eight principles: Public, Client and Employer, Product, Judgment, Management, Profession, Colleagues, and Self.

#### 1.3.3 Ethical Dilemmas

**Definition:** Situations where a professional must choose between conflicting values, e.g., disagreement with management over safety.

### 1.4 Case Studies

**Definition:** Real-world example systems used to illustrate concepts.

- **Embedded system:** Insulin pump control system.
- **Information system:** Patient records system (Mentcare).
- **Sensor-based/data collection system:** Wilderness weather station.
- **Learning environment:** iLearn digital learning system.

---

## Unit 2: Software Processes

**Definition:** A software process is a structured set of activities required to develop a software system.

### 2.1 Software Process Activities

#### 2.1.1 Software Specification

**Definition:** Establishing what services are required and the constraints on the system's operation and development (feasibility study, elicitation, specification, validation).

#### 2.1.2 Software Design and Implementation

**Definition:** Converting the specification into an executable system through design (structure) and implementation (programming).

#### 2.1.3 Software Validation

**Definition:** Verification and validation (V&V) to show a system conforms to its specification and meets customer expectations.

#### 2.1.4 Software Evolution

**Definition:** Modification of the system after delivery to respond to changing requirements.

### 2.2 Software Process Models

**Definition:** A simplified, abstract representation of a software process presenting one perspective.

#### 2.2.1 Plan-driven vs Agile Processes

- **Plan-driven:** *Definition:* All activities planned in advance and progress measured against the plan.
- **Agile:** *Definition:* Planning is incremental, so the process adapts easily to change.

#### 2.2.2 Waterfall Model

**Definition:** A linear sequential model in which each phase (requirements, design, implementation, testing, maintenance) must finish before the next starts.

- *Advantages:* Simple, well documented, easy to manage.
- *Disadvantages:* Inflexible to change; working software appears late.
- *Suitable for:* Well-understood requirements, safety-critical systems.

#### 2.2.3 Incremental Development

**Definition:** The system is developed and delivered in increments, each adding functionality.

- *Advantages:* Early delivery, easier to accommodate change, early customer feedback.
- *Disadvantages:* Process is less visible; structure degrades as increments are added.

#### 2.2.4 Integration and Configuration (Reuse-oriented)

**Definition:** Building systems by assembling existing components, COTS (commercial off-the-shelf) products and services.

#### 2.2.5 Prototyping

**Definition:** Creating an early, partial version of the system to elicit requirements and test design ideas.

- **Throwaway prototype:** Discarded after requirements are understood.
- **Evolutionary prototype:** Refined into the final system.

#### 2.2.6 Spiral Model

**Definition:** A risk-driven model presented as a spiral where each loop is a phase (objective setting, risk assessment and reduction, development and validation, planning).

#### 2.2.7 Rapid Application Development (RAD)

**Definition:** An incremental model emphasizing very short development cycles using component-based construction and parallel teams.

#### 2.2.8 Rational Unified Process (RUP)

**Definition:** A hybrid, iterative process framework with four phases: Inception, Elaboration, Construction and Transition.

#### 2.2.9 V-Model

**Definition:** An extension of the waterfall in which each development phase is paired with a corresponding testing phase.

### 2.3 Coping with Change

**Definition:** Techniques for handling the fact that change is inevitable in all large software projects.

#### 2.3.1 Change Avoidance

**Definition:** Activities that anticipate changes before rework is required, e.g., prototyping.

#### 2.3.2 Change Tolerance

**Definition:** Designing the process so that changes can be accommodated at relatively low cost, e.g., incremental delivery.

#### 2.3.3 Software Prototyping in Change Management

**Definition:** Using prototypes to check requirements and design early and reduce change costs.

#### 2.3.4 Incremental Delivery

**Definition:** Delivering some increments to customers and getting feedback while later increments are still being built.

### 2.4 Process Improvement

**Definition:** Understanding existing processes and changing them to improve product quality and reduce cost and time.

#### 2.4.1 Process Measurement and Analysis

**Definition:** Collecting data about the process and analyzing it to find weaknesses.

#### 2.4.2 Capability Maturity Model (CMM/CMMI)

**Definition:** A framework that rates organizational process maturity in five levels: Initial, Managed, Defined, Quantitatively Managed, and Optimizing.

---

## Unit 3: Agile Software Development

**Definition:** A family of iterative approaches that deliver working software rapidly through collaboration, small increments and responsiveness to change.

### 3.1 Agile Methods

**Definition:** Methods that focus the effort on the code rather than design, use iterative development, and aim to deliver working software quickly.

#### 3.1.1 Agile Manifesto

**Definition:** A 2001 statement valuing individuals and interactions over processes and tools; working software over comprehensive documentation; customer collaboration over contract negotiation; responding to change over following a plan.

#### 3.1.2 Agile Principles

**Definition:** Twelve guidelines including customer involvement, incremental delivery, people not process, embracing change, and maintaining simplicity.

### 3.2 Agile Development Techniques

#### 3.2.1 Extreme Programming (XP)

**Definition:** An agile method that pushes good practices to extreme levels, with very short releases and continuous testing.

- **Key practices:** Incremental planning, small releases, simple design, test-first development, refactoring, pair programming, collective ownership, continuous integration, sustainable pace, on-site customer.

#### 3.2.2 User Stories

**Definition:** Short descriptions of a feature written from the user's viewpoint ("As a ..., I want ..., so that ...").

#### 3.2.3 Refactoring

**Definition:** Improving the internal structure of code without changing its external behavior.

#### 3.2.4 Test-First Development

**Definition:** Writing automated tests before writing the code that makes them pass.

#### 3.2.5 Pair Programming

**Definition:** Two developers work together at one workstation, one coding and one reviewing.

### 3.3 Agile Project Management

#### 3.3.1 Scrum

**Definition:** An agile framework for managing iterative development in fixed-length sprints.

- **Roles:** *Product Owner* (defines backlog priorities), *Scrum Master* (facilitates process), *Development Team* (builds the product).
- **Artifacts:** *Product Backlog* (ordered list of requirements), *Sprint Backlog* (items chosen for a sprint), *Increment* (working product produced).
- **Events:** *Sprint* (1-4 week time-box), *Sprint Planning*, *Daily Scrum*, *Sprint Review*, *Sprint Retrospective*.

#### 3.3.2 Kanban

**Definition:** A visual workflow method that limits work in progress using a board of columns (To Do, Doing, Done).

### 3.4 Scaling Agile Methods

**Definition:** Applying agile ideas to large systems, large teams, and distributed development.

#### 3.4.1 Practical Problems with Agile

**Definition:** Issues such as contractual difficulties, maintainability, and difficulty with large or long-lived systems.

#### 3.4.2 Agile and Plan-driven Methods

**Definition:** Deciding on a balance depending on system size, type, lifetime, team distribution and regulations.

#### 3.4.3 Agile in Large Organizations

**Definition:** Scaling frameworks such as SAFe and LeSS used for multiple teams.

---

## Unit 4: Requirements Engineering

**Definition:** The process of establishing the services that a customer requires from a system and the constraints under which it operates and is developed.

### 4.1 Types of Requirements

#### 4.1.1 User Requirements

**Definition:** High-level statements, in natural language and diagrams, of what services the system is expected to provide to users.

#### 4.1.2 System Requirements

**Definition:** Detailed descriptions of the system's functions, services and operational constraints.

#### 4.1.3 Functional Requirements

**Definition:** Statements of services the system should provide, how it reacts to inputs, and how it behaves in particular situations.

#### 4.1.4 Non-functional Requirements

**Definition:** Constraints on services or functions such as performance, reliability, security, usability and standards.

- **Product requirements:** usability, efficiency, dependability, security.
- **Organizational requirements:** environmental, operational, development.
- **External requirements:** regulatory, ethical, legislative.

#### 4.1.5 Domain Requirements

**Definition:** Requirements that come from the application domain and reflect its characteristics.

### 4.2 Software Requirements Specification (SRS)

**Definition:** An official document that states precisely what the system developers should implement.

#### 4.2.1 Structure of an SRS (IEEE 830)

**Definition:** A standard layout: Introduction, Overall Description, Specific Requirements, Appendices, Index.

#### 4.2.2 Ways of Writing Requirements

- **Natural language:** Plain sentences, easy but ambiguous.
- **Structured natural language:** Forms/templates limiting freedom of the writer.
- **Graphical notations:** UML use case and sequence diagrams.
- **Mathematical specifications:** Formal notations, precise but hard for customers to read.

### 4.3 Requirements Engineering Processes

#### 4.3.1 Feasibility Study

**Definition:** A short study to decide whether the proposed system is worthwhile technically, economically and operationally.

#### 4.3.2 Requirements Elicitation and Analysis

**Definition:** Discovering requirements by interacting with stakeholders and studying documents and existing systems.

- **Interviews:** Closed and open conversations with stakeholders.
- **Ethnography:** Observing how people actually work.
- **Stories and scenarios:** Descriptive examples of system usage.
- **Use cases:** Identify actors and the interactions with the system.
- **Questionnaires and workshops (JAD):** Gathering input from many stakeholders.

#### 4.3.3 Requirements Validation

**Definition:** Checking that requirements actually define the system the customer wants.

- **Checks:** Validity, consistency, completeness, realism, verifiability.
- **Techniques:** Requirements reviews, prototyping, test-case generation.

#### 4.3.4 Requirements Management (Change)

**Definition:** Managing changing requirements during the requirements engineering process and system development, including traceability.

---

## Unit 5: System Modeling

**Definition:** The process of developing abstract models of a system, each presenting a different view or perspective, usually using UML.

### 5.1 Context Models

**Definition:** Models showing the operational context of a system and its boundary with other systems and its environment.

#### 5.1.1 System Boundaries

**Definition:** The line separating what is inside the system from what is outside.

#### 5.1.2 Data Flow Diagrams (DFD)

**Definition:** Diagrams showing processes, data stores, external entities and the flow of data between them (Level 0 context diagram, Level 1, Level 2).

### 5.2 Interaction Models

**Definition:** Models showing interactions between users and the system, or between components.

#### 5.2.1 Use Case Modeling

**Definition:** Describing discrete tasks in which an actor interacts with the system.

- **Actor:** External entity interacting with the system.
- **Use case:** A goal-oriented sequence of interactions.
- **Relationships:** include, extend, generalization.

#### 5.2.2 Sequence Diagrams

**Definition:** Diagrams showing the order of messages between objects/actors over time.

### 5.3 Structural Models

**Definition:** Models showing the organization of a system in terms of its components and their relationships.

#### 5.3.1 Class Diagrams

**Definition:** Diagrams showing classes with attributes and operations, and the associations between them.

- **Association, Aggregation, Composition, Generalization (inheritance), Dependency.**

#### 5.3.2 Generalization

**Definition:** Abstracting common features of classes into a superclass.

#### 5.3.3 Aggregation

**Definition:** A "has-a" relationship where a whole consists of parts that can exist independently.

### 5.4 Behavioral Models

**Definition:** Models showing the dynamic behavior of a system as it executes.

#### 5.4.1 Data-driven Modeling

**Definition:** Modeling that shows the sequence of actions in processing input data and generating output (activity diagrams, DFDs).

#### 5.4.2 Event-driven Modeling

**Definition:** Modeling that shows how a system responds to external and internal events (state machine diagrams).

#### 5.4.3 State Diagrams

**Definition:** Diagrams showing states of an object and transitions triggered by events.

### 5.5 Model-Driven Engineering (MDE)

**Definition:** An approach where models rather than programs are the principal outputs of development.

#### 5.5.1 Model-Driven Architecture (MDA)

**Definition:** An OMG approach using computation-independent (CIM), platform-independent (PIM) and platform-specific (PSM) models.

---

## Unit 6: Architectural Design

**Definition:** The design process of identifying the sub-systems making up a system and the framework for sub-system control and communication.

### 6.1 Architectural Design Decisions

**Definition:** Creative choices about system organization, distribution, styles, decomposition and non-functional requirements support.

### 6.2 Architectural Views

**Definition:** Different perspectives of the architecture.

- **Logical view:** key abstractions as objects/classes.
- **Process view:** run-time composition and interactions.
- **Development view:** decomposition for development.
- **Physical view:** hardware and distribution.
- **4+1 view model (Kruchten):** Adds scenarios (use cases) to tie the four views together.

### 6.3 Architectural Patterns

**Definition:** Stylized, reusable descriptions of good design practice, tested in different environments.

#### 6.3.1 Model-View-Controller (MVC)

**Definition:** Separates presentation and interaction from the data (model), with a controller mediating.

#### 6.3.2 Layered Architecture

**Definition:** Organizes the system into layers, each providing services to the layer above.

#### 6.3.3 Repository Architecture

**Definition:** All shared data is held in a central database accessed by all sub-systems.

#### 6.3.4 Client-Server Architecture

**Definition:** Functionality organized as services delivered by servers to clients over a network.

#### 6.3.5 Pipe and Filter Architecture

**Definition:** Processing is organized into filters that transform data, connected by pipes.

#### 6.3.6 Microservices and Service-Oriented Architecture

**Definition:** Building a system as small, independently deployable services communicating over a network.

### 6.4 Application Architectures

**Definition:** Generic architectures for common application types.

- **Transaction processing systems**, **Information systems**, **Language processing systems**, **Data processing systems.**

---

## Unit 7: Design and Implementation

**Definition:** The stage where an executable software system is developed, involving detailed design and programming.

### 7.1 Object-Oriented Design Using UML

**Definition:** Designing a system as interacting objects using UML models.

#### 7.1.1 System Context and Interactions

**Definition:** Defining the boundary and how the system communicates with its environment.

#### 7.1.2 Architectural Design

**Definition:** Identifying major components and their interactions.

#### 7.1.3 Object Class Identification

**Definition:** Finding the objects and classes from the problem description (noun/verb analysis).

#### 7.1.4 Design Models

**Definition:** Structural models (class, package) and dynamic models (sequence, state).

#### 7.1.5 Interface Specification

**Definition:** Precisely defining the operations and attributes an object exposes without revealing its implementation.

### 7.2 Design Patterns

**Definition:** A description of a solution to a common problem in a form that can be reused in different contexts.

- **Creational:** Singleton, Factory, Builder.
- **Structural:** Adapter, Facade, Decorator.
- **Behavioral:** Observer, Strategy, Iterator.

### 7.3 Implementation Issues

#### 7.3.1 Reuse

**Definition:** Using existing software components, frameworks or systems instead of writing new code.

- **Levels:** abstraction, object, component, system.

#### 7.3.2 Configuration Management (in implementation)

**Definition:** Controlling changes to source code and other artifacts during development.

#### 7.3.3 Host-Target Development

**Definition:** Developing on one computer (host) and running on a different one (target), typical for embedded systems.

### 7.4 Open Source Development

**Definition:** Making a software's source code public and allowing volunteers to participate.

#### 7.4.1 Open Source Licensing

**Definition:** Legal terms governing use and distribution, such as GPL, LGPL, BSD and MIT.

---

## Unit 8: Software Testing

**Definition:** The process of executing a program with the intent of finding errors and verifying that it meets its requirements.

### 8.1 Verification and Validation (V&V)

- **Verification:** *Definition:* "Are we building the product right?" (conformance to specification).
- **Validation:** *Definition:* "Are we building the right product?" (meets user needs).

### 8.2 Testing Stages

#### 8.2.1 Development Testing

**Definition:** Testing carried out by the development team during development.

- **Unit testing:** Testing individual functions, methods or classes.
- **Component testing:** Testing interfaces between integrated units.
- **System testing:** Testing the integrated system as a whole.

#### 8.2.2 Release Testing

**Definition:** Testing a particular release by a separate team to check it is ready for customers.

- **Requirements-based testing**, **Scenario testing**, **Performance testing.**

#### 8.2.3 User Testing

**Definition:** Users test the system in their own environment.

- **Alpha testing:** By selected users working with developers.
- **Beta testing:** Release to a wider set of users for feedback.
- **Acceptance testing:** Customer decides whether to accept the system.

### 8.3 Testing Techniques

#### 8.3.1 Black-Box Testing

**Definition:** Testing based on inputs and outputs without knowledge of internal code.

- **Equivalence partitioning:** Dividing inputs into classes expected to behave alike.
- **Boundary value analysis:** Testing at the edges of input classes.

#### 8.3.2 White-Box (Structural) Testing

**Definition:** Testing based on the internal logic of the code.

- **Statement, branch, path coverage; Basis path testing; Cyclomatic complexity** (V(G) = E - N + 2).

#### 8.3.3 Gray-Box Testing

**Definition:** A mix of black-box and white-box with partial knowledge of internals.

#### 8.3.4 Regression Testing

**Definition:** Re-running tests after changes to make sure existing features still work.

### 8.4 Test-Driven Development (TDD)

**Definition:** A cycle of writing a failing test, writing code to pass it, then refactoring (Red-Green-Refactor).

### 8.5 Integration Testing Approaches

**Definition:** Combining modules and testing their interfaces.

- **Top-down**, **Bottom-up**, **Big-bang**, **Sandwich**, using stubs and drivers.

### 8.6 Testing Documentation

- **Test case:** *Definition:* A set of inputs, execution conditions and expected results.
- **Test plan:** *Definition:* A document describing scope, approach, resources and schedule.
- **Test oracle:** *Definition:* A mechanism to determine expected results.

### 8.7 Debugging

**Definition:** The process of locating and correcting the cause of a defect found by testing.

---

## Unit 9: Software Evolution

**Definition:** The continuing process of changing software after delivery to keep it useful.

### 9.1 Evolution Processes

**Definition:** Activities from change proposal, impact analysis, release planning, to change implementation and release.

### 9.2 Lehman's Laws

**Definition:** Observations about how large systems evolve, including continuing change, increasing complexity, and declining quality.

### 9.3 Legacy Systems

**Definition:** Older systems still in use that are critical but built with outdated technology.

#### 9.3.1 Legacy System Management

**Definition:** Deciding whether to scrap, keep maintaining, re-engineer or replace.

### 9.4 Software Maintenance

**Definition:** Modifying a program after it has been put into use.

- **Corrective:** fixing bugs.
- **Adaptive:** adapting to new environments.
- **Perfective:** adding or improving features.
- **Preventive:** improving maintainability to prevent future problems.

#### 9.4.1 Maintenance Prediction

**Definition:** Estimating which parts will change and cost.

### 9.5 Re-engineering and Refactoring

- **Software re-engineering:** *Definition:* Restructuring or rewriting part or all of a legacy system without changing its functionality.
- **Reverse engineering:** *Definition:* Analyzing software to extract design and specification.
- **Architectural transformation:** *Definition:* Changing the architecture of a system.

---

## Unit 10: Project Management

**Definition:** Ensuring the software is delivered on time, within budget and to the required standard.

### 10.1 Risk Management

**Definition:** Identifying risks, assessing their impact, and planning to minimize them.

- **Risk identification**, **Risk analysis**, **Risk planning**, **Risk monitoring.**
- **Types:** Project, product and business risks.

### 10.2 Managing People

**Definition:** Motivating and organizing people to work effectively.

- **Motivation:** Basic needs, personal, social needs (Maslow).
- **Personality types:** Task-oriented, self-oriented, interaction-oriented.

### 10.3 Teamwork

**Definition:** Cooperation of group members toward common goals.

- **Group composition**, **Group cohesiveness**, **Group communications**, **Group organization.**

### 10.4 Project Planning

**Definition:** Breaking work into parts and assigning them to team members.

- **Project scheduling:** Task breakdown (WBS), Gantt charts, PERT/CPM networks.
- **Plan-driven planning and agile planning.**

### 10.5 Software Cost Estimation

**Definition:** Predicting the effort, time and cost required for a project.

#### 10.5.1 Function Point Analysis

**Definition:** Estimating size by counting inputs, outputs, inquiries, files and interfaces.

#### 10.5.2 COCOMO Model

**Definition:** Constructive Cost Model by Barry Boehm estimating effort from lines of code.

- **Basic COCOMO:** Effort = a(KLOC)^b person-months; Time = c(Effort)^d.
- **Modes:** Organic (a=2.4, b=1.05), Semi-detached (a=3.0, b=1.12), Embedded (a=3.6, b=1.20).
- **Intermediate and Detailed COCOMO; COCOMO II.**

#### 10.5.3 Algorithmic and Expert Judgement Estimation

**Definition:** Formula-based estimation versus estimation based on experience.

#### 10.5.4 Estimation Techniques

**Definition:** Delphi technique, analogy-based estimation, use case points, and story points.

---

## Unit 11: Software Quality Management

**Definition:** Ensuring that software meets its required level of quality through processes and standards.

### 11.1 Software Quality

**Definition:** The degree to which software meets specified requirements and user expectations.

- **McCall's and ISO 9126 / ISO 25010 quality models:** Functionality, reliability, usability, efficiency, maintainability, portability.

### 11.2 Quality Assurance and Standards

- **Quality assurance (QA):** *Definition:* Process-oriented activities that establish quality standards and procedures.
- **Quality control (QC):** *Definition:* Product-oriented activities that check that standards are followed.
- **Standards:** ISO 9001, IEEE standards, CMMI.

### 11.3 Reviews and Inspections

**Definition:** Groups examine software or documentation to find problems.

- **Walkthrough**, **Inspection (Fagan)**, **Peer review.**

### 11.4 Software Measurement and Metrics

**Definition:** Quantitative assessment of software attributes.

- **Product metrics:** size, complexity, coupling and cohesion.
- **Process metrics:** defect density, effort, productivity.
- **Coupling:** Degree of interdependence between modules.
- **Cohesion:** Degree to which elements of a module belong together.

### 11.5 Software Reliability

**Definition:** The probability of failure-free operation over a specified time in a given environment.

- **Metrics:** MTTF, MTBF, MTTR, POFOD, ROCOF, Availability.

---

## Unit 12: Configuration Management

**Definition:** The management of changing software systems so that changes are controlled and the integrity of the product is maintained.

### 12.1 Configuration Items and Baselines

- **Configuration item (CI):** *Definition:* Any work product placed under change control.
- **Baseline:** *Definition:* A formally approved version of a configuration item.

### 12.2 Version Management

**Definition:** Keeping track of different versions of components using tools such as Git, SVN.

### 12.3 System Building

**Definition:** Assembling program components, data and libraries and compiling them to create an executable system.

### 12.4 Change Management

**Definition:** A process to record, analyze, approve and implement change requests.

### 12.5 Release Management

**Definition:** Preparing and distributing a system release to customers.

### 12.6 Continuous Integration and Delivery (CI/CD)

**Definition:** Frequently merging code into a shared repository, with automated build and test, and delivering to production.

---

## Glossary of Key Terms

| Term | Definition |
|---|---|
| Abstraction | Hiding detail to focus on essential features. |
| Artifact | Any work product created during development. |
| Baseline | Approved reference version of an item. |
| Cohesion | Strength of relationship within a module. |
| Coupling | Interdependence among modules. |
| Defect | A flaw in a component that may cause failure. |
| Error | A human mistake that produces a defect. |
| Failure | Deviation of the system from expected behavior. |
| Fault | Same as a defect in the code. |
| Modularity | Dividing a system into separate components. |
| Refactoring | Restructuring code without changing behavior. |
| Stakeholder | Anyone affected by or interested in the system. |
| Traceability | Ability to follow a requirement through the life cycle. |
| UML | Unified Modeling Language for visual modeling. |

---

## Exam Preparation Tips

- Learn definitions and diagrams (process models, UML) since they are commonly asked.
- Practice numerical questions on COCOMO, cyclomatic complexity and function points.
- Compare models (waterfall vs agile, black-box vs white-box) in tables.
- Prepare a short case study answer using the insulin pump and Mentcare examples.
- Solve past TU question papers for the pattern (Group A short answers, Group B long answers, Group C detailed answers).

---

