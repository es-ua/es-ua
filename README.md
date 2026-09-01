# Hey there 👋 I'm Esso

**CTO & Solution Architect** building AI-powered products, SaaS platforms, and Web3 infrastructure.

Based in Hamburg, Germany 🇩🇪 — working with European startups and scale-ups to turn complex ideas into scalable products.

---

### 🚀 What I'm Building

#### 🔴 [XENPAD](https://xenpads.com) — buttons you press, and that press back

Desk hardware that works in **both directions**. Pressing runs something on your
computer; an event from the internet — a failed build, a page going down,
someone mentioning you — lights the device up. Two of them exist:

**XENPAD One** — a single mechanical switch with a full-colour indicator, on an
RP2040. Three gestures, each mapped independently, and a resting colour that
tells you the state of whatever it is watching.

**XENPAD Omni** — a round touchscreen on an ESP32-S3 with a rotary encoder and
an RGB ring. Tiles, layers, and alerts that take over the whole glass with the
actual message rather than a coloured dot. Press it and it opens the exact thing
that raised the alert.

The whole desk side is mine: firmware for both chips, a signed and notarized
macOS app, and the relay that carries events from the internet to a device
sitting behind someone's router.

**The firmware for both is open source:**

- [`xenpad-firmware`](https://github.com/xenpads/xenpad-firmware) — XENPAD One,
  RP2040, GPLv3
- [`xenpad-omni-firmware`](https://github.com/xenpads/xenpad-omni-firmware) —
  XENPAD Omni, ESP32-S3, GPLv3
- [`xenpad-app-releases`](https://github.com/xenpads/xenpad-app-releases) —
  the desktop app, macOS, universal build

The USB protocol is MIT in both, so anything can talk to the devices without
inheriting copyleft. That split is deliberate: the shortcuts live in the
device's own flash, so a button keeps working on a machine that has never seen
my software — and if I stop, someone else can build the firmware and write a
replacement app.

`C` · `C++` · `RP2040` · `ESP32-S3` · `TinyUSB` · `LVGL` · `Electron` · `NestJS`

---

<table>
  <tr>
    <td width="50%">
      <h3>🔗 <a href="https://y0.exchange">y0.exchange</a></h3>
      <p>Non-custodial crypto platform & MCP server — the AI interface layer for blockchain. Connect any wallet to AI agents without exposing private keys.</p>
      <p><a href="https://www.npmjs.com/package/@y0exchange/mcp"><code>@y0exchange/mcp</code></a> — 8 tools, 5 chains, dual transport (stdio + HTTP). Includes a <a href="https://github.com/y0exchange/mcp/tree/main/skill">Claude Skill</a> for guided DeFi workflows with smart slippage, gas optimization, and safety checks.</p>
      <p><code>TypeScript</code> <code>Web3</code> <code>MCP</code> <code>Claude Skill</code> <code>React</code></p>
    </td>
    <td width="50%">
      <h3>📊 <a href="https://citenso.com">Citenso</a></h3>
      <p>AI Visibility Tracking — monitor how ChatGPT, Claude, Perplexity and other AI models recommend your brand vs competitors.</p>
      <p><code>Next.js</code> <code>Python</code> <code>AI/LLM</code> <code>SaaS</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🗺️ Mapko</h3>
      <p>Location-based social platform with omnichannel CRM — map discovery, community chats, business listings with integrated customer management.</p>
      <p><code>Next.js</code> <code>PostgreSQL</code> <code>WebSocket</code> <code>React Native</code></p>
    </td>
    <td width="50%">
      <h3>✈️ Skydex</h3>
      <p>Pokédex for planes — spot aircraft in the sky, scan & collect them all. 20-rank progression system, rarity classifications, leaderboards, and 300+ aircraft models.</p>
      <p><code>React Native</code> <code>Swift</code> <code>Firebase</code> <code>Gamification</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔍 SERPOscan</h3>
      <p>AI-powered SEO audit tool — comprehensive technical analysis, performance scoring, and actionable recommendations.</p>
      <p><code>Node.js</code> <code>Lighthouse</code> <code>SEO</code></p>
    </td>
    <td width="50%"></td>
  </tr>
</table>

---

### 🤖 Side Quest: Flathead Robot

Building a **Cyberpunk 2077-inspired robot** from scratch — 3D printed chassis, stereo vision, ESP32 + Raspberry Pi 5, autonomous navigation with ROS 2, LED eye animations, and AI-powered human interaction.

Printing on **Bambu Lab A1 Mini** 🖨️ | Materials: PETG-CF, TPU

---

### 🛠️ Tech Stack

**Languages & Frameworks**
```
TypeScript · JavaScript · Python · Swift · SwiftUI · Rust
React · Next.js · Vue.js · React Native · Node.js · Express
```

**Cloud & DevOps**
```
AWS · Google Cloud · Docker · Jenkins · GitHub Actions · Vercel
```

**Data & Backend**
```
PostgreSQL · MongoDB · Redis · Supabase · Firebase · Strapi CMS · Prisma
```

**Blockchain & Web3**
```
Ethers.js · Wagmi · Reown · 1inch · 0x Protocol · LI.FI · MCP
```

**Automation & AI**
```
n8n · LangChain · OpenAI API · Anthropic API · Claude MCP
```

---

### 📜 Certifications

- Salesforce Certified Platform Developer I
- Salesforce Certified Administrator

---

### 📫 Let's Connect

<p>
  <a href="https://esso.dev"><img src="https://img.shields.io/badge/Blog-esso.dev-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" /></a>
  <a href="https://x.com/esso_dev"><img src="https://img.shields.io/badge/X-@esso__dev-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="https://y0.exchange"><img src="https://img.shields.io/badge/y0.exchange-Crypto_Platform-6366F1?style=for-the-badge" /></a>
  <a href="https://www.reddit.com/r/esso_dev/"><img src="https://img.shields.io/badge/Reddit-r/esso__dev-FF4500?style=for-the-badge&logo=reddit&logoColor=white" /></a>
</p>

---

<p align="center">
  <img src="https://img.shields.io/github/stars/es-ua?style=for-the-badge&color=f5a623&label=Total%20Stars" />
  <img src="https://img.shields.io/badge/Repos-106-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Contributions-1.5k+-6366F1?style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/es-ua?style=for-the-badge&color=58a6ff&label=Followers" />
</p>

---

<p align="center"><i>💡 Ask me about CRM, iOS, project management, AI integrations, or non-custodial crypto infrastructure</i></p>
