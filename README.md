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

## Week 52, 2022

- [Tailwind - Dynamic class names](https://tailwindcss.com/docs/content-configuration#dynamic-class-names)
  ```js
  class = `bg-${ zero ? pageColor : baseColor}` // not work
  class = zero ? `bg-${pageColor}` : `bg-${baseColor}` // not work
  ```
- [Control what you share with Google](https://developers.google.com/search/docs/crawling-indexing/control-what-you-share)
- [qwantify](https://github.com/wanjohiryan/qwantify) - Play games with your friends right from the browser.
- [Dioxus](https://github.com/DioxusLabs/dioxus) is a portable, performant, and ergonomic framework for building cross-platform user interfaces in Rust.
- [CDN Up and Running](https://github.com/leandromoreira/cdn-up-and-running) - Building a CDN from Scratch to Learn
- [2022 In Review: What’s New In Web Performance?](https://www.debugbear.com/blog/2022-in-web-performance)
- [Designing for Screen Reader Compatibility](https://webaim.org/techniques/screenreader/)
- [Table Like It's 2023](https://www.htmhell.dev/adventcalendar/2022/14/)
- [Password requirements: myths and madness](https://www.franzoni.eu/password-requirements-myths-madness/)
  - https://news.ycombinator.com/item?id=34098369

## Week 51, 2022

- [Using inline JavaScript modules to prevent CSS blockage](https://calendar.perfplanet.com/2022/using-inline-javascript-modules-to-prevent-css-blockage/)
  ```html
  <script async type="module" />
  ```
- [CSS Style Queries](https://ishadeed.com/article/css-container-style-queries/)
- [A Visual Guide to useEffect](https://alexsidorenko.com/blog/useeffect/)
  > Side effects shouldn’t happen during component render. Therefore they do not belong to the body of a functional component. React has a special place for them.
- [4 ways CSS :has() can make your HTML forms even better](https://austingil.com/css-has-with-html-forms/)
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
