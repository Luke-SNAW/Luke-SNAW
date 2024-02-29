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

## Week 09, 2024

- [Blur radius comparison](https://bjango.com/articles/blurradiuscomparison/)
  > the three Sketch blur types, scaled to the equivelent CSS box-shadow value. They now all match!
- [WebPerf Snippets](https://webperf-snippets.nucliweb.net/)
- [So, what exactly did Apple break in the EU?](https://blog.tomayac.com/2024/02/28/so-what-exactly-did-apple-break-in-the-eu/)
- [Youtube video embedding harm reduction](https://dustri.org/b/youtube-video-embedding-harm-reduction.html)
  ```html
  <iframe
    credentialless
    allowfullscreen
    referrerpolicy="no-referrer"
    sandbox="allow-scripts allow-same-origin"
    allow="accelerometer 'none'; ambient-light-sensor 'none'; autoplay 'none'; battery 'none'; browsing-topics 'none'; camera 'none'; display-capture 'none'; domain-agent 'none'; document-domain 'none'; encrypted-media 'none'; execution-while-not-rendered 'none'; execution-while-out-of-viewport ''; gamepad 'none'; geolocation 'none'; gyroscope 'none'; hid 'none'; identity-credentials-get 'none'; idle-detection 'none'; local-fonts 'none'; magnetometer 'none'; microphone 'none'; midi 'none'; otp-credentials 'none'; payment 'none'; picture-in-picture 'none'; publickey-credentials-create 'none'; publickey-credentials-get 'none'; screen-wake-lock 'none'; serial 'none'; speaker-selection 'none'; usb 'none'; window-management 'none'; xr-spatial-tracking 'none'"
    ,
    csp="sandbox allow-scripts allow-same-origin;"
    width="560"
    height="315"
    src="https://www.youtube-nocookie.com/embed/jfKfPfyJRdk"
    title="lofi hip hop radio 📚 - beats to relax/study to"
    frameborder="0"
    loading="lazy"
  ></iframe>
  ```
- [Netlify just sent me a $104K bill for a simple static site](https://old.reddit.com/r/webdev/comments/1b14bty/netlify_just_sent_me_a_104k_bill_for_a_simple/)
- [Four Steps to Achieving Operational Flow and Improving Quality in Tech Teams](https://www.infoq.com/articles/achieve-flow-improve-quality/)
  - Take on fewer things; focus on doing a complete job.
  - Dependencies destroy flow. Break down and remove dependencies in order to improve your team(s)'s ability to get things done.
  - Shift your focus toward keeping work moving and away from keeping people busy.
  - Work creates ROI only when a customer can use it. That means that completing work is more important than being busy.
  - It's more important for a team to be able to keep work moving than it is to keep the team small. Get work moving first, then think about how to reduce team size without compromising flow.
- [Dear Developer, the Web Isn’t About You](https://www.youtube.com/watch?v=WYXSck7TyVM)
  - The web was originally simple, robust and accessible to all due to technologies like HTML working together in a layered manner.
  - Performance and accessibility are major issues for many users but not priorities for most developers.
  - Simple, progressive techniques like serving HTML first make sites robust and usable for all.
  - The goal is caring for all people who use the web, not prioritizing new technologies.
- [SaaS Payment vs. SaaS Billing - What Those Terms Mean and What the Differences Are](https://www.wingback.com/blog/saas-payment-vs-saas-billing)
- [🦑 The 14 pains of building your own billing system](https://arnon.dk/the-14-pains-of-billing/)
- [Decoding Apple's Ploy To Scuttle Progressive Web Apps](https://infrequently.org/2024/02/home-screen-advantage/)
- [What is a non-capturing group in regular expressions?](https://stackoverflow.com/a/3513858/5163033)
- [console.delight](https://frontendmasters.com/blog/console-delight/)
- [Quality is a hard sell in big tech](https://www.pcloadletter.dev/blog/big-tech-quality/)

## Week 08, 2024

- [JavaScript Bloat in 2024](https://tonsky.me/blog/js-bloat/)
- [Scroll-Driven Animations: You want overflow: clip, not overflow: hidden](https://www.bram.us/2024/02/14/scroll-driven-animations-you-want-overflow-clip-not-overflow-hidden/)
- [Introducing SafeTest by Netflix: A Novel Approach to Front End Testing](https://netflixtechblog.com/introducing-safetest-a-novel-approach-to-front-end-testing-37f9f88c152d)
- [🔒Securing Web: A Deep Dive into Content Security Policy (CSP)](https://dev.to/vashnavichauhan18/securing-web-a-deep-dive-into-content-security-policy-csp-2nna)
- [Using localStorage in Modern Applications: A Comprehensive Guide](https://rxdb.info/articles/localstorage.html)
- [Using abbreviations for long CSS properties in VS Code](https://www.amitmerchant.com/using-abbreviations-for-long-css-properties-in-vs-code/)
- https://www.perfectmemory.ai/
  - https://www.rewind.ai/
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
