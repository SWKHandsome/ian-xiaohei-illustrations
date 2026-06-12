# Chibi Character Prompt Template

## 1) Core use cases

Use this template for:
- Profile icon / avatar generation
- Character mood variants (same identity, different expression)
- Small-pack icon sets for personal branding
- Lightweight reaction/marker assets consistent with project style

---

## 2) Prompt structure (copy and fill)

```text
Generate one original square chibi character icon.

Character identity:
{character name/label}
{core personality in 1-2 lines}

Visual style requirements:
Soft painterly anime style, semi-watercolor texture, visible painterly brush strokes, soft diffused lighting, gentle highlights, no harsh shadows.
Pastel and slightly muted cool palette (soft blue, teal, muted purple).

Design requirements:
- Chibi proportion with large head and small body
- Relaxed slightly sleepy expression, half-lidded eyes
- Original short slightly messy layered hairstyle with soft edges
- Original stylized tech-themed headphone/head accessory (no real product copy)
- Optional abstract redesigned animal-inspired ear shapes
- Small floating decorative symbols/shapes for personality

Composition and background:
Square format, centered composition, icon readability at small size.
Transparent or simple clean background.

Originality constraints:
Completely original work. Do not copy existing characters, artworks, or copyrighted designs. Do not imitate specific artists.

Output:
PNG, high resolution (recommended 1024x1024).
```

---

## 3) Technical specifications

- Aspect ratio: **1:1 (square)**
- Recommended resolution: **1024×1024** (minimum 512×512)
- File format: **PNG**
- Background: transparent preferred, or simple clean background
- Small-size check: must remain readable at **64px** and **128px**
- Style consistency: painterly texture and soft lighting must remain visible

---

## 4) Integration with existing skill workflow

When user requests chibi icons in this repo workflow:
1. Read `references/chibi-style-guide.md`
2. Use this template to construct a single-icon prompt
3. Generate one icon per prompt (avoid collage)
4. Save outputs under `assets/chibi-character-icons/`
5. Run QA using the checklist below before delivery

If task also includes main article illustrations:
- Keep chibi assets as identity/support visuals
- Keep 16:9 Xiaohei conceptual illustrations in their existing template flow

---

## 5) Chibi QA checklist

Must-pass checks:
- [ ] Square composition, centered subject
- [ ] Chibi proportion (head clearly larger than body)
- [ ] Half-lidded relaxed expression is visible
- [ ] Cool pastel palette (blue/teal/muted purple family)
- [ ] Painterly brush feel is visible (not clean vector output)
- [ ] Accessory is original and non-branded
- [ ] No derivative character/IP resemblance
- [ ] Readable at small avatar sizes
- [ ] PNG exported to the target path

Failure signals:
- Looks like a copied franchise mascot
- Hard-edged vector icon look with no painterly texture
- Harsh contrast or heavy dramatic shadows
- Too many details that collapse at 64px

---

## 6) Consistency best practices across variants

- Keep the same silhouette family (hair shape + accessory motif)
- Lock 2-3 core colors and rotate only one accent
- Keep eye shape/spacing stable across expressions
- Limit per-variant changes to one major variable (expression OR pose OR accessory detail)
- Maintain same framing distance to keep icon set coherent

---

## 7) Appropriate vs inappropriate approaches

### Appropriate
- “Same character, sleepy-to-focused expression variants, unchanged hairstyle silhouette.”
- “One original abstract headphone motif reused with minor color/material changes.”
- “Painterly soft-edge rendering with subtle floating symbols and clean background.”

### Inappropriate
- “Copy this famous anime character but change colors.”
- “Match a specific artist’s exact style and line treatment.”
- “Use a real branded headphone shape/logo.”
- “Add dense background scene and many tiny details unreadable at avatar size.”
