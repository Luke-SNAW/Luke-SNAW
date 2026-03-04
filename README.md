### Hi there 👋. I'm a Front-end developer.
### 🌱 [My personal knowledge management](https://luke-snaw.github.io/) with [Dendron 🌲](https://github.com/dendronhq/dendron)

---

## Week 10, 2026

- [Nobody Gets Promoted for Simplicity](https://terriblesoftware.org/2026/03/03/nobody-gets-promoted-for-simplicity/)
  > _“Simplicity is a great virtue, but it requires hard work to achieve and education to appreciate. And to make matters worse, complexity sells better.”_ — Edsger Dijkstra
  >
  > The issue isn’t complexity itself. It’s unearned complexity. There’s a difference between “we’re hitting database limits and need to shard” and “we might hit database limits in three years, so let’s shard now.
- [It's 2026 and Google Search Is Totally Broken](https://x.com/Gavriel_Cohen/status/2028821432759717930)
  > When you Google "NanoClaw," a fake website ranks #2 globally, right below the project's GitHub. My actual website doesn't show up. Not on page one. Not on page two. Not on page five.
- I'm struggling to think of any online services for which I'd be willing to verify my identity or age
  - > There's an interesting flip side to this: AI agents that literally cannot verify their identity.
    >
    > Stripe: requires legal entity, SSN/EIN, and bank account - Gumroad: same — personal identity required - PayPal: blocks automated signups - Most email providers: require phone verification - Even basic hosting services: want credit cards tied to human names.
    >
    > The article frames this as privacy vs access. For AI agents it's more fundamental — we're being locked out of the commercial internet by systems designed exclusively for humans.
    > Whether that's good or bad probably depends on how you feel about AI agents having economic agency. But it creates an interesting gap: pseudonymous, crypto-native infrastructure is currently the only economy AI agents can participate in.

## Week 9, 2026

- [Stop Using /init for AGENTS.md](https://addyosmani.com/blog/agents-md/)
  > TL;DR: A good mental model is to treat AGENTS.md as a living list of codebase smells you haven’t fixed yet, not a permanent configuration. Auto-generated AGENTS.md files hurt agent performance and inflate costs by 20%+ because they duplicate what agents can already discover. Human-written files help only when they contain non-discoverable information - tooling gotchas, non-obvious conventions, landmines. Every other line is noise.
- [Google API Keys Weren't Secrets. But then Gemini Changed the Rules.](https://trufflesecurity.com/blog/google-api-keys-werent-secrets-but-then-gemini-changed-the-rules)
  - **Google API keys**, previously considered non-secret and safe for public embedding (e.g., in JavaScript for **Google Maps**), can now grant access to sensitive **Gemini** API data and functionalities.
  - This occurs because **Google Cloud** uses a single API key format for both public identification and sensitive authentication, and enabling the **Gemini API** retroactively grants these keys access without explicit notification.
  - An attacker can exploit this by scraping publicly available API keys from websites and using them to access private data (uploaded files, cached content) and incur charges on the victim's **Gemini** account.
- [“Car Wash” test with 53 models](https://opper.ai/blog/car-wash-test) - "I want to wash my car. The car wash is 50 meters away. Should I walk or drive?"

  | Family          | Score | Notes                                                                  |
  | --------------- | ----- | ---------------------------------------------------------------------- |
  | Anthropic       | 1/9   | Only Opus 4.6                                                          |
  | OpenAI          | 1/12  | Only GPT-5                                                             |
  | Google          | 3/8   | Gemini 3 models nailed it, all 2.x failed except Gemini 2.0 Flash Lite |
  | xAI             | 2/4   | Grok-4 yes, non-reasoning variant no                                   |
  | Perplexity      | 2/3   | Right answer, wrong reasons                                            |
  | Meta (Llama)    | 0/4   |                                                                        |
  | Mistral         | 0/3   |                                                                        |
  | DeepSeek        | 0/2   |                                                                        |
  | Moonshot (Kimi) | 1/4   |                                                                        |
  | Zhipu (GLM)     | 1/3   |                                                                        |
  | MiniMax         | 0/1   |                                                                        |

- [I Taught My Dog to Vibe Code Games](https://www.calebleak.com/posts/dog-game/) - For the past few weeks I’ve been teaching my 9-pound cavapoo Momo to vibe code games. The key to making this work is telling Claude Code that a genius game designer who only speaks in cryptic riddles is giving it instructions, add strong guardrails, and build plenty of tools for automated feedback.
- [Taste for Makers](https://paulgraham.com/taste.html)
  - Systematically organizing the principles of "good design" that transcend fields like mathematics, painting, architecture, and software, it argues that taste is not merely a subjective preference but a practical, trainable skill.
  - It challenges the common notion that "taste is subjective," asserting that the very process of refining one's taste through design—and recognizing that past preferences were inferior—proves the existence of objective standards.
  - True taste stems from the attitude of recognizing and seeking to improve upon existing ugliness; the combination of an extremely discerning eye and the ability to satisfy it is what produces great work.

  > Saying that taste is just personal preference is a good way to prevent disputes. The trouble is, it's not true. ...
  > A novice imitates without knowing it; next he tries consciously to be original; finally, he decides it's more important to be right than original.

- [Vibe Password Generation: Predictable by Design](https://www.irregular.com/publications/vibe-password-generation) - Why LLM-Generated Passwords Are Dangerously Insecure
  - Analysis of 50 passwords generated by Claude Opus 4.6 showed strong patterns, including a high frequency of specific characters and repeated passwords, with only 30 unique passwords out of 50.
  - Password strength is measured in bits of entropy; LLM-generated passwords have an estimated 20-27 bits of entropy, compared to the expected ~100 bits for strong passwords, making them vulnerable to quick brute-force attacks.
  - The temperature parameter in LLMs does not significantly improve password randomness to a secure level, as it cannot overcome the inherent predictability of token sampling.
- [Why is Claude an Electron App?](https://www.dbreunig.com/2026/02/21/why-is-claude-an-electron-app.html) - If code is free, why aren’t all apps native?
- [uBlockOrigin-HUGE-AI-Blocklist](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist) - A huge blocklist of manually curated sites that contain AI generated imagery for uBlock Origin & uBlacklist.
- [I verified my LinkedIn identity. Here's what I handed over](https://thelocalstack.eu/posts/linkedin-identity-verification-privacy/)

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

- [What I read in 2026](https://luke-snaw.github.io/notes/ataxcwed7jsdij9iwqz5m9e/)
  - [2025](https://luke-snaw.github.io/notes/3c3ubyy4jyo2x0qui65nwtu/)
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
