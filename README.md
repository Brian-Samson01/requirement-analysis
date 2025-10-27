# 🧩 Requirement Analysis in Software Development

## 📖 Introduction
This repository is dedicated to documenting and exploring the **Requirement Analysis** phase of the Software Development Life Cycle (SDLC).  
Requirement analysis serves as the **foundation of software development**, ensuring that all project objectives, system needs, and stakeholder expectations are clearly defined before development begins.

The purpose of this project is to:
- Understand and apply the key principles of requirement analysis.
- Identify and document both **functional** and **non-functional** requirements.
- Visualize system interactions using diagrams created in **Draw.io** or similar tools.
- Establish **acceptance criteria** that align with business and user needs.

This repository will contain structured documentation, diagrams, and examples representing the real-world **requirement engineering process** for a **Booking Management System**.

🧠 What is Requirement Analysis?

Requirement Analysis is the process of identifying, documenting, and managing the needs and expectations of stakeholders for a software system. It is the first and most critical phase of the Software Development Life Cycle (SDLC), as it establishes the foundation upon which the entire project is built.

During requirement analysis, the development team works closely with clients, end-users, and other stakeholders to determine what the system should do and how it should perform. The main goal is to bridge the gap between a stakeholder’s ideas and a developer’s implementation plan.

🔍 Key Activities in Requirement Analysis

Elicitation – Gathering requirements from stakeholders using interviews, surveys, observations, and brainstorming sessions.

Analysis – Evaluating the gathered information to identify conflicts, ambiguities, or inconsistencies.

Specification – Clearly documenting the requirements in a structured format such as a Software Requirements Specification (SRS) document.

Validation – Ensuring that the documented requirements accurately reflect stakeholder needs.

Management – Tracking and updating requirements as the project evolves.

🚀 Importance of Requirement Analysis in SDLC

Prevents misunderstandings between clients and developers.

Ensures project alignment with business goals and user needs.

Reduces development costs by identifying issues early before implementation.

Improves system quality through clear and testable requirements.

Guides design, testing, and maintenance activities effectively.

In short, requirement analysis serves as a blueprint for building successful software systems—ensuring that every stakeholder has a shared understanding of what the system should deliver.


💡 Why is Requirement Analysis Important?

Requirement Analysis plays a vital role in ensuring the success of any software development project. It serves as the foundation for design, development, and testing, ensuring that the final system meets user expectations and business goals. Without thorough requirement analysis, projects often face challenges like cost overruns, missed deadlines, and product failures.

Here are three key reasons why Requirement Analysis is critical in the Software Development Life Cycle (SDLC):

1. 🎯 Ensures Clear Understanding of Project Goals

Requirement analysis helps all stakeholders — clients, users, and developers — achieve a shared understanding of what needs to be built. It eliminates ambiguity by translating business needs into precise, actionable requirements. This clarity ensures that the development process stays aligned with user and business objectives.

2. 💰 Reduces Development Costs and Rework

By identifying requirements early, teams can detect and fix misunderstandings before coding begins, which is much cheaper and faster than fixing them later. Effective requirement analysis minimizes unnecessary rework, helping organizations save time, effort, and resources throughout the project lifecycle.

3. ⚙️ Improves System Quality and User Satisfaction

When requirements are well-defined, developers can design and build systems that perform as expected, leading to better reliability, usability, and performance. Accurate requirements also help testers create precise test cases, ensuring that the final product meets stakeholder expectations and delivers a high-quality user experience.


⚙️ Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities that ensure a clear, comprehensive, and validated understanding of what a system must achieve. Each activity plays a crucial role in shaping the foundation of the software development process.

Below are the five key activities in Requirement Analysis:

📝 1. Requirement Gathering

Involves collecting information from stakeholders, users, and other sources about what the system should do.

Uses methods such as interviews, surveys, questionnaires, observations, and reviewing existing documentation.

The main goal is to capture all possible requirements — both functional and non-functional — to guide system development.

💬 2. Requirement Elicitation

Focuses on drawing out requirements through interactive communication with stakeholders.

Helps uncover hidden, implicit, or conflicting needs that may not be obvious at first.

Techniques include brainstorming sessions, workshops, prototyping, and use case discussions to refine the requirements.

📄 3. Requirement Documentation

The gathered and elicited requirements are documented formally in clear and structured formats such as a Software Requirements Specification (SRS) document.

Ensures that all team members have a single source of truth for project expectations.

Documentation includes functional, non-functional, and system constraints.

🔍 4. Requirement Analysis and Modeling

Involves examining, refining, and prioritizing requirements to ensure they are feasible, consistent, and unambiguous.

Modeling techniques like use case diagrams, data flow diagrams (DFDs), and entity-relationship diagrams (ERDs) are used to visualize system behavior and data interactions.

This step bridges the gap between user needs and technical implementation.

✅ 5. Requirement Validation

Ensures that the documented requirements accurately represent stakeholder needs and are practical to implement.

Involves review sessions, inspections, walkthroughs, and prototyping to confirm understanding and agreement.

Validation helps detect and correct inconsistencies or missing requirements before development begins.

