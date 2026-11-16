&#x20;\<div align="center">

\<!-- Compact Cowboy Bebop Hero -->

\<img src="[https://media.giphy.com/media/4ilFRqgbzbx4c/giphy.gif](https://media.giphy.com/media/4ilFRqgbzbx4c/giphy.gif)" alt="Spike Spiegel" width="260" style="border-radius: 6px; border: 1px solid #302824;" />

\<br/>\<br/>

\<!-- Terminal Typing Banner -->

\<a href="[https://github.com/PlayzAe](https://github.com/PlayzAe)">
&#x20; \<img src="[https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=F0532C&center=true&vCenter=true&width=520&lines=I+just+crack%2C+break+and+build+shi+yh.;Just+a+dude+who+loves+to+larp.;Cannot+even+solve+two-sum+lmao.;Whatever+happens%2C+happens](https://readme-typing-svg.demolab.com?font=Fira+Code\&size=18\&duration=3000\&pause=1000\&color=F0532C\&center=true\&vCenter=true\&width=520\&lines=I+just+crack%2C+break+and+build+shi+yh.;Just+a+dude+who+loves+to+larp.;Cannot+even+solve+two-sum+lmao.;Whatever+happens%2C+happens)." alt="Typing SVG" />
\</a>

\<br/>

\<p align="center">
&#x20; \<code>systems\</code> • \<code>reverse engineering\</code> • \<code>web workers\</code> • \<code>android internals\</code> • \<code>media engines\</code> • \<code>desktop software\</code>
\</p>

---

\</div>

### Who am I?

Honestly, just a dude who larps thinking he knows how to code when I cannot even write a fucking boilerplate lmao.

I'm George Moses Azuoru, also known as [@PlayzAe](https://github.com/PlayzAe). 21 in 2026. Full-time software enthusiast, part-time existential crisis enjoyer.

I think I can code, but I cannot even fucking solve Two Sum on LeetCode. Can't even larp on there because pasting AI answers is just cheating yourself out of actually learning.

I'm not going to pretend I write every single line from scratch or that AI doesn't help me a fuck ton. You think I build all this shit from the get-go?

*"Ohh you use AI to code? Eww."*

Man, at least I'm self-aware and honest about it, unlike people pretending they're Terry Davis after prompting an AI to build an entire SaaS.

I'm still learning every single day. I just hope the projects I put out actually help somebody. AI is here to stay. Adapt or stay mad.

Also, my LinkedIn account got banned due to inactivity and honestly, good fucking riddance. That platform is a corporate larping slop-fest. Literal *"I just ran over 50 kids with my Honda Civic, here's what it taught me about B2B sales and growing your business"* type bullshit.

When I'm not having an existential crisis over syntax, I co-run [Emberfig](https://emberfig.com/) with Adeboye Oluwatimileyin.

We build privacy-first consumer software out of pure spite whenever mainstream software breaks basic functionality or locks it behind a $20 monthly paywall.

Reach us at [hello@emberfig.com](mailto\:hello@emberfig.com).

```c
typedef struct {
    const char *handle;       /* "PlayzAe" / "playzae" */
    int age;                  /* 21 in 2026 */
    const char *status;       /* "D1 larper full-time" */
    const char *leetcode;     /* "failed two-sum" */
    const char *linkedin;     /* "banned for inactivity (blessing)" */
    const char *ai_copilot;   /* "carrying my entire career" */
    const char *motto;        /* "Whatever happens, happens." */
} Dude;
```

---

### Shipped Apps & Projects

Somehow between the larping, terminal staring and questioning my existence, actual software got built.

These are projects I've shipped, maintain or actively work on.

#### 01. [Arena Desktop](https://github.com/PlayzAe/arena.ai-desktop) — The unofficial desktop client for arena.ai

**Windows · Python · Flask · WebView2 · JavaScript · SSE · MCP**

\<a href="[https://github.com/PlayzAe/arena.ai-desktop](https://github.com/PlayzAe/arena.ai-desktop)">   \<img src="[https://img.shields.io/github/stars/PlayzAe/arena.ai-desktop?style=flat-square&color=f0532c&label=stars](https://img.shields.io/github/stars/PlayzAe/arena.ai-desktop?style=flat-square\&color=f0532c\&label=stars)" />   \<img src="[https://img.shields.io/github/forks/PlayzAe/arena.ai-desktop?style=flat-square&color=f0532c&label=forks](https://img.shields.io/github/forks/PlayzAe/arena.ai-desktop?style=flat-square\&color=f0532c\&label=forks)" />   \<img src="[https://img.shields.io/github/license/PlayzAe/arena.ai-desktop?style=flat-square](https://img.shields.io/github/license/PlayzAe/arena.ai-desktop?style=flat-square)" /> \</a>

