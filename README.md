## What is Requirement Analysis?

**Requirement Analysis** is a critical phase in the Software Development Life Cycle (SDLC) that involves **gathering, analyzing, and defining the requirements** of a software system. It ensures that the system meets the needs of stakeholders, including users, clients, and project sponsors. 

During this phase, analysts work closely with stakeholders to **understand what the system should do** (functional requirements) and **how well it should perform** (non-functional requirements). Key activities include:

- **Requirement Gathering:** Collecting information from stakeholders through interviews, surveys, workshops, and observation.
- **Requirement Elicitation:** Refining and elaborating on gathered requirements using techniques like brainstorming, prototyping, and use case modeling.
- **Requirement Documentation:** Creating detailed specifications, use cases, and requirement documents to provide a clear reference for the development team.
- **Requirement Validation:** Reviewing and confirming requirements with stakeholders to ensure accuracy, completeness, and feasibility.

**Importance of Requirement Analysis in SDLC:**

1. **Defines Project Scope:** Clearly outlines what the system will and will not do, reducing ambiguity.
2. **Prevents Scope Creep:** Helps manage changes effectively by establishing agreed-upon requirements.
3. **Improves Resource Allocation:** Prioritizes essential features, ensuring efficient use of time, budget, and human resources.
4. **Enhances System Quality:** By identifying potential issues early, it contributes to building a reliable, user-friendly, and secure system.
5. **Facilitates Communication:** Provides a common understanding between stakeholders and the development team, minimizing misunderstandings.

In summary, Requirement Analysis lays the foundation for a successful software project by ensuring that the system delivers **value, meets user expectations, and aligns with business goals**.

## Why is Requirement Analysis Important?

Requirement Analysis is a crucial phase in the Software Development Life Cycle (SDLC) because it lays the foundation for a successful project. Here are three key reasons why it is important:

1. **Defines Clear Project Scope:**  
   Requirement Analysis helps in specifying exactly what the system will deliver, which reduces ambiguity and sets clear boundaries for the project.

2. **Prevents Scope Creep:**  
   By documenting and agreeing on requirements upfront, it minimizes the risk of uncontrolled changes during development, ensuring the project stays on track.

3. **Ensures Efficient Resource Allocation:**  
   Prioritizing requirements allows teams to focus on high-value features first, optimizing the use of time, budget, and personnel.

4. **Improves System Quality:**  
   Early identification and clarification of requirements lead to fewer errors, better design decisions, and a system that meets stakeholder expectations.

5. **Enhances Communication:**  
   Clear documentation and validation of requirements ensure all stakeholders and team members share a common understanding, reducing misunderstandings.

## Key Activities in Requirement Analysis

Requirement Analysis involves several key activities that ensure the system meets stakeholder needs effectively:

- **Requirement Gathering:**  
  Collecting information from stakeholders through interviews, surveys, workshops, and observations to understand their needs and expectations.

- **Requirement Elicitation:**  
  Refining and elaborating on gathered requirements using techniques like brainstorming, prototyping, and use case modeling to extract detailed insights.

- **Requirement Documentation:**  
  Creating clear and detailed requirement specifications, use cases, and other documentation to provide a reference for the development team.

- **Requirement Analysis and Modeling:**  
  Analyzing the requirements to detect conflicts, redundancies, and feasibility issues. Modeling tools like flowcharts and UML diagrams are used to visualize system behavior.

- **Requirement Validation:**  
  Reviewing requirements with stakeholders to ensure they are accurate, complete, consistent, and aligned with business goals before development begins.

## Types of Requirements

### Functional Requirements

**Definition:**  
Functional requirements specify **what the system should do**—the core functionalities that the system must support to meet user needs.

**Examples for the Hotel Booking Management System:**

- **User Registration:** Users must be able to create an account by providing personal details, email, and password.
- **Room Search:** Users should be able to search for available rooms based on criteria like location, dates, and room type.
- **Booking Management:** Users can book, modify, or cancel reservations through the system.
- **Payment Processing:** The system must support secure payment methods for booking confirmations.
- **User Authentication:** Implement login and logout functionalities to secure user sessions.

### Non-functional Requirements

**Definition:**  
Non-functional requirements describe **how the system performs**—the quality attributes that the system must exhibit.

**Examples for the Hotel Booking Management System:**

- **Performance:** The system should handle up to 500 transactions per second during peak times.
- **Scalability:** The architecture must support scaling to accommodate increasing numbers of users and data.
- **Availability:** The system should ensure 99.9% uptime, providing continuous service availability.
- **Security:** Implement encryption for sensitive data and comply with industry standards for data protection.
- **Usability:** The user interface should be intuitive and accessible across various devices and browsers.

## Use Case Diagrams

**Definition:**  
A **Use Case Diagram** is a visual representation of the interactions between **users (actors)** and a **system**. It helps to illustrate the system’s functional requirements and shows how users achieve specific goals through different use cases.

**Benefits of Use Case Diagrams:**

- Provides a clear overview of system functionality from the user’s perspective.  
- Helps identify all actors and their interactions with the system.  
- Facilitates communication between stakeholders and the development team.  
- Serves as a reference for requirement validation and system design.

**Use Case Diagram for the Booking System:**  

Below is a use case diagram for the hotel booking system, illustrating the main actors and their interactions with the system:

**Actors:**  
- Guest  
- Registered User  
- Admin  

**Use Cases:**  
- Register / Login  
- Search Rooms  
- Make Booking  
- Cancel Booking  
- Process Payment  
- Manage Listings (Admin)  

**Diagram:**  

[Booking System Use Case Diagram](alx-booking-uc.png)

## Acceptance Criteria

**Definition:**  
**Acceptance Criteria** are the specific conditions or standards that a feature must meet to be considered complete and acceptable by stakeholders. They define what “done” means for a requirement and ensure that the delivered functionality aligns with user expectations.

**Importance in Requirement Analysis:**  

- Ensures clarity on what needs to be delivered for each feature.  
- Reduces misunderstandings between stakeholders and the development team.  
- Helps in **testing and validation** by providing measurable conditions for success.  
- Prevents scope creep by clearly defining boundaries for feature completion.  

**Example: Checkout Feature in the Booking Management System**

For the **Checkout** feature, the acceptance criteria could include:

1. Users can review their booking details before final confirmation.  
2. Payment options (credit card, PayPal, etc.) are available and functional.  
3. Successful payment triggers a booking confirmation email.  
4. Users cannot proceed with checkout if required fields (e.g., payment information, contact details) are missing.  
5. The system updates room availability immediately after a successful booking.  
6. The checkout process should complete within 10 seconds under normal load.


