# Requirement Analysis in Software Development.

## 📌 What is Requirement Analysis?

**Requirement Analysis** is a critical process in the Software Development Life Cycle (SDLC) that involves identifying, gathering, analyzing, and documenting the needs and expectations of stakeholders for a software system.

It serves as the foundation for all future stages of development by clearly defining:

- **What** the system should do (Functional Requirements)
- **How well** the system should perform (Non-functional Requirements)

---

## 🎯 Why is Requirement Analysis Important?

Requirement Analysis plays a vital role in the SDLC due to the following reasons:

### ✅ Clarity and Shared Understanding
Ensures that stakeholders and the development team are on the same page about the system’s objectives and functions.

### ✅ Accurate Project Planning
Allows for more precise estimation of time, budget, and resources.

### ✅ Reduced Rework and Cost
Minimizes misunderstandings and the need for costly changes later in the project.

### ✅ Better Design and Development
Provides a clear blueprint for developers to build the system correctly the first time.

### ✅ Effective Testing
Serves as the basis for creating test cases and ensures that the system meets the expected requirements.

### ✅ Easier Change Management
Helps in assessing the impact of any changes made during the development cycle.

---

## 🧩 Types of Requirements

Requirements are generally categorized into two main types:

### 1. ⚙️ Functional Requirements

These describe what the system **should do**—the core functions and behaviors.

**Definition:**  
Functional requirements specify specific actions or tasks the system must perform to meet user and business needs.

**Examples for a Booking Management System:**
- Users can **search available bookings** by date and category.
- The system allows **user registration and login** with verification.
- Admins can **create, update, or delete** booking records.
- The system **sends a confirmation email** upon successful booking.

---

### 2. 🚀 Non-functional Requirements

These describe **how well** the system should perform—its quality attributes.

**Definition:**  
Non-functional requirements define performance, usability, reliability, and other operational aspects of the system.

**Examples for a Booking Management System:**
- The system must **load any page within 3 seconds** under normal load.
- The platform should support **1,000 concurrent users** without performance degradation.
- The application must be **available 99.9% of the time** (high availability).
- User data should be **encrypted both at rest and in transit**.

---

## 🛠️ Key Activities in Requirement Analysis

The requirement analysis process includes five key activities, each playing a crucial role in ensuring comprehensive and accurate requirements.

### 1. 📥 Requirement Gathering
Collect raw information from stakeholders, users, and existing systems.
> Techniques: Interviews, surveys, document review

### 2. 🗣️ Requirement Elicitation
Uncover implicit or hidden needs through structured interaction.
> Techniques: Workshops, prototyping, brainstorming

### 3. 📝 Requirement Documentation
Clearly record requirements in SRS or other formats for shared understanding.
> Tools: SRS templates, user stories, flowcharts

### 4. 📊 Requirement Analysis and Modeling
Refine, prioritize, and model requirements to resolve conflicts and ensure clarity.
> Models: Use Case Diagrams, ERD, DFD, Activity Diagrams

### 5. ✅ Requirement Validation
Confirm that requirements are correct, feasible, and aligned with business goals.
> Techniques: Walkthroughs, reviews, stakeholder sign-offs

---

## ✅ Acceptance Criteria

### 🔍 What is Acceptance Criteria?

**Acceptance Criteria** define the specific conditions under which a feature or function is considered complete and acceptable by the client or stakeholders.

### 📌 Importance in Requirement Analysis

- Acts as the **“definition of done”** for each requirement
- Ensures **shared understanding** between developers, testers, and stakeholders
- Helps testers to create **precise test cases**
- Reduces ambiguity and **prevents scope creep**

### 🛒 Example: Acceptance Criteria for the **Checkout Feature** in a Booking Management System

**Feature:** User Checkout

**Acceptance Criteria:**
- ✅ The user must be able to view a summary of their selected bookings.
- ✅ The system must calculate the total price, including applicable taxes or discounts.
- ✅ The user must be able to select a payment method (credit card, PayPal, etc.).
- ✅ On successful payment, a booking confirmation page is shown.
- ✅ A confirmation email with booking details is sent within 5 minutes.
- ✅ If payment fails, the user receives an appropriate error message and can retry.

---

## 📉 Risks of Poor Requirement Analysis

- Project delays
- Increased cost
- Unsatisfied users
- Scope creep
- Failure to meet business goals

---

## ✅ Best Practices

- Engage stakeholders early and continuously
- Use visual tools (UML, flowcharts, wireframes)
- Prioritize requirements (MoSCoW method)
- Keep documentation clear, concise, and version-controlled
- Validate requirements regularly with all stakeholders

---

## 📘 Conclusion

Requirement Analysis is a foundational process in the SDLC. It ensures that software is built to solve the right problem in the right way. Investing in good requirement analysis leads to successful projects, reduced costs, and satisfied users.

---

## 📎 Related Documents

- [Software Requirements Specification (SRS)](docs/SRS.md)
- [Use Case Diagrams](docs/use-cases.md)
- [Prototypes and Mockups](docs/prototypes.md)

> _“If you don't fully understand the problem, any solution you build is guaranteed to be wrong.”_