Ever wondered why some AI platforms insist on keeping everything inside a browser tab?

I did too.

Arena.ai is a pretty interesting platform, but I wanted something more than another website sitting between 37 other Chrome tabs. I wanted an actual desktop environment, proper workspace integration, local tools and an agent that could interact with files on my machine.

So I built it.

**A browser tab is a product decision, not a law of fucking physics.**

Arena Desktop is an unofficial, community-built Windows client that puts arena.ai inside its own Edge WebView2 window and adds functionality around it.

What started as wanting a dedicated desktop experience turned into a much bigger project.

**What it does:**

- Chat with 100+ AI models through Arena.
- Battle, Side-by-Side, Direct and Agent modes.
- Real agent workflows with Claude Code-style tool rows.
- Let AI read, search, edit and create files inside a local workspace.
- Run local commands with explicit permission and approval controls.
- Connect local MCP servers and tools.
- Switch between multiple Arena accounts.
- Stream agent responses and tool execution through Server-Sent Events.
- Keep local workspace files synchronized with the agent's work.

**Under the hood:**

- Edge WebView2 / pywebview desktop shell.
- Local Python and Flask backend.
- SSE-based response and tool streaming.
- Local workspace management and permission controls.
- MCP server integration.
- Native desktop integration.

And here's the part I actually care about:

I don't know what Arena's internal roadmap looks like or why an official desktop client isn't their priority. Maybe there's a business reason. Maybe it's simply not something they want to spend engineering resources on.

But the technical argument that a proper desktop experience is somehow impossible? Nah.

A dedicated desktop client is entirely achievable, so I built the experience I wanted instead of waiting around for somebody else to do it.

**Consider this my open-source middle finger to the idea that users should settle for a browser tab when a proper desktop application is perfectly possible.**

Not affiliated with or endorsed by Arena AI Inc. Uses your own Arena account. Human verification remains manual.

