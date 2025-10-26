# Requirement Analysis in Software Development.

The Requirement Analysis Project focuses on crafting a comprehensive foundation for software development by documenting, analysing, and structuring requirements. Through a series of well-defined tasks, this repository provides a detailed blueprint of the requirements analysis phase for a booking management system. This project simulates a real-world development scenario, emphasising clarity, precision, and structure in defining requirements to set the stage for successful project execution.

## What is Requirement Analysis?

Requirement analysis is the process of understanding and documenting what an application needs before coding starts. In frontend development specifically, this means figuring out:

* What users will see (the user interface/UI)
* How users will interact with an application (clicking buttons, filling forms, navigating pages)
* What data needs to be displayed (user profiles, product lists, etc.)
* Which devices it must work on (mobile phones, tablets, desktops)
* Performance expectations (how fast pages should load)

Requirements analysis is important because it:

* Prevents Costly Mistakes
  Fixing bugs found during requirement analysis costs almost nothing. Fixing the same issue after deployment can cost 100x more because you've already written code, tested it, and deployed it.
* Sets Clear Expectations
  Everyone (developers, designers, clients) knows exactly what's being built. No surprises like "Wait, I thought the button would be blue!"
* Enables Better Planning
  You can accurately estimate the time required for development and the necessary resources. If requirements say you need a complex animation, you know to allocate time for that.
* Improves Code Quality
  When you understand requirements deeply, you write more maintainable code. You'll choose the right HTML semantic tags, structure your CSS logically, and organise JavaScript functions properly.
* Facilitates Testing
  Clear requirements become test cases. If the requirement says "form must show error for invalid email," that's exactly what testers will check.

## Why is Requirement Analysis Important?

### Saves Time and Money

Imagine building an entire website using a top-aligned navigation menu, then the client says "Actually, I wanted the menu on the left side, not the top." Now the HTML structure needs to be restructured, the CSS layout must be completely redone, and JavaScript event handlers possibly need to be rewritten. This could take days or even weeks to fix. With proper requirement analysis, it would have been known from day one that the menu goes on the left, and it would have been built correctly the first time. The cost difference is dramatic. Fixing a mistake during the requirements phase costs almost nothing because only a document needs updating. Fixing the same mistake after deployment can cost fifty to one hundred times more because it involves code changes, retesting, and redeployment.

### Creates Shared Understanding

Without clear requirements, misunderstandings are inevitable. One developer might think the submit button should be blue based on common conventions. The designer thinks it should be green to match the company's brand colours. The client expected it to be red because that's what their competitor uses. The result is conflict, wasted work, and frustration for everyone involved. When requirements are properly documented and agreed upon before development starts, everyone is on the same page. The designer, developers, and client all know exactly what's being built. This alignment eliminates surprises and ensures that the final product matches everyone's expectations.

### Enables Better Planning and Estimates

When all requirements are known upfront, accurate plans and estimates can be made. The project timeline can be determined, whether it's three weeks or three months. The necessary skills and knowledge can be identified, such as whether basic CSS or advanced animation capabilities are needed. Decisions about which libraries and frameworks to use can be made based on the complexity and requirements. For instance, if the requirements show that complex state management and reusable components are needed, React might be chosen. If it's a simple static site, vanilla JavaScript and CSS might be sufficient. This planning phase prevents a situation where development starts only to realise halfway through that the wrong tools were chosen.

### Guides Development

Requirements become a roadmap during development. Instead of sitting at the computer wondering "What should be built next?" or "How should this feature work?", there's a clear list of tasks prioritised and defined. The developer knows that first the navigation bar will be built over two days, then the login form will be created in one day, then the product gallery will be added over three days. Each morning, the requirements document can be consulted to know exactly what needs to be worked on. This structure is especially helpful for beginners who might otherwise feel overwhelmed by the scope of a project.

### Makes Testing Possible

