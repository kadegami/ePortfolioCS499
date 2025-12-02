# Karina Washington – Computer Science ePortfolio
# ePortfolioCS499
# Professional Self-Assessment
Karina Washington – B.S. Computer Science Candidate, SNHU

As I complete CS 499 and reflect on my journey through the Computer Science program at SNHU, I can clearly see how my coursework and ePortfolio have transformed me from a student who was simply “getting assignments done” into an emerging professional who can design, implement, and communicate complete computing solutions. Throughout this program I balanced being a high school Spanish teacher, a mother, and a computer science student, often working through health challenges and a high-risk pregnancy. That experience shaped my values: persistence, empathy, and the desire to build technology that genuinely helps people learn and communicate. My ePortfolio is the culmination of that growth, showcasing not only what I can build, but how I think, collaborate, and plan as a professional.

Growth Through the Program and Career Direction

When I first entered the program, my main goal was to “learn to code.” Over time, that goal evolved into a clearer professional direction: I want to work at the intersection of software engineering, education, and user experience, building tools that support learners, including the young children I already teach Spanish to. The artifacts I selected for my ePortfolio—an OpenGL 3D scene from CS-330, a GPIO Morse code embedded system from CS-350, and the Travlr Getaways full-stack web app from CS-465—represent three major areas of computer science: software design and engineering, algorithms and data structures, and databases.

Beyond these three artifacts, other courses contributed to my development. In CS-250 and CS-320, I learned about the software development lifecycle and testing, which helped me think more systematically about planning enhancements, writing testable code, and documenting my work. In DAD-220 and web-related courses, I gained practical experience with SQL, NoSQL, and RESTful APIs, which later helped me feel comfortable improving the data layer in my Travlr Getaways project. Together, these experiences shaped my long-term goal of applying computer science to real-world educational products, such as my “Spanish with Miss Kari” content and potential future web or mobile apps for language learning.

Collaboration and Communication with Stakeholders

Throughout the program, I developed strategies for collaborating and communicating in a way that supports shared decision-making. Although many courses were online and individual, I still had to treat instructors, peers, and sometimes “future maintainers” of my code as stakeholders. In my capstone, the code review video functioned as a simulated collaboration environment: I had to walk through existing code, explain its functionality, identify weaknesses, and propose enhancements in language that a manager or teammate could easily understand.

This experience helped me practice structuring my explanations: beginning with context, then demonstrating code behavior, and finally linking suggested changes to program outcomes such as performance, maintainability, and security. Similarly, writing the enhancement narratives for each artifact required me to shift out of a purely technical mindset and into a more reflective, stakeholder-focused perspective. I had to justify why each enhancement mattered, describe trade-offs, and connect my technical decisions to broader goals like usability, safety, and long-term maintainability.

As a teacher, communication is already part of my identity. The program strengthened that skill in a technical context—helping me explain complex systems to non-experts, which is essential in roles where I may one day work with product owners, designers, other educators, or clients.

Algorithms and Data Structures

The CS-350 GPIO Morse Code Embedded System artifact best represents my growth in algorithms and data structures. In this project, I implemented a state machine that uses timers and interrupts to control LEDs and display Morse code messages such as “SOS” and “OK.” For the enhancement, I restructured the logic using a MorseStep struct array to model the timing, LED selection, and on/off state as data rather than scattered conditionals. This made the algorithm easier to read, extend, and reason about.

Through this work, I applied principles I learned in CS-260, such as decomposing behavior into discrete states, using arrays and enums to represent domain concepts, and thinking about time-based events as a sequence of transitions. I also learned how embedded constraints—such as fixed timer periods and limited resources—force you to design algorithms that are not just correct, but efficient and predictable. This enhancement showed me that even a simple blinking LED project can teach deep lessons about abstraction, control flow, and algorithm design.

Software Engineering and Databases

The CS-330 OpenGL 3D Scene is my primary artifact for software design and engineering. Originally, the project rendered a static desk scene. For the capstone, I enhanced it by adding modular shader management, an interactive orbit camera, and keyboard controls for light intensity. This required me to refactor the main loop, separate responsibilities between ViewManager, SceneManager, and ShaderManager, and carefully manage OpenGL state. These changes demonstrate my ability to architect a system, not just “make it work,” and to design code that could be extended later (for example, to add new objects, materials, or camera modes).

The CS-465 Travlr Getaways full-stack application shows my skills in databases and web engineering. In the original project, I implemented RESTful APIs, MongoDB schemas, and Angular views. For the enhancement, I focused on improving the structure, validation, and clarity of the database interactions. I refined Mongoose models to ensure stronger data integrity, updated controllers to handle errors more gracefully, and improved how trip details and reviews are retrieved and displayed. I also revisited how routes were organized to make the API more intuitive and maintainable.

