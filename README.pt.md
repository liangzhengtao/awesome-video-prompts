[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md) | [العربية](README.ar.md) | [한국어](README.ko.md) | [Português](README.pt.md) | [Русский](README.ru.md) | [Deutsch](README.de.md)
n<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-orange.svg)](#prompt-collections)

**Pare de escrever prompts vagos. Mais de 200 prompts de geração de vídeo comprovados para Sora, Runway, Pika e Kling.**

---

## O Problema

**Prompt ruim:**
> "a cat walking"

**Resultado:** Gato aleatório, lugar aleatório, qualidade aleatória. Tente de novo. E de novo. E de novo.

---

## A Solução

**Bom prompt:**
> "A ginger tabby cat walks slowly along a rain-soaked cobblestone alley at dusk. Camera follows from behind at cat height, 35mm lens. Warm streetlamp light creates long shadows. Puddles reflect the neon signs above. Shot on ARRI Alexa, cinematic color grade, film grain."

**Resultado:** Exatamente o que você imaginou. De primeira.

---

## Início Rápido

1. **Navegue** nas coleções de prompts abaixo
2. **Copie** um prompt que se encaixe no seu projeto
3. **Cole** na sua ferramenta de vídeo com IA
4. **Ajuste** os detalhes para corresponder à sua visão
5. **Gere** — e obtenha resultados que realmente funcionam

---

## Folha de Referência de Prompt Engineering

### Anatomia de um Prompt de Vídeo

```
[Sujeito] + [Ação] + [Ambiente] + [Câmera] + [Iluminação] + [Estilo] + [Qualidade]
```

### Movimentos de Câmera Essenciais

| Movimento | Exemplo de Prompt |
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

### Iluminação Essencial

| Iluminação | Exemplo de Prompt |
|----------|----------------|
| Golden hour | Warm light, long shadows, 30 min before sunset |
| Blue hour | Deep blue ambient, 20 min after sunset |
| Rim light | Strong backlight on subject edges |
| Volumetric | Light shafts through fog/dust |
| Overcast | Soft, diffused, no hard shadows |
| Neon | Pink, blue, electric green reflections |
| Candlelight | Warm flickering, intimate shadows |
| Chiaroscuro | Single hard light, deep shadows |

### Dicas Profissionais

- **Nomeie a lente**: "21mm wide angle" ou "200mm telephoto" — a distância focal muda tudo
- **Nomeie um diretor de fotografia**: "In the style of Roger Deakins" dá à IA um alvo claro
- **Descreva o clima, não apenas a cena**: "A sense of quiet loneliness" > "empty room"
- **Uma ação por prompt**: Não encadeie 10 ações. Foque em um momento.
- **Inclua sinais negativos**: "No camera shake, no lens flare" — diga o que evitar

---

## Coleções de Prompts

### Sora (OpenAI)

| Categoria | Descrição | Prompts | Arquivo |
|----------|-------------|---------|------|
| 🎬 Tomadas Cinematográficas | Establishing shots, tracking shots, dolly zooms, aerial views, time-lapses | 25+ | [cinematic-shots.md](prompts/Sora/cinematic-shots.md) |
| 📖 Cenas Narrativas | Character actions, dialogue, emotional moments, conflict/resolution | 25+ | [narrative-scenes.md](prompts/Sora/narrative-scenes.md) |
| 🛍️ Vitrine de Produtos | Product reveals, unboxing, lifestyle shots, close-ups | 20+ | [product-showcase.md](prompts/Sora/product-showcase.md) |

### Runway Gen-3

| Categoria | Descrição | Prompts | Arquivo |
|----------|-------------|---------|------|
| 🎨 Motion Graphics | Liquid animations, particle effects, geometric transformations, text | 25+ | [motion-graphics.md](prompts/Runway/motion-graphics.md) |
| 📸 Cenas Realistas | People, animals, environments, weather, vehicles | 25+ | [realistic-scenes.md](prompts/Runway/realistic-scenes.md) |
| 🖌️ Transferência de Estilo | Impressionist, cyberpunk, noir, Studio Ghibli, Wes Anderson | 20+ | [style-transfer.md](prompts/Runway/style-transfer.md) |

### Pika

| Categoria | Descrição | Prompts | Arquivo |
|----------|-------------|---------|------|
| 📱 Conteúdo de Forma Curta | TikTok/Reels/Shorts style, meme-worthy, satisfying loops | 25+ | [short-form-content.md](prompts/Pika/short-form-content.md) |
| ✏️ Estilo de Animação | 2D animation, 3D render, pixel art, claymation | 20+ | [animation-style.md](prompts/Pika/animation-style.md) |
| ✨ Efeitos & Transformações | Morphing, explosions, weather effects, time manipulation | 20+ | [effects-and-transformations.md](prompts/Pika/effects-and-transformations.md) |

### Kling

| Categoria | Descrição | Prompts | Arquivo |
|----------|-------------|---------|------|
| 🏃 Foco no Humano | Dance, sports, cooking, crafts, performances | 25+ | [human-centric.md](prompts/Kling/human-centric.md) |
| 🌿 Natureza & Animais | Landscapes, wildlife, weather, seasons, micro/macro | 20+ | [nature-and-animals.md](prompts/Kling/nature-and-animals.md) |
| 🏯 Estética Chinesa | Ink wash painting, ancient architecture, martial arts, poetry, traditional culture | 20+ | [chinese-aesthetics.md](prompts/Kling/chinese-aesthetics.md) |

### Guias

| Guia | Descrição | Arquivo |
|-------|-------------|------|
| 📚 Prompt Engineering | Vocabulário de câmera, vocabulário de iluminação, referência de filme, erros comuns | [prompt-engineering.md](prompts/通用技巧/prompt-engineering.md) |
| 🎨 Palavras-chave de Estilo | 200+ palavras-chave de estilo organizadas por categoria: estilo visual, cor, textura, clima | [style-keywords.md](prompts/通用技巧/style-keywords.md) |

---

## Comparação de Ferramentas

| Recurso | Sora | Runway Gen-3 | Pika | Kling |
|---------|------|-------------|------|-------|
| **Melhor para** | Narrativo, cinematográfico | Motion graphics, abstrato | Redes sociais, animação | Movimento humano, natureza |
| **Duração máx.** | 60s | 10s | 4s | 10s |
| **Fotorrealismo** | ★★★★★ | ★★★★ | ★★★ | ★★★★ |
| **Animação** | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| **Movimento humano** | ★★★★ | ★★★ | ★★★ | ★★★★★ |
| **Transferência de estilo** | ★★★ | ★★★★★ | ★★★★ | ★★★ |
| **Proporções** | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1, 4:5 | 16:9, 9:16 |

### Quando Usar Qual Ferramenta

- **Sora**: Quando você precisa de uma cena completa com narrativa, movimento de câmera e qualidade cinematográfica
- **Runway**: Quando você precisa de motion graphics, visuais abstratos ou transferência de estilo forte
- **Pika**: Quando você precisa de conteúdo curto e impactante para redes sociais ou estilos de animação
- **Kling**: Quando seu vídeo gira em torno de movimento humano, culinária, dança ou estética chinesa

---

## Contribuição

Aceitamos contribuições de prompts! Consulte [CONTRIBUTING.md](CONTRIBUTING.md) para o formato e diretrizes.

**Como contribuir:**
1. Faça um fork deste repositório
2. Adicione seu prompt testado seguindo o [formato do template](CONTRIBUTING.md#prompt-format)
3. Envie um Pull Request
4. Revisamos e fazemos merge

---

## Estrutura do Projeto

```
awesome-video-prompts/
├── README.md                          ← Você está aqui
├── LICENSE                            ← Licença MIT
├── CONTRIBUTING.md                    ← Diretrizes de contribuição
├── CHANGELOG.md                       ← Histórico de versões
├── prompts/
│   ├── Sora/                          ← Prompts OpenAI Sora
│   │   ├── cinematic-shots.md         ← 25+ prompts cinematográficos
│   │   ├── narrative-scenes.md        ← 25+ prompts narrativos
│   │   └── product-showcase.md        ← 20+ prompts de produtos
│   ├── Runway/                        ← Prompts Runway Gen-3
│   │   ├── motion-graphics.md         ← 25+ prompts de motion graphics
│   │   ├── realistic-scenes.md        ← 25+ prompts realistas
│   │   └── style-transfer.md          ← 20+ prompts de transferência de estilo
│   ├── Pika/                          ← Prompts Pika
│   │   ├── short-form-content.md      ← 25+ prompts para redes sociais
│   │   ├── animation-style.md         ← 20+ prompts de animação
│   │   └── effects-and-transformations.md ← 20+ prompts de efeitos
│   ├── Kling/                         ← Prompts Kling
│   │   ├── human-centric.md           ← 25+ prompts de movimento humano
│   │   ├── nature-and-animals.md      ← 20+ prompts de natureza
│   │   └── chinese-aesthetics.md      ← 20+ prompts de estética chinesa
│   └── 通用技巧/                       ← Técnicas gerais
│       ├── prompt-engineering.md      ← Guia completo de prompt engineering
│       └── style-keywords.md          ← 200+ referência de palavras-chave de estilo
└── .github/
    ├── workflows/ci.yml               ← Pipeline de CI
    ├── ISSUE_TEMPLATE/                ← Templates de issues
    └── pull_request_template.md       ← Template de PR
```

---

## Veja Também

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — Coleção de prompts ChatGPT
- [awesome-prompts](https://github.com/DAGWorks-Inc/awesome-prompts) — Coleção de prompts multimodais
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) — Lista curada de ferramentas de IA
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) — Recursos de IA generativa
- [awesome-stable-diffusion](https://github.com/underctrlanatomy/awesome-stable-diffusion) — Recursos de Stable Diffusion
- [awesome-midjourney-prompts](https://github.com/willwulfken/awesome-midjourney-prompts) — Coleção de prompts Midjourney

---

## Licença

Este projeto está licenciado sob a MIT License — consulte o arquivo [LICENSE](LICENSE) para detalhes.

Copyright (c) 2026 liangzhengtao
