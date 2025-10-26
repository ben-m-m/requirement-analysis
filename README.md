Requirement Analysis in Software Development
Introduction

This repository documents the Requirement Analysis phase for a Booking Management System.
The goal is to understand and define the system’s needs clearly before development begins.
It includes explanations of key concepts, categorized requirements, a use case diagram, and acceptance criteria — forming a solid blueprint for the software project.

What is Requirement Analysis?

Requirement Analysis is a crucial phase of the Software Development Lifecycle (SDLC) where project goals, user needs, and system expectations are gathered, analyzed, and documented.
It bridges the communication gap between stakeholders and developers to ensure that the final product meets business objectives.

Key points:

It identifies what the system should do (functional) and how it should perform (non-functional).

It reduces misunderstandings and rework by defining scope early.

It serves as the foundation for system design and development.

Why is Requirement Analysis Important?

Clarity and Understanding:
Ensures that all stakeholders — clients, developers, and testers — have a shared understanding of the project goals.

Prevents Costly Errors:
Detecting and fixing requirement-related issues early is far cheaper than doing so during development or deployment.

Improves Project Planning:
Clear requirements make it easier to estimate time, cost, and resources accurately.

Ensures User Satisfaction:
By directly involving end-users, the final system better matches their expectations and needs.

Key Activities in Requirement Analysis

Requirement Gathering:
Collecting raw requirements from stakeholders through interviews, surveys, and observations.

Requirement Elicitation:
Clarifying and refining gathered data to ensure it’s complete, consistent, and relevant.

Requirement Documentation:
Recording requirements formally using Software Requirement Specification (SRS) documents, diagrams, and user stories.

Requirement Analysis and Modeling:
Analyzing the relationships, dependencies, and feasibility of requirements using models and diagrams (e.g., use case diagrams).

Requirement Validation:
Confirming that documented requirements align with stakeholder goals and are testable, achievable, and unambiguous.

Types of Requirements
Functional Requirements

Functional requirements describe what the system should do — the specific features and interactions.

Examples for the Booking Management System:

Users can create, modify, and cancel bookings.

Admins can view all bookings and manage available rooms.

The system sends confirmation emails after successful payments.

Users can log in, view booking history, and make new reservations.

Non-functional Requirements

Non-functional requirements describe how the system should perform — its quality attributes and constraints.

Examples:

The system should load any page within 3 seconds under normal conditions.

It should support up to 1,000 concurrent users.

Data must be encrypted during transmission and storage.

The UI should be responsive across desktop and mobile devices.

The system should be available 99.9% of the time.

Use Case Diagrams

Definition:
A Use Case Diagram visually represents system interactions by showing relationships between actors (users or systems) and use cases (functionalities).

Benefits:

Clarifies user roles and system boundaries.

Simplifies communication between technical and non-technical stakeholders.

Serves as a foundation for writing user stories and test cases.

Booking Management System – Use Case Diagram

Actors:

Customer

Admin

Payment Gateway

Use Cases:

Create Booking

Modify/Cancel Booking

Make Payment

Receive Confirmation

Manage Rooms (Admin)

View Reports (Admin)

Acceptance Criteria

Definition:
Acceptance criteria are predefined conditions that must be met for a feature to be considered complete and acceptable to the end user.

Importance:

Ensures each feature meets user and business expectations.

Helps developers and testers validate functionality objectively.

Reduces ambiguity by defining “done” clearly for each requirement.

Example — Checkout Feature:

Criteria	Description
Successful Payment	When a user completes payment, the system confirms the transaction with the payment gateway and records it in the database.
Booking Confirmation	After payment, the user receives a booking confirmation email within 2 minutes.
Error Handling	If payment fails, the system displays an error message and allows the user to retry.
Data Validation	All mandatory fields (date, room type, name, payment details) must be filled before submission.
