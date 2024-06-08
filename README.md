[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15221696&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

Software engineering is a part of computer science that deals with the design, development, testing, and maintenance of software applications.

What is software engineering, and how does it differ from traditional programming?
Software Development Life Cycle (SDLC):

While software engineering requires advanced computer science and engineering skills, traditional programming solely focuses on writing and debugging code.

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models:

1. Planning - this is the first stage of the cycle and it includes developing high level plans of what the application needs to do or look like based on the clients/business requirements/needs.

2. Analysis - in this stage, the high level plans that the team came up with are then transformed into actionable ideas. They do this by analysing how to best implement them.

3. Design - the design stage is when the team focuses on how the application will look like or what it would do. In this stage UI/UX designs could be drawn to have a clear understanding on how users will interact with the application.

4. Implementaion - also called the coding stage is when the team actually writes the code for the application to run as planned.

5. Testing - after the code is written, it is tested. The test asssess the applications's functionality, security, perfomance, etc. When the code does not meet the requiements orr align with the goals established during the early stages of the SDLC, the team will need to change some code and debug it if any bugs or errors were found.

6. Deployment - in this stage the application is moved into production and is then available to users.

7. Maintenance - the final stage is to monitor the application continuously to check if issues arised once in production. If errors were somehow triggered then the team will need to fix them as soon as possible to improve user experience.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Requirements Engineering:

Waterfall model is known as Linear Sequential Life Cycle Model which means that the team only moves to the next stage of development or testing when the previous step is completed successfully, and in agile the development and testing are a continuous iteration. Which means they are concurrent, which allows for more communication between developers, testers, customers, etc.
The key differences between the two is that agile  prides itself on its adaptability and ability to accommodate changes even late in the development process, while Waterfall is chosen for its stability and defined stages. Agile encourages continuous customer or stakeholder involvement throughout the project, whereas Waterfall generally restricts customer involvement to the initial stages. And agile allows for early identification and mitigation of issues through its iterative nature, while Waterfall might only identify issues once testing occurs.
An example where waterfall model might be preffered is in construction. Because in construction, you only move to the next stage after successfully completing the previous one and need comprehensive planning outfront.
Agile model might be preffered in digital marketing campaigns where strategies will nned to be shared and adjusted based on real time market feedback.

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Software Design Principles:

Requirements Engineering is a process used in engineering projects to define, document, and maintain requirements. The RE has several phases which are important to the projects success. These phases are:
~ Feasibility study - assesss whether the project should proceed.
~ Requirement elicitation and analysis - information about what the client/stakeholders need for the project is collected then goes through analysis to ensure it is clear, actionable and achievable.
~ Software Requirement Specification - this is a document that includes detailed descriptions of the system's functions, capabilities, etc.
~ Software Requirement Validation - this is the phase where errors are checked from the Software Requirement Specification phase and also ensures that the requirements are met, relevant and testable. 
It is important in the software development lifecycle because it is used to translate the imprecise, incomplete needs and wishes of the potential users of software into complete, precise and formal specifications.

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Testing in Software Engineering:

Modularity in software design is a technique where complex software is divided into smaller, independent modules, such as functions, classes, or components. It facilitates easier management and understanding of complex systems by breaking them down into digestible parts. It improves maintainability by isolating changes and providing a clear structure. It also improves scalability by optimizing resource allocation and enabling parallel development.

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
Version Control Systems:

~ Unit tetsing checks if software components are fulfilling functionalities or not by testing each part of the software by separating it into small testable portions. This kind of testing is performed by developers.
~ Integration testing checks the data flow from one module to other modules by combining them as a group. This kind of testing is performed by testers.
~ System testing evaluates both functional and non-functional needs for the testing. It allows checking system’s compliance as per the requirements such as load, perfomance, reliability and security. System testing most often the final test to verify that the system meets the specification.
~ Acceptance testing checks if the requirements of a specification are met.
Testing is important because it evaluates the system's/application's compliance with the specified needs/requirements.

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Software Project Management:

Version control systems are software that help track changes made in code over time. As a developer edits code, the version control system takes a snapshot of the files, then saves that snapshot permanently so it can be recalled later if needed.
Popular version control systems are git, SVN(Subverion) and Mercurial.
~Features of Git:
- It is based on a distributed architecture which means that each member has a complete local copy of the database. Which allows for offline work and provides backup options.
- It is fast and effecient.
- And it has the ability to create branches and easily merge changes between them. Which allows developers to work on separate bug fixes without interfering with each other's work.
~ Features of SVN:
- It follows a centralized model where there is a single central repository.
- It enforces atomic commits, meaning that a commit is only accepted if all changes within it are valid. This ensures that the repository remains in a consistent state.
- And it  has a simpler learning curve compared to Git, making it more accessible to beginners.
~ Features of Mercurial:
- It is easy to learn.
- It provides several built-in extensions that enhance its functionalities, including code review, bug tracking integration, and more.
- It works seamlessly across different operating systems, allowing teams with diverse setups to collaborate effectively.

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Software Maintenance:

A software project manager is the most important person inside a team who takes the overall responsibilities to manage the software projects and plays an important role in the successful completion of the projects and has to face many challenges to accomplish this. The job responsibilities of a project manager range from activites like building up team morale to coming with customer presentations. Most of the managers take responsibility for writing the project proposal, project staffing, risk management, etc. 
A commomn challenge in software managing projects is unclear expectations. This happens when the manager might fail to gather requirements clearly from the clients, which may further complicate the progress of the project. Another challenge is when the needs of the client may change and impact the project because more time, cost and resouces will need to allocated.

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Ethical Considerations in Software Engineering:

Software maintenance is an integral part of the software life cycle that involves modifying and updating software after it has been deployed. The goal of maintenance is to correct faults, improve performance or other attributes, and adapt the software to a changing environment throughout its lifetime. It is essential because it ensures that software remains reliable and secure by fixing bugs, applying security updates, etc.
Software maintenance activities include optimization, error corrrection, deletion of discarded features and enhancing them. The error correction type deals with defects, deleting and enhancing features adapts software to changing environments to avoid future errors/issues. These activities mak sure the software remains secure and reliable.

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Ethical issues faced by software engineers include:
- Algorithmic bias
- Personal data collection and privacy
- Weak security protection
- Negative relationship between feature and impact and
- Open source collaboration
Software engineers can adhere to ethical standards in their work by familiarizing themselves with the ethical codes and guidelines, be transparent about software limitations, potential risks, etc, and avoid losing the user's trust. They could also practice protecting user data and privacy and always stay informed about ethical challenges and developments in the field of software engineering, and to continuously learn to stay up to date with technology/software trends.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
