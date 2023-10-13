### Hi there 👋. I'm a Front-end developer.
### 🌱 Personal knowledge management - [Dendron](https://luke-snaw.github.io/)

---

> “Motivation often comes after starting, not before. Action produces momentum.”
>
> — James Clear

> Focus is more about **not** keeping busy when you need to wait for something.  
> Eat the boredom for a minute.
>
> — [life-tips#wodenokoto](https://luke-snaw.github.io/notes/ettkt3iClONnxpbGwBVLl/#wodenokoto)

> [4 minutes run hard enough to push heart rate to 90%, 3 minutes recover, repeat 4 times](https://news.ycombinator.com/item?id=34213181)

> [Leave Your Work Broken](https://census.dev/blog/an-on-ramp-to-flow)
>
> - Before stepping away, leave the code in a state where it is Obviously Broken, but Easy to Fix.
> - Applying this technique means thinking about how to exit flow in a way that makes it easy to re-enter.

> [recommended routine - bodyweightfitness](https://www.reddit.com/r/bodyweightfitness/wiki/kb/recommended_routine/) - I Don't Have This Much Time!
>
> - Don't workout at all (saves anywhere from 20 to 60 minutes, but really, really, really, really, really, really, really, really, really not recommended)

> [Just 4 pages a day. It really adds up.](https://news.ycombinator.com/item?id=34779980)

> I think it should be everyone's primary focus to sleep well, drink water, get outside, get active, and eat generally decently. I hate to say it, but if you're not eating a good amount of vegetables and fruit, decent protein, sleep, etc, no amount of XYZ will catch up to that detriment.
>
> — [CE02](https://news.ycombinator.com/item?id=35056071)

---

## Week 41, 2023

- [A comprehensive guide to the dangers of Regular Expressions in JavaScript](https://www.sonarsource.com/blog/vulnerable-regular-expressions-javascript/) explains how certain regex patterns can cause exponential backtracking on long strings, leading to regular expression denial of service (ReDoS) vulnerabilities. Two real world examples caused major outages at Stack Overflow and CloudFlare due to unintentionally vulnerable regex use.
- [JavaScript Hydration Is a Workaround, Not a Solution](https://thenewstack.io/javascript-hydration-is-a-workaround-not-a-solution/)
  > JavaScript hydration is a technique used to add interactivity to server-rendered HTML pages by attaching event handlers to DOM elements on the client-side.  
  > However, this process requires recovering the necessary information to rebuild the application state and framework state. The document argues that hydration is an overhead because it duplicates the work already done by the server.
  >
  > A better approach called resumability avoids this overhead by serializing and transferring the necessary information from server to client.
  > This allows lazy execution of event handlers on the client-side instead of eagerly executing all components.
- [Angular, Qwik Creator on How JS Frameworks Handle Reactivity](https://thenewstack.io/angular-qwik-creator-on-how-js-frameworks-handle-reactivity/)
  > Three approaches: values, signals, and observables.
  >
  > Angular and React use values and take a coarse-grained approach, re-rendering everything when data changes.  
  > Vue is more fine-grained and will skip re-rendering unchanged components.  
  > Svelte compilers code to be more efficient.  
  > Qwik downloads only the minimal code needed through signals and resumability, making it highly optimized for start-up performance.  
  > Solid uses signals to be the most fine-grained, only executing code initially.
- [Speeding up the JavaScript ecosystem - The barrel file debacle](https://marvinh.dev/blog/speeding-up-javascript-ecosystem-part-7/)
  > The use of barrel files, which only re-export other files, is very common in large JavaScript projects. However, they can significantly slow down development tasks by forcing the rebuilding of the entire module graph for every file.
- [AI is an Ideology, Not a Technology](https://www.wired.com/story/opinion-ai-is-an-ideology-not-a-technology/) argues that artificial intelligence is better understood as an ideology rather than just a technology. It promotes a view of autonomous machine intelligence that could replace humans, but this is a mirage since AI relies heavily on human data and contributions. An alternative view is to focus on how people are central to developing AI systems through providing examples, problem-solving and understanding the technology.
- [Thread-per-core](https://without.boats/blog/thread-per-core/)
  > The thread-per-core architecture for Rust async programs has been controversial. While it promises better performance and ease of implementation, it may only achieve one, not both. A share-nothing approach keeps data in separate core caches but is complex to implement transactionally.
  > 
  > [The debate isn't about thread-per-core work stealing executors, it's whether async/await is a good abstraction for it in Rust. And the more async code I write the more I feel that it's leaky and hard to program against.](https://news.ycombinator.com/item?id=37791635)

## Week 40, 2023

- [Speeding up the JavaScript ecosystem - Polyfills gone rogue](https://marvinh.dev/blog/speeding-up-javascript-ecosystem-part-6/)
  > Many popular npm packages depend on 6-8x more packages than they need to. Most of these are unnecessary polyfills.
- [Why HTTP/3 is eating the world](https://blog.apnic.net/2023/09/25/why-http-3-is-eating-the-world/)
  > It uses the QUIC protocol, which improves on TCP by more extensively encrypting metadata and enabling faster connection setup. QUIC also enhances performance by eliminating issues like head-of-line blocking and improving network handling. While HTTP/3 was created to work over QUIC, the true innovation was QUIC itself, which updates TCP with security and efficiency improvements. QUIC encryption makes it easier to update features, since middleboxes cannot access metadata. Overall, QUIC and HTTP/3 enhance web performance and security by modernizing core Internet protocols.
- [Meta in Myanmar](https://erinkissane.com/meta-in-myanmar-part-i-the-setup) discusses how hate speech and misinformation spread on Facebook contributed to real-world violence against Rohingya Muslims in Myanmar starting in 2012. Activists had warned Facebook for years about this issue but the company was slow to act.
- [Encrypted Client Hello](https://blog.cloudflare.com/announcing-encrypted-client-hello/)
- [Draggable objects](https://www.redblobgames.com/making-of/draggable/)
- [MMO Architecture: Source of truth, Dataflows, I/O bottlenecks and how to solve them](https://prdeving.wordpress.com/2023/09/29/mmo-architecture-source-of-truth-dataflows-i-o-bottlenecks-and-how-to-solve-them/) discusses architecture challenges for massively multiplayer online (MMO) games. Unlike enterprise systems, the source of truth for an MMO's game world is the in-memory state, not the database, as persisting frequent updates would cause bottlenecks. To address this, the article recommends using a data service with the full state cached in memory.
- [Everything authenticated by Microsoft is tainted.](https://graz.social/@publicvoit/111147782761723981)
- [🚨🚨 That's a lot of YAML 🚨🚨](https://noyaml.com/)
  > [There are a lot of problems in YAML, but I think the main real problem is trying to put logic inside configuration.](https://news.ycombinator.com/item?id=37687365)
- [Live Near Your Friends](https://headlineshq.substack.com/p/issue-no-029-live-near-your-friends) - in distance of 5-minute walk
  - [The Tail End](https://waitbutwhy.com/2015/12/the-tail-end.html)

## What I read in past

- [👓 What I read in](https://luke-snaw.github.io/notes/t9eilmx27nd8ytoelbm5v10/)
- 📝 [Gists](https://gist.github.com/Luke-SNAW)
- 📜 [Journals](https://luke-snaw.github.io/Luke-SNAW__netlify-CMS.github.io/)

## [What I struggled 🧗‍♂️/📣 brag In](https://luke-snaw.github.io/notes/6645fjtiqxtko03nuccgjj2/)
<!--
**Luke-SNAW/Luke-SNAW** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
