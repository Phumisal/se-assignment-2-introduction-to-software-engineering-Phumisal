[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15240735&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

What is software engineering, and how does it differ from traditional programming?

Software engineering is a systematic and disciplined approach to software development that aims to create high quality, reliable, and maintainable software. It is the branch of computer science that focuses on designing, developing, testing and maintaining software applications. It applies engineering principles, methods, tools and programming knowledge to create reliable and effective software products. 
Source: https://www.javatpoint.com/software-engineering

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Phases:
The Software Development Lifecycle consists of the following phases:
(i) The Requirements Phase - Gathering and documenting user needs and system requirements
Here the client (user) will define The Problem, User needs are The Problem. You as the software engineer will need system requirements to provide a solution to the user needs.
(ii) The Design Phase - Creating high-level and detailed designs of the software architecture and user interface.
Once the user needs have been defined, you will need to design/create a high level, detailed design of the software architecture ~ what the software will do and what the software will be doing and user interface ~ what the user will see i.e. computer graphics.
(iii) The Implementation Phase - Writing the code and building the software according to the design specifications
This phase entails the writing of the code and building the software according to the design specifications. The code is an instruction in a programme. It is a line or set of instructions in a programme, 
(iv) The Testing Phase - Conducting various tests to ensure the software meets quality standards and functional requirements. You have to test every module to assess the  following: To test the quality aspect and functional requirements of the code. Is the programme doing what it is intended to do? Are customer needs being met and is the client problem being resolved and is it of the quality expected. Is it doing what I wanted to do and how I wanted to do it and is it doing it the right way, am I getting the rightoutput, am I getting the right responses when using the programme.
(v) The Deployment Phase - This phase is where the software product is released to customers and users. 
(vi) The Maintenance Phase - Providing ongoing support, updates and enhancements to the software upon deployment. 

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

Waterfall Model - The Waterfall Model uses a sequential, step by step approach with distinct phases e.g. requirements, design, implementation, flowing downwards like a waterfall. 
The Agile Model on the other hand uses an iterative and incremental approach focused on flexibility, collaboration and responding to change 
Each methodology has its advantages and disadvantages, for example, with The Waterfall Approach, the stages are well defined making it easy to understand and implement, it’s linear approach makes it straightforward to grasp and put into practice and it also provides predictability and a clear distinct workflow. However, its rigidity makes it not suitable for complex projects as it does not test complex and object-oriented models at every stage. Moreover, it does not remove the error during the process. Waterfall model testing phase is the only stage which detects the error. Prior to the testing stage, there is no way to test if there are any mistakes or not. This is a major drawback of the Waterfall model because projects with moderate or high requirements are at increased risk of changing which cannot be done with this model. (source - 6 Advantages and Disadvantages of the Waterfall Model | Wadic )
In contrast, The Agile Approach which offers a dynamic and flexible approach to project management and product delivery. Agile adopts a more flexible and adaptive approach, allowing for continuous feedback and improvement, throughout the lifecycle. The Agile iteration workflow is a crucial aspect of this methodology, emphasizing short, manageable cycles of development known as iterations or sprints that provide rapid and tangible results and feedback and making human interaction a priority. It’s disadvantages however, include a high probability that it’s flexibility can lead to inconsistency and lack of predictability.
The Agile Methodology might be more suitable for longterm projects, like Facebook and other Social Media Applications.

The Agile Approach might be seen to be better than the Waterfall Approach because with Agile, ideas can follow up each other iteratively, you start with requirements and before you’re done, you can already move to the design phase and before you’re done with designing you can already begin testing the first module of code to see if all is working accordingly. Unlike like with the Waterfall model where you have to wait to first complete one phase before moving onto the next phase of the lifecycle and everything has to follow one after another in a orderly fashion, 

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirements engineering is the process of defining, maintaining and documenting requirements in the engineering design process. It involves identifying, eliciting, analyzing, specifying, validating, and managing the needs and expectations of stakeholders for a software system. Its processes and significance are:
Feasibility study:  this includes evaluation technical, operational and economic feasibility. Furthermore its assesses whether the project is viable in terms of resources, technology and costs. This ensures alignments with organizational goals.
Requirement elicitation: it involves gathering of information about the project domain and user needs. In addition, it also involves techniques like interviews, surveys and workshops. This is important to capture both financial and other requirements.
Requirements specification: this includes the use of cases, user stories and system specification to make sure documents requirements are in a clear and precise manner thus helps bridge the gap between stakeholders and development teams.
Requirements Verification and validation: this includes performing verification checks to determine whether requirements meet specified criteria. This ensures that requirements are complete, consistent and accurate and that system meets stakeholder expectations.
Requirements Management: involves tracking changes in requirements throughout the project and facilitating communication with stakeholders which is critical for delivering a successful software product. (geeksforgeeks.org)

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Modularity in software design refers to breaking down a complex system into smaller, self contained components or modules. Each module performs a specific task and interacts with other modules through well-defined interfaces. It improves maintainability by making it easier to update, debug enhance individual modules without impacting the whole system. New features can be added by extended or replacing specific modules thus improving scalability.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). 
The different levels of software testing are:
Unit Testing: this is testing individual components ( e.g functions) in isolation. It focuses on code-level functionality. For example, verify that an arithmetic function returns expected and correct results.
Integration Testing: it checks how components of the system interact with each other so that data can pass flawlessly within modules. This helps detect issues that may come up from component interactions. E.g  checking data from one module integrates correctly with another.
System testing: evaluates the whole system against functional and nonfunctional requirements. It involves end-to-end functionality e.g testing a web applications user database.
Accepting Testing: its purpose is to validate whether the software meets stakeholder expectations. It compares the software against specified criterias. This is important to determine if software is ready to be deployed. One example is checking if an app feature align with user requirements.()
Why is testing crucial in software development? 
Testing in software development is crucial because it helps in bug detection through identifying defects in the software. It also ensures quality of software as it helps check for security, performance and whether user expectations are met. In addition, testing reduces risk mitigation as it minimizes software to be deployed with faults thus preventing financial losses and legal issues. Lastly, testing enables user satisfaction, the software will get positive reviews and potentially get new users and increased adoption.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