Every requirement documented becomes a test case when the testing phase is reached. If a requirement states "Email field must show an error message for invalid email formats," the test case becomes: enter an invalid email like "notanemail" and verify that an error message appears. If the requirement says "The page must load within 3 seconds," browser tools can be used to measure load time and verify it meets this standard. Without clear requirements, testing becomes guesswork. How does one know if something works correctly if what "correct" means was never defined? Requirements provide that definition.

### Prevents Scope Creep

Scope creep is a common problem in software development where projects keep growing with new features that weren't originally planned. This causes delays, budget overruns, and developer burnout. With properly documented requirements, there's a defence against scope creep. When someone suggests a new feature mid-project, the requirements document can be referenced to say, "That's a great idea, but it wasn't in the original requirements. Let's document it as a future enhancement for version two." This keeps the current project focused and manageable while still acknowledging good ideas for the future.

## Key Activities in Requirement Analysis.

* Requirement Gathering
  
Requirement gathering is the broad initial phase where all information about what a project needs is collected. It's the umbrella activity that encompasses discovering stakeholder expectations, understanding business context, and identifying project constraints. This phase casts a wide net to capture every piece of relevant information before narrowing down to specific requirements. The process uses multiple techniques to collect comprehensive information. Stakeholder interviews provide direct conversations with clients, users, and team members about their needs and expectations. Surveys reach larger audiences when many users need to provide input. Document analysis examines existing materials like business plans, competitor websites, or current system documentation to understand context. User observation involves watching people perform their current tasks to identify pain points and opportunities they might not articulate verbally. Workshops bring multiple stakeholders together for collaborative discussions that surface needs and priorities through group interaction.

* Requirement Elicitation
  
Requirement elicitation is the focused, interactive process of drawing out specific requirements from stakeholders through active questioning and engagement. While gathering broadly collects information, elicitation specifically targets the extraction of concrete, detailed requirements. The distinction is important because stakeholders rarely present requirements in a clear, complete form. They often have vague ideas, unstated assumptions, or conflicting desires that elicitation techniques help uncover and clarify.
Different techniques suit different situations and stakeholder types. Open-ended interviews encourage stakeholders to share detailed perspectives through questions like "Walk me through your current workflow" or "What would make this process easier?" Brainstorming sessions generate creative ideas and help participants think beyond current limitations. Prototyping creates quick mockups or wireframes that stakeholders can react to, which is valuable because people often can't articulate what they want until they see something concrete. Focus groups leverage group dynamics to surface requirements that individual conversations might miss. Use case scenarios describe specific user interactions with the system, making abstract requirements more tangible.
The critical skill in elicitation is asking effective follow-up questions that transform vague statements into specific requirements. When a client says, "I want the site to load fast," effective elicitation asks, "What does fast mean specifically? Under 2 seconds? 5 seconds? Is initial page load or subsequent navigation more important?" This probing converts general desires into measurable, actionable requirements. Elicitation also uncovers hidden requirements by asking about edge cases, error conditions, and alternative scenarios that stakeholders might not mention without prompting.

* Requirement Documentation
  
Requirement documentation records all gathered and elicited requirements in structured, clear formats that serve as the authoritative reference throughout the project. Without proper documentation, requirements exist only in people's memories or scattered across email threads, making them impossible to track, verify, or use as a shared reference. Documentation ensures all team members and stakeholders access the same information and understand what needs to be built. Quality documentation has specific characteristics. Requirements should be atomic, describing single specific needs rather than bundling multiple concerns. They must be unambiguous so that different readers interpret them identically. Requirements need to be testable, meaning verification of their implementation is possible. They should be feasible given the project constraints of time, budget, and technology. Requirements must be necessary, directly supporting project goals rather than including nice-to-have features. Finally, they should be prioritised using methods like MoSCoW categorisation to guide development decisions when resources become constrained.

* Requirement Analysis and Modeling
  
