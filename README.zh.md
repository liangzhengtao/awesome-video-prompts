[English](README.md)

# Awesome Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-orange.svg)](#提示词合集)

**别再写模糊的提示词了。200+ 经过实战检验的 AI 视频生成提示词，覆盖 Sora、Runway、Pika、Kling 四大工具。**

---

## 问题

**糟糕的提示词：**
> "a cat walking"

**结果：** 随机的猫，随机的地点，随机的质量。反复尝试，反复失败。

---

## 解决方案

**好的提示词：**
> "一只姜黄色虎斑猫在黄昏时分沿着雨水浸湿的鹅卵石小巷缓缓行走。摄影机以猫的高度从后方跟随，使用35mm镜头。温暖的路灯投下长长的影子。水坑倒映着上方的霓虹灯牌。ARRI Alexa拍摄，电影级调色，胶片颗粒感。"

**结果：** 正是你想象中的画面。一次成功。

---

## 快速开始

1. **浏览** 下面的提示词合集
2. **复制** 适合你项目的提示词
3. **粘贴** 到你的 AI 视频工具中
4. **微调** 细节以匹配你的创意
5. **生成** — 得到真正有效的结果

---

## 提示词工程速查表

### 视频提示词结构

```
[主体] + [动作] + [环境] + [镜头] + [灯光] + [风格] + [质量]
```

### 核心镜头运动

| 运动 | 提示词示例 |
|------|-----------|
| 摇镜 | Camera pans left to right |
| 俯仰 | Camera tilts up from ground to sky |
| 推拉 | Camera dollies toward the subject |
| 跟踪 | Camera tracks alongside the runner |
| 升降 | Camera cranes up to 30ft overhead |
| 航拍 | Aerial drone shot descending from 200ft |
| 环绕 | Camera orbits 360° around the subject |
| 斯坦尼康 | Steadicam follows through the hallway |
| 手持 | Slight handheld shake, documentary feel |
| 固定 | Camera locked on tripod, no movement |

### 核心灯光

| 灯光 | 提示词示例 |
|------|-----------|
| 黄金时刻 | Warm light, long shadows, 30 min before sunset |
| 蓝色时刻 | Deep blue ambient, 20 min after sunset |
| 轮廓光 | Strong backlight on subject edges |
| 体积光 | Light shafts through fog/dust |
| 阴天 | Soft, diffused, no hard shadows |
| 霓虹灯 | Pink, blue, electric green reflections |
| 烛光 | Warm flickering, intimate shadows |
| 明暗对比 | Single hard light, deep shadows |

### 专业技巧

- **指定镜头焦距**："21mm广角"或"200mm长焦" — 焦距改变一切
- **引用摄影师**："Roger Deakins风格"给AI一个明确的目标
- **描述氛围，而非仅仅是场景**："一种安静的孤独感" > "空房间"
- **每个提示词一个动作**：不要串联10个动作。聚焦一个瞬间。
- **包含负面提示**："不要镜头晃动，不要镜头光晕" — 告诉它要避免什么

---

## 提示词合集

### Sora (OpenAI)

| 分类 | 描述 | 提示词数 | 文件 |
|------|------|----------|------|
| 🎬 电影镜头 | 建立镜头、跟踪镜头、推拉变焦、航拍、延时摄影 | 25+ | [cinematic-shots.md](prompts/Sora/cinematic-shots.md) |
| 📖 叙事场景 | 角色动作、对话、情感时刻、冲突/解决 | 25+ | [narrative-scenes.md](prompts/Sora/narrative-scenes.md) |
| 🛍️ 产品展示 | 产品揭幕、开箱、生活场景、特写 | 20+ | [product-showcase.md](prompts/Sora/product-showcase.md) |

### Runway Gen-3

| 分类 | 描述 | 提示词数 | 文件 |
|------|------|----------|------|
| 🎨 动态图形 | 液态动画、粒子效果、几何变换、文字 | 25+ | [motion-graphics.md](prompts/Runway/motion-graphics.md) |
| 📸 写实场景 | 人物、动物、环境、天气、车辆 | 25+ | [realistic-scenes.md](prompts/Runway/realistic-scenes.md) |
| 🖌️ 风格迁移 | 印象派、赛博朋克、黑色电影、吉卜力、韦斯·安德森 | 20+ | [style-transfer.md](prompts/Runway/style-transfer.md) |

### Pika

| 分类 | 描述 | 提示词数 | 文件 |
|------|------|----------|------|
| 📱 短视频内容 | TikTok/Reels/Shorts风格、梗图、循环动画 | 25+ | [short-form-content.md](prompts/Pika/short-form-content.md) |
| ✏️ 动画风格 | 2D动画、3D渲染、像素艺术、黏土动画 | 20+ | [animation-style.md](prompts/Pika/animation-style.md) |
| ✨ 特效与变换 | 变形、爆炸、天气效果、时间操控 | 20+ | [effects-and-transformations.md](prompts/Pika/effects-and-transformations.md) |

