# Contributing to Awesome Video Prompts

Thank you for your interest in contributing! This guide explains how to add prompts, fix issues, and improve the collection.

## How to Contribute

### Adding a Prompt

1. Fork the repository
2. Choose the correct tool folder (`Sora/`, `Runway/`, `Pika/`, `Kling/`)
3. Pick the appropriate category file
4. Follow the prompt format below
5. Submit a Pull Request

### Prompt Format

Every prompt entry MUST follow this template:

```markdown
### [Prompt Title]
**Prompt:** [The exact prompt text to copy-paste into the tool]

**Settings:** [Aspect ratio, duration, model version if applicable]

**Expected result:** [1-2 sentence description of what the video should look like]

**Variations:**
- [Alternative version 1 - change one variable]
- [Alternative version 2 - change a different variable]
```

### Quality Standards

A good prompt is:

- **Specific** - Not "a cat walking" but "a ginger tabby cat walking slowly along a rain-soaked cobblestone alley at dusk, paw prints visible in puddles"
- **Reproducible** - Someone else using this prompt should get a similar result
- **Practical** - Describes things the tool can actually generate
- **Formatted** - Follows the template exactly

### Commit Messages

Use conventional commits:

- `feat(sora): add underwater cinematography prompts`
- `fix(runway): correct prompt format in motion-graphics.md`
- `docs: update README with new tool support`

### Code of Conduct

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before contributing.

## Questions?

Open an issue with the `question` label.
