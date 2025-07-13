PROJECT REPORT FOR GROUP 11 PROJECT TITLE: WASTE EXCHANGE, A MOBILE PLATFORM FOR REPURPOSING WASTE MATERIAL IN CAMEROON.


INTRODUCTION
WasteExchange is a mobile platform designed to tackle Cameroon’s waste management challenges by connecting waste producers with individuals and businesses that can repurpose or recycle waste materials. The app facilitates a local marketplace where users can offer or request various types of waste-organic, plastic, paper, glass-enabling efficient exchange based on proximity to reduce transport costs and environmental impact.
Key Problem Addressed
●	Cameroon faces significant waste management challenges, with improper disposal causing pollution and health risks.
●	No existing platform connects waste producers with those who can repurpose or recycle waste materials.
●	Farmers, local beverage producers, artisans, and the general community miss opportunities to reuse waste materials beneficially.
Project Objectives
●	Reduce landfill waste by promoting reuse and recycling.
●	Connect waste producers (households, businesses) with waste users (farmers, recyclers, artisans).
●	Educate users on sustainable waste management practices.
●	Track environmental impact such as waste diverted.
Project Execution, Following Software Development Life Cycle (SDLC)
1.	Communication:
During the communication phase of the WasteExchange project, the following key points were communicated:
●	The introduction and objectives of the WasteExchange project, explaining the main goals and the specific waste management problems it aims to solve in Cameroon.
●	Identification of all key stakeholders, including farmers, artisans, beverage producers, recyclers, NGOs, and local authorities.
●	The overall project scope and expected deliverables, such as the main features of the app and the intended outcomes.
●	The proposed timeline and major milestones for each phase of the project.
●	The roles and responsibilities of each team member, including who is handling development, marketing, field research, and stakeholder engagement.
●	The communication channels to be used by the team (such as WhatsApp, email, and weekly meetings) and how updates would be shared with stakeholders.
●	Initial user needs and requirements gathered from surveys and interviews, including desired features like waste categories, map integration, and compensation options.
●	Potential risks and challenges, such as low user adoption or technical difficulties, along with possible strategies to address them.
●	The process for collecting feedback from stakeholders and outlining the next steps for moving forward with requirements gathering. 

2.	Requirements gathering:
At this stage of the project, we used surveys and interviews to understand what people would want from a Waste Exchange app. This helped us learn about their needs, what they expect, and how they would like to use the platform.
Here are some of the user requirements which we got:
●	Categories of Waste: People want a page where reusable waste is grouped into categories (like plastic bottles, leftover food, paper, etc.) so it’s easier to find what they’re looking for.
●	Simple User Interface: Since there’s no platform like this in Cameroon, users want the app to be very simple and easy to use, even for people who are not tech-savvy.
●	Compensation: Some users want to receive a small reward for giving out their waste, while others are okay with doing it for free to help the environment.
●	Chat Option: Users would like to be able to chat one-on-one with people who are offering or looking for waste, to ask questions or make arrangements.
●	Google Map Feature: Many users asked for a map feature so they can easily see who is offering waste nearby. This would make it easier to meet or arrange transport.
From all this feedback, we were able to identify the key features and qualities our app should have.
●	The application would be designed to support growing users demands in waste.

3.	Requirement Specifications
This was required to know how the application will interact with its hardware, maintenance, external interfaces and quality. The requirements gathered from the users is then documented. These requirements received from the users are in natural language and it is being changed into technical language and documented so that it can be comprehended and used by the development team (My team).
The application would have the following Features:
A.	FUNCTIONAL REQUIREMENTS
For the functional requirements we had;
●	Registration and Profiles: users shall be able to sign up as individuals, farmers, artisans, businesses, or recycling organizations. Each profile will include location, waste material types, and contact details.
●	Offer and Request Waste Materials: users can post available waste items or request specific materials. Posts include category (e.g., organic, plastic), quantity, and pickup/delivery options.
●	Categorized Waste Listings:  waste materials shall be organized into searchable categories such plastic, glass, organic to make browsing and matching easier.
●	Email Report: The users of the system should be able to receive notifications such as success or failure of delivery of their waste
●	Grouping Users: The system will have an option which ask users if you want to sell your waste or give it for free. This is because some users logging into the application might not have persons willing to buy their specific waste but persons willing to take the waste for free. For example, some developing farmers might not have money to buy waste but can still logging into the application and check for if the is a user willing to give his/her organic waste for free.
B.	NON-FUNCTIONAL REQUIREMENTS
                    For the Non-functional requirements we had;
