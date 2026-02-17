# CS-230 Operating Platforms
## Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client was The Gaming Room, and they wanted help designing a web based version of Draw It or Lose It that could move past being just an Android app. The big idea was letting people play together across different devices, with the game running in a distributed setup that can scale without turning into a glitchy mess. That means keeping things like games, teams, and players organized, making sure names stay unique, and having a clean way to manage game sessions so the whole thing feels consistent and fair when multiple people are playing at the same time.

## What did you do particularly well in developing this documentation?

I am a huge self hosted fan boy, so honestly one of the best things I did was resisting the urge to recommend running everything on a server in someone’s basement with a heroic amount of duct tape and optimism. All jokes aside, I think I did well at staying objective and laying out the pros and cons of each platform in a way that actually helps decision making. Instead of picking a favorite and forcing it, I focused on what fits the project goals like scalability, reliability, and long term maintainability.

## What about the process of working through a design document did you find helpful when developing the code?

There was not one magical section that suddenly made coding easy, but having guardrails mattered a lot. The design document kept me from wandering out of scope and building features nobody asked for, which is my natural talent if left unsupervised. It helped me stay focused on requirements and structure first, so when it was time to implement, I had a clearer picture of what classes and services needed to exist and why.

## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the development requirements section, because it felt like the one spot where the guardrails were not fully built yet. If that area is missing detail, it is easier to drift and accidentally design for assumptions instead of real requirements. I would improve it by adding clearer technical expectations like environment setup, tooling, testing approach, and deployment considerations so the document better supports the jump from design into actual implementation.

## How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I looked at user needs in a pretty simple way: users and usage should translate to success, success should bring income, and income is why most people go to work. If the user experience is bad, nobody plays, and then the project turns into a very expensive group chat with bugs. The users wanted to play with friends, which means cross platform support matters, and they need the game to be fast and reliable so it feels smooth during timed rounds. On the business side, it also needs to be affordable to run, because overhead costs can quietly kill a good idea even if the game is fun.

## How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach was to start with requirements and constraints, then map those into a clean structure that supports scaling and keeps data consistent. I tried to think about what the system must always do correctly, like managing game sessions and preventing duplicates, before worrying about extra features. In the future, I would use the same strategy but push harder on early validation, meaning I would confirm requirements sooner, draft a tighter architecture view up front, and keep a short pros and cons list for every major decision so the final design stays grounded instead of becoming a wishlist
