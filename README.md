# Knowledge

> **_General trick_**  - Medium and HBR enforce a limited number of reads for the free account. If you’re out of free reads, you can always open a new incognito session and paste the link there. You’ll automatically get some more free reads.


> **_General trick (2)_**  -  Tired of reading? Use text-to-speech extension to read along with you. You can also easily control the speed (words per minute) and voice. My personal favorite is: https://chrome.google.com/webstore/detail/natural-reader-text-to-sp/kohfgcgbkjodfcfkcackpagifgbcmimk?hl=en
(Try the free voice of Google UK English Female en-GB)

### System Design
#### guidelines
Good guideline resoure - [link](https://youtu.be/i7twT3x5yv8?si=hc-jdz8dB3_7vYR-)
1. Clarify: Why are we building the system? Who are the users? What features do we need to build?
2. Focus on the top few features to build and agree on the priority order
3. Clarify non-functional requirements (probably most relevant are scale and performance but there are also: security, consistency, accuracy and more)
4. Flow: API Design --> High level design diagram (retain a list of discussion points for later and avoid diving too deep ((db scaling, high concurrency, failure scenarios))) --> Deep dive (point out points of failure and figure out with the interviewer what to discuss about) --> Wrap up (summarize the design
#### links
1. [Scalability Lecture at Harvard](https://www.youtube.com/watch?v=-W9F__D3oY4)
2. [Jordan has no life course](https://www.youtube.com/@jordanhasnolife5163)
3. [Gaurav Sen system design course](https://www.youtube.com/watch?v=SqcXvc3ZmRU&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&ab_channel=GauravSen)
4. [System Design primer](https://github.com/donnemartin/system-design-primer/blob/master/README.md?source=post_page-----ba118f48bdfc--------------------------------)
5. [System Design course](https://github.com/karanpratapsingh/system-design)
6. [Avoiding fallback in distributed systems](https://aws.amazon.com/builders-library/avoiding-fallback-in-distributed-systems/)
7. [Resiliency in Distributed Systems](https://blog.pragmaticengineer.com/resiliency-in-distributed-systems/?utm_source=tldrnewsletter)
8. [CQRS](https://martinfowler.com/bliki/CQRS.html)
9. [Domain Driven Design basic intro](https://redis.io/glossary/domain-driven-design-ddd/)
10. [Domain Driven Design by Udi Dahan](https://www.youtube.com/watch?v=-iuMjjKQnhg&ab_channel=Domain-DrivenDesignEurope)
11. [Kafka Deep Dive](https://www.youtube.com/watch?v=DU8o-OTeoCc&ab_channel=HelloInterview-SWEInterviewPreparation)
#### concepts
1. "A service is scalable if it results in increased performance in a manner proportional to resources added"
2. Static HTML caching example - Craiglist - pros: low cost because disk space is relatively cheap, performance because db only "spits" up bits (static pages) and cons: every change is costly (need to configure ALL static pages)
3. **Metrics**  </br>
Quantitative measurements of system behaviour </br>
Key focus: Performance indicators like latency, throughput, resource usage </br>
**Logs** </br>
Time stamped records of discrete events and state changes </br>
Key focus: Debugging, audit trails, compliance </br>
**Traces** </br>
End-to-end request flow through system components <br>
Key focus: Performance bottlenecks, error propagation

### Code
1. [The symptoms of ugly code by Uncle Bob](https://www.youtube.com/watch?v=vsQya8Ai1jw&ab_channel=DevToolsMadeSimple)
2. [Clean Code book summary](https://gist.github.com/wojteklu/73c6914cc446146b8b533c0988cf8d29)

### DB
1. [Why NoSQL is better at "scaling out" than RDBMS?](https://stackoverflow.com/a/21539676) 
> **_NOTE:_** Basically complicated documents in NoSql remove the need in JOIN (think how you would implement JOIN between shards)
2. [The difference between ACID and BASE database](https://aws.amazon.com/compare/the-difference-between-acid-and-base-database/)
3. [Normal Forms](https://www.youtube.com/watch?app=desktop&v=GFQaEYEc8_8&ab_channel=Decomplexify)
4. [Difference between pessimistic approach and optimistic approach in dbms](https://www.geeksforgeeks.org/difference-between-pessimistic-approach-and-optimistic-approach-in-dbms/)
5. [BTree VS Hash index](https://stackoverflow.com/a/7306456)
   
### Algorithms
1. [coding-interview-university](https://github.com/jwasham/coding-interview-university)

### NodeJS
1. [Getting Started with Node.js](https://www.youtube.com/watch?v=gG3pytAY2MY&ab_channel=freeCodeCamp.org)
2. [Parallelism and worker threads](https://deepsource.com/blog/nodejs-worker-threads)
3. [Dependency Injection with TypeDI](https://blog.logrocket.com/dependency-injection-node-js-typedi/)
4. [How to use the NodeJS REPL](https://nodejs.org/en/learn/command-line/how-to-use-the-nodejs-repl)
5. [Awesome-NodeJS git repository with tons of content](https://github.com/sindresorhus/awesome-nodejs?tab=readme-ov-file)
6. [Node best practices](https://github.com/goldbergyoni/nodebestpractices?tab=readme-ov-file#translations)
7. [What the heck is the event loop anyway? | Philip Roberts | JSConf EU](https://www.youtube.com/watch?v=8aGhZQkoFbQ&t=1s&ab_channel=JSConf)
8. [Node.js project structure with example git repository](https://www.softwareontheroad.com/ideal-nodejs-project-structure/?utm_source=github&utm_medium=readme)

### Typescript
1. [Typescript handbook](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes-oop.html)

### C#
1. [Floating point](https://csharpindepth.com/articles/FloatingPoint)

### DevOps
1. [TechWorld with Nana](https://www.youtube.com/@TechWorldwithNana)

### Web
1. [DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)
2. TCP -\
   2.1. [TCP](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:transporting-packets/a/transmission-control-protocol--tcp)\
   2.2. [Why TCP uses 3way hand shake](https://networkengineering.stackexchange.com/a/24072)
3. [SSL/TLS](https://www.youtube.com/watch?v=Rp3iZUvXWlM&ab_channel=WhiteHatCalPoly)
4. [OAuth](https://www.youtube.com/watch?v=996OiexHze0&ab_channel=OktaDev)
5. [What happens when you type an URL in the browser an press enter](https://medium.com/@maneesa/what-happens-when-you-type-an-url-in-the-browser-and-press-enter-bb0aa2449c1a)
6. [Comprehensive guide when to use em vs rem](https://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984#:~:text=Use%20rem%20units%20for%20sizing,layout%20widths%20-%20use%20%25%20instead.)
7. [Airbnb styling guide](https://github.com/airbnb/javascript)
8. [Pruning git branches](https://alexwlchan.net/2017/11/pruning-git-branches/)
9. [Oh shit git - cheatsheet for git](https://ohshitgit.com/?s=31#magic-time-machine)
10. [Different merge types in git](https://lukemerrett.com/different-merge-types-in-git/)
#### react
1. [usehooks.com](https://usehooks.com/)

### Soft Skills
#### links
1. [How To Speak](https://www.youtube.com/watch?v=Unzc731iCUY&ab_channel=TEDxTalks)
2. [Public speaking tips](https://x.com/SahilBloom/status/1520391055878901761?t=fpSPbHK_AHAfgPClupXPGw&s=19)
3. [The Law of Leaky Abstractions - Joel Spolsky](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/)

### Leadership
#### links
1. [Ideation](https://read.perspectiveship.com/p/on-generating-ideas)
2. [Geekonomy episode with Gal Z.](https://geekonomy.net/2020/11/15/geekonomy376/)
3. [Teamistry - The brilliant success of Shackletons failure](https://www.atlassian.com/blog/podcast/teamistry/season/season-1/the-brilliant-success-of-shackletons-failure)
4. [Stackoverflow blog post about engineering management](https://stackoverflow.blog/2022/02/23/what-you-give-up-when-moving-into-engineering-management/)
   </br> 4.1 [Inner link #1](https://leaddev.com/self-care-burnout/learning-love-meta-productivity)
   </br> 4.2 [Inner link #2](https://medium.com/swlh/do-engineering-managers-need-to-write-code-d89903d68e8d)
   </br> 4.3 [Inner link #3](https://www.toptal.com/engineering-management/a-day-in-life-engineering-manager)
5. [How to approach feedback giving](https://drive.google.com/file/d/1jQHUu7nZIlSoCuFYkQHZWjhI2S2GeK-a/view?usp=sharing)
6. [How to Ask Whether an Employee Is Happy at Work - (Great article about communication and true listening)](https://hbr.org/2022/04/how-to-ask-whether-an-employee-is-happy-at-work)
7. [Why I Start All My 1:1s with this Question - (A nice piece about what 101-s)](https://maryamtaheri.medium.com/why-i-start-all-my-1-1s-with-this-question-8d26781c4683)
8. [How to Become a Better Listener - (Great article about listening skills)](https://hbr.org/2021/12/how-to-become-a-better-listener)
9. [The Magic of Setting Expectations - (a little over the top in my opinion - but might be useful sometimes)](https://betterprogramming.pub/the-magic-of-setting-expectations-978ba7316df8)
10. [The Cone Model for Teams' Support Network - (How to help the team help themselves)](https://betterprogramming.pub/the-cone-model-for-teams-support-network-9b87659c8008)
11. [Having Career Conversations](http://www.softwareonthebrain.com/2021/12/having-career-growth-conversations.html)
12. [5 things you'll never learn from management books](https://entrepreneurshandbook.co/5-things-you-will-never-learn-from-management-books-66d5ce3db4d9)
13. [Velocity metrics](https://software.rajivprab.com/2023/07/01/moneyball-for-software-teams/?utm_source=tldrnewsletter)
14. [Feedback importance](https://hbr.org/2023/07/overcoming-your-fear-of-giving-tough-feedback?utm_source=substack&utm_medium=email)
15. [How to build trust best practices](https://jacobian.org/2023/nov/16/how-to-build-trust/)
16. [Super specific feedback](https://newsletter.weskao.com/p/super-specific-feedback)
17. [Words of appreciation](https://marcusblankenship.substack.com/p/sometimes-a-single-phrase-can-change?utm_source=post-email-title&publication_id=1972941&post_id=142824735&utm_campaign=email-post-title&isFreemail=true&r=5qbxj&triedRedirect=true&utm_medium=email)
18. [High Agency: what is it, why it is important, and how to cultivate it](https://www.linkedin.com/pulse/high-agency-its-importance-how-cultivate-shreyas-doshi?utm_source=share&utm_medium=member_android&utm_campaign=share_via)
19. [Building a feedback rich culture](https://www.edbatista.com/2013/12/new-post-at-hbr-building-a-feedback-rich-culture.html)
20. [TRM (𝘁𝗮𝘀𝗸-𝗿𝗲𝗹𝗲𝘃𝗮𝗻𝘁 𝗺𝗮𝘁𝘂𝗿𝗶𝘁𝘆) levels and what level of guidance to provide on each level](https://substack.com/@refactoring/note/c-63277431)
21. [Managing underperformers - specifically useful part about expectation setting](https://jackdanger.com/managing-underperformers/)
22. [Why should you dissolve instead of resolve](https://x.com/Kpaxs/status/1817762223751643164?t=RqeieRKKnt8SEr9QXhTfnw&s=31)
23. [Managing up](https://www.reforge.com/blog/mastering-managing-up)
24. [Feedback coach](https://chatgpt.com/g/g-67e01ddcb6588191bc9046197cc75e85-feedbackcoach)
#### concepts
1. “Great processes have automatic triggers, clear actions, and effective review.”
2. When I give you a mission, I want to be sure that "you've got this". - If I give it to X he got this if he can't get that done he'll tell me but he won't drop it
3. A leader is there to help the team get something done. A friend is there to help you feel good
4. Build a team bond -
   </br> 3.1 Have a lingo/dialect of your own “Magical day”, “X of the morning”
   </br> 3.2 Lunch together
   </br> 3.3 Do fun activities


### Interviewing
1. [38 smart questions to ask in a job interview](https://hbr.org/2022/05/38-smart-questions-to-ask-in-a-job-interview)
2. [Reversim - Let's talk about your salary / Iftach Bar](https://www.youtube.com/watch?v=pzq37L4UBUU&ab_channel=Reversim)
3. [My ten rules for negotiating a job offer](https://haseebq.com/my-ten-rules-for-negotiating-a-job-offer/)

### Tools
1. [Bypass CORS Chrome extension](https://chromewebstore.google.com/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf)

### Books
1. [Radical Candor](https://www.goodreads.com/en/book/show/29939161-radical-candor)
2. [Extreme Ownership](https://www.goodreads.com/book/show/23848190-extreme-ownership?ac=1&from_search=true&qid=LnkbcTTX2S&rank=1)
3. [Mindset](https://www.goodreads.com/en/book/show/40745)
4. [Turn the ship around](https://www.goodreads.com/book/show/16158601-turn-the-ship-around)
5. [Netflix Culture - No rules rules](https://www.goodreads.com/book/show/49099937-no-rules-rules)
