# CS-230
Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The client for this project was "The Gaming Room". They wanted to design software for a game application where players had to guess the puzzle (a phrase, title, or thing), the application will render images from a large library of stock drawings as clues. The software also needed to meet the following requirements: 
A game will have the ability to have one or more teams involved.
Each team will have multiple players assigned to it.
Game and team names must be unique to allow users to check whether a name is in use when choosing a team name.
Only one instance of the game can exist in memory at any given time. This can be accomplished by creating unique identifiers for each instance of a game, team, or player. 

What did you do particularly well in developing this documentation?
I did particularly well in clearly translating the client’s requirements into a structured, easy-to-follow design. I effectively broke down the system into key components, defined how they interact, and aligned each part with the client’s goals. I also did a strong job comparing platform options and justifying design decisions, which showed thoughtful analysis rather than just describing a solution. This made the documentation both practical for implementation and understandable for stakeholders. 

What about the process of working through a design document did you find helpful when developing the code?
Working through a design document was helpful because it gave me a clear blueprint before writing any code. It forced me to think through system structure, data models, and interactions ahead of time, which reduced confusion and rework during development. By defining components, workflows, and constraints early, I was able to code more efficiently and stay aligned with the requirements. It also made it easier to spot potential issues in advance, so the implementation process was smoother and more organized.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could revise one part of my work, I’d focus on improving the evaluation of platform and technology choices. While I compared options at a basic level, I could strengthen that section by adding deeper analysis—such as more detailed trade-offs around scalability, cost, security, and performance. I would also include clearer justification for why one solution was selected over others, possibly supported by real-world examples or benchmarks. This would make the design decisions more convincing and give a stronger foundation for implementation. 

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
I interpreted the user’s needs by focusing on what players, developers, and administrators needed from the system—such as smooth multiplayer gameplay, unique team and game management, and reliable cross-platform access. I translated those needs into design features like real-time session handling, user authentication, and rules enforcement (for example, ensuring unique names and properly managed game states). I also structured the system to prioritize stability and performance so the game could run consistently across different devices.

Considering user needs is essential because it ensures the software actually solves the right problem and is usable in real-world situations. Even if a system is technically sound, it won’t be successful if users find it confusing, inefficient, or unreliable. Designing with the user in mind leads to better usability, higher satisfaction, and a system that people will actually adopt and continue using.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I approached designing the software by first identifying the client’s requirements and breaking them down into functional needs for different users and system components. From there, I organized the system into a clear structure, focusing on core features like user management, game session handling, and rule enforcement. I also considered how data would flow through the system and how different parts would interact to ensure the design was consistent and scalable.

In the future, I would continue using strategies like requirements analysis, use case development, and UML diagrams (such as class and sequence diagrams) to better visualize system behavior before coding. I would also apply modular design principles to keep the system flexible and maintainable, and use iterative or Agile development so the design can be refined based on feedback. Additionally, I would place more emphasis on early prototyping and testing assumptions to catch design issues before implementation.




