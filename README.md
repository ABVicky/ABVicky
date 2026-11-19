<a name="abv-top"></a>

<p align="center">
  <a href="https://abvicky.in"><img src="assets/hero.svg" width="100%" alt="abvicky.in — Vicky Prasad Mahato. System Architect, Product Engineer and Founder, M.Tech from IIT Patna. I turn real problems into shipped products: software, hardware and everything in between. Based in Kolkata, India."></a>
</p>

<p align="center">
  <a href="#abv-work"><img src="assets/nav-work.svg" width="19%" alt="01 Work"></a>
  <a href="#abv-stack"><img src="assets/nav-stack.svg" width="19%" alt="02 Stack"></a>
  <a href="#abv-arcade"><img src="assets/nav-arcade.svg" width="19%" alt="03 Arcade"></a>
  <a href="#abv-contact"><img src="assets/nav-contact.svg" width="19%" alt="04 Contact"></a>
  <a href="https://abvicky.in"><img src="assets/nav-site.svg" width="19%" alt="Visit abvicky.in"></a>
</p>

<p align="center">
  <img src="assets/about.svg" width="100%" alt="About: Engineer by degree, founder by habit, mentor by choice. Highest qualification: M.Tech from IIT Patna. B.Tech in Information Technology and Software Engineering, class of 2025. I build all kinds of software products end to end, including the hardware they talk to. Founder of Mera Paisaa, Tech Mentor at Digispire Academy, founded Coders' Club BBIT in 2022. Principles: problem first, hardware plus software, clean architecture, reliability, ship and iterate.">
</p>

<p align="center">
  <img src="assets/about-process.svg" width="100%" alt="How I build: 01 find the real problem, 02 design the hardware and software system, 03 build it end to end across web, mobile, backend and devices, 04 ship and keep improving.">
</p>

<p align="center">
  <a name="abv-work"></a><a href="#abv-top"><img src="assets/section-work.svg" width="100%" alt="01 — Selected work"></a>
</p>

<p align="center">
  <a href="https://merapaisaa.abvicky.in"><img src="assets/work-merapaisaa.svg" width="100%" alt="Flagship: Mera Paisaa — an offline-first, privacy-focused personal expense tracker for Indian users. TypeScript, React.js, Tailwind CSS, PWA, Vercel. Opens the live app."></a>
</p>

<p align="center">
  <a href="https://github.com/ABVicky/JewelPOS"><img src="assets/work-jewelpos.svg" width="49%" alt="JewelPOS — cross-platform point of sale and inventory system for jewelry retail. Dart, Flutter. Opens the repository."></a>
  <a href="https://github.com/ABVicky/Digispire-Academy"><img src="assets/work-digispire.svg" width="49%" alt="Digispire Academy — EdTech learning and mentorship portal. JavaScript, React.js, Vercel. Opens the repository."></a>
</p>

<p align="center">
  <a href="https://github.com/ABVicky/VeriCRM"><img src="assets/work-vericrm.svg" width="49%" alt="VeriCRM — CRM for sales pipelines and lead automation. Opens the repository."></a>
  <a href="https://github.com/ABVicky/hrms"><img src="assets/work-hrms.svg" width="49%" alt="HRMS — onboarding, attendance and performance analytics portal. Opens the repository."></a>
  <a href="https://priyadarshi-ias-academy.vercel.app"><img src="assets/work-ias.svg" width="49%" alt="Priyadarshi IAS Academy — portal for IAS coaching and competitive-exam resources. Opens the live site."></a>
  <a href="https://github.com/ABVicky/monorepo-turborepo"><img src="assets/work-turborepo.svg" width="49%" alt="Monorepo Turborepo — scalable monorepo template for full-stack apps. Opens the repository."></a>
</p>

<p align="center">
  <a href="https://abvicky.in"><img src="assets/work-coders-club.svg" width="100%" alt="Coders' Club BBIT — student developer community founded in 2022: open source, competitive programming, hackathons and mentorship in Kolkata."></a>
</p>

<p align="center">
  <sub><b>SOURCE CODE →</b>
  <a href="https://github.com/ABVicky/merapaisaa">merapaisaa</a> ·
  <a href="https://github.com/ABVicky/Priyadarshi-IAS-Academy">Priyadarshi-IAS-Academy</a> ·
  <a href="https://github.com/ABVicky?tab=repositories">all repositories ↗</a></sub>
</p>

<p align="center">
  <a name="abv-stack"></a><a href="#abv-top"><img src="assets/section-stack.svg" width="100%" alt="02 — The stack"></a>
</p>

<p align="center">
  <img src="assets/stack.svg" width="100%" alt="The stack, printed as a receipt. Core languages: TypeScript, JavaScript (ES6+), Dart, Python, Java, HTML5, CSS3. Frontend: React.js, Next.js, Flutter, Tailwind CSS, Vite, Framer Motion. Backend and storage: Node.js, Express.js, REST APIs, PostgreSQL, MongoDB, Firebase. DevOps and tooling: Git, GitHub, Turborepo, Vercel, Docker, Linux, WordPress. Media and UI design: Figma, Adobe Premiere Pro, Canva, GIMP, Adobe Creative Cloud.">
