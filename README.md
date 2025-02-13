# CEN4010
Repo for UNF Final Project

Team Project Description

Please read this document carefully in its entirety before starting your work.

This project aims to provide you with hands-on experience in analyzing requirements and designing, coding, and testing a software system. This project provides a realistic experience to apply the knowledge and skills you learn in class. The project will be completed in four iterations, as described below. You will complete this project in a group (2-3 members per group) and work in the same group for the entire project. But, note you may get a different score than your group depending on your contributions to the project. 

## Iteration 0 - Proposal

In this iteration, you will develop your project idea. Work with your team members to develop a project proposal that is interesting to you and should meet the following constraints:

The project should have some connection to the real world. The best projects will satisfy someone's need for computation — maybe even your own. Your software solution should have a graphical user interface that the user interact with the application.
The project must be able to be installed and run on SoC computers such as in a lab and must be installable and testable by the instructor. 
This must be a new project for this class; clones or minor improvements to past projects are not allowed. 
You may not receive monetary compensation or credit in another course for working on this project (no double-dipping). You are allowed to create something that you think could generate revenue for you in the future, but not to do a project for a particular paying boss/client/organization.
The project should be of suitable size and scope for to be completed (including design, testing, and documentation) in the remaining portion of the semester by a team of 2-3 student engineers; not much more or less.
As a team, discuss your project ideas and decide what you want to work on. Once you decide on the problem, work iteratively, deciding on the problem statement and the scope of the project. Then list your functional and non-functional requirements.

## Iteration 1 - Use Case Diagrams, Class Diagrams, and Version 1 implementation

You will develop version 1 of your project during Iteration 1 (Due: check Canvas). Iteration 1 will involve:

Deciding what requirements you will implement for version 1,
Analysis of requirements for version 1 with the help of use cases,
Creating a class model that describes the concepts in your domain,
Implementing version 1.
Iteration 2 - Version 2 Implementation

You will develop this version 2 in iteration 2 (Due: Check Canvas). Iteration 2 will involve:

Deciding what requirements you will implement for version 2,
Develop sequence diagrams,
Update the use case diagrams and class diagrams,
Implementing version 2,
Develop unit test cases.
Iteration 3 -  Version 3 Implementation

You will develop this version 3 in iteration 5 (Due: Check Canvas). Iteration 3 will involve:

Implementing all the requirements for your project,
Apply design patterns to your project,
Update use case diagrams, sequence diagrams, and class diagrams,
Develop system test cases,
Use test coverage tools to check the coverage of your test cases
__________________________________________________________________________________

Iteration 1 Deliverables

The project will be submitted in stages. Submit an electronic copy of the deliverables at each stage via Canvas. For Iteration 1 the deliverable will be a PDF document and code as a zip file.

You must embed all the images (i.e. jpg, bmp, etc.) in the PDF file as your submission. Any tool specific model files will NOT be accepted. Do not submit images as separate files. Please make sure that you include your names on the front page of all submitted documents.

Part 1 -  Use Case Analysis, Class diagrams, and Version 1 implementation

40 points.
Tasks
In your team meetings, flesh out the requirements you want to implement for version 1 of your software. Identify the actor(s). Discuss scenarios involved during startup and performing user activities. Think about alternative scenarios (e.g., what if the user action fails?). Use cases must cover all general kinds of end-to-end uses. Follow the format used in class when you write them up.
Based on the use cases identified above, model the classes and their relationships. Express identified classes as a UML class diagram. The class model should:
Include relevant and necessary associations and other links.
Attributes should be simple or "pure data elements" such as scalars. State that is complex should be represented as associations to concepts that represent the complex entity.
Include multiplicity if appropriate.
Use Generalization/Specialization (inheritance) sparingly, and only for true "is-a" relationships.
Use the provided GitHub repository-based version control system for all types of documents (design diagrams, tests, implementation code).
Implement the system for version 1 using an object-oriented language of your choice. We highly recommend using Java with Swing for the user interface since the UI for this application is very simple. If you are picking anything other than Java, make sure those languages have unit testing tools (such as Junit for Java) and test coverage tools (such as EclEmma for Java). Note that if you are using other languages, we will not be able to provide any technical support, especially regarding issues related to interfacing with unit testing and coverage tools.
Write appropriate unit test cases to test your implementation using a unit testing framework (such as JUnit if you are using Java).
Submission
Prepare a PDF document containing the following:
Use case diagram showing the actors and the use cases. (4 points)
All use cases in two-column form. (6 points)
UML class diagram. (8 points)
Commit log showing check-ins, checkouts, etc. from your GitHub repo (2 points). This log will help us determine a number of things, such as (1) level of individual participation, (2) adequate use of a version control system. If the document shows an inadequate amount of check-in and checkout, the team may lose points. If an individual has no corresponding entry in the log, this individual may lose a lot of points for not participating in the project (i.e., the penalty is not limited to the 2 points for submitting the commit log).
Prepare and submit a 5-minute video showing the implemented functionality of your software.
Submit the following code in a single zip file (the test and implementation should be in separate Java packages). Note that the code must implement the design you provided above. Points will be deducted if it doesn't.
Unit test code (5 points)
System implementation and a document describing how to run the system (15 points). This is broken down as follows:
Features (based on the requirements you selected): 10 points
Design quality (Did you identify appropriate classes, their attributes, and methods): 
Programming style (Have you used proper names for variables, methods, and classes. Are the methods too appropriate length?): 2 points

