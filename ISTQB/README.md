### Why is testing necessary?
This can help reduce the risk of failures occurring during operation. When defects are detected, and subsequently fixed, 
this contributes to the quality of the components or systems.

### Quality Assurance and Quality Control are the same?
Quality Assurance and Testing are not the same, but they are related.
Quality Assurance is typically focused on processes, for example the use of root cause analysis to detect amd remove the causes of defects, retrospective meetings to improve the processes. 
Quality Control involves various is focused on maintenance process.

### Errors, Defects and Failures
A person can make an error (mistake), which can lead to the introduction of a defect (fault or bug), and this may cause a failure.

Errors may occur for many reasons, such as:

1. Time pressure
2. Inexperienced
3. Miscommunication about requirements and design
4. Complexity of code
5. Misunderstandings of system interactions
6. Unfamiliar technologies

### Software Development Life Cycle
Is a structured process that enables the production of high quality, low cost software in the shortest possible production time.
The goal of SDLC is to produce superior software that meets and exceeds all customer expectations and demands.

It's divided by phases 
1. Planning  
2. Analysis/Requirement Gathering 
3. Design 
4. Implementation/Coding 
5. Execution
6. Maintenance/Monitoring

#### Planning
This includes making reasonable estimates of the cost and size od the software product as compared to the resources at hand.
#### Analysis/Requirement Gathering 
This step includes collecting maximum information from the client about desired product. All details and specifications of the product must be discussed with the customer and can response the question "What to test".
#### Design
In this phase, the developer checks the question "How to test" with this identify, design, prioritizing test case, test data, test conditions and create test environments. 
#### Implementation/Coding 
It means translating the design into a computer language ("Automated Scripts", "Manual Test Cases"), build test environments, preparing test data. 
#### Execution
This step is to found or report bugs and comparing actual results with expected results, analysing anomalies, and create summary reports to be communicated to stakeholders.
#### Maintenance/Monitoring
When the customer start using the developed system, the actual. problems come up and need to be solved from time to time. This process where the care is taken for the developed 
product is known as Maintenance.


### Software Development Lifecycle Models
Describes the types of activity performed at each stage in a software development project. The ISTQB syllabus categorizes common software development life cycle models as follows:
1. Sequential Development Model
   1. Waterfall Model
   2. V-Model
2. Iterative and Incremental Development Model
   1. Scrum 
   2. Kanban
   3. Spiral

Components or systems developed using these methods often involve overlapping and iterating test levels throughout development. Ideally, each feature is tested at several test levels as it moves towards delivery. In some
cases, teams use continuous delivery or continuous deployment, both of involve significant automation of multiple test levels as part of their delivery pipelines.
   
### Test Levels
Group of test activities, Each test level is an instance of the test process, the test level used in ISTQB syllabus are:
1. Component Testing
```
Component Testing (also known as unit or module testing) focuses on components that are separately testeable.
```
2. Integration Testing
```
Focuses on interactions between components or systems (microservices, databases, APIs, interfaces, web services)
```
3. System Testing 
```
Focuses on the behaviour and capabilities of a whole system or product, often considering the end to end tasks, this is tested on functional and non funtional test.
```
4. Acceptance Testing
```
Focuses on validate that the system is compleate and will work as expected, establishing confidence in the quality of the system.
Environments: UAT (User Acceptance Testing: simulate operational environment), OAT (Operation Acceptance Testing: Build confidence at the operators or systems administrators can keep the system working properly for the users in the operational environment)
```

### Test Types 
Evaluating Functional - Non-Functional characteristics
1. Functional Testing: Involves tests that evaluate functions that the system should perform (user story, epics, use cases or functional specification)
```
 1. Black Box Testing: Examines the functionality of an application without having knowledge of internal structure code.
```
2. Non-Functional Testing: Evaluates characteristics of systems and software such as usability, performance, security or efficiency
```
 1. White Box Testing: Evaluate code, architecture, work flows, data flows
```

### Static Testing 
Focuses on manual examine or work products (Specifications, Business requirements, Functional Requirements, User Stories, Acceptance Criteria), evaluate work products
written in natural language(e.g. checking for spelling, grammar, readability ), static testing enables the early detection of bugs or defects.

#### Difference between Static and Dynamic Testing
Static without execute the system and Dynamic you need execute the system to detect system behaviour.

#### Review Process
In this phase define the scope, purpose, documents, estimate effort and deadline, select people to participate in and define the entry and exit criteria.
You can use:
1. Ad Hoc
2. Checklist
3. Scenarios
4. Perspective-based


### Black box, White box and Experienced Test Techniques
1. Black box
```
   1. Equivalence Partioning: Divides data into partions 
   2. Boundary Value Analysis: Determines a certain range of values are acceptable by the system
   3. Desicion Table: Use a table as matrix to detect the major number of combinations
```
2. White box
```
   1. Desicion Coverage
   2. Condition Coverage
   3. Path Coverage
   4. Data Flow Testing
```
3. Experienced Test
```
   1. Exploratory Testing 
   2. Checklist 
   3. Error Guessing 
```
