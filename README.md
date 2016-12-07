# Fall2016Notes


### IceScrum
##### Sprint Plan
- View/Create Tasks and move them around accordingly

##### Release Plan
- Displays all springs and statuses of where they currently are

##### Timeline
- Shows a more undefined/vague overview of the whole project. This includes the sprint numbers and the project.

##### Product Backlog
- Contains stories which have been accepted by the product owner.

##### Sandbox
- Stories go into the sandbox 

##### Dashboard
- Displays a graph visual, kind of like Github which allows others to monitor how the sprints are being handled. Also shows an overview of the project description, release vision, retrospective, activity log, etc.

### Final Exam

- A Work Breakdown Structure (WBS) divides work into manageable pieces.
- Gantt Charts illustrate project schedules by using horizontal lines.
- Entity-Centered models need to have all issues in one category to be closed before any in the next category can be opened. Kind of like traveling together to the next destination with everyone's approval and without leaving anyone behind.
- No process is ideal or pure; in reality, real processes are a hybrid mix which takes different ideas from the models.
- Methodology is a collection of methods and tools for developing and managing a software system. 
- Proxy Client has knowledge but no authority
- Pseudo client has authority but no knowledge
- Royce's Methodology (based on Unified Process) uses visual modeling languages such as UML.
- Principles of Extreme Programming is basically meant to seize the day: Quality work the first time without going back and fixing things later, design focuses on current requirements without concerning the future, and also testing confronting issues early on. 
- A Document Rationale is used people sometimes new people might join the project. They need to be told how the system is built and WHY it is built like that. Also, they need to know what ideas have been considered and rejected, too.
- Steps for capturing a rationale: 

  1. identify the issues 
  2. proposals address the issues 
  3. criterion is used to evaluate proposals 
  4. arguments advocate for or against different proposals based on criteria 
  5. resolutions document final decisions and resolve issues 
  6. Action items document what is to be done to implement resolutions
  
- The three parts to design goals are Availability, Security and Usability.
- There are four transformations between model and code. 

  1. Model Transformation improves the model, independent of any code.
  2. Refactoring improves the code, independent of any models.
  3. Reverse Engineering generates models from code.
  4. Forward Engineering transforms models into code.
  
- Oracle is a means of determining what the correct results of a test should be.
- Inspections can help find more than one error at a time, can find more faults faster and can analyze good styles and practices.
- Inspections DO NOT replace testing.
- Black box -> Opaque - Acceptance tests are typically black boxes
- White box -> Transparent - Unit tests may be black or white boxes
- Equivalence Class is a range of input values for which the results are expected to be equivalent.
- Boundary Testing recognizes that errors most commonly occur at the boundary of equivalence classes.

##### Different types of testing
- Statement testing - test every executable line of code
- Branch testing - test every branch at every decision point
- Condition testing - test every condition in true and false cases
- Path testing - test all paths in flowchart
- Big Bang - Test everything at once.
- Functional testing - tests functional requirements
- Usability testing - tests user interface
- Performance testing - push the limits
- Regression testing - involves re-testing things that used to work, after other changes are made.
- Automating testing - supports frequent regression testing

##### Creational Patterns
- Abstract Factory: create related or dependent objects without specifying their concrete classes
- Builder: Deconstruct a complex object and use the construction of that to create different representations
- Factory Method: Define and interface for creating an object but let subclasses choose which classes to create
- Prototype: Specify objects to create a prototype and copy this instance to create new objects
- Singleton: Ensure a class has only one instance

##### Structural Patterns
- Adapter: Convert interface into another interface. Point is to make the new interface compatible with the new/old system.
- Bridge: Decouple abstraction to from implementation so two can work independently.
- Composite: Compose objects into tree structures
- Decorator: Attach additional responsibilities to an object dynamically
- Facade: Provide a unified interface for a set of interfaces. 
- Flyweight: Use sharing to support large numbers of fine-grained objects
- Proxy: Allow another surrogate or placeholder to control access to an object.

### Questions for Midterm #1


- Q:What is the key feature that distinguishes agile development methods from more traditional classical Software Engineering approaches?
- A: Lecture #1

- Q:What is shown in a UML use-case diagram?
- A:
- Q&A: -|> is arrow for inheritance

- Q:What type of diagram is nearly equivalent to a sequence diagram?
- A:Communication diagram

- Q:What is the first step in developing tasks for a new scenario in iceScrum
- A:


### Topics for Midterm #1

- The Classic Waterfall Model
- The V model
- Activity Diagram 
### Iterative Approaches
- Boehm's Spiral Model
- Unified Process

### Agile Development
- Embrace change, rather than fear it
- Development in small chunks without planning the whole project out. Do it as you go.
- Incremental functionality delivered as the project proceeds
- Rapid development methods
- More suitable for small teams working on shorter-term projects

- Rugby method is moving forward in a series of sprints.

### Use Case Diagram
- AKA Scenario diagrams

- Scenarios are informal stories written in a narrative fashion. They help convey a general understanding
- Use Cases are more formal

### Sequence Diagrams 

- document the steps taken during a single use case

### Communication Diagrams

- AKA collaboration diagrams
- Same info as a sequence diagram

# Older stuff is below this line
---

### Requirements
- Specific, detailed, unambiguous specifications of the features
- Often used as a contract between others
- Functional Requirements specify features the SW must perform
- Non-Function Requirements specify other properties the system must have
- WHAT versus HOW the product does it
- Constraints are a requirement set by the client before the project. ie. budget, space
- Design goals are properties that are desirable to optimize without limits.


# 08/31/16 (440)

- Communication Diagrams -> aka collaboration diagrams
- Class diagrams are the most widely used and known
- Italics represent an abstract class
- Multiplicities: 1 is exactly one, * is many (zero or more), 0..1 is optional (zero or one), m..n is numerically specified.
