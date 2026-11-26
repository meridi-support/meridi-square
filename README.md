![MeridiSync](MeridiSync.jpg)

# MeridiSync

A lightweight, high-speed snippet management tool designed to streamline your daily typing tasks.

- **Community-Driven:** Now at v1.0.3, this project thrives on collective wisdom. Bring your ideas, feedback, and "mad scientist" tweaks to help evolve this tool together!

## 🆕 What's New — v1.0.3 (2026-11-26)

New look for the `{step:}` wizard — a cyan progress bar and "1 / 4", matching the demo on [meridibrand.com/sync](https://meridibrand.com/sync/).
Also in v1.0.2 (same day): faster & more accurate expansion — no more leftover letters or stray "v", reliable pasting in slow apps (Excel, browsers), sharp text on scaled displays, and input pop-ups ready to type. Your existing snippets carry over as-is.
> 💡 Type triggers with English input — while a Japanese / Chinese / Korean IME is composing, MeridiSync waits so your text is never broken.

👉 [Full release notes](https://github.com/meridi-support/meridi-square/releases/tag/v1.0.3)

## 📥 Download & Store

| Store | Market | Price | Link |
|---|---|---|---|
| 🌍 **Gumroad** | International | $8 | [Buy on Gumroad](https://meridius4.gumroad.com/l/meridisync) |
| 🇯🇵 **BOOTH** | Japan | ¥1,000 | [Buy on BOOTH](https://meridistore.booth.pm/items/8790105) |
| 🆓 **GitHub** | Open Source | Free | [Download from Releases](https://github.com/meridi-support/meridi-square/releases) |
| ☕ **Support** | — | Any amount | [Buy Me a Coffee](https://buymeacoffee.com/meridius) |

> 💡 MeridiSync is open-source under MIT License — free to use, modify, and share. Purchasing on Gumroad or BOOTH directly supports the developer and future updates. Thank you! 🐟

## 🎮 Try Before You Buy

Experience MeridiSync in your browser — no download, no signup required.

🔗 **[Try it on meridibrand.com/sync](https://meridibrand.com/sync/)** · [Full demo](https://meridi-support.github.io/meridisync-demo/)

## 🚀 Overview

- **Concept:** Ad-free, 100% Offline, and Lightweight.
- **OS:** Windows Only (.exe)
- **Built with:** Python (tkinter / pynput)

## 📦 Built-in Templates — Ready to Use

MeridiSync comes with 4 practical templates pre-installed:

| Trigger | Output | Example |
|---|---|---|
| `.today` | Today's date | 2026-09-15 |
| `.now` | Current date & time | 2026-09-15 09:30 |
| `.week` | Day of the week | Tuesday |
| `.kyou` | Japanese date format | 2026年09月15日（火） |

> 💡 Type a trigger, and your text expands instantly — no delay, no internet, no hassle.

## 🧩 Variables (excerpt)

| Variable | Result |
|---|---|
| `{date}` `{datetime}` `{time}` `{weekday}` `{date_jp}` | Date & time |
| `{date+1}` `{date_jp-1}` | Add / subtract days |
| `{weekday+3}` `{weekday_jp+3}` | Business days (skips weekends) |
| `{time+2h}` `{time-30m}` `{datetime+1h}` | Add / subtract time |
| `{clipboard}` | Current clipboard text |
| `{input:Name}` | Ask for a value at expansion time |
| `{step:Subject}{step:Body}` | Multi-step wizard with Back / Next |
| `{if:weekday=Monday}...{else}...{endif}` | Conditional text (weekday / month / day / time) |

## 📊 Quick Specs

| Spec | Detail |
|---|---|
| Category | Offline Text Expander / Productivity Tool |
| Version | v1.0.3 (2026-11-26) |
| Price | $8 / ¥1,000 (one-time — no subscription, ever) |
| License | MIT (mod-friendly — customize freely) |
| Size | 29.9 MB (portable ZIP — no install needed) |
| OS | Windows 10 / 11 |
| Language | Bilingual (English / Japanese) |
| Internet | Not required (works 100% offline) |
| Ads/Tracking | None. Ever. |

## ✨ Key Features

- **GUI Editor** — No YAML, no config files. Visual editing, done.
- **{step:} Multi-step Wizard** — Back/Next guided text flows.
- **{input:} Dynamic Prompts** — Insert custom values at expansion time.
- **Date & Time Math / Conditional Text** — `{date+1}`, `{weekday+3}`, `{if:...}`.
- **Quick Launcher (Ctrl+Space)** — Search and insert any snippet.
- **Dark/Light Mode** — Easy on the eyes, day or night.
- **Excel Import/Export** — Manage snippets in bulk.
- **Usage Statistics** — See which snippets you use most.
- **Categories & Favorites (pin)** — Organize your snippets your way.
- **100% Offline** — No internet, no tracking, no ads. Data files are saved next to the exe.
- **Open to Modding (MIT)** — Make it yours.

## 🛠️ Tweak-Friendly & Contribution Welcome

MeridiSync is currently at v1.0.3. We are looking forward to evolving this tool together with your ideas and insights!

- **Call for Ideas:** If you have a lightweight Python approach, please feel free to share your ideas, solutions, or PRs on GitHub!

## ⚙️ 魔改造・アイデアの募集について

本作は現在 v1.0.3 です。皆様のアイデアや知恵で、このツールをさらに昇華させていただければ幸いです。

- **求む知見:** Python で軽量に作るベストプラクティスやスマートなコーディングアイデアをお持ちの方は、ぜひGitHubで知恵を貸してください（魔改造推奨です！）。

## 💬 Community & Discussions

Want to share your snippets, request features, or discuss the future of MeridiSync? Join us on [GitHub Discussions](https://github.com/meridi-support/meridi-square/discussions)

---

## 🌐 Visit Us

**[meridibrand.com](https://meridibrand.com/)** — Our official home since November 1st, 2026.

---

## 🌐 Meridi Family

| Tool | Description | Link | Live Demo |
|---|---|---|---|
| 💻 **MeridiSync** | High-speed snippet manager (Windows) | [Gumroad (&#36;8)](https://meridius4.gumroad.com/l/meridisync) / [BOOTH (¥1,000)](https://meridistore.booth.pm/items/8790105) | [Try Free](https://meridibrand.com/sync/) |
| 📅 **MeridiMeet** | Multi-Timezone Scheduler — No ads, No signup | Free | [meridibrand.com/meet](https://meridibrand.com/meet) |
| 🐾🪄 **MeridiLingo** | 900+ expressions & AI prompts — Language, Culture & AI Prompt Vocabulary | Free | [meridibrand.com/lingo](https://meridibrand.com/lingo) |
| 🌌 **MeridiStars** | Planetarium — 88 constellations, 119 locations | Free | [meridibrand.com/stars](https://meridibrand.com/stars) |
| ☁️ **MeridiSkies** | Sky & weather explorer — clouds, lightning, aurora, foehn & sky colors | Free | [meridibrand.com/skies](https://meridibrand.com/skies) |
| 🪨 **MeridiGround** | From the sky to Earth's core — rock layers, volcanoes, plate tectonics & 11 world stages | Free | [meridibrand.com/ground](https://meridibrand.com/ground) |
| 🌊 **MeridiDepths** | Dive to the deepest ocean — 230+ sea creatures, shipwrecks & records, 11 deep places | Free | [meridibrand.com/depths](https://meridibrand.com/depths) |
| 🎮 **MeridiPlay** | 18 browser games — casino, fortune-telling, retro candy-shop machines | Free | [meridibrand.com/play](https://meridibrand.com/play) |
| 🧮 **MeridiConvert** | Unit converter, graph paper, graphing calculator & handy calculators | Free | [meridibrand.com/convert](https://meridibrand.com/convert) |
| 🧰 **Meridi Tools** | Ad-free toolbox — bill splitter & tips, timer & scoreboard, text cleaner, TRPG dice, direct QR codes, photo location remover | Free | [meridibrand.com/tools](https://meridibrand.com/tools) |
| 🗺️ **MeridiAtlas** | GIS for the Rest of Us | In Development | — |
| 📔 **MeridiDiary** | Your Journey, Your Map | Planned | — |

## 🌐 Meridi ファミリー

| ツール | 説明 | リンク | ライブデモ |
|---|---|---|---|
| 💻 **MeridiSync** | 高速スニペット管理ツール (Windows) | [BOOTH (¥1,000)](https://meridistore.booth.pm/items/8790105) | [無料で体験](https://meridibrand.com/sync/) |
| 📅 **MeridiMeet** | 時差調整ツール — 広告なし・登録不要 | 無料 | [meridibrand.com/meet](https://meridibrand.com/meet) |
| 🐾🪄 **MeridiLingo** | 900以上の表現と AI プロンプト — 言語・文化・AIプロンプト語彙集 | 無料 | [meridibrand.com/lingo](https://meridibrand.com/lingo) |
| ☁️ **MeridiSkies** | 空と天気の図鑑 — 雲・雷・オーロラ・フェーン・空の色 | 無料 | [meridibrand.com/skies](https://meridibrand.com/skies) |
| 🌌 **MeridiStars** | ブラウザで動くプラネタリウム — 88星座・世界119か所 | 無料 | [meridibrand.com/stars](https://meridibrand.com/stars) |
| 🪨 **MeridiGround** | 空の上から地球の中心まで — 地層・火山・プレート、世界の 11 か所 | 無料 | [meridibrand.com/ground](https://meridibrand.com/ground) |
| 🌊 **MeridiDepths** | 海面から海溝の底まで潜る深海図鑑 — 生き物・沈没船・記録 230 件以上、世界の 11 か所 | 無料 | [meridibrand.com/depths](https://meridibrand.com/depths) |
| 🎮 **MeridiPlay** | 無料ブラウザゲーム18種 — カジノ・占い・駄菓子屋レトロ | 無料 | [meridibrand.com/play](https://meridibrand.com/play) |
| 🧮 **MeridiConvert** | 尺・坪・合も使える単位変換、方眼紙の作図、グラフ、現場の計算 | 無料 | [meridibrand.com/convert](https://meridibrand.com/convert) |
| 🧰 **Meridi Tools** | 広告なし・通信なしの道具箱 — 割り勘・チップ、タイマー、テキスト整形、ダイス、QR コード、写真の位置情報を消す | 無料 | [meridibrand.com/tools](https://meridibrand.com/tools) |
| 🗺️ **MeridiAtlas** | 地図インテリジェンスツール | 開発中 | — |
| 📔 **MeridiDiary** | あなたの旅、あなたの地図 | 計画中 | — |

---

📅 MeridiMeet → 🐾 MeridiLingo → 💻 MeridiSync → 🌌 MeridiStars → ☁️ MeridiSkies → 🪨 MeridiGround → 🌊 MeridiDepths → 🎮 MeridiPlay → 🧮 MeridiConvert → 🧰 Meridi Tools → 🗺️ MeridiAtlas → 📔 MeridiDiary

---

## 📧 Contact

For feedback, feature requests, or bug reports: [meridisupport@gmail.com](mailto:meridisupport@gmail.com)

---

## 🇯🇵 日本語について (Japanese)

MeridiSyncは、日常のタイピング作業を効率化するスニペット管理ツールです。

- **コンセプト:** 広告なし、完全オフライン、極めて軽量。
- **対応OS:** Windows専用（.exe 形式）
- **最新版:** v1.0.3（2026-11-26）— {step:} の入力窓に進み具合のバー（v1.0.2 で速く・正確に）
- **ご注意:** トリガーは英字入力（A）で打ってください。日本語入力中は展開しません
- **お問い合わせ:** [meridisupport@gmail.com](mailto:meridisupport@gmail.com)

---

*No Ads. No Subscriptions. Just Tools.* 🐾

**Meridi Brand © 2026 — Since November 1st, 2026**