✅ Summary

These five activities collectively help ensure that software requirements are complete, correct, and aligned with user expectations — setting the foundation for a successful software development project.


🧩 Types of Requirements

In software engineering, requirements are broadly categorized into Functional and Non-functional Requirements.
Both types are essential to ensure the system operates correctly and meets user expectations.
Below is an explanation and examples based on the Booking Management System case study.

⚙️ 1. Functional Requirements

Functional requirements describe what the system should do — the specific behaviors, features, and functions that define how users interact with the system.
They define inputs, outputs, and processes necessary to meet user and business needs.

Examples for the Booking Management System:

✅ Users should be able to search for available properties based on date, location, and price range.

✅ The system should allow users to create an account, log in, and log out securely.

✅ Users should be able to book a property and receive a confirmation email with booking details.

✅ The system should allow property owners to list, edit, and delete their property details.

✅ Administrators should be able to approve, suspend, or remove property listings.

✅ The system should generate booking invoices and allow users to view booking history.

Functional requirements ensure that the core operations of the booking system function as intended.

🧠 2. Non-functional Requirements

Non-functional requirements describe how the system performs rather than what it does.
They define the quality attributes of the system, such as performance, usability, security, and reliability.

Examples for the Booking Management System:

⚡ The system should be able to handle up to 1,000 concurrent users without performance degradation.

🔒 All sensitive user data (e.g., passwords, payment details) should be encrypted using industry standards.

⏱️ The system should ensure that search results are displayed within 3 seconds.

🧭 The interface should be responsive and accessible, supporting both desktop and mobile devices.

🕒 The system should have 99.9% uptime availability to ensure continuous service.

🧩 The application should be scalable, allowing for easy integration of additional modules (e.g., reviews, loyalty programs).

Non-functional requirements ensure the overall quality, security, and performance of the booking management system.

✅ Summary

Functional requirements define what the system does, while non-functional requirements define how well it performs.
Both are crucial for building a robust, user-friendly, and efficient booking management system.


🎯 Use Case Diagrams
🧩 What is a Use Case Diagram?

A Use Case Diagram is a visual representation that shows how users (known as actors) interact with a system to achieve specific goals (use cases). It helps in understanding system functionality, user roles, and interactions between components during the Requirement Analysis phase.

Use Case Diagrams are part of the Unified Modeling Language (UML) and are commonly used during system analysis and design.

💡 Benefits of Use Case Diagrams

📘 Provides a clear understanding of system boundaries and how different users interact with it.

👥 Helps identify all possible user interactions with the system.

🧭 Aids communication between developers, stakeholders, and designers.

🧱 Serves as a foundation for writing detailed use case scenarios and test cases.

🔍 Ensures all functional requirements are captured early in the SDLC.

👨‍💻 Actors in the Booking Management System

User/Customer – Searches for properties, books stays, and manages bookings.

Property Owner – Lists, updates, and manages property information.

Admin – Manages users, verifies listings, and monitors system activities.

🧾 Use Cases

Some of the main use cases for the Booking Management System include:

Register and Login

Search for Properties

View Property Details

Make a Booking

Process Payment

Manage Bookings

Add/Edit Property Listings (for Owners)

Approve Listings (for Admin)

Generate Reports (for Admin)

🖼️ Use Case Diagram

Below is the use case diagram for the Booking Management System, illustrating interactions between actors and the system’s main functionalities
<img width="1114" height="652" alt="alx-booking-uc" src="https://github.com/user-attachments/assets/3be2f7ad-c906-43f8-964c-d5cdc2a6428c" />
<img width="1114" height="652" alt="alx-booking-uc" src="https://github.com/user-attachments/assets/617f5809-28ae-4e73-93c6-4cf1d0a630a0" />


Acceptance Criteria
What is Acceptance Criteria?

Acceptance Criteria are specific, measurable conditions that a software product must satisfy to be accepted by the client or stakeholders.
They define what needs to be done for a feature or user story to be considered complete and working as expected.

Acceptance Criteria are written before development begins, serving as a bridge between requirements and testing.
They ensure both the development team and the client share the same understanding of the feature’s behavior and expected outcomes.

Importance of Acceptance Criteria

✅ Clarifies Expectations – Clearly defines what the system should do, minimizing ambiguity.

🧩 Guides Development – Helps developers understand the exact functionality to implement.

🧪 Facilitates Testing – Provides a basis for creating test cases to verify functionality.

🧭 Supports Acceptance Decisions – Helps stakeholders decide if a feature is complete and acceptable.

Example: Acceptance Criteria for the Checkout Feature

Feature: Checkout

Description:
This feature allows users to complete their booking by reviewing booking details, making payments, and receiving confirmation.

Acceptance Criteria:

The system must display the booking summary, including selected dates, room type, and total cost before payment.

The user must be able to select a payment method (credit card, PayPal, or mobile money).

The system must validate payment details before processing.

Upon successful payment, the user must receive a confirmation message and an email receipt.

If payment fails, the system should display an error message and allow retry.

The checkout process must complete within 3 minutes under normal conditions.