What are Version Control Systems (VCS), and why are they important in software development? Give examples of popular version control systems and their features. 
Version Control systems are essential tools in software development that help developers to manage changes to source code, ensuring that modifications are trackable and reversible. VCS fosters collaboration, error recovery and code consistency all which are critical for successful software development.
VCS’s are important in Software Development for the following reasons:
(i) Streamlined Release Management:
VCS maintains different software versions, aligning with release roadmaps.
Each release captures all changes and features for specific customers.
(ii) Conflict Prevention:
Separate branches in VCS minimize code conflicts
Changes don’t overlap, reducing the risk of conflicts during development
(iii) Tracking Changes to Digital Artifacts:
VCS isn’t limited to code, it tracks changes to other artifacts e.g. design specs, requirements.
VCS ensures a comprehensive history of project iterations
Popular VCS include 
Local VCS: 
Stores changes locally before pushing to a central database.
Retrieving changes can be challenging if local versions or the central code become corrupted


Central VCS:
Hosts code versions in a centralized repository
Developers can access, push, and pull changes
Risk: If the central repository corrupts, retrieval becomes difficult


Distributed VCS (DVCS): 
Each developer has full copy of the repository
Examples include Git(GitHub and GitLab) and Subversion
Advantages: These repositories are robust, allowing for collaborations among developers and can work offline.