1.	Performance: the app would be able to handle a large number of users without slow processing.
2.	Security and Data Protection: users data shall be stored and encrypted for protection and confidentiality
3.	Flexibility: the application would be able to adapt in change in requirements, user needs and technology advancement without significant work.
4.	Compatibility Requirement: the app would work on both Android and iOS.
5.	Cost: The application would be an opensource software.
6.	Scalability: the application would be designed to support growing users demands in waste



4.	FEASIBILITY STUDY
A.	Technical feasibility:
We noticed our users will either be using the android or iOS operating system, so a cross - platform framework such as flutter will be used for the app development.
The app will also implement a location and waste category - based search to assist users in finding what they need.
B.	Operational feasibility:
The system will have simple descriptions and training instructions for users with low IT literacy and will focus on pictures and buttons to make it user friendly.
Offline capabilities such as previously loaded searches that will appear during seasons of network distances.
C.	Resources feasibility:
In terms of human resource, the team is made up of developers, marketers and field agents
Financial resources will include; initial fundings and grants from stakeholders such as NGO's, farmers cooperatives, businesses.
D.	Legal Feasibility:
The waste exchange platform is legally feasible in Cameroon, requiring compliance with environmental regulations, business registration, and data protection laws.
E.	Market Feasibility:
The platform has market potential, driven by growing demand for sustainable waste management solutions, targeting industries that generate significant waste, and assessing the competitive landscape.
F.	Economic Feasibility:
The platform is economically feasible, generating revenue through commission-based transactions, subscription fees, or advertising, while providing economic benefits to users by reducing waste disposal costs and promoting sustainable practices.
5.	System Analysis:
●	At this stage of the project, our team conducted a structured analysis to establish a clear roadmap for the development of the WasteExchange mobile platform. This phase focused on understanding the scope of the product, identifying technical and operational constraints, and selecting a suitable development model. The insights gained informed our design and planning decisions.
Understanding Product Scope and Limitations
●	We defined the WasteExchange platform as a mobile application aimed at connecting waste producers with waste collectors and recyclers in Cameroon. Our objective was to encourage responsible waste disposal and promote a circular economy. During analysis, we identified the following limitations:
●	Internet Dependence: We observed that many users may have limited or unstable internet access. As a result, we planned for offline capabilities, such as saving drafts of listings and delayed synchronization.
●	Device Constraints: Recognizing that many users own low-end Android devices, we decided to optimize performance to ensure smooth operation on such devices.
●	User Diversity: Since our target audience includes users from varying digital literacy levels, we committed to a simple, intuitive, and multilingual user interface.
2. Identifying System-Related Problems
●	We examined the current waste management landscape and identified several problems our platform aimed to solve:
●	Lack of Coordination: We found no structured way for waste producers and recyclers to connect or communicate.
●	Inefficient Disposal Practices: Users often dispose of recyclable materials due to lack of access to recycling options.
●	Data Fragmentation: There was no centralized platform or data source to track recyclable waste or collection patterns in communities.
●	Our analysis confirmed that a mobile platform with listing, search, communication, and reporting features would significantly address these gaps.
3. Feasibility and Impact Assessment
We assessed the feasibility and potential impact of the project in three main areas:
●	Technical Feasibility: We concluded that the technical requirements were within our capabilities, using tools such as Android Studio, Firebase, and cloud-based databases.
●	Operational Feasibility: We considered the willingness and ability of local waste actors to adopt digital solutions. Based on preliminary user feedback, we confirmed operational feasibility.
●	Organizational and Social Impact: We anticipated positive impacts, including better waste tracking, improved recycling rates, and increased community awareness about sustainable practices.
4. Software Model Selection
●	After reviewing possible approaches, we agreed that an Incremental Model would be the most suitable for this project. This allows us to deliver and test core features in phases—such as registration, waste listing, and search—while gradually integrating advanced functionalities like messaging, notifications, and administrative controls.
5. Project Scope and Resource Planning
●	We defined the scope of the project to include:
●	A mobile application with core functionalities (user roles, listings, messaging, notifications)
●	A backend system for data storage and processing
●	An admin dashboard for content management and user monitoring
●	Resources planned and allocated included:
●	Team Roles: Developers, UI/UX designer, system analyst, and project manager
●	Tools and Technologies: Flutter, Firebase backend, MySQL database, GitHub for version control
●	Project Timeline: We estimated a development duration of approximately 3–4 months, with clearly defined milestones for each phase: analysis, design, development, testing, and deployment
●	
●	This analysis formed the foundation for our project planning, helping us align development goals with real-world constraints and opportunities.
6.	System Design
Following the system analysis phase, our team proceeded with the system design for the WasteExchange mobile platform. The design process was divided into three levels—Architectural Design, High-Level Design, and Detailed Design to systematically break down and represent the structure and functionality of the system. Each level of design provided a clearer roadmap for implementation. 
a)	Architectural Design

 
At this level, we identified the WasteExchange application as a software system composed of several major components that interact to deliver core functionality. The system was designed as a client-server architecture comprising the following: 
Mobile Client Application (Flutter): 
 Interface for users to register, post waste, browse listings, chat, and receive notifications. 