[View Source Code](https://github.com/PlayzAe/arena.ai-desktop) · [Download for Windows](https://github.com/PlayzAe/arena.ai-desktop/releases)

---

#### 02. [Quilore](https://quilore.com/) — Spotify listening history, without the bullshit

**Web · React · TypeScript · Web Workers**

Your entire Spotify listening history, processed directly in your browser from your own GDPR data export.

Spotify's API doesn't give you the complete listening history or reliable track durations. So I went through the raw export and built a parser that reconstructs listening sessions using timestamp deltas.

- 160,000+ plays processed.
- Parsing and indexing in under 4 seconds.
- Web Workers for intensive processing.
- No server uploads.
- No account or login.
- No subscriptions or paywalls.
- 100/100 Lighthouse Performance score.

Your listening history stays yours. No unnecessary backend collecting your shit.

[Open Quilore](https://quilore.com/) · [Longplay Source Code](https://github.com/PlayzAe/Longplay)

---

#### 03. [StudyPomo](https://play.google.com/store/apps/details?id=com.everythingabuad.studypomo) — A Pomodoro timer that actually keeps counting

**Android · Kotlin · Foreground Services · WakeLocks**

A Pomodoro timer built around one particularly annoying problem: Android aggressively killing background applications.

Built persistent foreground services and wake locks to keep sessions alive even when the display turns off.

- Designed for aggressive OEM task killers.
- Tested on TECNO KI7 and KM7.
- Android 7.0+.
- Offline statistics.
- No account required.
- Six ambient sounds.

Built after reading roughly 2,000 reviews of other timer apps and finding out how many people were dealing with the same problem.

[Get it on Google Play](https://play.google.com/store/apps/details?id=com.everythingabuad.studypomo)

---

#### 04. [PlayzAnime](https://playzae.github.io/playz_anime_landingpage/) — Anime and manga without unnecessary restrictions

**Windows · Android · Web · Electron · React · Flutter · Dart**

An ad-free anime and manga streaming platform with a custom media experience.

- Custom HLS video player.
- Adaptive pre-buffering.
- Automatic intro/outro skipping.
- Touch-friendly playback controls.
- Direct-chunk downloading without depending on torrent seeders.
- Offline CBZ chapter downloads.
- Windows desktop application built with Electron and React.
- Android client built with Flutter and Dart.

[Landing Page](https://playzae.github.io/playz_anime_landingpage/) · [Desktop Source Code](https://github.com/PlayzAe/playz_anime_desktopapp) · [Web Client](https://playz-anime.onrender.com)

---

#### 05. [Ponderanda](https://ponderanda.com/) — Five problems. One attempt. Every day.

**Web · Android**

A daily arithmetic progression ladder.

Five problems, one attempt, the same experience for everyone.

Built against brain-training applications that restrict basic functionality behind premium subscriptions.

- Daily arithmetic challenges.
- Past days remain accessible.
- No account required.
- Zero advertisements.
- No subscription tiers.
- Available on Android and the web.

[Open Ponderanda](https://ponderanda.com/)

---

#### 06. [Herewise](https://emberfig.com/apps/) — Offline lecture attendance

**Windows · Python · Desktop Software**

A lecture attendance application that reads fingerprint records from ZKTeco terminals and keeps the register on the lecturer's computer.

No cloud dependency. No internet requirement. No unnecessary accounts.

Built because losing attendance records shouldn't be an acceptable feature of an attendance management system.

---

#### 07. [Zykof](https://zykof.best/) — My own little corner of the internet

**Full-stack · Next.js · C++ · Payments · License Management**

A full-stack platform I operate independently.

Includes:

- Digital storefront and product management.
- Card and regional payment integrations.
- Cryptocurrency checkout.
- Automated license-key delivery after confirmed payments.
- Customer dashboards and HWID resets.
- Reseller management and credit systems.
- Administrative controls and support tooling.
- A C++ client developed alongside my reverse-engineering hobby.

[Visit Zykof](https://zykof.best/)

---

### Architectural Teardowns

I occasionally write about the engineering decisions and problems behind the things I build.

Not another recycled tutorial explaining what a variable is.

Actual breakdowns of things I've investigated, built or broken.

- [Spotify Timestamp Gap Analysis](https://emberfig.com/teardowns/)
- Android background services and OEM task killers.
- Desktop application architecture.
- Local-first software and privacy.

[Explore Emberfig Teardowns](https://emberfig.com/teardowns/)

---

### Tech Stack & Mini-Hobbies

**01. Low-Level & Reverse Engineering**

C/C++, x64 assembly, x64dbg, IDA, binary analysis, protocol investigation and generally poking around things I probably shouldn't be poking around.

**02. Frontend & Web Engines**

React 19, TypeScript, Next.js, Vite, Tailwind CSS, Web Workers, JavaScript, custom HLS streaming pipelines.

**03. Backend & Infrastructure**

C#, ASP.NET Core, EF Core, Node.js, PostgreSQL, SQL Server, Docker, REST APIs.

**04. Desktop Development**

Python, Flask, pywebview, Edge WebView2, Electron, local process execution, SSE streaming and desktop integrations.

**05. Android Internals**

Kotlin, Flutter, Dart, Android SDK, Foreground Services, WakeLocks, background execution and OEM power management.

---

\<div align="center">

\<a href="[https://github.com/PlayzAe](https://github.com/PlayzAe)">
&#x20; \<img src="[https://github-readme-streak-stats.herokuapp.com/?user=playzae&theme=tokyonight&hide_border=true&card_width=450](https://github-readme-streak-stats.herokuapp.com/?user=playzae\&theme=tokyonight\&hide_border=true\&card_width=450)" alt="GitHub Streak" />
\</a>

\<br/>\<br/>

\<p align="center">
&#x20; \<a href="[https://playzae.github.io/main-portfolio/](https://playzae.github.io/main-portfolio/)">Portfolio\</a> •
&#x20; \<a href="[https://emberfig.com/](https://emberfig.com/)">Emberfig\</a> •
&#x20; \<a href="[https://emberfig.com/teardowns/](https://emberfig.com/teardowns/)">Teardowns\</a> •
&#x20; \<a href="mailto\:hello\@emberfig.com">Contact\</a> •
&#x20; \<a href="[https://github.com/PlayzAe](https://github.com/PlayzAe)">GitHub\</a>
\</p>

\<br/>

\<code>WHATEVER HAPPENS, HAPPENS.\</code>

\</div>