Requirement analysis examines documented requirements critically to ensure they're complete, consistent, and feasible before development begins. This phase involves deep thinking about what's been gathered and documented, looking for gaps where important requirements are missing, conflicts where requirements contradict each other, and ambiguities where multiple interpretations are possible. Analysis also breaks down high-level requirements into detailed, granular sub-requirements that developers can actually implement. Analysis also assesses feasibility across multiple dimensions. Technical feasibility determines whether requirements can be implemented with available technologies and team expertise. A requirement for real-time collaboration might be technically possible but require WebSocket technology the team hasn't used before. Schedule feasibility evaluates whether requirements fit within the project timeline. Cost feasibility checks whether the implementation stays within budget. This analysis often leads to requirement refinement where specifications are adjusted to be more realistic, or features are phased with critical functionality in the first release and enhancements in subsequent versions.

* Requirement Validation
  
Requirement validation ensures that documented requirements are correct, complete, and aligned with stakeholder needs before development begins. Validation answers "Are we building the right thing?" which differs from verification that asks "Are we building the thing right?" The distinction is crucial because validation catches errors in requirements when they're cheapest to fix, before significant time and resources have been invested in implementation. When validation reveals problems, requirements undergo revision cycles where stakeholders provide feedback, documentation is updated, and validation happens again. This iteration continues until stakeholders formally sign off, agreeing that documented requirements represent what should be built. This baseline protects both the development team and the client by providing clear direction and establishing a controlled change management process for any subsequent modifications.

## Types of Requirements.
### Functional Requirements

Functional requirements specify the concrete features and behaviours the system must provide. They describe the actions users can perform and the outputs the system must produce. For a hotel booking management system, these requirements define the core business logic and user interactions.

* User Management and Authentication
  
The system must allow users to create profiles and authenticate themselves. Users need the ability to register new accounts with email and password, log in to access their profiles, update their personal information like contact details and preferences, and reset passwords through email verification. The system should maintain separate user types with different permissions, distinguishing between customers who book rooms and hotel managers who list properties.

* Hotel and Property Management
  
Hotel managers must be able to register hotels on the platform, add or update room types in their hotels, and manage individual rooms within each room type. This includes uploading hotel images and descriptions, defining room specifications like bed types and amenities, setting room availability calendars, and updating pricing information. Managers need the capability to add multiple room types, such as standard rooms, deluxe rooms, and suites, with each type having its own inventory and pricing structure.

* Search and Discovery
  
The system must provide search functionality where customers can search for hotels based on location, check-in and check-out dates, number of guests, and room preferences. Search results should display available properties that match the criteria with relevant details like pricing, ratings, and amenities. Users should be able to filter results by price range, star rating, amenities like WiFi or parking, and distance from specific locations. The search must return only hotels with available rooms for the selected dates to prevent showing unavailable inventory.

* Booking and Reservation Management
  
The system must allow users to book hotel rooms, view booking details, and manage their reservations. The booking flow includes selecting a room type, specifying guest details, confirming dates, and proceeding to payment. Rooms are assigned during check-in, not while booking, meaning the system reserves a room type rather than a specific room number. Users need the ability to view their booking history, access upcoming reservations, cancel bookings according to the cancellation policy, and modify reservations if permitted.

* Payment Processing
  
The booking service must interact with payment services, which are typically third-party integrations. The system needs to support multiple payment methods, including credit cards, debit cards, and digital wallets. Payment processing must handle authorisation before finalising bookings, process refunds for cancellations, generate payment receipts, and maintain secure payment information storage, complying with payment card industry standards.

### Non-functional Requirements 

* Performance and Latency

Searching for hotels should be extremely fast with a latency under 500 milliseconds. This low-latency requirement reflects user expectations for immediate search results. Different system components have varying latency tolerances. Search and listing pages require high throughput and low latency, whereas reservation-booking transactions have lower throughput and more acceptance for a few seconds of latency while performing constraint checks. The system uses caching mechanisms like Redis that store temporary data so information need not be fetched from the database, which reduces database load and API response time.

