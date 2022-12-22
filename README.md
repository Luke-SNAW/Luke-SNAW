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

---

## Week 51, 2022

- [15 Useful JavaScript Tips](https://javascript.plainenglish.io/15-useful-javascript-tips-814eeba1f4fd)

  - Event listeners run only once

  ```js
  element.addEventListener("click", () => console.log("I run only once"), {
    once: true,
  })
  ```

  - element’s dataset

  ```html
  <div id="user" data-name="Maxwell" data-age="32" data-something="Some Data">
    Hello Maxwell
  </div>
  <script>
    const user = document.getElementById("user")

    console.log(user.dataset)
    // { name: "Maxwell", age: "32", something: "Some Data" }

    console.log(user.dataset.name) // "Maxwell"
    console.log(user.dataset.age) // "32"
    console.log(user.dataset.something) // "Some Data"
  </script>
  ```

- [Run Just The Failed Tests In Cypress](https://glebbahmutov.com/blog/run-failed-tests/)
- [Project Guidelines](https://github.com/elsewhencode/project-guidelines)
- [Most Usefull Queries for Sql Server](https://towardsdev.com/most-usefull-queries-for-sql-server-596dda5742c1)
- [Let’s Make A Better “Light / Dark” Toggle](https://medium.com/codex/lets-make-a-better-light-dark-toggle-760499a8bc82)
- [Does WWW still belong in URLs?](https://css-tricks.com/does-www-still-belong-in-urls/)
  - WWW-less domain concern 1: Leaking cookies to subdomains
  - WWW-less domain concern 2: DNS headaches
  - [WWW-less benefits](https://css-tricks.com/does-www-still-belong-in-urls/#aa-www-less-benefits)
  - [WWW benefits](https://css-tricks.com/does-www-still-belong-in-urls/#aa-www-benefits)
- [Building the main navigation for a website](https://web.dev/website-navigation/)
- [The W3C Markup Validation Service](https://validator.w3.org/)
- [How to transfigure wireframes into HTML](https://www.htmhell.dev/adventcalendar/2022/1/)
- [How do I commit case-sensitive only filename changes in Git?](https://stackoverflow.com/a/20907647/5163033)
  ```shell
  git mv -f yOuRfIlEnAmE yourfilename
  ```

## Week 50, 2022

- [ReadEra](https://readera.org/en/book-reader) - ReadEra is an Android application for reading books and viewing documents, free and without ads.
- [Zapatos](https://github.com/jawj/zapatos) - Zero-abstraction Postgres for TypeScript: a non-ORM database library
- [Responsive Images 101, Part 4: Srcset Width Descriptors](https://cloudfour.com/thinks/responsive-images-101-part-4-srcset-width-descriptors/)
- [Mars Now | Explore – NASA Mars Exploration](https://mars.nasa.gov/explore/mars-now/)
- [A schedule's primary purpose is not to tell you what you're supposed to be doing on any given day, but to tell you when you should start cutting corners.](https://buildtogether.tech/process/#:~:text=A%20schedule%27s%20primary%20purpose%20is%20not%20to%20tell%20you%20what%20you%27re%20supposed%20to%20be%20doing%20on%20any%20given%20day%2C%20but%20to%20tell%20you%20when%20you%20should%20start%20cutting%20corners.)
- [Highlights from Git 2.39](https://github.blog/2022-12-12-highlights-from-git-2-39/)
- [How Cypress version 12 retries the chains of multiple query commands.](https://glebbahmutov.com/blog/cypress-v12/)
- [How to Write Useful Commit Messages](https://dev.to/jacobherrington/how-to-write-useful-commit-messages-my-commit-message-template-20n9)
  - This commit will `What`
  - `Why`
- [Ask HN: Those with money-making side projects,how did you come up with the idea?](https://news.ycombinator.com/item?id=33942558)
- [Just Use Postgres for Everything](https://www.amazingcto.com/postgres-for-everything/) - How to reduce complexity and move faster
  > Postgres can replace - up to millions of users - many backend technologies, Kafka, RabbitMQ, Mongo and Redis among them.
  >
  > [Each component has its own debugging requirements and tooling. Each component adds a bunch of complexity. Sometimes it's worth it, sometimes it's not.](https://news.ycombinator.com/item?id=33936703)
- [Radical Simplicity](http://www.radicalsimpli.city/)
- [When to use gRPC vs GraphQL](https://stackoverflow.blog/2022/11/28/when-to-use-grpc-vs-graphql/)
  > Use GraphQL for client-server communication and gRPC for server-to-server. See the Verdict section for exceptions to this rule.
- [Using `npm query` for better dependency management](https://blog.logrocket.com/npm-query-better-dependency-management/)
- [Make sense of flame charts in Performance Tab by example](https://calendar.perfplanet.com/2022/make-sense-of-flame-charts-in-performance-tab-by-example/)
  > During sampling profiling, a browser forces an engine to stop every 1 ms, and record the call stack at that moment.
- [So `<HGROUP>` Is Back In HTML 5, And Dumb As Ever!](https://medium.com/codex/so-hgroup-is-back-in-html-5-and-dumb-as-ever-c81e00f6320d)
- [HTML Entities, Diacritical Marks, And Emojis](https://blog.openreplay.com/html-entities-marks-and-emojis/)
- [numverify](https://numverify.com/) - Global Phone Number Validation & Lookup JSON API: Real-time REST API supporting 232 countries
- [Cypress: Skip Before Each Hook](https://glebbahmutov.com/blog/skip-before-each-hook/)
- [Functional Programming: Part 5 - Functors](https://blog.bitsrc.io/functional-programming-oh-functors-5e670d8eeb8d)

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
