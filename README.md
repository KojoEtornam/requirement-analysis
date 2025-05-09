                                                              Requirement Analysis in Software Development.

What is Requirement Analysis?
Requirement Analysis is a critical phase in the Software Development Lifecycle (SDLC) where the needs and expectations of stakeholders are gathered, analyzed, and documented to establish a clear understanding of what the software system must achieve. This process involves interaction with stakeholders such as clients, users, managers, and technical staff to ensure that all requirements are clearly understood and feasible.
                                        Objectives of Requirement Analysis
Identify the purpose and goals of the software.
Determine functional and non-functional requirements.
Resolve ambiguities, conflicts, and incomplete information.
Establish a baseline for project planning and development.
                                    Importance of Requirement Analysis in SDLC
Foundation for All Subsequent Phases:
Accurate requirements guide design, development, testing, and deployment.
Prevents Project Failures:
Most software project failures stem from poor requirements or misunderstood needs.
Saves Time and Cost:
Catching errors early in the requirement phase is far less expensive than fixing them later in development or post-deployment.
Improves Communication:
A well-documented set of requirements serves as a communication bridge between stakeholders and developers.
Ensures User Satisfaction:
Capturing true user needs leads to a product that meets or exceeds expectations.
Facilitates Testing and Validation:
Well-defined requirements serve as the basis for test case development and system validation.


                                                                  Why is Requirement Analysis Important?
  Prevents Project Failures
  Saves Time and Cost
  Improves Communication and Clarity


                                                                Key Activities in Requirement Analysis.
  1. Requirement Gathering
Involves collecting initial information about the system from stakeholders.

Focuses on understanding high-level business needs and objectives.

Sources include clients, users, business documents, and existing systems.

Often considered the starting point for the entire requirements process.

2. Requirement Elicitation
A deeper and more structured process than gathering.

Uses techniques like interviews, questionnaires, observations, brainstorming, and workshops.

Aims to uncover both expressed and unspoken requirements.

Helps in identifying conflicts, constraints, and assumptions early on.

3. Requirement Documentation
Involves writing clear, structured, and detailed descriptions of requirements.

Produces documents like the Software Requirements Specification (SRS).

Uses tools such as use cases, user stories, flowcharts, and UML diagrams.

Ensures all stakeholders can review and agree on what the system will deliver.

4. Requirement Analysis and Modeling
Focuses on evaluating and organizing gathered requirements.

Identifies relationships, dependencies, conflicts, and redundancies.

May use models (e.g., data flow diagrams, ER diagrams) to visualize system behavior.

Helps in prioritizing features and determining feasibility.

5. Requirement Validation
Ensures that the documented requirements accurately reflect stakeholder needs.

Checks for completeness, consistency, clarity, and testability.

Involves stakeholder reviews, walkthroughs, and prototyping.

Final validation leads to a baseline that guides design and development.

                                                                            
                                                                            Types of Requirements.
        Functional Requirements
        
Hotel managers can add, update, and delete hotel information (e.g., room availability, pricing, amenities).

Managers have a separate portal to manage hotel data.

Hotel service APIs must route through a load balancer to the correct service instance.

Data changes made by hotel managers must be synced to the slave database and sent to the CDN and messaging queue.

Customers can search for hotels using filters such as location, price, and ratings.

Customers can view personalized hotel listings and promotional offers from the CDN.

Customers can book hotels through a dedicated booking service.

        Non-Functional Requirements
        
The system must be scalable to handle high user traffic and large volumes of requests.

Ensure high availability using master-slave database architecture and distributed server clusters.

Maintain low latency for API responses using caching systems like Redis and fast search tools like ElasticSearch.

Data updates must be consistently and reliably synchronized across master and slave databases.

The CDN should deliver content quickly and globally for smooth user experience.

The system should be fault-tolerant, especially for third-party dependencies like payment gateways.

                                                                        Use Case Diagrams.
    A Use Case Diagram is a visual representation used in Unified Modeling Language (UML) to show the interactions between users (actors) and a system. It illustrates what the system does (its use cases) and who interacts with it. Use case diagrams are widely used during the requirement analysis phase of software development
Benefits of Use Case Diagrams
✅ Clarify System Functionality: They help stakeholders understand the system’s intended behavior.

✅ Identify System Boundaries: Clearly define what is inside and outside the scope of the system.

✅ Enhance Communication: Facilitate discussion between developers, clients, and end-users.
alx-booking-uc.png

                                                                      Acceptance Criteria.

  Acceptance Criteria are specific conditions or statements that a software product must satisfy to be accepted by the user, customer, or stakeholders. They are defined for each user story or feature during the requirement analysis phase and serve as a clear guideline for both development and testing teams. Acceptance criteria bridge the gap between requirements and implementation, ensuring that all parties have a common understanding of what a successful outcome looks like.

✅ The user must be able to view a summary of selected hotel, dates, room type, and total cost before confirming booking.

✅ The system must allow the user to enter or select payment details (e.g., credit card, digital wallet).

✅ The system must validate the payment details before processing.

✅ Upon successful payment, the booking must be stored in the booking database and a confirmation message must be displayed.

✅ A confirmation email and in-app notification must be sent to the user and the hotel manager.

✅ If payment fails, the user must be notified with a relevant error message and prompted to retry.

✅ The checkout process must complete within 5 seconds under normal load.