## Iteration 2 - Version 2 Implementation

You will develop this version 2 in iteration 2 (Due: Check Canvas). Iteration 2 will involve:

Deciding what requirements you will implement for version 2,
Develop sequence diagrams,
Update the use case diagrams and class diagrams,
Implementing version 2,
Develop unit test cases.
Iteration 3 -  Version 3 Implementation

You will develop this version 3 in iteration 3 (Due: Check Canvas). Iteration 3 will involve:

Implementing all the requirements for your project,
Apply design patterns to your project,
Update use case diagrams, sequence diagrams, and class diagrams,
Develop system test cases,
Use test coverage tools to check the coverage of your test cases
________________________________________________________________________________________________________

## Iteration 3 Deliverables

Iteration 3. Design and Implementation of Version 3

100 points.
Tasks
Incorporate the feedback you received for iterations 1 and 2 into your design and code.
Change the code from iteration 2 to cleanly separate the user interface layer from the application and domain layers. Hint: use the facade pattern or any other patterns as necessary.
In your team meetings, flesh out the remaining requirements that should be completed under version 3 and implement them. Note any deviations from the original proposal and the reasons for those. 
Update any use cases and class diagrams, and sequence diagrams accordingly. Note: your class diagram should now show the applied design pattern/s.
Add appropriate unit test cases to test your implementation of version 3.
Develop system test cases (end-to-end) to test your application. Note that since your application has a GUI, we are going to conduct system testing manually using test scripts. You can see a sample test script here. Use the developed test scripts to test your application.
Use a coverage tool (such as EclEmma) to check the coverage of the JUnit test cases developed for your code. Use the coverage information to update your test suite.
Submission
Prepare a PDF document containing the following:
Updated design document (use cases, class diagrams, and sequence diagrams) (10 points)
System test cases (10 points)
Unit test coverage report (5 points)
A text file named README, that 1) lists the external file dependencies, if any, (user interface, logging, etc.), 2) shows how to run from command line, or eclipse run configurations, 3) deviations from the original proposal and the reasons and 4) what design patterns were used. (4 points)
Commit log (1 points). This log will help us determine a number of things, such as (1) level of individual participation, (2) adequate use of a version control system. If the document shows an inadequate amount of checkin and checkout, the team may lose points. If an individual has no corresponding entry in the log, this individual may lose a lot of points for not participating in the project (i.e., the penalty is not limited to the 1 points for submitting the commit log).
Prepare and submit a 5-10 minute video showing the completed functionality of your software.
Submit the following code in a single zip file (the test and implementation should be in separate folders). Note that the code must implement the design you provided above. Points will be deducted if it doesn't.
JUnit test code (5 points)
System implementation (You can name subpackages as you like: test, ui, view, model, core, etc.,) (60 points). This is broken down as follows:
Features: based on the completion of features that were listed in the original proposal or the variations based on proper reasoning (45 points)
Design quality: clear separation of the domain and user interface layers. Use of appropriate design patterns. Clearly defined domain classes with responsibilities. Coupling and cohesion levels of classes   (20points)
