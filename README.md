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

## Week 08, 2024

- [If Architects had to work like Programmers](http://www.gksoft.com/a/fun/architects.html)
- [Bloom Filters](https://samwho.dev/bloom-filters/)
  - Bloom filters return true it doesn't mean "yes", it means "maybe", false-positive.
  - If you're happy to accept being wrong 0.0001% of the time (1 in a million), you could use a bloom filter which can store the same data in 82% reduction in size.
- [In Defense of Simple Architectures](https://danluu.com/simple-architectures/)
  - [Microservices aren't a performance strategy. They are a POTENTIAL cost saving strategy against performance. And an engineering coordination strategy.](https://news.ycombinator.com/item?id=39441508)
  - [Towards Modern Development of Cloud Applications](https://dl.acm.org/doi/pdf/10.1145/3593856.3595909)
- [The Case Against Caffeine](https://zantafakari.substack.com/p/the-case-against-caffeine)
  - But it gets worse, especially if you drink lots of caffeine throughout the day. In that case, you never give your body the chance to clear it out. So the base concentration in your blood slowly creeps up. - https://zantafakari.substack.com/i/141012714/the-science-of-sleep
- [htmz](https://github.com/Kalabasa/htmz) is a minimalist HTML microframework that gives you the power to create dynamic web user interfaces with the familiar simplicity of plain HTML.
  ```html
  <iframe
    hidden
    name="htmz"
    onload="setTimeout(()=>document.querySelector(this.contentWindow.location.hash||null)?.replaceWith(...this.contentDocument.body.childNodes))"
  ></iframe>
  ```

## Week 07, 2024

- [LLRT (**L**ow **L**atency **R**un**t**ime)](https://github.com/awslabs/llrt) is a lightweight JavaScript runtime designed to address the growing demand for fast and efficient Serverless applications. LLRT offers up to over **10x** faster startup and up to **2x** overall lower cost compared to other JavaScript runtimes running on **AWS Lambda**
- [A Guide To Designing For Older Adults](https://www.smashingmagazine.com/2024/02/guide-designing-older-adults/)
  > Today, one billion people are 60 years or older. That’s 12% of the entire world population, and the age group is growing faster than any other group. Yet, online, the needs of older adults are often overlooked or omitted.
- [How to make external links accessible](https://blog.pope.tech/2024/01/02/how-to-make-external-links-accessible/)
  - [Why external links should open in the same tab](https://blog.pope.tech/2024/01/02/how-to-make-external-links-accessible/#why)
    - giving users the choice
  - [When external links should open in a new tab](https://blog.pope.tech/2024/01/02/how-to-make-external-links-accessible/#when)
    - Lose form progress
    - An alternative solution
    - Terminate login
    - User needs information on both pages
  - [Accessible design and code for external links opening in a new tab](https://blog.pope.tech/2024/01/02/how-to-make-external-links-accessible/#design)
    - give users a warning that it opens in a new tab.
- [:focus vs :focus-visible](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible#focus_vs_focus-visible)
  > The `:focus-visible` pseudo-class also matches the focused element, but only if the user needs to be informed where the focus currently is.
  - https://daverupert.com/2024/01/focus-visible-love/
- [The psychology of site speed and human happiness](https://www.speedcurve.com/blog/psychology-site-speed/)
- [Apple has not fixed the macOS audio left/right balance bug for nearly 10 years](https://twitter.com/ffaebi/status/1757669861377949930)
  - https://news.ycombinator.com/item?id=39367460
- [I designed a cube that balances itself on a corner](https://willempennings.nl/balancing-cube/)
- [How to Study](https://cse.buffalo.edu/~rapaport/howtostudy.html)
- [(Almost) Every infrastructure decision I endorse or regret after 4 years running infrastructure at a startup](https://cep.dev/posts/every-infrastructure-decision-i-endorse-or-regret-after-4-years-running-infrastructure-at-a-startup/)
- [Classless CSS](https://github.com/dbohdan/classless-css)
- [Drop-in switcher for previewing minimal CSS frameworks](https://dohliam.github.io/dropin-minimal-css/)

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
