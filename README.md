### Hi there 👋. I'm a Front-end developer.
### 🌱 [My personal knowledge management](https://luke-snaw.github.io/) with [Dendron 🌲](https://github.com/dendronhq/dendron)

---

## Week 39, 2025

- [Give footnotes the boot](https://jakearchibald.com/2025/give-footnotes-the-boot/)

  - Footnotes disrupt the reading flow by requiring readers to navigate away from the main content.
  - On the web, footnotes are even more cumbersome due to scrolling and navigation challenges.
  - Readers should be able to easily skip over supplementary content if they choose.

  > For example: [#](https://jakearchibald.com/2025/give-footnotes-the-boot/#comment-6731381255)
  >
  > - 50+% likelihood and content is short? → Parentheses
  > - 50+% likelihood and content is medium or long? → note block
  > - 20-50% likelihood and content is medium or long? → collapsed note block
  > - < 20% likelihood and content is short or medium? → footnote

## Week 38, 2025

- [V8과 WebAssembly: 현대 자바스크립트 엔진의 구조와 성능 최적화(상하편)](https://www.zigae.com/chrome-gc/)
  - V8의 세대별 힙 구조는 객체의 수명에 따라 최적화된 처리를 가능하게 하며, Young Generation과 Old Generation으로 구분되어 관리된다.
  - V8의 세대별 객체 승격 메커니즘은 Age-based, Size-based, Pretenuring 등의 복합적인 휴리스틱을 사용하여 객체를 Old Generation으로 승격시킨다.
  - React의 Fiber 아키텍처는 V8의 세대별 가설과 충돌하며, Fiber 노드는 컴포넌트가 마운트된 동안 계속 살아있어 Old Generation으로 승격되어 Major GC 부담을 증가시킨다.
  - React Hooks는 클로저 메모리 누수를 일으킬 수 있으며, useEffect와 같은 훅은 클로저가 전체 컴포넌트 스코프를 캡처하여 메모리 누수를 유발할 수 있다.
  - V8의 Orinoco 프로젝트는 병렬 처리, 증분 처리, 동시 처리 등의 기술을 도입하여 GC pause time을 크게 감소시켰으며, 특히 동시 마킹은 Major GC pause time을 60-70% 감소시켰다.
- [Distributing your own scripts via Homebrew](https://justin.searls.co/posts/how-to-distribute-your-own-scripts-via-homebrew/)
  - Creating a Homebrew tap involves setting up a GitHub repository and using the brew tap-new command.
- [Anycrap](https://anycrap.shop/) - A store that generates products from anything you type in search
- [Many Hard Leetcode Problems are Easy Constraint Problems](https://buttondown.com/hillelwayne/archive/many-hard-leetcode-problems-are-easy-constraint/)
  > Constraint solvers runtimes are unpredictable and almost always slower than an ideal bespoke algorithm because they are more expressive, in what I refer to as the [capability/tractability tradeoff](https://buttondown.com/hillelwayne/archive/the-capability-tractability-tradeoff/). But even so, they'll do way better than a _bad_ bespoke algorithm, and I'm not experienced enough in handwriting algorithms to consistently beat a solver.
  > The real advantage of solvers, though, is how well they handle new constraints.
- [Proton Mail suspended journalist accounts at request of cybersecurity agency](https://theintercept.com/2025/09/12/proton-mail-journalist-accounts-suspended/)
- [UTF-8 is a Brilliant Design](https://iamvishnu.com/posts/utf8-is-brilliant-design) - still be backward compatible with ASCII
  1.  Read a byte. If it starts with 0, it's a single-byte character (ASCII). Show the character represented by the remaining 7 bits on the screen. Continue with the next byte.
  2.  If the byte didn't start with a 0, then:
      - If it starts with 110, it's a two-byte character, so read the next byte as well.
      - If it starts with 1110, it's a three-byte character, so read the next two bytes.
      - If it starts with 11110, it's a four-byte character, so read the next three bytes.
  3.  Once the number of bytes are determined, read all the remaining bits except the leading bits, and find the binary value (aka. code point) of the character.
  4.  Look up the code point in the Unicode character set to find the corresponding character and display it on the screen.
  5.  Read the next byte and repeat the process.

---

- 🥱 -> 🤔💡🌱 — [On The Death of Daydreaming](https://www.afterbabel.com/p/on-the-death-of-daydreaming)

> I've often described my motivation for building software to others using imagery: I like to go find a secluded beach, build a large, magnificent sand castle, and then walk away. Will anyone notice? Probably not. Will the waves eventually destroy it? Yep. Did I still get immense satisfaction? Absolutely. — [aliasxneo](https://news.ycombinator.com/item?id=41497113)

> We love to see the process, not just the result. The imperfections in your work can be beautiful if they show your struggle for perfection, not a lack of care. — [ralphammer](https://ralphammer.com/is-perfection-boring/)

> Simplicity, even if it sacrifices some ideal functionality has better survival characteristics than the-right-thing. — [The Rise of Worse is Better](https://www.dreamsongs.com/RiseOfWorseIsBetter.html)

> [Roberto Blake was talking about making 100 crappy videos](https://www.youtube.com/watch?v=OnUBaQ1Sp_E) to get better over time. Putting in the reps and improving a little bit each time.
>
> Putting in the work without expecting any external reward at first (eg views, followers, likes, etc) will pay off in the long run. — [100 Scrappy Things](https://www.florin-pop.com/blog/100-scrappy-things/)

> Make the difficult habitual, the habitual easy, and the easy beautiful. — [Constantin S. Stanislavski](https://www.goodreads.com/quotes/7102271-make-the-difficult-habitual-the-habitual-easy-and-the-easy)

> A good match is a **structured** dance, where players aim to **score** while they are following well-defined **rules**. This **freedom within a structure** is what makes it fun. — [ralphammer](https://ralphammer.com/how-to-get-started/)

- [Pivot Points](https://longform.asmartbear.com/pivot-points/)
  - non-judgmental aspects of personality that can be strengths in some contexts and weaknesses in others
  - Pivot Points are fixed in the short term

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
> 책을 펼쳐놓는 것으로 충분하다. 읽지 못해도 좋다. 매일 정해진 진도를 나가야 하는 학교 수업이 아니니까. 하지만 읽지 않아도 괜찮다고 해서 펼쳐두지조차 않으면 곤란하다. 가능한 한 자주 책을 펼쳐두도록 하자. 전혀 읽지 않고 멍하니 바라보고 있다가 다시 덮게 되더라도
> — 막막한 독서. 시로군. P.10~13

> I think it should be everyone's primary focus to sleep well, drink water, get outside, get active, and eat generally decently. I hate to say it, but if you're not eating a good amount of vegetables and fruit, decent protein, sleep, etc, no amount of XYZ will catch up to that detriment. — [CE02](https://news.ycombinator.com/item?id=35056071)

> My real battle is doing good versus doing nothing. — [Deirdre Sullivan](https://www.npr.org/2005/08/08/4785079/always-go-to-the-funeral)

[Kind Engineering](https://kind.engineering/) - How To Engineer Kindness

> Sometimes magic is just someone spending more time on something than anyone else might reasonably expect. — [Teller](https://www.goodreads.com/quotes/6641527-sometimes-magic-is-just-someone-spending-more-time-on-something)

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
