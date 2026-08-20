[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)
n<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-orange.svg)](#prompt-collections)

**Stop writing vague prompts. 200+ tried-and-true video generation prompts for Sora, Runway, Pika, and Kling.**

---

## The Problem

**Bad prompt:**
> "a cat walking"

**Result:** Random cat, random place, random quality. Try again. And again. And again.

---

## The Solution

**Good prompt:**
> "A ginger tabby cat walks slowly along a rain-soaked cobblestone alley at dusk. Camera follows from behind at cat height, 35mm lens. Warm streetlamp light creates long shadows. Puddles reflect the neon signs above. Shot on ARRI Alexa, cinematic color grade, film grain."

**Result:** Exactly what you imagined. First try.

---

## Quick Start

1. **Browse** the prompt collections below
2. **Copy** a prompt that fits your project
3. **Paste** it into your AI video tool
4. **Tweak** the details to match your vision
5. **Generate** — and get results that actually work

---

## Prompt Engineering Cheat Sheet

### Anatomy of a Video Prompt

```
[Subject] + [Action] + [Environment] + [Camera] + [Lighting] + [Style] + [Quality]
```

### Essential Camera Movements

| Movement | Prompt Example |
|----------|----------------|
| Pan | Camera pans left to right |
| Tilt | Camera tilts up from ground to sky |
| Dolly | Camera dollies toward the subject |
| Tracking | Camera tracks alongside the runner |
| Crane | Camera cranes up to 30ft overhead |
| Drone | Aerial drone shot descending from 200ft |
| Orbit | Camera orbits 360° around the subject |
| Steadicam | Steadicam follows through the hallway |
| Handheld | Slight handheld shake, documentary feel |
| Static | Camera locked on tripod, no movement |

### Essential Lighting

| Lighting | Prompt Example |
|----------|----------------|
| Golden hour | Warm light, long shadows, 30 min before sunset |
| Blue hour | Deep blue ambient, 20 min after sunset |
| Rim light | Strong backlight on subject edges |
| Volumetric | Light shafts through fog/dust |
| Overcast | Soft, diffused, no hard shadows |
| Neon | Pink, blue, electric green reflections |
| Candlelight | Warm flickering, intimate shadows |
| Chiaroscuro | Single hard light, deep shadows |

### Pro Tips

- **Name the lens**: "21mm wide angle" or "200mm telephoto" — focal length changes everything
- **Name a cinematographer**: "In the style of Roger Deakins" gives the AI a clear target
- **Describe mood, not just scene**: "A sense of quiet loneliness" > "empty room"
- **One action per prompt**: Don't chain 10 actions. Focus on one moment.
- **Include negative cues**: "No camera shake, no lens flare" — tell it what to avoid

---

## Prompt Collections

### Sora (OpenAI)

| Category | Description | Prompts | File |
|----------|-------------|---------|------|
| 🎬 Cinematic Shots | Establishing shots, tracking shots, dolly zooms, aerial views, time-lapses | 25+ | [cinematic-shots.md](prompts/Sora/cinematic-shots.md) |
| 📖 Narrative Scenes | Character actions, dialogue, emotional moments, conflict/resolution | 25+ | [narrative-scenes.md](prompts/Sora/narrative-scenes.md) |
| 🛍️ Product Showcase | Product reveals, unboxing, lifestyle shots, close-ups | 20+ | [product-showcase.md](prompts/Sora/product-showcase.md) |

### Runway Gen-3

| Category | Description | Prompts | File |
|----------|-------------|---------|------|
| 🎨 Motion Graphics | Liquid animations, particle effects, geometric transformations, text | 25+ | [motion-graphics.md](prompts/Runway/motion-graphics.md) |
| 📸 Realistic Scenes | People, animals, environments, weather, vehicles | 25+ | [realistic-scenes.md](prompts/Runway/realistic-scenes.md) |
| 🖌️ Style Transfer | Impressionist, cyberpunk, noir, Studio Ghibli, Wes Anderson | 20+ | [style-transfer.md](prompts/Runway/style-transfer.md) |

### Pika

| Category | Description | Prompts | File |
|----------|-------------|---------|------|
| 📱 Short-Form Content | TikTok/Reels/Shorts style, meme-worthy, satisfying loops | 25+ | [short-form-content.md](prompts/Pika/short-form-content.md) |
| ✏️ Animation Style | 2D animation, 3D render, pixel art, claymation | 20+ | [animation-style.md](prompts/Pika/animation-style.md) |
| ✨ Effects & Transformations | Morphing, explosions, weather effects, time manipulation | 20+ | [effects-and-transformations.md](prompts/Pika/effects-and-transformations.md) |

### Kling

| Category | Description | Prompts | File |
|----------|-------------|---------|------|
| 🏃 Human-Centric | Dance, sports, cooking, crafts, performances | 25+ | [human-centric.md](prompts/Kling/human-centric.md) |
| 🌿 Nature & Animals | Landscapes, wildlife, weather, seasons, micro/macro | 20+ | [nature-and-animals.md](prompts/Kling/nature-and-animals.md) |
| 🏯 Chinese Aesthetics | Ink wash painting, ancient architecture, martial arts, poetry, traditional culture | 20+ | [chinese-aesthetics.md](prompts/Kling/chinese-aesthetics.md) |

### Guides

| Guide | Description | File |
|-------|-------------|------|
| 📚 Prompt Engineering | Camera vocabulary, lighting vocabulary, film stock reference, common mistakes | [prompt-engineering.md](prompts/通用技巧/prompt-engineering.md) |
| 🎨 Style Keywords | 200+ style keywords organized by category: visual style, color, texture, mood | [style-keywords.md](prompts/通用技巧/style-keywords.md) |

---

## Tool Comparison

| Feature | Sora | Runway Gen-3 | Pika | Kling |
|---------|------|-------------|------|-------|
| **Best for** | Narrative, cinematic | Motion graphics, abstract | Social media, animation | Human motion, nature |
| **Max duration** | 60s | 10s | 4s | 10s |
| **Photorealism** | ★★★★★ | ★★★★ | ★★★ | ★★★★ |
| **Animation** | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| **Human motion** | ★★★★ | ★★★ | ★★★ | ★★★★★ |
| **Style transfer** | ★★★ | ★★★★★ | ★★★★ | ★★★ |
| **Aspect ratios** | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1, 4:5 | 16:9, 9:16 |

### When to Use Which Tool

- **Sora**: When you need a complete scene with narrative, camera movement, and cinematic quality
- **Runway**: When you need motion graphics, abstract visuals, or strong style transfer
- **Pika**: When you need short, punchy social media content or animation styles
- **Kling**: When your video centers on human movement, cooking, dance, or Chinese aesthetics

---

## Contributing

We welcome prompt contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for the format and guidelines.

**How to contribute:**
1. Fork this repo
2. Add your tested prompt following the [template format](CONTRIBUTING.md#prompt-format)
3. Submit a Pull Request
4. We review and merge

---

## Project Structure

```
awesome-video-prompts/
├── README.md                          ← You are here
├── LICENSE                            ← MIT License
├── CONTRIBUTING.md                    ← Contribution guidelines
├── CHANGELOG.md                       ← Version history
├── prompts/
│   ├── Sora/                          ← OpenAI Sora prompts
│   │   ├── cinematic-shots.md         ← 25+ cinematic prompts
│   │   ├── narrative-scenes.md        ← 25+ narrative prompts
│   │   └── product-showcase.md        ← 20+ product prompts
│   ├── Runway/                        ← Runway Gen-3 prompts
│   │   ├── motion-graphics.md         ← 25+ motion graphics prompts
│   │   ├── realistic-scenes.md        ← 25+ realistic prompts
│   │   └── style-transfer.md          ← 20+ style transfer prompts
│   ├── Pika/                          ← Pika prompts
│   │   ├── short-form-content.md      ← 25+ social media prompts
│   │   ├── animation-style.md         ← 20+ animation prompts
│   │   └── effects-and-transformations.md ← 20+ effects prompts
│   ├── Kling/                         ← Kling prompts
│   │   ├── human-centric.md           ← 25+ human motion prompts
│   │   ├── nature-and-animals.md      ← 20+ nature prompts
│   │   └── chinese-aesthetics.md      ← 20+ Chinese aesthetic prompts
│   └── 通用技巧/                       ← General techniques
│       ├── prompt-engineering.md      ← Complete prompt engineering guide
│       └── style-keywords.md          ← 200+ style keyword reference
└── .github/
    ├── workflows/ci.yml               ← CI pipeline
    ├── ISSUE_TEMPLATE/                ← Issue templates
    └── pull_request_template.md       ← PR template
```

---

## See Also

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — ChatGPT prompt collection
- [awesome-prompts](https://github.com/DAGWorks-Inc/awesome-prompts) — Multi-modal prompt collection
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) — Curated AI tools list
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) — Generative AI resources
- [awesome-stable-diffusion](https://github.com/underctrlanatomy/awesome-stable-diffusion) — Stable Diffusion resources
- [awesome-midjourney-prompts](https://github.com/willwulfken/awesome-midjourney-prompts) — Midjourney prompt collection

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

Copyright (c) 2026 liangzhengtao