* Scalability
* 
The system must be highly scalable to handle increases in the number of hotels and customers. Microservice architecture is necessary because the system has different functionalities that need to be scaled differently, with search-related functionalities typically having much higher usage than actual booking and payment completion. The architecture should support horizontal scaling by adding more servers to handle increased traffic. If there is a spike in traffic, the system can scale by adding more nodes to components like Kafka, search consumers, and the Elasticsearch cluster.

* Availability and Reliability
* 
The discovery platform showing hotels to customers should be highly available. The system must minimize downtime and remain accessible even during peak booking periods like holidays. Components like load balancers with auto-scaling handle traffic spikes to prevent downtime. Database replication for booking and property databases provides redundancy, while Kafka ensures decoupled, reliable event processing where events are retried even if a service fails.

* Consistency and Concurrency Control
System operations related to hotel managers and booking flows should be highly consistent. Double booking of the same room must not be allowed, requiring strong concurrency control mechanisms. The booking service internally locks a room at the database table row level while the user proceeds to payment. ACID properties and transactional guarantees are required for avoiding double booking a particular room type. This ensures that when two users simultaneously attempt to book the last available room, only one booking succeeds.

## Use Case Diagrams

The primary purpose of use case diagrams is to capture functional requirements in a visual format that both technical and non-technical stakeholders can understand. They help development teams identify all the ways users will interact with the system, ensure no critical functionality is overlooked, communicate system scope clearly to stakeholders, and serve as a foundation for more detailed requirements documentation. During the early phases of a project, use case diagrams facilitate discussions about what features the system needs and help prioritise development efforts.

Use case diagrams are powerful tools for visualising system functionality from the user's perspective. They consist of actors represented by stick figures, use cases shown as ovals, a system boundary rectangle, and various relationships connecting these elements. For a hotel booking system, key actors include guests, hotel managers, administrators, and external systems like payment gateways. Use cases cover the full range of functionality from searching and booking to property management and administration.

### Benefits of Use Case Diagrams

Use case diagrams provide multiple benefits throughout the software development lifecycle. They create a shared vocabulary between technical teams and business stakeholders by visualizing functionality in an accessible way. Non-technical stakeholders can look at a use case diagram and understand what the system will do without reading detailed technical specifications. The diagrams help ensure completeness by forcing teams to systematically identify all actors and their interactions with the system. This process often reveals missing requirements that might not surface in text-based requirements documents. Seeing all use cases visually makes it easier to spot gaps in functionality.
Use case diagrams support scope management by clearly showing what's inside the system boundary and what's outside. This visual boundary helps prevent scope creep by making it obvious when new requests fall outside the original scope. When stakeholders request new features, the diagram can be updated to show how the feature fits into the existing system, making scope discussions more concrete.

The diagrams serve as a foundation for other development activities. Use cases become the basis for writing detailed use case descriptions, creating user stories in agile development, designing system architecture, and writing test cases. Each use case on the diagram eventually maps to specific implementation tasks and test scenarios.
Finally, use case diagrams facilitate communication across distributed teams. In modern development, where team members might work in different locations or time zones, a visual diagram serves as a persistent reference that everyone can access and understand, regardless of when they review it.

## Acceptance Criteria

Acceptance criteria are specific, measurable conditions that a feature or requirement must satisfy to be considered complete and acceptable to stakeholders. They define the boundaries of a user story or requirement by stating what must be true for the feature to work correctly from the user's perspective. Acceptance criteria transform vague requirements into concrete, testable conditions that developers can implement and testers can verify. They answer the fundamental question: "How will we know when this feature is done and working correctly?" These criteria serve as a contract between stakeholders and the development team. Before development begins, everyone agrees on what constitutes successful implementation. This agreement prevents misunderstandings where developers build something they think is correct, only to have stakeholders reject it because it doesn't meet their expectations. Acceptance criteria make implicit assumptions explicit, ensuring all parties share the same understanding of what "done" means.

