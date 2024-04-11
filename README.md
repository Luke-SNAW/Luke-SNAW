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

## Week 15, 2024

- [QWANJI](https://byronicalpatrick.github.io/qwanji/)
- [The Power of :has() in CSS](https://css-tricks.com/the-power-of-has-in-css/)
  ```css
  h1:has(+ h2) {
    color: blue;
  }
  ```
- [How to Kill the Cascade](https://robinrendle.com/the-cascade/017-how-to-kill-the-cascade/)
- [In-app browsers are still a privacy, security, and choice problem](https://www.theregister.com/2024/03/27/inapp_browsers/)
- [How to think about HTML responsive images](https://danburzo.ro/responsive-images-html/)
  ```html
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="macos-dark.png" />
    <source media="print" srcset="macos-contrast.png" />
    <img src="macos-light.png" alt="…" />
  </picture>
  ```
- [The 37signals Guide to Internal Communication](https://37signals.com/how-we-communicate)

## Week 14, 2024

- [An Interactive Guide to CSS Container Queries](https://ishadeed.com/article/css-container-query-guide)

  ```css
  /* Try to add more items and see what happens. */
  .timelineWrapper {
    container: timeline / inline-size;
    --force-vertical: false;

    &:has(.c-timeline__item:nth-last-child(n + 5)) {
      --force-vertical: true;
    }
  }
  ```

  ```css
  @container timeline (inline-size > 430px) and style(--force-vertical: false) {
    /* Apply the full variation. */
  }
  ```

- [Reddit Migrates Media Metadata from S3 and Other Systems into AWS Aurora Postgres](https://www.infoq.com/news/2024/03/reddit-metadata-s3-postgres/)
- [Chill Scroll Snapping: Article Headers](https://frontendmasters.com/blog/chill-scroll-snapping-article-headers/)
- [JavaScript Visualized: Promise Execution](https://www.lydiahallie.com/blog/promise-execution)
  > Long story short, Promises are just objects with some additional functionality to change their internal state.
  >
  > The cool thing about Promises is that this can trigger an asynchronous action if a handler is attached by either then or catch. Since the handlers are pushed to the Microtask Queue, you can handle the eventual result in a non-blocking way. This makes it easier to handle errors, chain multiple operations together, and keep your code more readable and maintainable!
- [Happy 404 Day. Whats your favorite 404 error page?](https://news.ycombinator.com/item?id=39928950)
  - [Financial Times 404](https://www.ft.com/404)
- [Kobold Letters](https://lutrasecurity.com/en/articles/kobold-letters/) - Why HTML emails are a risk to your organization
- [Spicing up text with text-emphasis in CSS](https://www.amitmerchant.com/spicing-up-text-with-text-emphasis-in-css/)
  ```css
  .text-emphasis-dollar {
    text-emphasis: "$" lime;
    text-emphasis-position: under;
  }
  ```
- [CSS scoping from What You Need to Know about Modern CSS (Spring 2024 Edition)](https://frontendmasters.com/blog/what-you-need-to-know-about-modern-css-spring-2024-edition/#scoping)
- [CSS Button Styles You Might Not Know](https://dbushell.com/2024/03/10/css-button-styles-you-might-not-know/)
  > The manipulation value disables gestures like ‘double-tap to zoom’. Other gestures like ‘panning’ and ‘pinch to zoom’ are unaffected. An extra benefit is that the browser no longer needs to delay the click event waiting for a second tap.
  ```css
  .button,::file-selector-button {
    inline-size: fit-content;
    touch-action: manipulation;
    user-select: none;
  }
  *:focus-visible {
      outline: 2px solid magenta;
      outline-offset: 2px;
    }
  }
  ```
- [BIG DATA IS DEAD](https://motherduck.com/blog/big-data-is-dead/)
  > The author suggests that the real problem is often data hoarding rather than true "Big Data" challenges. Overall, the passage contends that the Big Data hype has passed and organizations should focus on using their data effectively rather than worrying about sheer data volume.
- [What’s the Difference Between OLAP and OLTP?](https://aws.amazon.com/compare/the-difference-between-olap-and-oltp/)
- [Postgres is eating the database world](https://medium.com/@fengruohang/postgres-is-eating-the-database-world-157c204dcfc4)
  > PostgreSQL is emerging as a dominant database platform that is capable of handling a wide range of use cases, from OLTP to OLAP workloads. Its extensibility through a thriving ecosystem of add-ons and integrations allows it to compete with specialized databases across various domains like time-series, geospatial, and vector data. The rise of analytical extensions like ParadeDB and DuckDB have further bolstered PostgreSQL's capabilities, making it a viable alternative to dedicated data warehousing solutions. As hardware advancements have addressed performance and scalability concerns, the need for separate OLTP and OLAP systems is diminishing, leading to a convergence where PostgreSQL can serve as a unified, multi-model database. The author argues that the real competitive frontier now lies in leveraging PostgreSQL's extensibility through integrated distributions and services, rather than focusing on the core database kernel.
- [The power of CSS Variables 💪: A flexible solution for spacing utilities](https://dev.to/karsten_biedermann/the-power-of-css-variables-a-flexible-solution-for-spacing-utilities-4bch)

  ```html
  <div style="--space-top: 30px; --space-bottom: 100px;"></div>
  ```

  ```css
  @media (min-width: 992px) {
    [style*="--space-bottom"] {
      margin-bottom: var(--space-bottom);
    }
    [style*="--space-top"] {
      margin-top: var(--space-top);
    }
  }
  ```

- [What is safe alignment in CSS?](https://frontendmasters.com/blog/what-is-safe-alignment-in-css/)
  ```css
  .flex {
    display: flex;
    align-items: safe center;
  }
  ```
- [LiveView is best with Svelte](https://blog.sequin.io/liveview-is-best-with-svelte/)
  > LiveView is a unique approach to building web applications that combines the benefits of server-rendered and client-side frameworks. While LiveView offers many advantages, the authors found some limitations around handling complex client-side interactions and the blurry line between client and server state. To address these challenges, the authors describe using LiveView together with the Svelte frontend framework, which they found to be a powerful and productive combination. The LiveView backend handles data fetching, validation, and state management, while the Svelte frontend focuses on rendering and simple event handling. This "LiveSvelte" approach eliminates the need for a separate frontend microservice and allows for a clean separation of concerns between the client and server.
  >
  > > One possible solution which I didn't investigate, but should work, is to write all game logic in gleam ([https://gleam.run/](https://gleam.run/)). Gleam is compatible with Elixir, AND it also can compile to js, so you could in theory run the same code on the server and the client. — [POiNTx](https://news.ycombinator.com/item?id=39919223)
- [HTTP Speed](https://kitsonkelly.com/posts/http-speed) - Deno, Bun, Node.js
- [Optimizing Javascript for fun and for profit](https://romgrk.com/posts/optimizing-javascript)
  - [Avoid different shapes](https://romgrk.com/posts/optimizing-javascript#2-avoid-different-shapes)
- [Runtime compatibility across JavaScript runtimes](https://runtime-compat.unjs.io/)
  - https://node.green/
- [Alpine Ajax - Comparisons between Alpine AJAX and other similar libraries](https://alpine-ajax.js.org/comparisons/)
- [WebSockets vs Server-Sent-Events vs Long-Polling vs WebRTC vs WebTransport](https://rxdb.info/articles/websockets-sse-polling-webrtc-webtransport.html)

## What I read in past

- [👓 What I read in 2024](https://luke-snaw.github.io/notes/t9eilmx27nd8ytoelbm5v10/)
  - [2023](https://luke-snaw.github.io/notes/d9io1hr2n9vdbvucvy3iquj/)
  - [2022](https://luke-snaw.github.io/notes/l4c5ilaotvka1yh10wv88cy/)
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
