# CS-230_8-2_Journal_Portfolio_Submission

- Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was looking to develop their game, Draw It or Lose It, into a web app that could exist on multiple platforms. They had already developed an Android application of their game. The client required for one or more teams consisting of multiple players, and a solution must be implemented to check for unique team and player names. Also, only one instance of the game could exist in memory at any given time. 

- What did you do particularly well in developing this documentation?

I felt like I did particular well at identifying the client's requests and finding an applicable solution to meet client needs. I also feel as though as I was able to effectively explain my solutions in a non-technical way. I'm a big believer in developing documentation and knowledge base articles in a way that anyone can follow and not just the person developing the solution.

- What about the process of working through a design document did you find helpful when developing the code?

What I found helpful about the documentation process is it allowed me to organize my thoughts and goals for developing the solution in code. For instance, knowing that only one instance of the game could exist in memory helped me more effectively design the Singleton pattern in a way to effectively achieve this.

- If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I think the one part of my document I would revise more is the section on server-client side requirements for each platform. I think I could have added some additional information on the benefits and negatives of each platform, as well as the various pros and cons for each platform developing on a cloud-based, serverless solution (i.e. AWS vs Azure, etc.).

- How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

Using the authentication API to verify whether a login attempt is an admin or user account was an effective way of interpreting a user's needs and prevent unauthorized access. Using while loops in my Team class allowed to effectively scan for unique player names and place them in their unique team.

- How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

How I approached designing the software was to implicit, effective methods for meeting the client's demands. For instance, incorporating the singleton pattern to ensure only one instance of the game exists and to use effective loops to ensure that unique player and teams names are not duplicated. I think some strategies I would use in the future for further software development is incorporating further API methods to achieve functions outside of the primary source code, such as authentication.
