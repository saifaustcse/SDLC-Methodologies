# Find me

> If you think that these can be improved in anyway, please do suggest. Pull Request are highly appreciated. Find me if you wish [@Saif(https://www.linkedin.com/in/saif-aust-cse/).


### Table of Contents

| No. | Topic |
| --- | --------- |
|1  | [What is SDLC??](#what-is-SDLC) |
|2  | [What are the phases of SDLC?](#what-are-the-phases-of-SDLC ) |
|3  | [Pros and Corns of SDLC](#Pros-and-Corns-of-SDLC ) |
|4  | [Top SDLC Methodologies?](#Top-SDLC-methodologies ) |
|5  | [Waterfall Model](#Waterfall-Model ) |
|6  | [Iterative and incremental Model](#Iterative-and-incremental-Model ) |
|7  | [Prototype Model](#Prototype-Model ) |
|8  | [Spiral Model](#Spiral-Model ) |
|9  | [V-Model Model](#V-Model-Model ) |
|10 | [RAD Model](#RAD-Model ) |
|11 | [Prototype Model](#Prototype-Model ) |

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
        Once the requirement analysis and feasibility ftudy is done the next step is to clearly define and document the product requirements and get them approved from the               customer or the market analysts. This is done through an SRS (Software Requirement Specification) document which consists of all the product requirements to be designed         and developed during the project life cycle.
        
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
   
   
4. ### Top-SDLC-methodologies

    ![](https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/flow-chart.png)


   **[⬆ Back to Top](#table-of-contents)**
  
              
5. ### Waterfall Model

    Waterfall is a sequential and linear flow for developing a software application. The process is outlined by a series of finite stages, each of which must be fully completed     before moving on to the next one. The idea here is quite simple: develop one phase of the project completely and move on to the next. In this way, the project progresses and     moves forward in a linear flow. This SDLC methodology is best fitted for small projects where deliverables can be defined clearly.
 
    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/waterfall.jpg" width="500" height="300">
    <div>

    Use cases for the Waterfall model:

        * This model is used only when the requirements are very well known, clear and fixed.
        * Product definition is stable
        * No ambiguous requirements
        * The requirements are precisely documented
        * The technologies stack is predefined which makes it not dynamic
        * The project is short

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
    
 6. ### Iterative and incremental Model

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

      
 7. ### Prototype Model

    Prototyping model is a software development model in which prototype is built, tested, and reworked until the model is accepted by the customer. It works best in scenarios where the project's requirements are not known in detail.

    Software prototyping is used in typical cases and the decision should be taken very carefully so that the efforts spent in building the prototype add considerable value to the final software developed.
 
    <div  style="text-align: center;">
          <img src="https://github.com/saifaustcse/SDLC_Methodologies/blob/master/images/waterfall.jpg" width="500" height="300">
    <div>

    Once the requirement gathering is done, the quick design is created and the prototype which is presented to the customer for evaluation is built.

    Customer feedback and the refined requirement is used to modify the prototype and is again presented to the customer for evaluation. Once the customer approves the prototype, it is used as a requirement for building the actual software. The actual software is build using the Waterfall model approach.


    Use cases for the Prototype model:

        * It is used when user is not sure of the system, in other words requirements are incomplete.

    Pros:
    
        * The prototype helps to gain a better understanding of the customer's needs.
        * Prototypes can be changed and even discarded.
        * Prototyping Methodology is quite adaptive as any updates or new requirements are accommodated 
        * Increased user involvement in the product even before its implementation.
        * Allows the client to compare if the software code matches the software specification.   
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
        * Risk of insufficient requirement analysis owing to too much dependency on the prototype.
        * Users may get confused in the prototypes and actual systems.
        * Developers may try to reuse the existing prototypes to build the actual system, even when it is not technically feasible.
        * The effort invested in building prototypes may be too much if it is not monitored properly.
        * Prototyping may encourage excessive change requests.
        * There may be far too many variations in software requirements when each time the prototype is evaluated by the customer.
        * Poor documentation because the requirements of the customers are changing.
        * It is very difficult for software developers to accommodate all the changes demanded by the clients.
        * After seeing an early prototype model, the customers may think that the actual product will be delivered to him soon.
        * Developers who want to build prototypes quickly may end up building sub-standard development solutions.

    **[⬆ Back to Top](#table-of-contents)**


    7. ### Spiral Model

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

