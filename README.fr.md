[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [Français](README.fr.md) | [Español](README.es.md)

<div align="center">

<img src=".banner.svg" width="100%" alt="banner">

</div>


# Awesome Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Prompts](https://img.shields.io/badge/Prompts-200+-orange.svg)](#collections-de-prompts)

**Arrêtez d'écrire des prompts vagues. Plus de 200 prompts de génération vidéo éprouvés pour Sora, Runway, Pika et Kling.**

---

## Le problème

**Mauvais prompt :**
> "a cat walking"

**Résultat :** Un chat au hasard, un endroit au hasard, une qualité au hasard. Recommencez. Encore et encore.

---

## La solution

**Bon prompt :**
> "A ginger tabby cat walks slowly along a rain-soaked cobblestone alley at dusk. Camera follows from behind at cat height, 35mm lens. Warm streetlamp light creates long shadows. Puddles reflect the neon signs above. Shot on ARRI Alexa, cinematic color grade, film grain."

**Résultat :** Exactement ce que vous aviez imaginé. Du premier coup.

---

## Démarrage rapide

1. **Parcourez** les collections de prompts ci-dessous
2. **Copiez** un prompt adapté à votre projet
3. **Collez-le** dans votre outil de vidéo IA
4. **Ajustez** les détails selon votre vision
5. **Générez** — et obtenez des résultats concrets

---

## Aide-mémoire de prompt engineering

### Anatomie d'un prompt vidéo

```
[Sujet] + [Action] + [Environnement] + [Caméra] + [Éclairage] + [Style] + [Qualité]
```

### Mouvements de caméra essentiels

| Mouvement | Exemple de prompt |
|-----------|-------------------|
| Panoramique | Camera pans left to right |
| Inclinaison | Camera tilts up from ground to sky |
| Travelling | Camera dollies toward the subject |
| Plan de suivi | Camera tracks alongside the runner |
| Grue | Camera cranes up to 30ft overhead |
| Drone | Aerial drone shot descending from 200ft |
| Orbite | Camera orbits 360° around the subject |
| Steadicam | Steadicam follows through the hallway |
| Porté | Slight handheld shake, documentary feel |
| Fixe | Camera locked on tripod, no movement |

### Éclairages essentiels

| Éclairage | Exemple de prompt |
|-----------|-------------------|
| Heure dorée | Warm light, long shadows, 30 min before sunset |
| Heure bleue | Deep blue ambient, 20 min after sunset |
| Lumière de contour | Strong backlight on subject edges |
| Volumétrique | Light shafts through fog/dust |
| Couvert | Soft, diffused, no hard shadows |
| Néon | Pink, blue, electric green reflections |
| Bougie | Warm flickering, intimate shadows |
| Chiaroscuro | Single hard light, deep shadows |

### Conseils de pro

- **Nommez l'objectif** : "21mm wide angle" ou "200mm telephoto" — la focale change tout
- **Citez un directeur photo** : "In the style of Roger Deakins" donne à l'IA une cible précise
- **Décrivez l'ambiance, pas seulement la scène** : "A sense of quiet loneliness" > "empty room"
- **Une action par prompt** : N'enchaînez pas 10 actions. Concentrez-vous sur un instant.
- **Incluez des indications négatives** : "No camera shake, no lens flare" — dites ce qu'il faut éviter

---

## Collections de prompts

### Sora (OpenAI)

| Catégorie | Description | Prompts | Fichier |
|-----------|-------------|---------|---------|
| 🎬 Plans cinématiques | Plans d'ensemble, plans de suivi, zooms travelling, vues aériennes, timelapses | 25+ | [cinematic-shots.md](prompts/Sora/cinematic-shots.md) |
| 📖 Scènes narratives | Actions de personnages, dialogues, moments émotionnels, conflit/résolution | 25+ | [narrative-scenes.md](prompts/Sora/narrative-scenes.md) |
| 🛍️ Présentation produit | Dévoilement de produit, déballage, plans lifestyle, gros plans | 20+ | [product-showcase.md](prompts/Sora/product-showcase.md) |

### Runway Gen-3

| Catégorie | Description | Prompts | Fichier |
|-----------|-------------|---------|---------|
| 🎨 Motion design | Animations liquides, effets de particules, transformations géométriques, texte | 25+ | [motion-graphics.md](prompts/Runway/motion-graphics.md) |
| 📸 Scènes réalistes | Personnes, animaux, environnements, météo, véhicules | 25+ | [realistic-scenes.md](prompts/Runway/realistic-scenes.md) |
| 🖌️ Transfert de style | Impressionnisme, cyberpunk, film noir, Studio Ghibli, Wes Anderson | 20+ | [style-transfer.md](prompts/Runway/style-transfer.md) |

### Pika

| Catégorie | Description | Prompts | Fichier |
|-----------|-------------|---------|---------|
| 📱 Contenu court | Style TikTok/Reels/Shorts, mèmes, boucles satisfaisantes | 25+ | [short-form-content.md](prompts/Pika/short-form-content.md) |
| ✏️ Style animation | Animation 2D, rendu 3D, pixel art, claymation | 20+ | [animation-style.md](prompts/Pika/animation-style.md) |
| ✨ Effets et transformations | Morphing, explosions, effets météo, manipulation temporelle | 20+ | [effects-and-transformations.md](prompts/Pika/effects-and-transformations.md) |

### Kling

| Catégorie | Description | Prompts | Fichier |
|-----------|-------------|---------|---------|
| 🏃 Centré sur l'humain | Danse, sport, cuisine, artisanat, performances | 25+ | [human-centric.md](prompts/Kling/human-centric.md) |
| 🌿 Nature et animaux | Paysages, faune, météo, saisons, micro/macro | 20+ | [nature-and-animals.md](prompts/Kling/nature-and-animals.md) |
| 🏯 Esthétique chinoise | Peinture à l'encre, architecture ancienne, arts martiaux, poésie, culture traditionnelle | 20+ | [chinese-aesthetics.md](prompts/Kling/chinese-aesthetics.md) |

### Guides

| Guide | Description | Fichier |
|-------|-------------|---------|
| 📚 Prompt engineering | Vocabulaire caméra, vocabulaire lumière, référence pellicule, erreurs courantes | [prompt-engineering.md](prompts/通用技巧/prompt-engineering.md) |
| 🎨 Mots-clés de style | Plus de 200 mots-clés de style organisés par catégorie : style visuel, couleur, texture, ambiance | [style-keywords.md](prompts/通用技巧/style-keywords.md) |

---

## Comparaison des outils

| Fonctionnalité | Sora | Runway Gen-3 | Pika | Kling |
|----------------|------|-------------|------|-------|
| **Idéal pour** | Narratif, cinématique | Motion design, abstrait | Réseaux sociaux, animation | Mouvement humain, nature |
| **Durée max** | 60s | 10s | 4s | 10s |
| **Photoréalisme** | ★★★★★ | ★★★★ | ★★★ | ★★★★ |
| **Animation** | ★★★ | ★★★★ | ★★★★★ | ★★★ |
| **Mouvement humain** | ★★★★ | ★★★ | ★★★ | ★★★★★ |
| **Transfert de style** | ★★★ | ★★★★★ | ★★★★ | ★★★ |
| **Ratios d'aspect** | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1 | 16:9, 9:16, 1:1, 4:5 | 16:9, 9:16 |

### Quand utiliser quel outil

- **Sora** : Quand vous avez besoin d'une scène complète avec narration, mouvements de caméra et qualité cinématique
- **Runway** : Quand vous avez besoin de motion design, de visuels abstraits ou d'un fort transfert de style
- **Pika** : Quand vous avez besoin de contenu court et percutant pour les réseaux sociaux ou de styles d'animation
- **Kling** : Quand votre vidéo met en avant le mouvement humain, la cuisine, la danse ou l'esthétique chinoise

---

## Contribuer

Nous accueillons les contributions de prompts ! Consultez [CONTRIBUTING.md](CONTRIBUTING.md) pour le format et les directives.

**Comment contribuer :**
1. Forker ce dépôt
2. Ajouter votre prompt testé selon le [format du modèle](CONTRIBUTING.md#prompt-format)
3. Soumettre une Pull Request
4. Nous examinons et fusionnons

---

## Structure du projet

```
awesome-video-prompts/
├── README.md                          ← Vous êtes ici
├── LICENSE                            ← Licence MIT
├── CONTRIBUTING.md                    ← Directives de contribution
├── CHANGELOG.md                       ← Historique des versions
├── prompts/
│   ├── Sora/                          ← Prompts OpenAI Sora
│   │   ├── cinematic-shots.md         ← 25+ prompts cinématiques
│   │   ├── narrative-scenes.md        ← 25+ prompts narratifs
│   │   └── product-showcase.md        ← 20+ prompts produit
│   ├── Runway/                        ← Prompts Runway Gen-3
│   │   ├── motion-graphics.md         ← 25+ prompts motion design
│   │   ├── realistic-scenes.md        ← 25+ prompts réalistes
│   │   └── style-transfer.md          ← 20+ prompts transfert de style
│   ├── Pika/                          ← Prompts Pika
│   │   ├── short-form-content.md      ← 25+ prompts réseaux sociaux
│   │   ├── animation-style.md         ← 20+ prompts animation
│   │   └── effects-and-transformations.md ← 20+ prompts effets
│   ├── Kling/                         ← Prompts Kling
│   │   ├── human-centric.md           ← 25+ prompts mouvement humain
│   │   ├── nature-and-animals.md      ← 20+ prompts nature
│   │   └── chinese-aesthetics.md      ← 20+ prompts esthétique chinoise
│   └── 通用技巧/                       ← Techniques générales
│       ├── prompt-engineering.md      ← Guide complet de prompt engineering
│       └── style-keywords.md          ← Référence de 200+ mots-clés de style
└── .github/
    ├── workflows/ci.yml               ← Pipeline CI
    ├── ISSUE_TEMPLATE/                ← Modèles d'issue
    └── pull_request_template.md       ← Modèle de PR
```

---

## Voir aussi

- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) — Collection de prompts ChatGPT
- [awesome-prompts](https://github.com/DAGWorks-Inc/awesome-prompts) — Collection de prompts multimodaux
- [awesome-ai-tools](https://github.com/mahseema/awesome-ai-tools) — Liste de outils IA sélectionnés
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) — Ressources en IA générative
- [awesome-stable-diffusion](https://github.com/underctrlanatomy/awesome-stable-diffusion) — Ressources Stable Diffusion
- [awesome-midjourney-prompts](https://github.com/willwulfken/awesome-midjourney-prompts) — Collection de prompts Midjourney

---

## Licence

Ce projet est sous licence MIT — voir le fichier [LICENSE](LICENSE) pour plus de détails.

Copyright (c) 2026 liangzhengtao
