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
### Non-functional Requirements 