Acceptance criteria are essential components of requirement analysis that define specific, measurable conditions that features must satisfy. They provide clarity and shared understanding, enable systematic testing, define scope boundaries, support accurate estimation, establish objective completion standards, facilitate stakeholder engagement, and enable distributed team collaboration. Effective acceptance criteria are specific, measurable, complete, independent, user-centric, and realistic.

### Example of acceptance criteria for a feature like the Checkout feature in the booking management system

For complex features like checkout in a hotel booking system, comprehensive acceptance criteria cover guest information collection, booking summary display, payment method selection, payment processing security, booking confirmation, discount handling, cancellation policy communication, error handling, accessibility, responsive design, and performance requirements. Each criterion provides testable conditions that guide development, testing, and stakeholder acceptance. By investing time in defining thorough acceptance criteria during requirement analysis, projects reduce ambiguity, minimize rework, improve quality, and increase the likelihood of delivering features that truly meet stakeholder needs.

* Guest Information Collection

Given a user has selected rooms and dates, When they click "Proceed to Checkout," Then they are presented with a form collecting guest information, including full name, email address, phone number, and special requests field. The form must validate that the name contains at least two words, the email matches the standard email format, and the phone number contains at least 10 digits. Validation errors must display in red text below the relevant field immediately upon field blur. The special requests field must accept up to 500 characters and display the remaining character count.
Given the user is logged in, when they reach the checkout page, the form must be pre-populated with their saved profile information, including name, email, and phone number. Users must be able to modify this information for the current booking without permanently updating their profile.
Given the user is not logged in, when they reach the checkout page, they must see a prominent option to "Checkout as Guest" that allows proceeding without account creation. A secondary "Sign In" link must be available for users who want to access saved information.

* Booking Summary Display

Given the user is on the checkout page, When the page loads, Then a booking summary must be prominently displayed showing hotel name, selected room type(s), check-in date, check-out date, number of nights, number of guests, and nightly rate for each room. The summary must calculate and display the subtotal for room charges, taxes with percentage rate shown, service fees if applicable, and the total amount to be charged. All monetary amounts must display in the user's selected currency with the appropriate currency symbol and decimal places.
Given that multiple rooms are booked, when the summary displays, then each room must be listed separately with its own nightly rate and subtotal. A total combining all rooms must be clearly displayed and visually distinguished from individual room totals.

* Payment Method Selection

Given the user has completed guest information, When they proceed to payment, they must be presented with available payment options, including credit card, debit card, and PayPal. The default selection must be credit card. Each payment method must be represented by a clearly labelled radio button or selection card with recognisable brand icons.
Given the user selects credit card payment, when the payment form displays, it must include fields for card number, cardholder name, expiration date (month and year), and CVV code. The card number field must accept 13-19 digits depending on the card type. The field must format the number with spaces for readability as the user types. The expiration date field must only accept future dates and display appropriate format guidance. CVV field must accept 3-4 digits and mask input for security.
Given the user enters a card number, when the first 4-6 digits are entered, then the system must detect the card type (Visa, Mastercard, American Express, Discover) and display the corresponding card logo. If the card type is not supported, an error message must appear stating "This card type is not accepted."
Given that the user selects PayPal payment, when they click to proceed, they must be redirected to PayPal's secure payment interface in a new browser window or modal. After completing PayPal authentication and authorisation, they must be returned to the booking system with payment confirmation.

* Payment Security and Processing