### Kling

| 分类 | 描述 | 提示词数 | 文件 |
|------|------|----------|------|
| 🏃 人物运动 | 舞蹈、运动、烹饪、手工、表演 | 25+ | [human-centric.md](prompts/Kling/human-centric.md) |
| 🌿 自然与动物 | 风景、野生动物、天气、季节、微距/广角 | 20+ | [nature-and-animals.md](prompts/Kling/nature-and-animals.md) |
| 🏯 中国美学 | 水墨画、古风建筑、武侠、诗词意境、传统文化 | 20+ | [chinese-aesthetics.md](prompts/Kling/chinese-aesthetics.md) |

### 参考指南

| 指南 | 描述 | 文件 |
|------|------|------|
| 📚 提示词工程 | 镜头词汇、灯光词汇、胶片参考、常见错误 | [prompt-engineering.md](prompts/通用技巧/prompt-engineering.md) |
| 🎨 风格关键词 | 200+ 风格关键词，按视觉风格、颜色、纹理、氛围分类 | [style-keywords.md](prompts/通用技巧/style-keywords.md) |

---

## 工具对比

| 特性 | Sora | Runway Gen-3 | Pika | Kling |
|------|------|-------------|------|-------|
| **最擅长** | 叙事、电影感 | 动态图形、抽象 | 社交媒体、动画 | 人物运动、自然 |
| **最长时长** | 60s | 10s | 4s | 10s |
| **写实度** | ★★★★★ | ★★★★ | ★★★ | ★★★★ |
| **动画** | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| **人物运动** | ★★★★ | ★★★ | ★★★ | ★★★★★ |
| **风格迁移** | ★★★ | ★★★★★ | ★★★★ | ★★★ |
| **画幅比例** | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1, 4:5 | 16:9, 9:16 |

### 何时使用哪个工具

- **Sora**：需要完整的叙事场景、镜头运动和电影质感时
- **Runway**：需要动态图形、抽象视觉或强烈的风格迁移时
- **Pika**：需要短小精悍的社交媒体内容或动画风格时
- **Kling**：视频以人物运动、烹饪、舞蹈或中国美学为核心时

---

## 贡献

欢迎贡献提示词！请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解格式和指南。

**如何贡献：**
1. Fork 此仓库
2. 按照[模板格式](CONTRIBUTING.md#prompt-format)添加你测试过的提示词
3. 提交 Pull Request
4. 审核并合并

---

## 项目结构

```
awesome-video-prompts/
├── README.md                          ← 你在这里
├── LICENSE                            ← MIT 许可证
├── CONTRIBUTING.md                    ← 贡献指南
├── CHANGELOG.md                       ← 版本历史
├── prompts/
│   ├── Sora/                          ← OpenAI Sora 提示词
│   │   ├── cinematic-shots.md         ← 25+ 电影镜头提示词
│   │   ├── narrative-scenes.md        ← 25+ 叙事场景提示词
│   │   └── product-showcase.md        ← 20+ 产品展示提示词
│   ├── Runway/                        ← Runway Gen-3 提示词
│   │   ├── motion-graphics.md         ← 25+ 动态图形提示词
│   │   ├── realistic-scenes.md        ← 25+ 写实场景提示词
│   │   └── style-transfer.md          ← 20+ 风格迁移提示词
│   ├── Pika/                          ← Pika 提示词
│   │   ├── short-form-content.md      ← 25+ 短视频提示词
│   │   ├── animation-style.md         ← 20+ 动画提示词
│   │   └── effects-and-transformations.md ← 20+ 特效提示词
│   ├── Kling/                         ← Kling 提示词
│   │   ├── human-centric.md           ← 25+ 人物运动提示词
│   │   ├── nature-and-animals.md      ← 20+ 自然提示词
│   │   └── chinese-aesthetics.md      ← 20+ 中国美学提示词
│   └── 通用技巧/                       ← 通用技巧
│       ├── prompt-engineering.md      ← 提示词工程完整指南
│       └── style-keywords.md          ← 200+ 风格关键词参考
└── .github/
    ├── workflows/ci.yml               ← CI 流水线
    ├── ISSUE_TEMPLATE/                ← Issue 模板
    └── pull_request_template.md       ← PR 模板
```

---

## 相关项目

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — ChatGPT 提示词合集
- [awesome-prompts](https://github.com/DAGWorks-Inc/awesome-prompts) — 多模态提示词合集
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) — AI 工具精选列表
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) — 生成式 AI 资源
- [awesome-stable-diffusion](https://github.com/underctrlanatomy/awesome-stable-diffusion) — Stable Diffusion 资源
- [awesome-midjourney-prompts](https://github.com/willwulfken/awesome-midjourney-prompts) — Midjourney 提示词合集

---

## 许可证

本项目采用 MIT 许可证 — 详情请参阅 [LICENSE](LICENSE) 文件。

Copyright (c) 2026 liangzhengtao