Backend Server: 
Handles business logic, user authentication, waste listing management, messaging, and notifications. 
Database: 
 Stores user profiles, listings, messages, feedback, and transaction records. 
Admin Dashboard (Web-Based): 
Used by administrators to monitor content, manage users, and view analytics. 
We ensured that components interacted via well-defined APIs, with secure communication protocols (HTTPS) to maintain data integrity and privacy. 
b)	High-Level Design
 
In the high-level design phase, we decomposed the system into sub-systems and modules. Each sub-system was defined by its core functionality and interaction with other components: 
Sub-systems and Modules:
User Management Sub-System
Modules: Registration/Login, Profile Editing, Role Assignment (producer or recycler) 
Listing Management Sub-System
Modules: Create Listing, Edit/Delete Listing, Waste Categories 
Matching and Search Sub-System
Modules: Location-based Filtering, Search by Waste Type, Suggested Matches (GPS-based) 
Messaging Sub-System
Modules: Chat Interface, Message Storage, Read Notifications 
Notification Sub-System
Modules: Push Notifications for Listings, Messages, and System Alerts 
Exchange Tracker Sub-System
Modules: Status Updates (Available, Reserved, Picked Up, Completed) 
Review Sub-System 
 Modules: Feedback Submission, User Rating Calculation 
Admin Control Sub-System
Modules: User Moderation, Content Management, Analytics Dashboard 
Each module was assigned to a developer or pair of developers for implementation during the coding phase. 

c)	Detailed Design
 
In the detailed design phase, we defined the internal logic and interfaces of each module. This included specifying: 
Data Structures: 
For instance, the `User` model contained fields such as `userID`, `role`, `contactInfo`, and `rating`. 
The `WasteListing` model contained `listingID`, `wasteType`, `quantity`, `location`, `status`, and `photoURL`. 
Interfaces and API Endpoints:
●	POST /api/register, GET /api/listings, POST /api/message, etc.
●	API responses were designed to return standardized JSON objects.