Together, these artifacts show that I am comfortable working across the stack: from C++ graphics and memory management to Node.js, Express, and MongoDB. They also demonstrate that I can use industry-standard tools and libraries to deliver working solutions that align with real project goals, not just classroom exercises.

Security Mindset and Safe Design

Throughout the program, I gradually developed a stronger security mindset. Early on, I mostly focused on “happy path” behavior, but later courses and the capstone pushed me to think about error handling, input validation, and potential misuse of my systems. In the Travlr Getaways enhancement, I considered how invalid or unexpected data might enter the database and adjusted model validation and controller checks accordingly. Even though this is an academic project, approaching it as if it were deployed to the public helped me think more like a professional developer.

In embedded work like CS-350, I also learned to think about reliability and failure modes: what happens if inputs arrive out of order, if a button is pressed rapidly, or if the system restarts mid-sequence? While these may not be “hackers” in the traditional sense, they still represent potentially unsafe states that the software must guard against. These experiences taught me to anticipate problems before they occur and to design code that is resilient, not fragile.

How the Artifacts Fit Together

Each artifact in my ePortfolio highlights a different dimension of my abilities, but together they present a consistent story:

CS-330 (Software Design & Engineering): Shows my ability to design interactive, modular applications in C++ and OpenGL, manage complex rendering logic, and build user-friendly features like camera and lighting controls.

CS-350 (Algorithms & Data Structures): Demonstrates my understanding of state machines, time-based logic, interrupt-driven design, and how to translate requirements into efficient embedded algorithms.

CS-465 (Databases): Highlights my experience with full-stack web development, RESTful APIs, MongoDB schema design, and secure, maintainable handling of user and trip data.

Together with my code review video and enhancement narratives, these artifacts show that I can design and evaluate computing solutions, use appropriate tools and techniques, communicate my reasoning, and maintain a security-conscious mindset. They also align with my long-term goal of building interactive, user-focused systems—whether that is a 3D learning environment, an embedded educational device, or a full-stack application that supports real users.

Conclusion and Professional Readiness

Completing the CS program and building this ePortfolio has helped me clarify my strengths and career direction. I now see myself not just as a teacher who is learning to code, but as a computer science professional who can collaborate, communicate, and deliver complete solutions. I have practiced planning enhancements, refactoring legacy code, documenting my decisions, and thinking about security and usability from the beginning.

As I move forward, I plan to apply these skills to educational and user-centered technologies, continuing to grow in areas like cloud deployment, security, and interactive media. This professional self-assessment, along with my artifacts and narratives, serves as both a reflection on how far I have come and a starting point for the next phase of my career in computer science.


# Karina Washington – Computer Science ePortfolio

Welcome to my ePortfolio for SNHU’s CS-499 Capstone Project.  
Here, I showcase three key artifacts that demonstrate my skills across major computer science domains.

## 🟣 Software Design & Engineering
**CS-330: 3D Scene Project (OpenGL)**
- Developed an interactive 3D desk environment using C++ and OpenGL.
- Enhanced structure through modular scene and shader management.

[View Repository →](https://github.com/kadegami/CS330)

## 🟢 Algorithms & Data Structures
**CS-350: GPIO Morse Code Embedded System**
- Designed a state machine to control LEDs using interrupts and timers.
- Demonstrates algorithm design and embedded C programming.

[View Repository →](https://github.com/kadegami/CS-350)

## 🟠 Databases
**CS-465: Travlr Getaways (Full-Stack Web App)**
- Built with Node.js, Express, MongoDB, and Angular.
- Implements RESTful APIs, schema modeling, and CRUD operations.

[View Repository →](https://github.com/kadegami/CS-465)

## 🎥 Code Review Video

Here is my CS-499 Code Review Video for the capstone project:
https://www.youtube.com/watch?v=AKJuHGlMdjM

# 🔗🎯 Enhanced Artifacts (Original + Enhanced Files)


Below are the original and enhanced versions of my capstone artifacts.
Each repository includes:

A folder named CS499_Original_Project_Files

A folder named CS499_Enhancement1, CS499_Enhancement2, or CS499_Enhancement3

A written narrative (Word document)

All required source code

1️⃣ CS-330 – Software Design & Engineering (Enhancement 1)

Interactive OpenGL 3D Scene

Original project files folder

Enhanced project files folder

Enhancement narrative document

🔗 Repository:
https://github.com/kadegami/CS330

2️⃣ CS-350 – Algorithms & Data Structures (Enhancement 2)

Timer + Interrupt Morse Code State Machine

Original embedded system files

Enhanced version with improved algorithm logic and comments

Enhancement narrative document

🔗 Repository:
https://github.com/kadegami/CS-350

3️⃣ CS-465 – Databases (Enhancement 3)

Travlr Getaways Full Stack Application

Original MongoDB/Express/Node/Angular project

Enhanced features and improved database design

Enhancement narrative document

🔗 Repository:
https://github.com/kadegami/CS-465