Given the user submits payment information, when processing begins, a loading indicator must display with text "Processing your payment..." and all form controls must be disabled to prevent double submission. The page must not allow navigation away during processing.
Given that payment processing is successful, when confirmation is received from the payment gateway, the user must be redirected to a confirmation page within 3 seconds. The payment form must not store complete credit card numbers, storing only the last 4 digits for display on the confirmation page and for future reference.
Given that payment processing fails when an error is received from the payment gateway, the user must see a specific error message explaining the failure, such as "Payment declined by your bank," "Insufficient funds," or "Invalid card information." Generic messages like "Payment failed" must only be used when specific error details aren't available. The user must be able to modify payment information and retry without re-entering guest information.
Given that payment processing takes longer than 10 seconds, when the timeout threshold is reached, then the system must display a message "Your payment is taking longer than usual. Please wait while we confirm your booking" and continue waiting for up to 30 seconds total. After 30 seconds without response, the user must see a message to contact support with a reference number.

*  Booking Confirmation

Given that payment is successfully processed, when the confirmation page loads, it must display a unique booking confirmation number, payment confirmation with amount charged and last 4 digits of card used, booking details including hotel name, address, check-in and check-out dates, room type(s), guest information, and cancellation policy with deadline date clearly stated. A prominent button labelled "View My Bookings" must link to the user's booking history page.
Given that payment is confirmed, when the booking is saved to the system, a confirmation email must be sent to the user's email address within 30 seconds. The email must include the booking confirmation number, complete booking details, hotel contact information, directions or map link, and a link to view or manage the booking online. A secondary confirmation SMS must be sent to the user's phone number if they opted in for text notifications.
Given a logged-in user completes a booking, when confirmation is displayed, then the booking must be automatically added to their account booking history and accessible from their user dashboard. Guest checkout bookings must offer the option to create an account and have the booking associated with it.

* Discount and Promo Code Handling

Given the user is on the checkout page, when the payment section displays, there must be a clearly labelled field to "Enter promo code" with an "Apply" button. The field must accept alphanumeric codes up to 20 characters.
Given the user enters a valid promo code, when they click "Apply," Then the discount must be calculated and reflected in the booking summary within 1 second. The summary must show the original subtotal with a line item indicating the discount amount and percentage or code description, followed by the new discounted total. The applied promo code must be displayed with an option to remove it.
Given the user enters an invalid promo code, when they click "Apply," Then an error message must appear stating "This promo code is invalid or has expired" in red text near the promo code field. The booking total must not change. The user must be able to clear the invalid code and try a different one without refreshing the page.
Given a promo code has usage restrictions, when it is applied to an ineligible booking, then a specific error message must explain why it cannot be used, such as "This code is only valid for bookings over $200" or "This code cannot be combined with your selected dates."
* Cancellation Policy Display
  
Given the user is on the checkout page, when reviewing their booking, then the applicable cancellation policy must be clearly displayed, including whether the booking is refundable or non-refundable, the cancellation deadline date and time if refundable, the percentage of refund available if cancelled by the deadline, any cancellation fees that apply, and what happens if cancelled after the deadline. This information must be presented in plain language, not legal jargon, and must be visually distinct from other page content, possibly in a bordered box or highlighted section.
Given that different rooms have different cancellation policies, when multiple rooms are booked, each room's specific cancellation policy must be clearly indicated in the booking summary next to the room details. Users must be alerted if mixing refundable and non-refundable rooms.

* Error Handling and Validation
  
Given required fields are incomplete, when the user attempts to submit the checkout form, the page must not submit, must scroll to the first incomplete field, must highlight all incomplete required fields with red borders, and must display an error summary at the top of the form listing all fields that need attention. Field-specific error messages must appear below each problematic field.
Given that the hotel becomes fully booked during checkout, when the user attempts to complete payment, they must receive a clear message stating "We're sorry, but this room is no longer available for your selected dates" before any payment processing occurs. The message must suggest viewing alternative room types or dates. No charge must be processed if rooms are unavailable.
Given the user's session expires during checkout, when they submit payment, then the system must preserve their booking details and guest information, require re-authentication if they were logged in, and allow them to complete checkout without re-entering all information.
