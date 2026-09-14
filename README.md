# 英國生活知識圖譜 · Life in the UK Knowledge Graph

An interactive bilingual (Traditional Chinese / English) knowledge graph for studying the Life in the UK citizenship test.

## Features

| Feature | Description |
|---------|-------------|
| 🕸️ Force graph | 139 nodes, 112 links across 7 types — drag, zoom, explore |
| 🔗 Relationships | 112 links — causal, chronological, institutional, created-by |
| 📋 Click panels | Click any node for facts table + linked nodes |
| 📝 Quiz mode | Every node has a built-in quiz question with reveal |
| 🕐 Timeline mode | Arrange nodes by historical era on horizontal axis |
| 🔍 Search | Filter nodes by English name in real time |
| 🏷️ Type filters | Toggle People / Events / Laws / Institutions / Concepts / Dates / Sport & Culture |
| 🇨🇳🇬🇧 Bilingual | Node labels and proper nouns always in English; facts and quiz switch to Traditional Chinese |

## Language Behaviour

| Element | Behaviour |
|---------|-----------|
| Node labels on graph | Always English (proper nouns stay English) |
| Panel title | Always English |
| Chinese subtitle | Shown below the English title in 中文 mode |
| Facts table & quiz | Switch between English and Traditional Chinese |
| Type badges & legend | Switch between English and Traditional Chinese |

## Node Types

| Type | Count | Colour |
|------|-------|--------|
| People 人物 | 47 | Blue |
| Events 事件 | 30 | Amber |
| Laws 法律 | 8 | Green |
| Institutions 機構 | 19 | Purple |
| Concepts 概念 | 12 | Sky blue |
| Dates 年份 | 13 | Orange |
| Sport & Culture 體育文化 | 10 | Red |
| **Total** | **139** | |

## Relationship Types

| Arrow | Meaning |
|-------|---------|
| 🔴 Red | Causal — caused / led to |
| 🟢 Green | Created — founded / established |
| 🔵 Blue | Chronological — next in time |
| ⚫ Grey | Structural — part of |

## Coverage

Covers all six chapters of the Life in the UK handbook:

| Chapter | Topics |
|---------|--------|
| CH1 | Values, citizenship, oath |
| CH2 | UK geography, devolution, Union Flag, Crown Dependencies |
| CH3 | Full history — Roman to modern (42% of real test questions) |
| CH4 | Society, religion, arts, sport, culture |
| CH5 | Parliament, government, law, voting, courts |
| CH6 | NHS, education, housing, work, everyday life |

## How to Use

1. Open `index.html` in any browser — or visit the GitHub Pages URL
2. Click any node to open the detail panel
3. In the panel, click related nodes to navigate the knowledge graph
4. Use the **Quiz** button to test yourself on any node
5. Click **Next →** after revealing an answer for a random next question
6. Switch to **Timeline** mode to arrange nodes by historical era
7. Click an era strip in the timeline bar to highlight that era's nodes
8. Use the **search bar** to find specific nodes by English name
9. Toggle **type chips** to focus on one category at a time
10. Switch 中文 / EN to change the language of facts and quiz content

## Attribution

> Based on material from the *Life in the UK* handbook, published by HMSO.
> Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

## Licence

MIT — see LICENSE file. Free to use, adapt, and share with attribution.

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main / root**
4. Live at `https://[your-username].github.io/[repo-name]` within ~60 seconds

No build step. No dependencies to install. Pure HTML + D3.js from CDN.
