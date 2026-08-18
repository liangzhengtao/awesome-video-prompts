# Video Prompt Engineering Guide

> Last updated: 2026 | 通用技巧 (General Techniques)

This guide teaches you how to write effective prompts for any AI video generation tool — Sora, Runway, Pika, Kling, or others.

---

## The Anatomy of a Good Video Prompt

A great video prompt has **7 components**. You don't always need all 7, but the more you include, the more control you have.

```
[Subject] + [Action] + [Environment] + [Camera] + [Lighting] + [Style] + [Quality]
```

### Example

**Bad prompt:**
> "A cat walking"

**Good prompt:**
> "A ginger tabby cat walks slowly along a rain-soaked cobblestone alley at dusk. Camera follows from behind at cat height, 35mm lens. Warm streetlamp light creates long shadows. Puddles reflect the neon signs above. Shot on ARRI Alexa, cinematic color grade, film grain."

**Why the good prompt works:**
- **Subject**: ginger tabby cat (specific breed, color)
- **Action**: walks slowly (pace defined)
- **Environment**: rain-soaked cobblestone alley at dusk (time, weather, surface)
- **Camera**: follows from behind at cat height, 35mm lens (perspective, focal length)
- **Lighting**: warm streetlamp, long shadows, neon reflections
- **Style**: cinematic color grade, film grain
- **Quality**: ARRI Alexa (camera reference)

---

## Camera Movement Vocabulary

### Basic Movements

| Movement | Description | Prompt Phrase |
|----------|-------------|---------------|
| **Pan** | Camera rotates horizontally on a fixed point | "Camera pans left to right" |
| **Tilt** | Camera rotates vertically on a fixed point | "Camera tilts up from the ground to the sky" |
| **Dolly** | Camera physically moves toward/away from subject | "Camera dollies in toward the subject" |
| **Zoom** | Lens magnification changes (not physical movement) | "Slow zoom in on the face" |
| **Tracking** | Camera follows a moving subject | "Camera tracks alongside the runner" |
| **Crane/Jib** | Camera moves vertically through space | "Camera cranes up from ground level to 30ft overhead" |
| **Drone/Aerial** | Camera flies through the air | "Aerial drone shot descending from 200ft" |
| **Steadicam** | Smoothed handheld, often following subject | "Steadicam follows behind through the hallway" |
| **Handheld** | Slightly shaky, documentary feel | "Handheld camera, slight natural shake" |
| **Static/Locked** | Camera doesn't move at all | "Camera is locked on a tripod, no movement" |

### Advanced Movements

| Movement | Description | Prompt Phrase |
|----------|-------------|---------------|
| **Orbit** | Camera circles around the subject | "Camera orbits 360 degrees around the subject" |
| **Push-in** | Gradual movement closer (builds tension) | "Slow push-in over 10 seconds" |
| **Pull-back** | Gradual movement away (reveals context) | "Camera pulls back to reveal the full scene" |
| **Dutch angle** | Camera tilted on its axis | "Slight Dutch angle — 15 degrees off-axis" |
| **Whip pan** | Very fast horizontal rotation | "Whip pan from left to right, motion blur" |
| **Dolly zoom** | Dolly in while zooming out (or vice versa) | "Dolly zoom — camera pushes in while lens zooms out, vertigo effect" |
| **Overhead/Bird's eye** | Directly above, looking straight down | "Bird's eye view, looking straight down" |
| **Worm's eye** | Ground level, looking straight up | "Worm's eye view from the ground looking up" |

### Camera Speed

- "At walking pace" — slow, natural movement
- "At running pace" — faster, following action
- "At vehicle speed" — fast tracking, road scenes
- "400x time-lapse speed" — compressed time
- "1000fps slow motion" — extreme slow motion
- "Smooth, constant speed" — no acceleration/deceleration

---

## Lighting Vocabulary

### Natural Light Conditions

| Condition | Description | Prompt Phrase |
|-----------|-------------|---------------|
| **Golden hour** | 30 min before/after sunset — warm, long shadows | "Golden hour, warm light, long shadows" |
| **Blue hour** | 20 min after sunset — deep blue ambient light | "Blue hour, deep blue ambient light, no direct sun" |
| **High noon** | Direct overhead sun — harsh, minimal shadows | "Midday sun, harsh overhead light, short shadows" |
| **Overcast** | Cloudy sky — soft, diffused, no hard shadows | "Overcast sky, soft diffused light, even illumination" |
| **Dawn/First light** | Very early morning — cool, gentle | "First light of dawn, pale pink sky, gentle illumination" |
| **Twilight** | After sunset, before full dark — purple/orange sky | "Twilight, purple-orange sky, ambient glow" |

