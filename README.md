# CS255Portfolio

# Project Summary

The DriverPass project focused on planning a comprehensive management platform for Liam's driving school, alongside his technical officer, Ian. The client needed a secure, cloud-hosted web application to replace manual paper scheduling, automate customer registrations, manage driver training packages, and help lower high student exam failure rates. The system was designed to coordinate two-hour behind-the-wheel driving lessons by matching students with available instructors and vehicles from a ten-car fleet without double-booking. The platform also features an online e-learning portal linked directly to Department of Motor Vehicles data feeds for real-time exam practice, as well as distinct access levels for five user groups ranging from students to administrators.

# Strengths and Successes

The strongest aspect of this work was translating complex operational business rules into clear, structured visual models and actionable functional requirements. The three-way resource-matching engine was effectively diagrammed using activity and sequence workflows, mapping out the precise steps required to verify car and instructor availability before confirming a lesson. Furthermore, the requirements clearly established role-based access control across all five user tiers and defined essential operational safeguards, such as validating that pickup and drop-off addresses match and allowing the owner to toggle packages on or off without writing code. This tight alignment between the business requirements and the technical diagrams created a dependable roadmap for development.

# Areas for Revision

If one section of these documents were to be revised, it would be the rigid resource constraints built into the scheduling engine and class structure. The current design assumes a static fleet of ten vehicles and paired instructors, which creates an operational bottleneck as the business grows. To improve this, the class diagram and activity models could be expanded to support dynamic fleet management, vehicle maintenance states, and flexible instructor availability schedules. Updating the scheduling logic to handle variable fleet sizes and varied pickup arrangements would make the system architecture much more scalable for future business expansion.

# Incorporating User Needs

User needs were identified by reviewing client interview discussions and turning specific requests into concrete system features. For example, Liam's hand-drawn dashboard sketch was translated into modular interface panels displaying student profiles, practice test progress, and post-lesson instructor feedback. At the same time, role-based permission tiers were created to match the daily duties of staff, drivers, and students. Considering the user's needs is essential because software must simplify everyday tasks rather than adding unnecessary friction. Designing around user workflows ensures strong system adoption, prevents expensive redesigns later, and guarantees that the finished application genuinely solves the client's problems.

# Design Approach and Future Strategies

The approach to software design centers on breaking down a project into iterative, logical phases that move from client discovery to formal requirements, architectural modeling, and schedule mapping. In future projects, this strategy can be strengthened by pairing visual Unified Modeling Language diagrams with interactive UI prototypes early in the requirements phase to confirm layout expectations with clients before completing the system design. Continuing to use clear activity workflows, automated validation checks, and structured timeline planning will ensure that future systems remain secure, scalable, and easy to maintain throughout the development lifecycle.

