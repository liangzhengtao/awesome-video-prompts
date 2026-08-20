[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)
n<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-orange.svg)](#prompt-collections)

**모호한 프롬프트 작성은 그만하세요. Sora, Runway, Pika, Kling을 위한 200개 이상의 검증된 영상 생성 프롬프트.**

---

## 문제

**나쁜 프롬프트:**
> "a cat walking"

**결과:** 무작위 고양이, 무작위 장소, 무작위 품질. 다시 시도. 또 다시. 또 다시.

---

## 해결

**좋은 프롬프트:**
> "A ginger tabby cat walks slowly along a rain-soaked cobblestone alley at dusk. Camera follows from behind at cat height, 35mm lens. Warm streetlamp light creates long shadows. Puddles reflect the neon signs above. Shot on ARRI Alexa, cinematic color grade, film grain."

**결과:** 상상한 바로 그것. 첫 번째 시도에.

---

## 빠른 시작

1. **탐색** 아래 프롬프트 컬렉션
2. **복사** 프로젝트에 맞는 프롬프트
3. **붙여넣기** AI 영상 도구에
4. **수정** 비전에 맞게 세부사항 조정
5. **생성** — 실제로 작동하는 결과 획득

---

## 프롬프트 엔지니어링 치트시트

### 영상 프롬프트의 구조

```
[주제] + [동작] + [환경] + [카메라] + [조명] + [스타일] + [품질]
```

### 필수 카메라 움직임

| 움직임 | 프롬프트 예시 |
|----------|----------------|
| 팬 | Camera pans left to right |
| 틸트 | Camera tilts up from ground to sky |
| 달리 | Camera dollies toward the subject |
| 트래킹 | Camera tracks alongside the runner |
| 크레인 | Camera cranes up to 30ft overhead |
| 드론 | Aerial drone shot descending from 200ft |
| 오르빗 | Camera orbits 360° around the subject |
| 스테디캠 | Steadicam follows through the hallway |
| 핸드헬드 | Slight handheld shake, documentary feel |
| 정적 | Camera locked on tripod, no movement |

### 필수 조명

| 조명 | 프롬프트 예시 |
|----------|----------------|
| 골든 아워 | Warm light, long shadows, 30 min before sunset |
| 블루 아워 | Deep blue ambient, 20 min after sunset |
| 림 라이트 | Strong backlight on subject edges |
| 볼류메트릭 | Light shafts through fog/dust |
| 흐린 날 | Soft, diffused, no hard shadows |
| 네온 | Pink, blue, electric green reflections |
| 촛불 | Warm flickering, intimate shadows |
| 키아로스쿠로 | Single hard light, deep shadows |

### 프로 팁

- **렌즈 이름 지정**: "21mm wide angle" 또는 "200mm telephoto" — 초점 거리가 모든 것을 바꿉니다
- **촬영감독 이름 지정**: "In the style of Roger Deakins"는 AI에게 명확한 목표를 줍니다
- **장면뿐만 아니라 분위기 표현**: "A sense of quiet loneliness" > "empty room"
- **프롬프트당 하나의 동작**: 10개의 동작을 연결하지 마세요. 하나의 순간에 집중.
- **부정적 큐 포함**: "No camera shake, no lens flare" — 피해야 할 것을 알려주세요

---

## 프롬프트 컬렉션

### Sora (OpenAI)

| 카테고리 | 설명 | 프롬프트 | 파일 |
|----------|-------------|---------|------|
| 🎬 시네마틱 샷 | Establishing shots, tracking shots, dolly zooms, aerial views, time-lapses | 25+ | [cinematic-shots.md](prompts/Sora/cinematic-shots.md) |
| 📖 내러티브 신 | Character actions, dialogue, emotional moments, conflict/resolution | 25+ | [narrative-scenes.md](prompts/Sora/narrative-scenes.md) |
| 🛍️ 제품 쇼케이스 | Product reveals, unboxing, lifestyle shots, close-ups | 20+ | [product-showcase.md](prompts/Sora/product-showcase.md) |

### Runway Gen-3

| 카테고리 | 설명 | 프롬프트 | 파일 |
|----------|-------------|---------|------|
| 🎨 모션 그래픽 | Liquid animations, particle effects, geometric transformations, text | 25+ | [motion-graphics.md](prompts/Runway/motion-graphics.md) |
| 📸 리얼리스틱 신 | People, animals, environments, weather, vehicles | 25+ | [realistic-scenes.md](prompts/Runway/realistic-scenes.md) |
| 🖌️ 스타일 전이 | Impressionist, cyberpunk, noir, Studio Ghibli, Wes Anderson | 20+ | [style-transfer.md](prompts/Runway/style-transfer.md) |

### Pika

| 카테고리 | 설명 | 프롬프트 | 파일 |
|----------|-------------|---------|------|
| 📱 숏폼 콘텐츠 | TikTok/Reels/Shorts style, meme-worthy, satisfying loops | 25+ | [short-form-content.md](prompts/Pika/short-form-content.md) |
| ✏️ 애니메이션 스타일 | 2D animation, 3D render, pixel art, claymation | 20+ | [animation-style.md](prompts/Pika/animation-style.md) |
| ✨ 효과 및 변환 | Morphing, explosions, weather effects, time manipulation | 20+ | [effects-and-transformations.md](prompts/Pika/effects-and-transformations.md) |

### Kling

| 카테고리 | 설명 | 프롬프트 | 파일 |
|----------|-------------|---------|------|
| 🏃 휴먼 센트릭 | Dance, sports, cooking, crafts, performances | 25+ | [human-centric.md](prompts/Kling/human-centric.md) |
| 🌿 자연 & 동물 | Landscapes, wildlife, weather, seasons, micro/macro | 20+ | [nature-and-animals.md](prompts/Kling/nature-and-animals.md) |
| 🏯 중국 미학 | Ink wash painting, ancient architecture, martial arts, poetry, traditional culture | 20+ | [chinese-aesthetics.md](prompts/Kling/chinese-aesthetics.md) |

### 가이드

| 가이드 | 설명 | 파일 |
|-------|-------------|------|
| 📚 프롬프트 엔지니어링 | 카메라 어휘, 조명 어휘, 필름 스톡 레퍼런스, 일반 실수 | [prompt-engineering.md](prompts/通用技巧/prompt-engineering.md) |
| 🎨 스타일 키워드 | 200개 이상의 스타일 키워드: 시각 스타일, 색상, 질감, 분위기별 분류 | [style-keywords.md](prompts/通用技巧/style-keywords.md) |

---

## 도구 비교

| 기능 | Sora | Runway Gen-3 | Pika | Kling |
|---------|------|-------------|------|-------|
| **최적 용도** | 내러티브, 시네마틱 | 모션 그래픽, 추상적 | 소셜 미디어, 애니메이션 | 인간 움직임, 자연 |
| **최대 길이** | 60s | 10s | 4s | 10s |
| **포토리얼리즘** | ★★★★★ | ★★★★ | ★★★ | ★★★★ |
| **애니메이션** | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| **인간 움직임** | ★★★★ | ★★★ | ★★★ | ★★★★★ |
| **스타일 전이** | ★★★ | ★★★★★ | ★★★★ | ★★★ |
| **화면 비율** | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1, 4:5 | 16:9, 9:16 |

### 어떤 도구를 언제 사용할까

- **Sora**: 내러티브, 카메라 움직임, 시네마틱 품질이 포함된 완전한 장면이 필요할 때
- **Runway**: 모션 그래픽, 추상적 비주얼, 강한 스타일 전이가 필요할 때
- **Pika**: 짧고 임팩트 있는 소셜 미디어 콘텐츠나 애니메이션 스타일이 필요할 때
- **Kling**: 영상이 인간의 움직임, 요리, 춤, 중국 미학 중심일 때

---

## 기여

프롬프트 기여를 환영합니다! 형식과 가이드라인은 [CONTRIBUTING.md](CONTRIBUTING.md)를 참조하세요.

**기여 방법:**
1. 이 저장소를 포크하세요
2. [템플릿 형식](CONTRIBUTING.md#prompt-format)에 따라 테스트된 프롬프트를 추가하세요
3. Pull Request를 제출하세요
4. 검토 후 머지합니다

---

## 프로젝트 구조

```
awesome-video-prompts/
├── README.md                          ← 여기입니다
├── LICENSE                            ← MIT 라이선스
├── CONTRIBUTING.md                    ← 기여 가이드라인
├── CHANGELOG.md                       ← 버전 이력
├── prompts/
│   ├── Sora/                          ← OpenAI Sora 프롬프트
│   │   ├── cinematic-shots.md         ← 25+ 시네마틱 프롬프트
│   │   ├── narrative-scenes.md        ← 25+ 내러티브 프롬프트
│   │   └── product-showcase.md        ← 20+ 제품 프롬프트
│   ├── Runway/                        ← Runway Gen-3 프롬프트
│   │   ├── motion-graphics.md         ← 25+ 모션 그래픽 프롬프트
│   │   ├── realistic-scenes.md        ← 25+ 리얼리스틱 프롬프트
│   │   └── style-transfer.md          ← 20+ 스타일 전이 프롬프트
│   ├── Pika/                          ← Pika 프롬프트
│   │   ├── short-form-content.md      ← 25+ 소셜 미디어 프롬프트
│   │   ├── animation-style.md         ← 20+ 애니메이션 프롬프트
│   │   └── effects-and-transformations.md ← 20+ 효과 프롬프트
│   ├── Kling/                         ← Kling 프롬프트
│   │   ├── human-centric.md           ← 25+ 인간 움직임 프롬프트
│   │   ├── nature-and-animals.md      ← 20+ 자연 프롬프트
│   │   └── chinese-aesthetics.md      ← 20+ 중국 미학 프롬프트
│   └── 通用技巧/                       ← 일반 기법
│       ├── prompt-engineering.md      ← 완전한 프롬프트 엔지니어링 가이드
│       └── style-keywords.md          ← 200개 이상의 스타일 키워드 레퍼런스
└── .github/
    ├── workflows/ci.yml               ← CI 파이프라인
    ├── ISSUE_TEMPLATE/                ← 이슈 템플릿
    └── pull_request_template.md       ← PR 템플릿
```

---

## 함께 보기

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — ChatGPT 프롬프트 컬렉션
- [awesome-prompts](https://github.com/DAGWorks-Inc/awesome-prompts) — 멀티모달 프롬프트 컬렉션
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) — AI 도구 큐레이션 목록
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) — 생성 AI 리소스
- [awesome-stable-diffusion](https://github.com/underctrlanatomy/awesome-stable-diffusion) — Stable Diffusion 리소스
- [awesome-midjourney-prompts](https://github.com/willwulfken/awesome-midjourney-prompts) — Midjourney 프롬프트 컬렉션

---

## 라이선스

이 프로젝트는 MIT License 하에 라이선스가 부여됩니다 — 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

Copyright (c) 2026 liangzhengtao
