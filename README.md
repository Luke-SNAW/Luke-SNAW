### Hi there 👋. I'm a Front-end developer.
### 🌱 [My personal knowledge management](https://luke-snaw.github.io/) with [Dendron 🌲](https://github.com/dendronhq/dendron)

---

## Week 17, 2025

- [AI Horseless Carriages](https://koomen.dev/essays/horseless-carriages/)
  > Their app is a little bit of AI jammed into an interface designed for mundane human labor rather than an interface designed for automating mundane labor.
  > [“Horseless carriage”](https://en.wikipedia.org/wiki/Horseless_carriage) refers to the early motor car designs that borrowed heavily from the horse-drawn carriages that preceded them.
- [Botnet Part 2: The Web is Broken](https://jan.wildeboer.net/2025/04/Web-is-Broken-Botnet-Part-2/)
  > Certain companies recruit app developers to create botnets by injecting “network sharing” SDKs into their apps. These botnets then use the network bandwidth of unsuspecting users of said apps to crawl the web, brute-force mail servers and other nasty things.
- [Why LLM-Powered Programming is More Mech Suit Than Artificial Human](https://matthewsinclair.com/blog/0178-why-llm-powered-programming-is-more-mech-suit-than-artificial-human) - [“Centaur chess”](https://en.wikipedia.org/wiki/Advanced_chess) pairs humans with AI chess engines, creating teams that outperform both solo humans and solo AI systems playing on their own.
- [Vibe Coding is not an excuse for low-quality work](https://addyo.substack.com/p/vibe-coding-is-not-an-excuse-for) - AI 기반 바이브 코딩은 혁신적이지만, 품질 없는 속도는 위험하다는 경고의 글
  - 품질은 자동으로 따라오지 않음
  - 속도는 품질 없이는 무의미함
  - AI는 대체자가 아니라 인턴입니다 (사람이 루프 안에 있어야 함)
- [Cozy comfort](https://www.reuters.com/graphics/VIDEO-GAMES/MENTAL-HEALTH/akpeewkqgpr/) - New research backs up what gamers have thought for years: video games can be an antidote to stress and anxiety.
- [How to pack ternary numbers in 8-bit bytes](https://compilade.net/blog/ternary-packing)
  > `log(3) / log(2)` bits per ternary digit
- [Some features that every JavaScript developer should know in 2025](https://waspdev.com/articles/2025-04-06/features-that-every-js-developer-must-know-in-2025)
  ```js
  arr
    .values()
    .drop(10)
    .take(10)
    .filter((el) => el < 10)
    .map((el) => el + 5)
    .toArray()
  ```

## Week 16, 2025

- [The Problem with “Vibe Coding”](https://dylanbeattie.net/2025/04/11/the-problem-with-vibe-coding.html)
- [Understanding JavaScript Memory Management: Deep Dive into Garbage Collection Techniques](https://jsdev.space/js-garbage-collection/)
  > Generational Garbage Collection
  - Core Principle: The Weak Generation Hypothesis suggests younger objects tend to die faster.
  - V8 Specific Implementation: Objects that survive several GC cycles in the "new generation" are promoted to the "old generation."
- [Making :visited more private](https://developer.chrome.com/blog/visited-links)
  - with partitioning, browsing on Site A and click a link to go to Site B, the combination of "Site A + Site B" is stored in your `:visited` history
- [New Vulnerability in GitHub Copilot and Cursor](https://www.pillar.security/blog/new-vulnerability-in-github-copilot-and-cursor-how-hackers-can-weaponize-code-agents)
  - "Rules File Backdoor," which injects malicious instructions into configuration files used by AI coding assistants
  - The attack exploits hidden unicode characters and evasion techniques
- [Anubis works](https://xeiaso.net/notes/2025/anubis-works/)
- [Four years of running a SaaS in a competitive market](https://maxrozen.com/on-four-years-running-saas-competitive-market)
- [But what if I really want a faster horse?](https://rakhim.exotext.com/but-what-if-i-really-want-a-faster-horse)
  - YouTube. YouTube: Once a video catalog with social discovery. Now? TikTok.
  - LinkedIn. Once a network of resumes. Now? TikTok.
  - Substack. Yeah, a newsletter platform... now launching TikTok-style videos. [Seriously](https://techcrunch.com/2025/03/31/substack-is-rolling-out-a-tiktok-like-video-feed-in-its-app/).

---

> We love to see the process, not just the result. The imperfections in your work can be beautiful if they show your struggle for perfection, not a lack of care. — [ralphammer](https://ralphammer.com/is-perfection-boring/)

> I've often described my motivation for building software to others using imagery: I like to go find a secluded beach, build a large, magnificent sand castle, and then walk away. Will anyone notice? Probably not. Will the waves eventually destroy it? Yep. Did I still get immense satisfaction? Absolutely. — [aliasxneo](https://news.ycombinator.com/item?id=41497113)

> Simplicity, even if it sacrifices some ideal functionality has better survival characteristics than the-right-thing. — [The Rise of Worse is Better](https://www.dreamsongs.com/RiseOfWorseIsBetter.html)

> [Roberto Blake was talking about making 100 crappy videos](https://www.youtube.com/watch?v=OnUBaQ1Sp_E) to get better over time. Putting in the reps and improving a little bit each time.
>
> Putting in the work without expecting any external reward at first (eg views, followers, likes, etc) will pay off in the long run. — [100 Scrappy Things](https://www.florin-pop.com/blog/100-scrappy-things/)

> A good match is a **structured** dance, where players aim to **score** while they are following well-defined **rules**. This **freedom within a structure** is what makes it fun. — [ralphammer](https://ralphammer.com/how-to-get-started/)

> “Motivation often comes after starting, not before. Action produces momentum.” — James Clear

> Focus is more about **not** keeping busy when you need to wait for something.  
> Eat the boredom for a minute.
>
> — [[life-tips#wodenokoto]]

> [4 minutes run hard enough to push heart rate to 90%, 3 minutes recover, repeat 4 times](https://news.ycombinator.com/item?id=34213181)
>
> - https://www.ntnu.edu/cerg/advice
> - [Get running with Couch to 5K](https://www.nhs.uk/live-well/exercise/running-and-aerobic-exercises/get-running-with-couch-to-5k/)

> [recommended routine - bodyweightfitness](https://www.reddit.com/r/bodyweightfitness/wiki/kb/recommended_routine/) - I Don't Have This Much Time!
>
> - Don't workout at all (saves anywhere from 20 to 60 minutes, but really, really, really, really, really, really, really, really, really not recommended)

> 도무지 읽히지 않는 책 앞에서 내가 택한 방법은 펼쳐진 페이지 앞에서 멍때리기이다. 다르게 표현하면 이렇다. 펼쳐진 두 페이지 앞에서 오래 머물기.
>
> 책을 펼쳐놓는 것으로 충분하다. 읽지 못해도 좋다. 매일 정해진 진도를 나가야 하는 학교 수업이 아니니까. 하지만 읽지 않아도 괜찬다고 해서 펼쳐두지조차 않으면 곤란하다. 가능한 한 자주 책을 펼쳐두도록 하자. 전혀 읽지 않고 멍하니 바라보고 있다가 다시 덮게 되더라도
> — 막막한 독서. 시로군. P.10~13

> I think it should be everyone's primary focus to sleep well, drink water, get outside, get active, and eat generally decently. I hate to say it, but if you're not eating a good amount of vegetables and fruit, decent protein, sleep, etc, no amount of XYZ will catch up to that detriment. — [CE02](https://news.ycombinator.com/item?id=35056071)

> My real battle is doing good versus doing nothing. — [Deirdre Sullivan](https://www.npr.org/2005/08/08/4785079/always-go-to-the-funeral)

[Kind Engineering](https://kind.engineering/) - How To Engineer Kindness

> Sometimes magic is just someone spending more time on something than anyone else might reasonably expect. — [Teller](https://www.goodreads.com/quotes/6641527-sometimes-magic-is-just-someone-spending-more-time-on-something)

> Before leaving for the day I leave a comment in code: I’m working on this, need to do A, B C… to get it working. — [makz](https://news.ycombinator.com/item?id=40744916)

---

## What I read in past

- [👓 What I read in 2025](https://luke-snaw.github.io/notes/3c3ubyy4jyo2x0qui65nwtu/)
  - [2024](https://luke-snaw.github.io/notes/t9eilmx27nd8ytoelbm5v10/)
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