POST /api/register`, `GET /api/listings`, `POST /api/message`, etc. 
API responses were designed to return standardized JSON objects. 
Interaction Flow: 
 We mapped out the sequence of operations for example, what happens when a user posts a listing or sends a message. 
Error Handling: 
We outlined expected exceptions and fallback strategies (e.g., retry logic for failed network requests). 
User Interface Wireframes: 
UI sketches were created using Figma to design a clean, accessible interface tailored to mobile users. 
Design Considerations and Best Practices Followed
We adopted modular design principles to ensure maintainability and scalability. 
The system was designed to support asynchronous operations to improve performance and user experience. 
Security measures such as password hashing, role-based access control, and input validation were planned and included in our detailed design. 
This structured design process allowed our team to move confidently into the development phase with a shared understanding of the system’s architecture, responsibilities, and data flow.

Decisision Tables



	RuleID	User Type	
Logged in	Location Enabled?	Waste Type Selected?	Show Nearby Listings	Show filtered Listings	Show All Listings	Send Notifications
	R1	WasteCollector	Yes	Yes	No	Yes	No	No	Yes
	R2	WasteCollector	Yes	No	Yes	No	Yes	No	Yes
	R3	WasteCollector	Yes	No	No	No	No	Yes	No
	R4	WasteCollector	Yes	-	-	No	No	Yes	Yes
	R5	Wasteproducer	No	-	-	No	No	No	No
									



7.	Coding Phase
During the coding phase, the team successfully developed all core modules of the WasteExchange platform, adhering to secure and maintainable software development practices. 
Key modules implemented:
●	User Authentication and Session Management
●	Secure registration and login system 
●	Role-based login for producers, collectors, and admin 
●	User Profile and Role Management 
●	Profile editing 
●	Dynamic access control based on roles 
●	Waste Listings Management
●	Full CRUD (Create, Read, Update, Delete) for waste materials 
●	Categories, descriptions, and availability tracking 
●	Messaging/Inbox System 
●	Direct messaging between producers and collectors 
●	Notification system for unread messages 
●	Admin Dashboard 
●	User management, system statistics, listing approval/rejection 
Coding Best Practices Applied:
▪	Passwords hashed using secure algorithms 
▪	Input validation and sanitization across all forms 
▪	Unauthorized access restrictions for protected pages 
▪	Code modularization with reusable includes (`header.php`, `footer.php`, `auth.php`, `functions.php`) 
▪	Clean UI/UX using Tailwind CSS for responsive and modern interfaces 
8.	Testing Phase

During the testing phase, both manual and automated tests were performed to ensure functional correctness, security, and usability of the WasteExchange platform.
9.	Key areas tested:
▪	User registration and login functionality with valid and invalid credentials
▪	Waste listing creation, update, deletion, and display across user roles
▪	Messaging system functionality, including sending, receiving, and viewing messages
▪	Profile updates and access control according to user roles (producer, collector, admin)
▪	Admin capabilities to monitor, approve, or reject listings
▪	Error handling and edge cases:
▪	Input validation for required fields, invalid formats, and large file uploads
▪	Duplicate registration checks and protection against double listings
▪	Unauthorized access blocked for restricted pages or actions
▪	Cross-platform compatibility:
▪	Verified UI responsiveness on various screen sizes (mobile, tablet, desktop)
▪	Cross-browser testing including Chrome, Firefox, and Microsoft Edge
▪	Security testing:
▪	Checked for SQL injection vulnerabilities using prepared statements
▪	Ensured proper session handling with logout and inactivity expiration
▪	Role-based redirection and restricted access to admin-only areas
▪	Bugs encountered during testing were documented and fixed iteratively, improving system stability before integration.
10.	 Intergration Phase
The integration phase involved connecting and synchronizing all the system modules to ensure a cohesive and functional platform. This included linking the front-end interface with the back-end logic and database operations.
Front-end and back-end integration:
●	Linked user input forms (registration, login, listings, messaging) to PHP processing scripts
●	Established connection between PHP scripts and MySQL database using PDO for secure queries
●	Implemented session handling across pages for authenticated user flow
●	Verified correct routing between user actions and server responses
Third-party and external integration:
●	Integrated Tailwind CSS for consistent UI design across pages
●	Used Font Awesome for icons to enhance usability and visual feedback
●	Ensured JavaScript interactions, such as dropdowns and form validations, functioned correctly
End-to-end testing:
●	Simulated complete user journeys:
o	Account creation to login and profile editing
o	Listing waste items, browsing as a collector, and initiating messages
o	Admin reviewing and managing all data and user roles
●	Checked for data persistence across pages and accurate database reflection of user activities
Consistency and optimization:
●	Centralized header, footer, and layout elements using PHP includes for maintainability
●	Minimized redundant code and optimized loading times for better performance
●	Ensured error pages and redirects worked correctly under various conditions
This phase confirmed all modules interact seamlessly, providing a unified and user-friendly experience.


















Demonstration and User Interface Screenshots of WasteExchange
1.	Homepage
 
2.	User Registration Page

 
3.	Login Page
 
4.	User Dashboard
 
5.	Create Waste Listing
 
6.	Browse Listings Page
 
7.	Chat or Messaging Interface
 
8.	Admin Dashboard
 
9.	Admin Actions
 


11.	Platform’s Impact and Analytics page
 
12.	Achievements
 
