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

## Week 26, 2023

- [MJML](https://github.com/mjmlio/mjml) - the only framework that makes responsive-email easy
- [SSMPL : A Wishful Thinking HTML Replacement Proposal](https://medium.com/codex/ssmpl-a-wishful-thinking-html-replacement-proposal-1e11e8d86bf6)
- [Slonik](https://github.com/gajus/slonik) - A [battle-tested](https://github.com/gajus/slonik#user-content-battle-tested) Node.js PostgreSQL client with strict types, detailed logging and assertions.
- [Stop using Knex.js](https://gajus.medium.com/stop-using-knex-js-and-earn-30-bf410349856c) - Using SQL query builder is an anti-pattern
  > Knex.js (and other query builders) was designed to be a building block for ORMs; it does not add value when majority of the query is static.  
  > I recommend that you use a query builder for those few queries that need to be generated dynamically, and use raw SQL for everything else. It is not one or the other; the two work together.
- [Is ORM still an 'anti pattern'?](https://github.com/getlago/lago/wiki/Is-ORM-still-an-%27anti-pattern%27%3F)

  > - ["ORMs make the easy parts slightly easier, but they make the hard parts really hard"](https://news.ycombinator.com/item?id=36500429)

  > - Sequelize is extremely simpler and writing code with it is a joy compared to hibernate.
  > - A year ago i had to develop a big Java application without orm (cto’s choice): i didn’t remember how tedious, error prone and slow is development without orm!!! Never do it again!
  > - I think the best approach is to use orm for common crud tasks and add specific sql queries when things get a little bit complicated.
  >   [andretti1977](https://news.ycombinator.com/item?id=36503105)

- [Inverted Triangle Architecture For CSS (ITCSS)](https://apiumhub.com/tech-blog-barcelona/inverted-triangle-architecture-for-css-itcss/)
- [A Complete Guide to CSS Cascade Layers](https://css-tricks.com/css-cascade-layers/)
  > - `@layer reset, default, themes, patterns, layouts, components, utilities;`
- [try](https://github.com/binpash/try) lets you run a command and inspect its effects before changing your live system. `try` uses Linux's [namespaces (via `unshare`)](https://docs.kernel.org/userspace-api/unshare.html) and the [overlayfs](https://docs.kernel.org/filesystems/overlayfs.html) union filesystem.

## Week 25, 2023

- [Handles are the better pointers](https://floooh.github.io/2018/06/17/handles-vs-pointers.html)
- [Microsoft Clarity - Free Heatmaps & Session Recordings](https://clarity.microsoft.com/)
- [Modern CSS in Real Life](https://chriscoyier.net/2023/06/06/modern-css-in-real-life/)
  > - `margin-right`: Translated to RTL, spacing problem. use `margin-inline-end` (or `gap`).
  > - `img` alt: With that brief information, perhaps someone might be able to, say, recognize the exact pier in the photo if they had been there before or the like.
  > - higher layer will win, regardless of specificity.
  > - `@import url(~) layer;` - my @import of Bootstrap is plunked onto a layer. Note: we don’t even have to name it, and we can use this keyword instead of @layer while importing. - my super weak CSS selector in which I’m trying to override header margin does win
  > - `@layer reset, default, themes, patterns, layouts, components, utilities;`
- [Software effort estimation is mostly fake research](https://shape-of-code.com/2021/01/17/software-effort-estimation-is-mostly-fake-research/)
  > from [HK news](https://news.ycombinator.com/item?id=36350632)
  >
  > - It's not fake research. It's actually quite an established science in the 24 years I've been doing it.
  > - Take your first guess, double it, double it again if the stakeholder is a poser, add 20% per developer less experience than you, subtract 10% for the features you're going to essentially copy paste, add 15% for sick leave (browsing HN) and then double it for every question you have that are unresolved and divide it by the room temperature multiplied by the amount of people with mechanical keyboards.
  > - That gives you roughly the right estimate for any job, until the next sprint.
- [My Custom CSS Reset](https://www.joshwcomeau.com/css/ccustom-css-reset/)
  - In MacOS Mojave, released in 2018, Apple disabled subpixel antialiasing across the operating system.
  - Confusingly, MacOS browsers like Chrome and Safari still use subpixel antialiasing by default. We need to explicitly turn it off, by setting `-webkit-font-smoothing` to `antialiased`.

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