### Artificial Light Types

| Type | Description | Prompt Phrase |
|------|-------------|---------------|
| **Tungsten** | Warm, orange-yellow (traditional bulbs) | "Warm tungsten practical lights, 3200K" |
| **Fluorescent** | Cool, slightly green (offices, hospitals) | "Cool fluorescent overhead, slightly green cast" |
| **Neon** | Colored, glowing (night scenes, signs) | "Neon lighting — pink, blue, electric green" |
| **LED** | Variable color temperature, modern | "Clean LED panel light, daylight balanced" |
| **Candle/firelight** | Warm, flickering, intimate | "Candlelight only, warm flickering, intimate shadows" |
| **Moonlight** | Cool, blue, soft shadows | "Moonlight, cool blue ambient, soft shadow edges" |

### Lighting Techniques

| Technique | Description | Prompt Phrase |
|-----------|-------------|---------------|
| **Rim light** | Backlight that outlines the subject's edges | "Strong rim light from behind, separating subject from background" |
| **Volumetric** | Light visible in fog/dust/steam | "Volumetric light shafts through fog" |
| **Chiaroscuro** | High contrast light and dark | "Dramatic chiaroscuro — single hard light, deep shadows" |
| **Three-point** | Standard key + fill + back light | "Classic three-point studio lighting" |
| **Low-key** | Mostly dark, minimal light areas | "Low-key lighting — mostly shadows, selective highlights" |
| **High-key** | Mostly bright, minimal shadows | "High-key lighting — bright, even, minimal shadows" |
| **Gel lighting** | Colored lights using color gels | "Blue-gelled key light from camera left" |
| **Practical** | Light sources visible in the scene (lamps, candles) | "Practical lighting only — desk lamp, window light" |

---

## Film Stock & Lens Vocabulary

### Film Stocks

| Stock | Look | Prompt Phrase |
|-------|------|---------------|
| **Kodak Vision3 500T** | Tungsten-balanced, warm grain, cinematic | "Shot on Kodak Vision3 500T — warm grain, tungsten tones" |
| **Kodak Vision3 250D** | Daylight-balanced, natural, clean | "Shot on Kodak 250D — natural daylight, clean grain" |
| **Kodak Ektachrome** | Slide film, saturated, vivid | "Ektachrome look — vivid saturated colors, fine grain" |
| **Fujifilm Pro 400H** | Pastel, soft highlights, gentle | "Fujifilm 400H look — pastel tones, soft highlight roll-off" |
| **Ilford HP5** | Black and white, classic grain | "Ilford HP5 black and white — rich grain, deep blacks" |
| **CineStill 800T** | Tungsten, halation on highlights, moody | "CineStill 800T — halation glow on highlights, moody tungsten" |

### Lens Focal Lengths

| Focal Length | Effect | Use Case |
|-------------|--------|----------|
| **14mm ultra-wide** | Extreme perspective, distortion at edges | Landscapes, architecture, immersive POV |
| **24mm wide** | Wide perspective, moderate distortion | Establishing shots, environmental portraits |
| **35mm** | Natural perspective, slight wide | Street photography, documentary, natural feel |
| **50mm** | Closest to human eye | Portraits, standard coverage, interviews |
| **85mm** | Flattering compression, bokeh | Portraits, close-ups, shallow depth of field |
| **135mm** | More compression, creamy bokeh | Headshots, detail shots |
| **200mm telephoto** | Significant compression, background blur | Wildlife, sports, compressing distance |
| **400mm+ super telephoto** | Extreme compression, distant subjects | Moon shots, wildlife at distance |

### Lens Characteristics

| Characteristic | Description | Prompt Phrase |
|---------------|-------------|---------------|
| **Anamorphic** | Widescreen format, oval bokeh, lens flares | "Anamorphic lens — horizontal lens flares, oval bokeh" |
| **Bokeh** | Out-of-focus light rendering | "Shallow depth of field, creamy bokeh background" |
| **Lens flare** | Light hitting the lens directly | "Subtle lens flare from the sun entering frame" |
| **Chromatic aberration** | Color fringing at high-contrast edges | "Slight chromatic aberration on edges" |
| **Barrel distortion** | Straight lines bow outward (wide angle) | "Wide-angle barrel distortion" |
| **Vignetting** | Darkened corners | "Natural vignetting — darker at frame edges" |
| **Halation** | Glowing halo around bright light sources | "Halation glow around the window light" |

---

## Negative Prompts for Video

Negative prompts tell the AI what to **avoid**. Not all tools support them natively, but you can include them in your prompt.

