# Prompt: Build Ohad Gadassi's portfolio page

You are working in `F:\Programming\new stuff\portfolio` (already created; it contains only this file).
Build a basic personal portfolio page for me, Ohad Gadassi, and publish it on GitHub Pages.

This is a workshop exercise. **Keep the design deliberately basic.** Next lesson is about design and
the page will be fully restyled then, so clean structure matters more than looks.

All the research is already done and is below. Use only these facts. Do not invent jobs, dates,
numbers, features or claims. If you need more detail on a project, read that repo's README with
`gh` (I'm logged in as `ogadassi`, and private repos are readable too). Don't trust my GitHub
profile README for project descriptions, because parts of it are out of date. If something is
still unclear, leave it out.

---

## 1. Deliverables

```
portfolio/
├── index.html        semantic HTML5, English, one page
├── style.css         one small stylesheet, no framework
├── assets/
│   └── profile.<ext> my GitHub avatar (see below)
├── README.md         2-5 lines: what this is + live URL
└── PROMPT.md         this file (keep it, commit it)
```

- **No JavaScript, no build step, no CSS framework, no external fonts or icon libraries.**
- **Profile photo:** download `https://avatars.githubusercontent.com/u/141135190?s=460` into
  `assets/`, using the extension that matches the returned content type. Show it as a round image
  in the header with alt text "Ohad Gadassi".

## 2. Design rules (basic on purpose)

- A single centered column, about 800px max width, comfortable padding, and system font stack.
- 1 accent color and neutral greys, light background. Simple borders or light background
  boxes for project cards are fine, but no gradients, shadows-galore, animations or dark mode.
- Must look fine on a phone: the photo and text stack, nothing overflows.
- Use meaningful semantic tags (`header`, `nav`, `main`, `section`, `article`, `footer`) and
  readable class names, so the next lesson can restyle it easily.
- A simple top nav with in-page links to the sections.
- External links open in a new tab (`target="_blank" rel="noopener"`).

## 3. Content

### Header
- **Name:** Ohad Gadassi
- **Title:** Full-Stack Developer · Mobile & Web Applications · IT Support
- **Location:** Ramat Gan, Israel
- **Status line:** Open to work: Junior Full-Stack / Frontend / Backend, Junior Mobile (React
  Native), Support Engineer / Tier 3
- **Links:** Email `ogadassi@gmail.com` (mailto), GitHub `https://github.com/ogadassi`, LinkedIn
  `https://www.linkedin.com/in/ohad-gadassi/`. **Do not include a phone number anywhere.**

### About (short paragraph, base it on this)
Full-Stack developer with a strong background in IT infrastructure and system management. Builds
end-to-end web, mobile and desktop projects, and lately a lot of tools that automate his own daily
life: Android apps, browser extensions, desktop widgets and Discord bots. Graduated the John Bryce
Full-Stack course with honors. Proactive problem-solver who likes learning new technologies.

### Skills (simple grouped list, not progress bars)
- **Languages:** JavaScript, TypeScript, Python, Kotlin, Lua, HTML/CSS
- **Frontend & mobile:** React, React Native / Expo, Angular, Jetpack Compose (Android), Electron, Chrome extensions
- **Backend & data:** Node.js, NestJS, Flask, REST APIs, WebSockets (Socket.io), MySQL, MongoDB, Supabase, Appwrite
- **Tools:** Git, Docker, Vercel, GitHub

### Featured projects (8 cards, in this order)
Each card: name, one or two sentence description, stack tags, and links. For **private** repos,
show a small "Private repo" label and **no repo link**, only a live link if one is listed here.

1. **Steelman**: argument training app and website. Expo / React Native, TypeScript, Supabase.
   Live: https://playsteelman.vercel.app. *Private repo.* (Read the private repo's docs via `gh`
   if you need a better one-line description.)
2. **Sterrify**: tools for guitarists that follow what's playing on Spotify.
   - Desktop app (Electron, Node.js): Songsterr wrapper with Spotify sync, Discord status and
     automatic instrument/tuning switching. Repo: https://github.com/ogadassi/Sterrify
   - *Sterrify Tabs* (newer, private): a Spicetify custom app that renders the tab for the current
     song inside the Spotify client with alphaTab, synced to the playhead, with MIDI out to an amp sim.
3. **AC Notification**: proximity-based smart AC automation. An Android + Android Auto app (Kotlin)
   uses geofencing around home to offer a 1-tap "turn on AC" notification, backed by a Python Flask
   server on a Windows PC via ngrok. Repo: https://github.com/ogadassi/ac-notification
