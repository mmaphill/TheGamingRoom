# TheGamingRoom
CS 230 Repository

## Briefly summarize The Gaming Room client and their software requirements. 
### Who was the client? 
- The Gaming Room is the client
### What type of software did they want you to design?
- This client is seeking a web-based version of their multiplayer game, *Draw It or Lose It*, inspired by *Win, Lose or Draw*. The client requires a scalable, efficient, and secure disributed system that supports the following.
  - Multiple teams and players in a game session
  - Timed rounds with clues progressively revealed
  - Real-time guess submissions
  - Web accessibility across multiple platforms
  - Unique naming for g ames, teams, and players
  - Singe game instance in memory via a singleton patter
  - Secure handling of user data
### What did you do particularly well in developing this documentation?
- Detailed breakdown of components: Clearly defined classes, attributes, methods, and relationships following best practices
- Singleton pattern implementation: Made sure only one game instance could exist in memory, meeting a critical client requirement
- Systeme Architecture Consideration: Discussed distributed architecture, time synchronization, and WebSocket use for real-time interaction.
### What about the process of working through a design document did you find helpful when developing the code?
- Working through the design document allowed me to clarify user requirements early on in the project. It made it easier to plan logical class hierarchies and system interactions before actually writing code. Additionally, it helped to identify potential risk or design flaws before development starts. 
### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
- I believe overall the document was created well and covered most of the necessary items. If I did go back and revise this document, I might add more detail into the recommendations to help with painting a clearer picture.
### How did you interpret the user’s needs and implement them into your software design?
- I interpreted user needs throug analysis of their requirements, then translated those into concrete functional requirements, a focused technical design, and platform choices that met their goals for scalability, cost-effiency, and performance.
### Why is it so important to consider the user’s needs when designing?
- Understanding and designing around the user's needs ensures the software is usable, reliable, and valuable to the client. If user experience or core goals are ignored, the product may technically function but still fail overall. 
### How did you approach designing software?
- I used the singleton patter to force critical restraints
- I defined system goals, data flows, and interactions before coding. 
### What techniques or strategies would you use in the future to analyze and design a similar software application?
- I would focus on test-driven devvelopment to make sure coding is efficient and effective during scaling 