(Source: https://blog.logrocket.com/product-management/version-control-systems-definition-types/ 2: https://learn.microsoft.com/en-us/devops/develop/git/what-is-version-control)

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Software Maintenance:

The Role of a Software Project Manager:

The software project manager leads a team of developers and oversees the software project from start to finish, determining scope and setting deadlines, ensuring that projects are completed on time, within budget and to the satisfaction of the stakeholder. The responsibilities of the project manager include planning, execution, and project closure, they define the scope of the project, create schedules, allocate resources, manage risks, and monitor progress, whilst maintaining effective communication with clients, management, and team members.
In essence, software project managers play a critical role in successful project delivery by balancing technical expertise, leadership, and effective communication. 
Key Responsibilities:
Overseeing software projects from start to finish, determining scope and setting deadlines
Managing and motivating software developers and other team members, allocating roles and tasks
Coordinating the project’s internal and external teams, giving customer presentations and discussing new projects and proposals with stakeholders
Monitoring the project’s progress, key performance indicators and budget, and ensuring projects stay on schedule
Writing project proposals, reports and documentation
(source: what are the key responsibilities of a software project manager role - Search (bing.com) )
Challenges:
Some of the challenges faced in managing software projects include but are not limited to the following: 
Unclear and undefined expectations ~ Defining goals is crucial for a successful project. However, sometimes the project managers might fail to gather requirements clearly from the clients, which further complicates the progress. The expectations and objectives become ambiguous, and the output deviates from the actual results. The time and resources you spent will be for nothing. More than that, it will affect your image and reputation in the market.
This may cause the project to be delayed, incurring additional costs and compromising the quality of project output with client’s expectations unmet and demotivating the team.

Poor Communication ~ Poor communication with clients, other stakeholders, and the development team affects the overall project. 
miscommunication with clients will prevent getting the requirements, which will complicate the working process.
Conflict may arise in the team if members don’t communicate with each other, which can lead to their roles and responsibilities overlapping.
It is important to communicate and coordinate with each other for smooth operation. 
Time Constraints ~ unrealistic deadlines create pressure, which leads to more problems during the development process.
Changing Requirements and Priorities ~ One of the substantial challenges in software project management is changing requirements and priorities. The needs of the clients may change as the project progresses. And when that happens, extra time, cost, and resources need to be allocated, which further impacts the project.
This means planning, reviewing, and implementation of the new requirements into the existing ones which can be taxing on the project manager and the development team.
(Source: https://thedevpost.com/blog/challenges-in-software-project-management/ )  https://www.geeksforgeeks.org/software-engineering-software-project-management-spm/ )

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
 
Software maintenance is an ongoing process that spans the entire life cycle of a software system. It occurs after the software has been delivered to users and aims to ensure that the system remains functional, efficient, and secure over time. 
Bug Fixing: This includes activities such as bug fixing where errors and issues in the software are identified and resolved. 
Enhancements: Where adding new features or improving existing ones to meet evolving user needs.
Performance Optimization: To enhance speed, efficiency and reliability.
Porting and Migration: Adapting the software to run on new platforms.
Re-Engineering: Improving design and architecture for mainatinability.
Documentation: Creating and maintaining user manuals, technical specs, and design documents.
Software Maintenace is essential for the following reasons:
Longevity: Ensuring the continued operation of software systems so that they can last for years. 
User Satisfaction: Regular updates enhance user experience and prevent frustration.
Cost Saving: Proactive maintenance avoids expensive emergency fixes.
Security: Patching vulnerabilities keeps systems secure.
Competitiveness: Well-maintained software remains relevant in a dynamic market.
(Source: https://www.scrums.com/guides/the-4-main-categories-of-software-maintenance )

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

As with any profession, Software Engineers encounter various ethical challenges in their work, such as the ones listed below:


Algorithm Bias: Developing algorithms that unintentionally discriminate against certain groups due to biased training.
Personal Data Collection: Balancing data collection for functionality with user privacy concerns.
Weak Security Protection: Ensuring robust security measures to safeguard user data and prevent breaches.
Feature-Impact Relationship: Considering the impact of new features on users and society before implementation.
~ Ethical awareness is crucial for responsible software development. 


(Source: https://fellow.app/blog/engineering/engineering-everything-you-need-to-know-about-software-engineering-ethics/ )


How can software engineers ensure they adhere to ethical standards in their work? 


Software engineers can adhere to ethical standards by following established codes of ethics and professional practice, such as the one jointly approved by the ACM and the IEEE-CS. These principles guide software engineers in making ethical decisions that encompass responsibility, accountability, fairness and justice. Listed below are some key principles from this code:

Public Interest: Developers should act consistently with public interest in mind.
Professional Standards: Ensure products meet the highest professional standards.
Ethical judgement: Maintain integrity and independence in professional judgement.
Lifelong Learning: Engage in lifelong learning and promote ethical approach to the profession.

Software engineers play a crucial role in creating and maintaining software systems, and ethical considerations are essential. Here are some ways they can adhere to ethical standards:
Learn the Code of Ethics: Familiarize themselves with the Software Engineering Code of Ethics. This code, jointly developed by ACM and IEEE-CS, outlines principles that guide ethical behavior in software engineering1. It covers aspects like public interest, client and employer interests, product quality, professional judgment, and more.
Responsibility and Accountability: Software engineers should recognize their responsibility to society, users, and stakeholders. They must be accountable for the impact of their work.
Fairness and Justice: Treat all users fairly and avoid discrimination. Consider the broader societal implications of software decisions.
Quality Assurance: Ensure that software products meet high professional standards. Rigorous testing, security measures, and quality control are essential.
Integrity and Independence: Maintain integrity in professional judgment. Avoid conflicts of interest and undue influence.
Ethical Management: Software engineering managers should promote ethical practices in development and maintenance processes.
Professional Reputation: Uphold the integrity and reputation of the profession. Act in ways that enhance public trust.
Supportive Colleagues: Be fair and supportive to fellow software engineers. Collaboration and mutual respect are vital.
Lifelong Learning: Engage in continuous learning about ethical practices and stay informed about industry developments. 
Ethical decisions often involve complex trade-offs, but adhering to these principles helps create a positive impact on society and builds trust in the profession. 
(Source: https://www.institutedata.com/us/blog/software-engineering-code-of-ethics/ )

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