### Common Negative Cues

**For realism:**
- "No CGI look, no artificial feel, no plastic skin"
- "No lens flare, no bloom, no HDR look"
- "No perfect symmetry, no sterile environment"

**For cinematography:**
- "No camera shake, no jittery movement"
- "No zoom — only physical camera movement"
- "No slow motion — real-time speed"

**For style:**
- "No anime style, no cartoon, no illustration"
- "No vintage filter, no Instagram look"
- "No oversaturated colors"

**For content:**
- "No text, no watermarks, no UI elements"
- "No people, no faces"
- "No pets, no animals"

### How to Use Negative Prompts

Place them at the end of your prompt, after a period or on a new line:

```
A sunrise over the ocean. Camera static, tripod-mounted.
No camera shake. No lens flare. No artificial saturation.
Shot on ARRI Alexa, natural color science.
```

---

## Common Mistakes and Fixes

### Mistake 1: Too Vague
**Bad:** "A beautiful sunset"
**Fix:** "A sunset over the Pacific Ocean from a cliff in Big Sur. Orange and pink clouds reflect on calm water. Camera static, wide angle. Golden hour, 20 minutes before sun disappears."

### Mistake 2: Too Many Actions
**Bad:** "A person walks in, sits down, eats dinner, talks to someone, gets up, and leaves"
**Fix:** Focus on ONE moment: "A person lifts a fork of pasta to their mouth at a candlelit restaurant. Shallow depth of field. Camera close-up on the fork and mouth."

### Mistake 3: Conflicting Descriptions
**Bad:** "A bright, dark, colorful, monochrome scene"
**Fix:** Choose a direction: "A dark scene with isolated warm highlights — only the candles and the subject's face are lit."

### Mistake 4: Ignoring Camera
**Bad:** "A dog running in a field"
**Fix:** "Camera tracks alongside a golden retriever running through a wheat field at sunset. 200mm telephoto, compressed perspective, background blur."

### Mistake 5: No Style Direction
**Bad:** "A city street"
**Fix:** "A rain-soaked Tokyo street at night. Neon signs reflect on wet asphalt. Wong Kar-wai color grade — warm amber, teal shadows. 35mm anamorphic lens."

### Mistake 6: Describing Impossible Things
**Bad:** "A person's face shows 47 different emotions in 3 seconds"
**Fix:** "A person's face shifts from confusion to realization to a small smile. Camera holds on close-up for the full duration."

### Mistake 7: Forgetting the Environment
**Bad:** "A woman dancing"
**Fix:** "A woman dances barefoot on a rooftop at dusk. City skyline behind her. Her dress catches the breeze. Warm ambient light from the setting sun."

---

## Quick Reference: The 30-Second Prompt Checklist

Before sending your prompt, check:

- [ ] **Subject**: Is it specific? (not "a thing" but "a red 1967 Ford Mustang")
- [ ] **Action**: Is there ONE clear action? (not a sequence of 10 actions)
- [ ] **Environment**: Where does this happen? (not "somewhere" but "in a foggy pine forest at dawn")
- [ ] **Camera**: How are we seeing this? (angle, movement, focal length)
- [ ] **Lighting**: What's the light doing? (golden hour, neon, overcast, candlelight)
- [ ] **Style**: What does it look like? (cinematic, anime, documentary, noir)
- [ ] **Quality**: How sharp/clean? (8K, film grain, macro detail)
- [ ] **No conflicts**: Nothing contradictory? (not "bright AND dark" without context)
- [ ] **Length**: Under 150 words? (shorter prompts often work better)
- [ ] **One focus**: Can you describe the video in one sentence? If not, simplify.

---

## Tool-Specific Notes

### Sora (OpenAI)
- **Strengths**: Long-form scenes, narrative, complex camera movements
- **Best practices**: Name cinematographers, reference films, describe camera precisely
- **Limitations**: Can struggle with text in video, multiple characters interacting

### Runway Gen-3
- **Strengths**: Motion graphics, abstract, style transfer, short clips
- **Best practices**: Keep prompts focused, name styles explicitly, use quality cues
- **Limitations**: Shorter clip lengths, less narrative capability

### Pika
- **Strengths**: Short social media content, animation styles, effects
- **Best practices**: Short prompts, one action, specify aspect ratio for social
- **Limitations**: Clip length limited, less photorealistic than Sora

### Kling
- **Strengths**: Human motion, hand fidelity, Chinese aesthetics, natural scenes
- **Best practices**: Describe human actions precisely, use cultural aesthetics
- **Limitations**: Less abstract/motion graphics capability