</p>

<p align="center">
  <a name="abv-arcade"></a><a href="#abv-top"><img src="assets/section-arcade.svg" width="100%" alt="03 — Arcade"></a>
</p>

<p align="center">
  <img src="assets/arcade-bughunt.svg" width="100%" alt="Bug hunt: four tiny JavaScript gotchas. Guess what each one prints, then reveal the answers below the cards.">
</p>

<p align="center">
  <img src="assets/arcade-bug-1.svg" width="49%" alt="Level 1: console.log(typeof null); — what does this print?">
  <img src="assets/arcade-bug-2.svg" width="49%" alt="Level 2: console.log(0.1 + 0.2 === 0.3); — what does this print?">
</p>

<details>
<summary><a name="abv-reveal-1"><img src="assets/toggle-reveal-1.svg" height="52" align="absmiddle" alt="Reveal level 01 — typeof null"></a></summary>
<br>

**It prints `object`.** One of JavaScript's oldest quirks: a bug from the language's very first version that can't be fixed without breaking the web. Check for `null` directly instead:

```js
if (value === null) { /* handle it */ }
```

</details>

<details>
<summary><a name="abv-reveal-2"><img src="assets/toggle-reveal-2.svg" height="52" align="absmiddle" alt="Reveal level 02 — 0.1 + 0.2 === 0.3"></a></summary>
<br>

**It prints `false`.** JavaScript numbers are binary floating point, so `0.1 + 0.2` is really `0.30000000000000004`. Money apps should store amounts as whole paise (₹1 = 100 paise) and only format them for display:

```js
const total = 10 + 20;                          // paise
console.log(total === 30);                      // true
console.log(`₹${(total / 100).toFixed(2)}`);    // ₹0.30
```

</details>

<p align="center">
  <img src="assets/arcade-bug-3.svg" width="49%" alt="Level 3: const scores = [10, 1, 2]; console.log(scores.sort()); — what does this print?">
  <img src="assets/arcade-bug-4.svg" width="49%" alt="Level 4: for (var i = 0; i < 3; i++) { setTimeout(() => console.log(i)); } — what does this print?">
</p>

<details>
<summary><a name="abv-reveal-3"><img src="assets/toggle-reveal-3.svg" height="52" align="absmiddle" alt="Reveal level 03 — [10, 1, 2].sort()"></a></summary>
<br>

