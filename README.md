# Find me

> If you think that these can be improved in anyway, please do suggest. Pull Request are highly appreciated. Find me if you wish [@Saif(https://www.linkedin.com/in/saif-aust-cse/).


### Table of Contents

| No. | Topic |
| --- | --------- |
|1  | [What is SDLC?](#what-is-SDLC) |
|2  | [What are the phases of SDLC?](#what-are-the-phases-of-SDLC ) |
|3  | [Top SDLC Methodologies?](#top-SDLC-methodologies ) |
|4  | [Waterfall Model](#waterfall-model ) |
|5  | [V-Shaped Model](#v-shaped-model ) |
|6  | [Difference between V-model and Waterfall model](#Difference-between-v-model-and-Waterfall-model ) |
|7  | [Prototype Model](#prototype-model ) |
|6  | [Difference between V-model and Prototype model](#Difference-between-v-model-and-prototype-model ) |
|8  | [Iterative and incremental Model](#iterative-and-incremental-Model ) |
|9  | [Spiral Model](#spiral-Model ) |
|9  | [RAD Model](#RAD-Model ) |
|10 | [Prototype Model](#prototype-Model ) |

## Details 

1. ### What is SDLC?

    The Software Development Life Cycle (SDLC) refers to a methodology with clearly defined processes for creating high-quality software.


   **[⬆ Back to Top](#table-of-contents)**
    
    
2. ### What are the phases of SDLC?

    The SDLC methodology consists  of the following phases of software development:
    
    <div  style="text-align: center;">
         <img src="https://github.com/saifaustcse/SDLC_Methodologies/raw/master/images/sdlc_1.png" width="300" height="300">
    <div>

    1. **Phase 1 – Analysis/Planning**  
      The very first phase of the SDLC known as the planning stage. It is the most important phase of the entire SDLC from the perspective of project managers and stakeholders.       It is performed by the senior members of the team with inputs from the customer, the sales department, market surveys and domain experts in the industry.
      Planning pahse can be divided in 3 sub pahses:
    
        **Sub Phase 1 –  Requirement Analysis** 
        * How the software will be used?
        * What data will serve as the input of the software?
        * What data will be the output given by the software?
        * Who is going to use the software?
       
       **Sub Phase 2 –  Feasibility Study** 
        In this phase, evaluate the requirements for feasibility. The goal is to quantify the opportunities and risk of addressing the agreed requirements with the variety of           resources and strategies available to the organization. The feasibility study evaluates the following key aspects, among others:
        * Economic: Is it financially viable to invest in the project based on the available resources?
        * Legal: What is the scope of regulations and the organization’s capacity to guarantee compliance?
        * Operational: Can we satisfy the requirements within scope definition according to the proposed operational framework and workflows?
        * Technical: What is the availability of technology and HR resources to support the SLDC process?
        * Schedule: Can we finish the project in time?
        * Executive decision makers should answer and document these questions and study them carefully—before proceeding with the software design and implementation process.

        **Sub Phase 3 –  Defining Requirements**  
        Once the requirement analysis and feasibility study is done the next step is to clearly define and document the product requirements and get them approved from the               customer or the market analysts. This is done through an SRS (Software Requirement Specification) document which consists of all the product requirements to be designed         and developed during the project life cycle.
        
    2. **Phase 2 – Design** 
      
        This phase describes, in detail, the necessary specifications, features and operations that will satisfy the functional requirements of the proposed system which will           be in place. This is the step for end users to discuss and determine their specific business information needs for the proposed system. It"s during this phase that they         will consider the essential components (hardware and/or software) structure (networking capabilities), processing and procedures for the system to accomplish its                 objectives.
    
        SRS is the reference for product architects to come out with the best architecture for the product to be developed. Based on the requirements specified in SRS, usually           more than one design approach for the product architecture is proposed and documented in a DDS - Design Document Specification.

        This DDS is reviewed by all the important stakeholders and based on various parameters as risk assessment, product robustness, design modularity, budget and time                 constraints, the best design approach is selected for the product.

        A design approach clearly defines all the architectural modules of the product along with its communication and data flow representation with the external and third             party modules (if any). The internal design of all the modules of the proposed architecture should be clearly defined with the minutest of the details in DDS.
   
    3. **Phase 3 – Development/Implementation** 
        In this phase of SDLC the actual development starts and the product is built. The programming code is generated and database is designed as per DDS during this stage. If         the design is performed in a detailed and organized manner, code generation can be accomplished without much hassle. 
       
        Developers must follow the coding guidelines defined by their organization and programming tools like compilers, interpreters, debuggers, etc. are used to generate the           code. Different high level programming languages such as C, C++, Pascal, Java and PHP are used for coding and different types (structued and non structured) databases           such as oracle, MSSQL, MySQL, MongoDb are used for dumping data.
        
    4. **Phase 4 – Testing/Quality Assurance** 
        In this phase systems integration and system testing (of programs and procedures)—normally carried out by a Quality Assurance (QA) professional—to determine if the               proposed design meets the initial set of business goals. Testing may be repeated, specifically to check for errors, bugs and interoperability. This testing will be               performed until the end user finds it acceptable.
        
        During this phase of the SDLC, various types of functional testing, such as acceptance testing, integration testing, system testing, and unit testing, as well as the             non-functional testing is carried out.
    
    5. **Phase 5 – Deployment/Release** 
        This phase is carried out right after the successful testing of the software product. It is simply delivering the software to the end-user or installing it onto the             customer’s system(s).
        The first thing that takes place once the product is delivered to the customer is beta testing. All the bugs and enhancements are then reported to the developer team             working on the project afterward. Once all the changes are complete, the final deployment takes place.

    6. **Phase 6 – Maiantenance** 
        The final phase involves maintenance and regular required updates. This step is when end users can fine-tune the system, if they wish, to boost performance, add new             capabilities or meet additional user requirements


   **[⬆ Back to Top](#table-of-contents)**
   
   
3. ### Top-SDLC-methodologies

    ![](https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/flow-chart.png)


   **[⬆ Back to Top](#table-of-contents)**
  
              
4. ### Waterfall Model

    Waterfall is a sequential and linear flow for developing a software application. The process is outlined by a series of finite stages, each of which must be fully completed before moving on to the next one. The idea here is quite simple: develop one phase of the project completely and move on to the next. In this way, the project progresses and moves forward in a linear flow. This SDLC methodology is best fitted for small projects where deliverables can be defined clearly.
 
    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/waterfall.jpg" width="500" height="300">
    <div>

    Use cases for the Waterfall model:

        * This model is used only when the requirements are very well known, clear and fixed.
        * There are no ambiguous or undefined requirements.
        * The requirements are precisely documented
        * The technologies stack is predefined which makes it not dynamic
        * The project is small or mid-sized 

    Pros:

        * Each stage are clearly defined
        * Process and results are well documented.
        * Easy to manage due to the rigidity of the model. 
        
    Cons:
   
        * Cannot accommodate changing requirements.
        * Any change in the later stages would lead to cost higher as the changes would be required 
          in all the phases
        * No working software module is produced until late during the life cycle.
        * The progress of the stage is hard to measure while it is still in the development
        * Not suitable for the projects where requirements are at a moderate to high risk of changing.
   
    **[⬆ Back to Top](#table-of-contents)**

5. ### V-Shaped Model

    V-shaped SDLC model is an expansion of classic waterfall model where each development activity is associated with a testing phase. It is also known as Verification and Validation model. 
 
    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/v-model.png" width="500" height="300">
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

        * This model is used only when the requirements are very well known, clear and fixed.
        * There are no ambiguous or undefined requirements.
        * The requirements are precisely documented
        * The technologies stack is predefined which makes it not dynamic
        * The project is small or mid-sized 
        * For the projects where an accurate product testing is required

    Pros:

        * Ability to avoid the downward flow of defects
        * Higher success chances
        * Proactive defect tracking – that is defects are found at early stage.
        * Saves a lot of time as planning and designing related to testing is done way before the actual coding takes place. 
        * Every stage of V-shaped model has strict results so it’s easy to control	
        * Testing and verification take place in the early stages	
        * It is a systematic and disciplined model which results in a high-quality product.
        * Simple and easy to understand and use.
        * Testing activities like planning, test designing happens well before coding. This saves a lot of time. Hence higher chance of success over the waterfall model.
        * This is a highly-disciplined model and Phases are completed one at a time.
        * Easy to manage due to the rigidity of the model. Each phase has specific deliverables and a review process.
        * Covers all functional areas.
        * Contains instructions and recommendations, which provide a detailed explanation of problems involved.
        * Emphasizes the significance of testing and ensures that testing is planned.
        * This model focuses on verification and validation activities early in the life cycle thereby enhancing the probability of building an error-free and good quality product.
        * It enables project management to track progress accurately.

    Cons:
   
        * Even more rigid and less flexible than the Waterfall model
        * No working software module is produced until late during the life cycle.
        * Requirement and test documents need to be updated if any changes had to be made amid the software development
        * Lack of the flexibility
        * Bad choice for the small projects
        * Relatively big risk
        * V-shaped model is not good for ongoing projects.
        * Requirement change at the later stage would cost too high.
        * Very rigid and least flexible.
        * If any changes happen in midway, then the test documents along with requirement documents has to be updated.
        * High risk and uncertainty.
        * Not a good model for complex and object-oriented projects.
        * Poor model for long and ongoing projects.
        * Not suitable for the projects where requirements are at a moderate to high risk of changing.
        * Once an application is in the testing stage, it is difficult to go back and change a functionality.
        * The processes are institutionalized during the project and when the project is finished, they are abolished.
        * Not a good for a complex project.
        * This model does not support iteration of phases.
        * It does not easily handle concurrent events.


    **Difference between V-model and Waterfall model:**
   
    **[⬆ Back to Top](#table-of-contents)**
    
6. ### Prototype Model

    Prototyping model is a software development model in which prototype is built, tested, and reworked until the model is accepted by the customer. It works best in scenarios where the project's requirements are not known in detail.

    Software prototyping is used in typical cases and the decision should be taken very carefully so that the efforts spent in building the prototype add considerable value to the final software developed.
 
    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/prototype.jpg" width="500" height="300">
    <div>

    Once the requirement gathering is done, the quick design is created and the prototype which is presented to the customer for evaluation is built.

    Customer feedback and the refined requirement is used to modify the prototype and is again presented to the customer for evaluation. Once the customer approves the prototype, it is used as a requirement for building the actual software. The actual software is build using the Waterfall model approach.


    Use cases for the Prototype model:

        * It is used when user is not sure of the system, in other words requirements are incomplete.

    Pros:
    
        * Prototyping Methodology is quite adaptive as any updates or new requirements are accommodated 
        * Prototypes can be changed and even discarded.
        * Increased user involvement in the product even before its implementation.
        * Allows the client to compare if the software code matches the software specification.   
        * Helps to gain a better understanding of the customer's needs.
        * It mitigates or eliminates  the risks before the actual product is developed 
        * Quicker client feedback is available leading to better solutions.
        * Missing functionality identified in the evaluation phase and implemented in the refined prototype.
        * It also identifies the complex or difficult functions.
        * Encourages innovation and flexible designing.
        * No need for specialized experts to build the model
        
    Cons:
   
        * Prototyping is a time consuming  process.
        * It can be comparatively costly as more time and resources are required for prototyping
        * The cost of developing a prototype is a total waste as the prototype is ultimately thrown away.
        * The effort invested in building prototypes may be too much if it is not monitored properly.
        * Poor documentation because the requirements of the customers are insufficient.
        * Risk of insufficient requirement analysis owing to too much dependency on the prototype.
        * Prototyping may encourage excessive change requests.
        * There may be far too many variations in software requirements when each time the prototype is evaluated by the customer.
        * It is very difficult for software developers to accommodate all the changes demanded by the clients.
        * Users may get confused in the prototypes and actual systems.
        * After seeing an early prototype model, the customers may think that the actual product will be delivered to him soon.
        * Developers who want to build prototypes quickly may end up building sub-standard development solutions.
        * Developers may try to reuse the existing prototypes to build the actual system, even when it is not technically feasible.
        

    **[⬆ Back to Top](#table-of-contents)**

7. ### Iterative and incremental Model

    The iterative and incremental methodology is designed to overcome any fault or shortcoming of the Waterfall methodology.    

    In this incremental model, the whole requirement is divided into various builds. During each iteration, the development module goes through the requirements, design, implementation and testing phases. Each subsequent release of the module adds function to the previous release. The process continues till the complete system is ready as per the requirement.
 
    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/incremental.png" width="500" height="300">
    <div>

    Use cases for the Iterative and incremental model:

        * This model can be used when the requirements of the complete system are clearly defined and understood.
        * There is a need to get a functinal module of the product to the market early.

    Pros:
    
        * It supports changing requirements.
        * Less costly to change the scope/requirements.
        * Results are obtained early and periodically.
        * With every increment, operational product is delivered.
        * It delivers business value early in the development lifecycle
        * Progress can be measured.
        * Parallel development can be planned.
        * Testing and debugging during smaller iteration is easy.
        * Customer evaluation and feedback is available in each increment which leading to better solutions.
        * Issues, challenges and risks identified from each increment can be resolved to the next increment.
        
        
    Cons:
   
        * Needs a clear and complete definition of the whole system before it can be broken down and built incrementally.
        * Each iteration is rigid
        * Although cost of change is lesser, but it is not very suitable for changing requirements.
        * More resources may be required.
        * Highly skilled resources are required for risk analysis.
        * More management attention is required.

        
    **[⬆ Back to Top](#table-of-contents)**


8. ### Spiral Model

    Spiral Model 

 
    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/waterfall.jpg" width="500" height="300">
    <div>

    Use cases for the Waterfall model:

        * It is used when user is not sure of the system, in other words requirements are incomplete.

    Pros:
    
        * 
        *
        *
        * 
        
    Cons:
   
        * 
        * 
        * 
    **[⬆ Back to Top](#table-of-contents)**

