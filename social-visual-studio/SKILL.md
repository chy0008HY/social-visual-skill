---
name: social-visual-studio
description: Plan and produce social-media carousel visuals plus natural, human-sounding copy by coordinating the installed baoyu-xhs-images and humanizer skills. Use for Instagram, Xiaohongshu, Facebook, LinkedIn, or similar social posts that need a hook, card-by-card narrative, captions, calls to action, image-card generation, or final copy polishing.
---

# Social Visual Studio

Create one coherent social package: strategy, card copy, generated image cards, caption, and final quality checks.

## Route the request

- For carousel or image-card production, use `baoyu-xhs-images`.
- For copy-only editing, use `humanizer` without loading the visual workflow.
- For a complete social package, use both in the sequence below.
- Do not load optional references from either dependency unless the selected workflow requires them.

## Complete package workflow

1. Establish the platform, audience, objective, language, card count, desired action, and brand constraints. If unspecified, infer reversible defaults and state them before generation.
2. Extract only facts supplied by the user or supported by cited sources. Never invent claims, numbers, testimonials, or product benefits.
3. Draft the narrative before rendering:
   - Card 1: specific hook or tension.
   - Middle cards: one clear idea each, ordered as problem, insight, proof, or action.
   - Final card: concise takeaway and one call to action.
   - Caption: complementary context rather than a transcript of every card.
4. Apply `humanizer` to all approved on-card copy and the caption. Preserve every factual claim. If the user supplies a voice sample, match it. Freeze on-card wording after this step.
5. Use `baoyu-xhs-images` to plan and generate the cards. Follow its confirmation, prompt-file, image-backend, reference-image, and batch-generation requirements. Prefer Codex's native `imagegen` backend when available.
6. Inspect the generated cards for text accuracy, legibility, visual continuity, reading order, safe margins, and platform-appropriate aspect ratio. Regenerate flawed images; never paint replacement text over a rendered bitmap.
7. Deliver:
   - final caption and CTA;
   - card-by-card copy outline;
   - generated image files and prompt files;
   - the selected style, layout, palette, aspect ratio, and assumptions.

## Quality bar

- Lead with a concrete idea, not generic hype.
- Keep each card readable at mobile size.
- Avoid duplicated sentences across caption and cards.
- Use one consistent audience, tone, visual language, and CTA.
- Preserve the source language unless the user requests translation.
- Stop before publishing to an external platform unless the user explicitly authorizes publication.

## Dependencies and attribution

This orchestration skill depends on separately installed third-party skills. Read [references/sources.md](references/sources.md) only when installing, redistributing, auditing, or updating dependencies.