**It prints `[1, 10, 2]`.** Without a compare function, `sort()` turns every item into a string and compares them as text, so `"10"` lands before `"2"`. It also sorts the array in place. Pass a comparator, or use [`toSorted()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/toSorted) to get a new array:

```js
scores.sort((a, b) => a - b);        // [1, 2, 10]
const ranked = scores.toSorted((a, b) => b - a); // [10, 2, 1], original untouched
```

</details>

<details>
<summary><a name="abv-reveal-4"><img src="assets/toggle-reveal-4.svg" height="52" align="absmiddle" alt="Reveal level 04 — var inside a loop"></a></summary>
<br>

**It prints `3`, `3`, `3`.** `var` is function-scoped, so all three callbacks share a single `i`, and they only run after the loop has finished, when `i` is already `3`. `let` creates a fresh `i` for every iteration:

```js
for (let i = 0; i < 3; i++) {
  setTimeout(() => console.log(i));   // 0, 1, 2
}
```

</details>

<p align="center">
  <sub>Got 4/4 without peeking? <a href="https://linkedin.com/in/abvicky">Tell me on LinkedIn ↗</a></sub>
</p>

<p align="center">
  <img src="assets/arcade-quests.svg" width="100%" alt="Side quests: five free, beginner-friendly roadmaps for new developers: start coding, web, mobile, hardware and open source. Pick a quest below and tap it open.">
</p>

<details>
<summary><a name="abv-quest-1"><img src="assets/toggle-quest-1.svg" height="52" align="absmiddle" alt="Quest 01 — I'm just starting to code"></a></summary>
<br>

1. **How the web works, HTML & CSS** → [MDN: Learn web development](https://developer.mozilla.org/en-US/docs/Learn_web_development)
2. **JavaScript fundamentals** → [javascript.info](https://javascript.info/) (Part 1 is plenty to start)
3. **Git & GitHub basics** → [GitHub Skills](https://skills.github.com/)
4. **Practice with structure** → [The Odin Project: Foundations](https://www.theodinproject.com/paths/foundations/courses/foundations) or [freeCodeCamp](https://www.freecodecamp.org/learn)
5. **Learn to think like a programmer** → [Harvard CS50x](https://cs50.harvard.edu/x/) (free)

🏁 **Boss level:** build a one-page portfolio and put it online with [GitHub Pages](https://pages.github.com/).

</details>

<details>
<summary><a name="abv-quest-2"><img src="assets/toggle-quest-2.svg" height="52" align="absmiddle" alt="Quest 02 — I want to build web apps"></a></summary>
<br>

1. **TypeScript** → [The TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
2. **React** → [react.dev/learn](https://react.dev/learn)
3. **Next.js** → [Next.js Learn](https://nextjs.org/learn)
4. **APIs & databases** → [Node.js Learn](https://nodejs.org/learn) + the [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html)
5. **See the whole map** → [roadmap.sh: Full Stack](https://roadmap.sh/full-stack)

🏁 **Boss level:** solve a real problem for someone you know. Build it, ship it, watch them use it. Bonus: make it installable with [web.dev: Learn PWA](https://web.dev/learn/pwa).

</details>

<details>
<summary><a name="abv-quest-3"><img src="assets/toggle-quest-3.svg" height="52" align="absmiddle" alt="Quest 03 — I want to build mobile apps"></a></summary>
<br>

1. **Dart** → [The Dart language tour](https://dart.dev/language)
2. **Flutter** → [Install Flutter and build your first app](https://docs.flutter.dev/install)
3. **Save data on the device** → [Flutter cookbook: Persistence](https://docs.flutter.dev/cookbook/persistence)
4. **Ship it** → [Build and release an Android app](https://docs.flutter.dev/deployment/android)

🏁 **Boss level:** a stock & billing app for a local shop, the idea behind [JewelPOS](https://github.com/ABVicky/JewelPOS).

</details>

<details>
<summary><a name="abv-quest-4"><img src="assets/toggle-quest-4.svg" height="52" align="absmiddle" alt="Quest 04 — I want to make hardware talk to software"></a></summary>
<br>

1. **Electronics basics** → [Arduino: Getting started](https://docs.arduino.cc/learn/starting-guide/getting-started-arduino/)
2. **No board yet? Simulate one** → [Wokwi](https://wokwi.com/) (free, in the browser)
3. **Single-board computers** → [Raspberry Pi projects](https://projects.raspberrypi.org/en)
4. **Talk to a device from a web app** → [Web Serial API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Serial_API)
5. **Connect many devices** → [MQTT: Getting started](https://mqtt.org/getting-started/)

🏁 **Boss level:** read a sensor on a microcontroller and stream it live to a web dashboard.

</details>

<details>
<summary><a name="abv-quest-5"><img src="assets/toggle-quest-5.svg" height="52" align="absmiddle" alt="Quest 05 — I want my first open-source PR"></a></summary>
<br>

1. **Rehearse the flow** → [first-contributions](https://github.com/firstcontributions/first-contributions)
2. **Learn Git properly** → [Pro Git](https://git-scm.com/book/en/v2) (free book)
3. **Find a beginner-friendly issue** → [goodfirstissue.dev](https://goodfirstissue.dev/) or GitHub's [good first issue search](https://github.com/search?q=label%3A%22good+first+issue%22+state%3Aopen&type=issues)
4. **Contribute like a pro** → read `CONTRIBUTING.md`, comment before you code, keep PRs small ([Open Source Guide](https://opensource.guide/how-to-contribute/))

🏁 **Boss level:** get one PR merged, then help the next person land theirs.

</details>

<p align="center">
  <sub>Stuck on a quest? I mentor student developers. <a href="https://linkedin.com/in/abvicky">Message me on LinkedIn ↗</a></sub>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ABVicky&bg_color=F4EFE6&color=141414&title_color=141414&line=FF5B1F&point=141414&area=true&area_color=FFD43B&hide_border=true&radius=16&custom_title=Commit%20pulse" width="100%" alt="Vicky's GitHub contribution activity graph">
</p>

<p align="center">
  <a name="abv-contact"></a><a href="mailto:abvicky01@gmail.com"><img src="assets/contact.svg" width="100%" alt="Bring me a problem. Let's ship the answer. Open for product builds, hardware and software integrations, technical consulting, architecture roles and engineering collaborations. Email abvicky01@gmail.com"></a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/abvicky"><img src="assets/btn-linkedin.svg" width="24%" alt="LinkedIn — in/abvicky"></a>
  <a href="https://github.com/ABVicky"><img src="assets/btn-github.svg" width="24%" alt="GitHub — @ABVicky"></a>
  <a href="https://quora.com/profile/AB-Vicky-Prasad-Mahato"><img src="assets/btn-quora.svg" width="24%" alt="Quora — AB-Vicky-Prasad-Mahato"></a>
  <a href="https://abvicky.in"><img src="assets/btn-website.svg" width="24%" alt="Website — abvicky.in"></a>
</p>

<p align="center">
  <a href="#abv-top"><img src="assets/footer.svg" width="100%" alt="© 2026 Vicky Prasad Mahato — abvicky.in. Back to top."></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ABVicky&color=FF5B1F&style=flat-square&label=VISITORS" alt="Profile views">
</p>
