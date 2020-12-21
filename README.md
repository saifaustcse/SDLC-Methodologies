# Find me

> If you think that these can be improved in anyway, please do suggest. Pull Request are highly appreciated. Find me if you wish [@Saif(https://www.linkedin.com/in/saif-aust-cse/).

### Table of Contents

| No. | Topic                                                        |
| --- | ------------------------------------------------------------ |
| 1   | [What is SDLC?](#what-is-SDLC)                               |
| 2   | [What are the phases of SDLC?](#what-are-the-phases-of-SDLC) |
| 3   | [Top SDLC Methodologies?](#top-SDLC-methodologies)           |
| 4   | [Waterfall Model](#waterfall-model)                          |
| 5   | [V-Shaped Model](#v-shaped-model)                            |
| 6   | [Incremental Model](#incremental-model)                      |
| 7   | [Iterative Model](#iterative-model)                          |
| 8   | [Prototype Model](#prototype-model)                          |
| 9   | [RAD Model](#RAD-model)                                      |
| 10  | [Spiral Model](#spiral-model)                                |
| 11  | [References](#references)                                    |

## Details

1.  ### What is SDLC?

    The Software Development Life Cycle (SDLC) refers to a methodology with clearly defined processes for creating high-quality software.

    **[⬆ Back to Top](#table-of-contents)**

2.  ### What are the phases of SDLC?

    The SDLC methodology consists of the following phases of software development:

    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/raw/master/images/sdlc_1.png" width="600" height="500">
    <div>

    **Phase 1 – Analysis/Planning**

    The very first phase of the SDLC known as the planning stage. It is the most important phase of the entire SDLC from the perspective of project managers and stakeholders.
    It is performed by the senior members of the team with inputs from the customer, the sales department, market surveys and domain experts in the industry.
    Planning pahse can be divided in 3 sub pahses:

    **Sub Phase 1 – Requirement Analysis**

    -   How the software will be used?
    -   What data will serve as the input of the software?
    -   What data will be the output given by the software?
    -   Who is going to use the software?

    **Sub Phase 2 – Feasibility Study**

    In this phase, evaluate the requirements for feasibility. The goal is to quantify the opportunities and risk of addressing the agreed requirements with the variety of
    resources and strategies available to the organization. The feasibility study evaluates the following key aspects, among others:

    -   Economic: Is it financially viable to invest in the project based on the available resources?
    -   Legal: What is the scope of regulations and the organization’s capacity to guarantee compliance?
    -   Operational: Can we satisfy the requirements within scope definition according to the proposed operational framework and workflows?
    -   Technical: What is the availability of technology and HR resources to support the SLDC process?
    -   Schedule: Can we finish the project in time?
    -   Executive decision makers should answer and document these questions and study them carefully—before proceeding with the software design and implementation process.

    **Sub Phase 3 – Defining Requirements**

    Once the requirement analysis and feasibility study is done the next step is to clearly define and document the product requirements and get them approved
    from the customer or the market analysts. This is done through an SRS (Software Requirement Specification) document which consists of all the product requirements
    to be designed and developed during the project life cycle.

    **Phase 2 – Design**

    This phase describes, in detail, the necessary specifications, features and operations that will satisfy the functional requirements of the proposed system
    which will be in place. This is the step for end users to discuss and determine their specific business information needs for the proposed system. It"s during
    this phase that they will consider the essential components (hardware and/or software) structure (networking capabilities), processing and procedures for the system
    to accomplish its objectives.

    SRS is the reference for product architects to come out with the best architecture for the product to be developed. Based on the requirements specified in SRS,
    usually more than one design approach for the product architecture is proposed and documented in a DDS - Design Document Specification.

    This DDS is reviewed by all the important stakeholders and based on various parameters as risk assessment, product robustness, design modularity, budget and time
    constraints, the best design approach is selected for the product.

    A design approach clearly defines all the architectural modules of the product along with its communication and data flow representation with the external and third party
    modules (if any). The internal design of all the modules of the proposed architecture should be clearly defined with the minutest of the details in DDS.

    **Phase 3 – Development/Implementation**

    In this phase of SDLC the actual development starts and the product is built. The programming code is generated and database is designed as per DDS during this stage.
    If the design is performed in a detailed and organized manner, code generation can be accomplished without much hassle.

    Developers must follow the coding guidelines defined by their organization and programming tools like compilers, interpreters, debuggers, etc. are used to generate the code. Different high level programming languages such as C, C++, Pascal, Java and PHP are used for coding and different types (structued and non structured) databases such as oracle, MSSQL, MySQL, MongoDb are used for dumping data.

    **Phase 4 – Testing/Quality Assurance**

    In this phase systems integration and system testing (of programs and procedures)—normally carried out by a Quality Assurance (QA) professional—to determine if the proposed design meets the initial set of business goals. Testing may be repeated, specifically to check for errors, bugs and interoperability. This testing will be performed until the end user finds it acceptable.

    During this phase of the SDLC, various types of functional testing, such as acceptance testing, integration testing, system testing, and unit testing, as well as the non-functional testing is carried out.

    **Phase 5 – Deployment/Release**

    This phase is carried out right after the successful testing of the software product. It is simply delivering the software to the end-user or installing it onto the customer’s system(s).
    The first thing that takes place once the product is delivered to the customer is beta testing. All the bugs and enhancements are then reported to the developer team working on the project afterward. Once all the changes are complete, the final deployment takes place.

    **Phase 6 – Maiantenance**

    The final phase involves maintenance and regular required updates. This step is when end users can fine-tune the system, if they wish, to boost performance, add new capabilities or meet additional user requirements

    **[⬆ Back to Top](#table-of-contents)**

3.  ### Top-SDLC-methodologies

    ![](https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/flow-chart.png)

    **[⬆ Back to Top](#table-of-contents)**

4.  ### Waterfall Model

    Waterfall is a sequential and linear flow for developing a software application. The process is outlined by a series of finite stages, each of which must be fully completed before moving on to the next one. The idea here is quite simple: develop one phase of the project completely and move on to the next. In this way, the project progresses and moves forward in a linear flow.

    <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/waterfall.jpg" width="800" height="450">
    <div>

    Use cases for the Waterfall model:

        * This model is used only when the requirements are very well known, clear and fixed
        * There are no ambiguous or undefined requirements
        * The requirements are precisely documented
        * The technologies stack is predefined which makes it not dynamic
        * The project is small or mid-sized

    Pros:

        * Each stage are clearly defined
        * Process and results are well documented
        * Simple and easy to understand and use
        * Easy to manage due to the rigidity of the model

    Cons:

        * Cannot accommodate changing requirements
        * Requirement change at the later stages would lead to cost higher as the changes would be required
          in all the phases
        * No working software module is produced until late during the life cycle
        * The progress of the stage is hard to measure while it is still in the development
        * Not suitable for the projects where requirements are at a moderate to high risk of changing

    **[⬆ Back to Top](#table-of-contents)**

5.  ### V-Shaped Model

    V-shaped SDLC model is an expansion of classic waterfall model where each development activity is associated with a testing phase. It is also known as Verification and Validation model.

     <div  style="text-align: center;">
            <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/v-model.png" width="800" height="450">
     <div>

    The V-Model contains Verification phases on one side of the Validation phases on the other side. Verification and Validation process is joined by coding phase in V-shape. Thus it is known as V-Model.

    **Verification:** It involves a static analysis method (review) done without executing code. It is the process of evaluation of the product development process to find whether specified requirements meet.

    **Validation:** It involves dynamic analysis method (functional, non-functional), testing is done by executing code. Validation is the process to classify the software after the completion of the development process to determine whether the software meets the customer expectations and requirements.

    **V-Model - Verification Phases:**

    1. **Business requirement analysis:** This is the first step where product requirements understood from the customer's side. This phase contains detailed communication to understand customer's expectations and exact requirements.

    2. **System Design:** In this stage system engineers analyze and interpret the business of the proposed system by studying the user requirements document.

    3. **Architecture Design:** The baseline in selecting the architecture is that it should understand all which typically consists of the list of modules, brief functionality of each module, their interface relationships, dependencies, database tables, architecture diagrams, technology detail, etc. The integration testing model is carried out in a particular phase.

    4. **Module Design:** In the module design phase, the system breaks down into small modules. The detailed design of the modules is specified, which is known as Low-Level Design.

    5. **Coding Phase:** After designing, the coding phase is started. Based on the requirements, a suitable programming language is decided. There are some guidelines and standards for coding. Before checking in the repository, the final build is optimized for better performance, and the code goes through many code reviews to check the performance.

    **V-Model - Validation Phases:**

    1. **Unit Testing:** Unit Test Plans are developed during module design phase. These Unit Test Plans are executed to eliminate bugs at code or unit level.

    2. **Integration testing:** After completion of unit testing Integration testing is performed. In integration testing, the modules are integrated and the system is tested. Integration testing is performed on the Architecture design phase. This test verifies the communication of modules among themselves.

    3. **System Testing:** System testing test the complete application with its functionality, inter dependency, and communication.It tests the functional and non-functional requirements of the developed application.

    4. **User Acceptance Testing (UAT):** UAT is performed in a user environment that resembles the production environment. UAT verifies that the delivered system meets user’s requirement and system is ready for use in real world.

    Use cases for the Waterfall model:

          * This model is used only when the requirements are very well known, clear and fixed
          * There are no ambiguous or undefined requirements
          * The requirements are precisely documented
          * The technologies stack is predefined which makes it not dynamic
          * The project is small or mid-sized
          * For the projects where an accurate product testing is required

    Pros:

          * Each stage are clearly defined
          * Process and results are well documented
          * Simple and easy to understand and use
          * Easy to manage due to the rigidity of the model
          * Proactive defect tracking – that is defects are found at early stage
          * Testing and verification take place in the early stages which leads to developing an error-free
            and good quality product
          * Higher success chances
          * Covers all functional areas
          * It enables project management to track progress accurately

    Cons:

          * Cannot accommodate changing requirements. Even more rigid and less flexible than
            the Waterfall model
          * Requirement change at the later stages would lead to cost higher as the changes would be required
            in all the phases
          * Requirement and test documents need to be updated if any changes had to be made amid the software
            development
          * No working software module is produced until late during the life cycle
          * The progress of the stage is hard to measure while it is still in the development
          * Not suitable for the projects where requirements are at a moderate to high risk of changing
          * Not a good model for large or complex and object-oriented projects

    **Similarities between Waterfall and V-model:**

     <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_vmodel_similarities.PNG" width="800" height="450">
    <div>

    **Differences between Waterfall and V-model:**

      <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_vmodel_differences.PNG" width="800" height="200">
    <div>

    **[⬆ Back to Top](#table-of-contents)**

6.  ### Incremental Model

    The iterative and incremental methodology is designed to overcome any fault or shortcoming of the Waterfall methodology.

    In this incremental model, the whole requirement is divided into various builds. During each iteration, the development module goes through the requirements, design, implementation and testing phases. Each subsequent release of the module adds function to the previous release. The process continues till the complete system is ready as per the requirement.

    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/incremental.png" width="800" height="450">
    <div>
     <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/incremental_.png" width="800" height="450">
    <div>

    Use cases for the Iterative and incremental model:

        * This model can be used when the requirements of the complete system are clearly defined
          and understood
        * There is a need to get a functinal module of the product to the market early

    Pros:

        * It supports changing requirements
        * Less costly to change the scope/requirements
        * Results are obtained early and periodically
        * With every increment, operational product is delivered
        * It delivers business value early in the development lifecycle
        * Progress can be measured
        * Parallel development can be planned
        * Testing and debugging during smaller iteration is easy
        * Customer evaluation and feedback is available in each increment which leading to better solutions
        * Issues, challenges and risks identified from each increment can be resolved to the next increment

    Cons:

        * Needs a clear and complete definition of the whole system before it can be broken down and
          built incrementally
        * Each iteration is rigid
        * Although cost of change is lesser, but it is not very suitable for changing requirements
        * More resources may be required
        * Highly skilled resources are required for risk analysis
        * More management attention is required

    **Similarities between Waterfall and Incremental model:**

     <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_incemental_similarities.PNG" width="800" height="200">
    <div>

    **Differences between Waterfall and Incremental model:**

     <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_incemental_differences.PNG" width="800" height="450">
    <div>

    **[⬆ Back to Top](#table-of-contents)**

7.  ### Iterative Model

    The iterative and incremental methodology is designed to overcome any fault or shortcoming of the Waterfall methodology.

    In this incremental model, the whole requirement is divided into various builds. During each iteration, the development module goes through the requirements, design, implementation and testing phases. Each subsequent release of the module adds function to the previous release. The process continues till the complete system is ready as per the requirement.

    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/iterative.png" width="800" height="450">
    <div>

    Use cases for the Iterative and incremental model:

        * This model can be used when the requirements of the complete system are clearly defined
          and understood
        * There is a need to get a functinal module of the product to the market early

    Pros:

        * It supports changing requirements
        * Less costly to change the scope/requirements
        * Results are obtained early and periodically
        * With every increment, operational product is delivered
        * It delivers business value early in the development lifecycle
        * Progress can be measured
        * Parallel development can be planned
        * Testing and debugging during smaller iteration is easy
        * Customer evaluation and feedback is available in each increment which leading to better solutions
        * Issues, challenges and risks identified from each increment can be resolved to the next increment

    Cons:

        * Needs a clear and complete definition of the whole system before it can be broken down and
          built incrementally
        * Each iteration is rigid
        * Although cost of change is lesser, but it is not very suitable for changing requirements
        * More resources may be required
        * Highly skilled resources are required for risk analysis
        * More management attention is required

    **Similarities between Waterfall and Iterative model:**

     <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_incemental_similarities.PNG" width="800" height="200">
    <div>

    **Differences between Waterfall and Iterative model:**

     <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_incemental_differences.PNG" width="800" height="450">
    <div>

    **[⬆ Back to Top](#table-of-contents)**

8.  ### Prototype Model

    -   The Prototype model is an evolutionary software process model that is a combination of the Iterative and waterfall model
    -   Prototype is built, tested, and reworked using iterative methodology until the model is accepted by the customer.
    -   Customer feedback and the refined requirement is used to modify the prototype and is again presented to the customer for evaluation. Once the customer approves the prototype, it is used as a requirement for building the actual software. The actual software is build using the Waterfall model approach.
    -   Software prototyping is used in typical cases and the decision should be taken very carefully so that the efforts spent in building the prototype add considerable value to the final software developed.

    <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/prototype.jpg" width="800" height="450">
    <div>

    Use cases for the Prototype model:

        * It is used when user is not sure of the system, in other words requirements are incomplete

    Pros:

         * Prototyping Methodology is quite adaptive as any updates or new requirements are accommodated
         * Prototypes can be changed and even discarded
         * Increased user involvement in the product even before its implementation
         * Allows the client to compare if the software code matches the software specification
         * Helps to gain a better understanding of the customer's needs
         * It mitigates or eliminates  the risks before the actual product is developed
         * Quicker client feedback is available leading to better solutions
         * Missing functionality identified in the evaluation phase and implemented in the refined prototype
         * It also identifies the complex or difficult functions
         * Encourages innovation and flexible designing
         * No need for specialized experts to build the model

    Cons:

         * Prototyping is a time consuming  process
         * It can be comparatively costly as more time and resources are required for prototyping
         * The cost of developing a prototype is a total waste as the prototype is ultimately thrown away
         * The effort invested in building prototypes may be too much if it is not monitored properly
         * Poor documentation because the requirements of the customers are insufficient
         * Risk of insufficient requirement analysis owing to too much dependency on the prototype.
         * Prototyping may encourage excessive change requests
         * There may be far too many variations in software requirements when each time the prototype is
           evaluated by the customer
         * It is very difficult for software developers to accommodate all the changes demanded by the clients.
         * Users may get confused in the prototypes and actual systems
         * After seeing an early prototype model, the customers may think that the actual product will be
           delivered to him soon
         * Developers who want to build prototypes quickly may end up building sub-standard development
           solutions
         * Developers may try to reuse the existing prototypes to build the actual system, even when it is
           not technically feasible

    **Similarities between Waterfall and Prototype model:**

    <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_prototype_similarities.PNG" width="800" height="250">
    <div>

    **Differences between Waterfall and Prototype model:**

    <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_prototype_differences.PNG" width="800" height="450">
    <div>

    **[⬆ Back to Top](#table-of-contents)**

9.  ### RAD Model

    -   The RAD model is a concurrent software process model which is generally based on the prototype
        (Iterative and waterfall) model.
    -   The entire project is divided into various small modules and each module is allocated to different party to finish the working of the small modules. After that, all small modules are combined together to obtain the final project
    -   Each module is developed using the Prototyping (Iterative and waterfall) model approach.
    -   This model is used to completing the process of software product developing in a very short time.
    -   If your project can be divided into many parts or modules then the Rapid application development model is used.

    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/rad.png" width="800" height="400">
    <div>

    Although RAD has changed over the years, following four basic phases provide some continuity over the years.

    <div  style="text-align: center;">
        <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/rad_iterative.png" width="800" height="400">
    <div>

    1. **Requirement Analysis:** There are various approaches which is used in requirement planning like brainstorming , task analysis ,form analysis ,user scenario etc. This phase consists plan or designing of each module which contains data, methods and other resources.

    2. **Customer Evaluation:** In this phase, developer evaluates the customer satisfaction by delivering the prototype and taking the reviews from them. If the customer is satisfied then developer starts implementation.

    3. **Construction:** Prototype is refining and all the modification ,correction and improvements is done in this phase. This phase helps us to convert the process and modules into the final working product.

    4. **Cut Over:** This is the last stage of the RAD model. In this phase, all the independent modules are evaluated separately .The tools and sub-parts of product makes the testing of the product very easy.

    Use cases for the RAD model:

         * This model works only when the requirements are clearly specified
         * RAD should be used only when a system can be modularized to be delivered in an incremental manner.
         * When there's a necessity to make a system, which modularized in 2-3 months of period.
         * When the requirements are well-known.
         * When the technical risk is limited.

         * This model uses the powerful techniques and tools.
         * It should be used only if the budget allows the use of automatic code generating tools.
         * It should be used if there is a high availability of designers for Modelling.
         * It should be used only if the budget permits use of automated code generating tools.
         * RAD SDLC model should be chosen only if domain experts are available with relevant business knowledge.

    Pros:

         * Changing requirements can be accommodated.
         * Requirements can be changed at any time
         * It has more flexibility and adaptability to acquire the new requirements.
         * This model is flexible for change.
         * In this model, changes are adoptable.

         * It reduced development time.
         * Reduced development time.
         * Development time is drastically reduced
         * RAD model completes the project in a short period of time.

         * Reviews are quick
         * This model also helps client’s to take quick reviews for the project
         * Encourages customer feedback.
         * Encourages and priorities customer feedback

         * Reduce cost because very less developers are needed.
         * More productivity with fewer people

         * Iteration time can be short with use of powerful RAD tools.
         * Time between prototypes and iterations is short

         * The progress and development of project can be check on various stages .

         * Integration from very beginning solves a lot of integration issues.
         * Integration isn’t a problem, since it integrates from project inception
         * Prototype is delivered to the customer so the customer is satisfied.

         * Reusability of the components is increased.
         * It increases the reusability of features.
         * Reusability of components makes or speeds up the development and reduces the time that
           it needs for developing a product.

         * The modularized way of crafting each function within the system makes the development task easier.
         * Rapid Application development model helps to reduce the risk and required efforts on
           the part of the software developer
         * This methodology encourages customer feedback which always provides improvement scope
           for any software development project

    Cons:

         * All application is not compatible with RAD

         * Suitable for systems that are component based and scalable
         * It only works on systems that can be modularized can be built using this methodology
         * Only systems which can be modularised can be developed using Rapid application development
         * Only system that can be modularized can be built using RAD
         * High dependency on Modelling skills
         * Requires highly skilled developers/designers
         * Needs strong team collaboration
         * Dependency on technically strong team members for identifying business requirements

         * On the high technical risk, it's not suitable

         * Needs user requirement throughout the life cycle of the product
         * Requires user involvement throughout the life cycle
         * Customer involvement are needed
         * Required user involvement

         * More complex to manage when compared to other models
         * Management complexity is more

         * A proper time-frame should have to be maintained for both end customer as well
           as developers for completing the system
         * A slight complexity in the modularizing in RAD model can lead to failure of the entire project
         * This method is not applicable for the developer to use in small budget projects
           as a cost of modeling and automated code generation is very high
         * Inapplicable to cheaper projects as cost of Modelling and automated code generation is very high

    **Similarities between Waterfall and RAD model:**

    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_prototype_similarities.PNG" width="800" height="250">
    <div>

    **Differences between Waterfall and RAD model:**

     <div  style="text-align: center;">
            <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_prototype_differences.PNG" width="800" height="450">
     <div>

    **[⬆ Back to Top](#table-of-contents)**

10. ### Spiral Model

    -   The spiral model is an evolutionary software process model that is a combination of the Iterative and Prototyping with the systematic, controlled aspects of the waterfall model.
    -   It allows incremental releases of the product or incremental refinement through each iteration around the spiral.
    -   It has very high emphasis on risk analysis during each each iteration

      <div  style="text-align: center;">
            <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/spiral_model.png" width="800" height="400">
      <div>

    Each loop of the spiral is called a Phase of the software development process. Each phase of Spiral Model is divided into four quadrants as shown in the above figure. The functions of these four quadrants are discussed below-

    1. **Determining objectives, alternatives and constraints:** Requirements are gathered from the customers and the objectives are identified, constraints are evaluated and different alternative solutions for the development are proposed in this quadrant.
    2. **Evaluating alternatives, identifying and resolving risks:** During the second quadrant all the possible solutions are evaluated to select the best possible solution. Then the risks associated with that solution is identified and the risks are resolved using the best possible strategy. At the end of this quadrant, Prototype is built for the best possible solution.
    3. **Develop and verify next level project:** During the third quadrant, the identified features are developed and verified through testing. At the end of the third quadrant, the next version of the software is available.
    4. **Review and plan for the next Phase:** In the fourth quadrant, the Customers evaluate the so far developed version of the software. In the end, planning for the next phase is started.

    Use cases for the Waterfall model:

          * Customer isn’t sure about the requirements
          * Requirements are unclear or complicated and require continuous clarification
          * Frequent releases of modules are required
          * When creation of a prototype is applicable
          * Customer evaluation and feedback is required in each increment to develop a better solutions
          * Significant changes are expected in the product during the development cycle
          * Projects in which needs continuous risk evaluation
          * It is suitable for large and complex project

    Pros:

          * Requirements changes can be easily adopted and incorporated at the later stage of the development
          * Requirements can be captured more accurately by emphasizing customer feedback of each phase
          * Any enhancement or change in the functionality can be done in the next iteration
          * Customer evaluation and feedback is available in each increment which leading to better solutions
          * Handling risk analysis in every phase which improve security and
            mitigates the chances of attacks and breakages
          * Allows extensive use of prototypes
          * Users see the system early
          * More and more features are added in a systematic way

    Cons:

          * It is complex to understand , manage and implement
          * Requires high risk-analysing expertise
          * Demands risk management expertise

          * Since the number of iteration are unknown, the time required to complete the project remains a mystery
          * The project takes a significantly long time to develop, increasing the overall expense of the project
          * End of the project may not be known early
          * High risk for falling behind schedule or going over budget
          * Large number of intermediate stages requires excessive documentation

    **Similarities between Waterfall and Spiral model:**

    <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_incemental_similarities.PNG" width="800" height="200">
    <div>

    **Differences between Waterfall and Spiral model:**

    <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_incemental_differences.PNG" width="800" height="450">
    <div>

    **[⬆ Back to Top](#table-of-contents)**

11. ### Agile Model

    -   The Agile Model

      <div  style="text-align: center;">
            <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/agile-umbrella.png" width="500" height="500">
      <div>

    Use cases for the Agile model:

          * The Agile Model

    Pros:

          * The Agile Model

    Cons:

          * The Agile Model

    **Similarities between Waterfall and Spiral model:**

    <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_incemental_similarities.PNG" width="800" height="200">
    <div>

    **Differences between Waterfall and Spiral model:**

    <div  style="text-align: center;">
           <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/water_incemental_differences.PNG" width="800" height="450">
    <div>

    **[⬆ Back to Top](#table-of-contents)**

12. ### References

    I have followed many articles but among them, the following articles are really helpful. Those articles helped me a lot and also encourage me to write this article according to my understanding.

    -   [tutorialspoint](https://www.tutorialspoint.com/sdlc/index.htm)
    -   [Top 12 SDLC Methodologies with Pros and Cons](https://www.techuz.com/blog/top-12-sdlc-methodologies-with-pros-and-cons/)
    -   [SDLC Methodologies](https://svitla.com/blog/sdlc-methodologies)
    -   [Top 6 SDLC Methodologies And How To Choose The Best One?](https://www.goodcore.co.uk/blog/sdlc-methodologies/)
    -   [Top 7 SDLC Methodologies](https://hackr.io/blog/sdlc-methodologies)
    -   [SDLC Models Explained: Agile, Waterfall, V-Shaped, Iterative, Spiral](https://existek.com/blog/sdlc-models/)
    -   [TOP SOFTWARE DEVELOPMENT MODELS: THEIR PROS & CONS](https://cybercraftinc.com/blog/top-software-development-models-their-pros-cons)
    -   [SDLC (Software Development Life Cycle) Phases, Methodologies, Process, And Models](https://www.softwaretestinghelp.com/software-development-life-cycle-sdlc/)
    -   [Waterfall vs. Incremental vs. Spiral vs. Rad Model: Key Difference](https://www.guru99.com/compare-waterfall-vs-incremental-vs-spiral-vs-rad.html)
    -   [What are the Different Types of Agile Methodologies?](https://www.wrike.com/project-management-guide/faq/what-are-the-different-types-of-agile-methodologies/)
    -   [Agile Methodologies](https://www.blueprintsys.com/agile-development-101/agile-methodologies)
    -   [Difference between V-model and Waterfall model](https://www.geeksforgeeks.org/difference-between-v-model-and-waterfall-model/)
    -   [Choosing the right Software development life cycle model](https://melsatar.blog/2012/03/21/choosing-the-right-software-development-life-cycle-model/?fbclid=IwAR1mpCDGUxD0CuhdSWtgtHsUEXQWMtPi4aWCdG03P1p-bYoXXY9M_geNZl4)
    -   [Spiral Model – What Is SDLC Spiral Model?](https://www.softwaretestinghelp.com/spiral-model-what-is-sdlc-spiral-model/)

    **[⬆ Back to Top](#table-of-contents)**
