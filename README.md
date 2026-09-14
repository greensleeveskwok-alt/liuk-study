# 英國生活知識圖譜 · Life in the UK Knowledge Graph

An interactive bilingual (Traditional Chinese / English) knowledge graph for studying the Life in the UK citizenship test.

## Features

| Feature | Description |
|---------|-------------|
| 🕸️ Force graph | 90+ nodes across 6 types — drag, zoom, explore |
| 🔗 Relationships | Causal, chronological, institutional, created-by links |
| 📋 Click panels | Click any node for facts table + linked nodes |
| 📝 Quiz mode | Every node has a built-in quiz question with reveal |
| 🕐 Timeline mode | Arrange nodes by historical era on horizontal axis |
| 🔍 Search | Filter nodes by name in real time |
| 🏷️ Type filters | Toggle People / Events / Laws / Institutions / Concepts / Dates |
| 🇨🇳🇬🇧 Bilingual | Switch between Traditional Chinese and English at any time |

## How to Use

1. Open `index.html` in any browser — or visit the GitHub Pages URL
2. Click any node to open the detail panel
3. In the panel, click related nodes to navigate the knowledge graph
4. Use the **Quiz** button to test yourself
5. Switch to **Timeline** mode to see nodes arranged by era
6. Use the **search bar** to find specific nodes
7. Toggle **type chips** to focus on one category

## Attribution

> Based on material from the *Life in the UK* handbook, published by HMSO.
> Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

## Node Types

| Type | Count | Colour |
|------|-------|--------|
| People 人物 | 20 | Blue |
| Events 事件 | 17 | Amber |
| Laws 法律 | 5 | Green |
| Institutions 機構 | 11 | Purple |
| Concepts 概念 | 6 | Sky blue |
| Dates 年份 | 10 | Orange |

## Relationship Types

| Arrow | Meaning |
|-------|---------|
| 🔴 Red | Causal (caused / led to) |
| 🟢 Green | Created (founded / established) |
| 🔵 Blue | Chronological (next in time) |
| ⚫ Grey | Structural (part of) |

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your graph will be live at `https://[username].github.io/[repo-name]`

No build step needed. Pure HTML + D3.js (loaded from CDN).
