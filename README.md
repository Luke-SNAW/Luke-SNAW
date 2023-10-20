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

## Week 42, 2023

- [Build a Better Mobile Input](https://better-mobile-inputs.netlify.app/)
  - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#%3Cinput%3E_types
  - https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/inputmode
  - https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete
- [Styling External Links with Attribute Selectors](https://css-irl.info/styling-external-links-with-attribute-selectors/)
  - `a[class~='link']`, `a[href*='css-irl' s]`
- [The Ultimate Low-Quality Image Placeholder Technique](https://csswizardry.com/2023/09/the-ultimate-lqip-lcp-technique/)
- [Fast-Paced Multiplayer (Part IV): Lag Compensation](https://www.gabrielgambetta.com/lag-compensation.html)
- [Fast-Paced Multiplayer (Part III): Entity Interpolation](https://www.gabrielgambetta.com/entity-interpolation.html)
- [How to escape CSS selectors in JavaScript](https://www.stefanjudis.com/today-i-learned/how-to-escape-css-selectors-in-javascript/) - a handy static method in the `CSS` JavaScript namespace to help with this exact problem — [`CSS.escape()`](https://developer.mozilla.org/en-US/docs/Web/API/CSS/escape_static)
- [Fast-Paced Multiplayer (Part II): Client-Side Prediction and Server Reconciliation](https://www.gabrielgambetta.com/client-side-prediction-server-reconciliation.html)
- [Write more "useless" software](https://ntietz.com/blog/write-more-useless-software/) for the joy of computing.
- [Reflect](https://reflect.net/) - High-performance sync for multiplayer web apps
  - [Ready Player Two](https://rocicorp.dev/blog/ready-player-two) - Transactional Conflict Resolution instead of CRDTs
- [PartyKit](https://github.com/partykit/partykit/) simplifies developing multiplayer applications
- [Microfrontends should be your last resort](https://www.breck-mckye.com/blog/2023/05/Microfrontends-should-be-your-last-resort/) argues teams should first refactor their code into isolated domains and minimize dependencies before considering microfrontends.
- [alternative-front-ends](https://github.com/mendel5/alternative-front-ends/) - Overview of alternative open source front-ends for popular internet platforms (e.g. YouTube, Twitter, etc.)
- [Organizing multiple Git identities](https://garrit.xyz/posts/2023-10-13-organizing-multiple-git-identities)
  - [You can also filter based on the remote URL!](https://news.ycombinator.com/item?id=37904125)
- [Populating the page: how browsers work](https://developer.mozilla.org/en-US/docs/Web/Performance/How_browsers_work)
- [One Game, By One Man, On Six Platforms: The Good, The Bad and The Ugly](https://ruoyusun.com/2023/10/12/one-game-six-platforms.html)

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