4. **YouTube Watch Later Manager**: a Chrome extension adding 1-click add/remove Watch Later buttons
   across YouTube, theme-aware and language-independent. JavaScript. Published on the Chrome Web Store:
   https://chromewebstore.google.com/detail/youtube-watch-later-manag/cipblemimaiffjenjhnplnegbembhgmc
   Repo: https://github.com/ogadassi/WatchLater
5. **Forest**: visual, canvas-based task management with drag-and-drop and real-time sync; mobile
   companion with time/location reminders in development. React 19, Vite, Tailwind, Node.js,
   Socket.io. Repo: https://github.com/ogadassi/Forest
6. **Grapevine**: gamified mobile social network with a real-time feed, custom reactions,
   multiplayer games and a virtual economy. React Native, Appwrite. Repo:
   https://github.com/ogadassi/Grapevine
7. **Friendmeter**: a real-time Windows desktop widget: a "Liquid Glass" Rainmeter skin (Lua) plus a
   Node.js/TypeScript bridge that tracks Discord friends' presence and WhatsApp notifications;
   clicking a notification jumps to the chat. *Private repo.*
8. **Android Bluetooth Control Widget**: a home-screen widget that connects/disconnects specific
   Bluetooth devices in one tap, without root, using Shizuku. Kotlin, Jetpack Compose. Shrunk the APK
   from 13.9 MB to 1.9 MB with R8. *Private repo.*

### Earlier & smaller work (plain list, one line each)
- **RLScoreBot**: Python Discord bot that watches Rocket League with computer vision and plays a
  sound in voice chat when a goal is scored. https://github.com/ogadassi/RLScoreBot
- **Mythical Vision**: a "vintage morning TV" YouTube player: channel-style, no scrolling or
  algorithms. https://github.com/ogadassi/gmm-player
- **JobScout**: TypeScript/NestJS tool that aggregates and scores junior developer job listings
  into Excel. *Private repo.*
- **Vacation Time**: John Bryce final project, a vacation-planning web app.
  https://github.com/ogadassi/Vacation-Time
- **TRIOT**: website for my band. https://github.com/ogadassi/triot-official-website
- **MineSweeper**: browser game. Live: https://ogadassi.github.io/MineSweeper/

### Experience (newest first)
- **IT Support Specialist**, Ramat Gan Municipality, 2025-present. Diagnosed and resolved hardware
  and OS issues in a large organization; managed user permissions and connectivity; supported core systems.
- **General Insurance Service Representative**, Phoenix, 2024-2025. Identified client needs and
  explained complex technical and insurance information under strict KPIs.
- **Electronics Logistics Stock Keeper**, Rad Data Communications, 2022-2023. Managed logistics
  with modern inventory systems in a fast-paced high-tech environment.

### Military service
- **Bureau Manager & Assistant to Head of Casualty Department**, 2019-2022. Managed executive
  schedules and discussion materials and trained bureau staff. Ran the command-and-control center
  during national emergencies, processing real-time casualty data. Recalled for reserve duty in
  2022 to manage the leadership transition for the Head of the Department.

### Education
- **John Bryce**: Full-Stack Development, 2023-2024 (graduated with honors)
- **Ort Ebin**: Full Matriculation Certificate, 2016-2019

### Languages
Hebrew (native), English (fluent)

### Beyond code (one or two short sentences, no more)
Musician who plays in a band (TRIOT) and builds tools for his own playing (Sterrify). Rocket
League player. Most side projects start as "this annoys me, let me automate it."

### Footer
"© 2026 Ohad Gadassi" plus the GitHub and LinkedIn links again.

## 4. Publish to GitHub

1. `git init` in this folder, default branch `main`, and commit everything (including PROMPT.md).
2. Create a **public** repo named exactly **`ogadassi.github.io`** (a GitHub user site, so it's served
   at https://ogadassi.github.io) and push:
   `gh repo create ogadassi.github.io --public --source . --push --description "Ohad Gadassi - personal portfolio"`
   (The older `Portfolio` repo from 2023 stays untouched. Don't modify or delete it.)
3. Make sure GitHub Pages is on for `main` / root. Check with `gh api repos/ogadassi/ogadassi.github.io/pages`;
   if it isn't enabled, enable it with
   `gh api -X POST repos/ogadassi/ogadassi.github.io/pages -f "source[branch]=main" -f "source[path]=/"`.
4. Wait for the first Pages build to finish and confirm https://ogadassi.github.io loads, with the
   photo showing.

## 5. Before you finish

- Open the page (local file or live URL) and check it at desktop and phone width.
- Check that every link points to the URL listed above, and that private projects have no repo link.
- Confirm no phone number appears in any committed file.
- Report the repo URL and the live URL.
