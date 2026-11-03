---
name: soda-product-generator
description: Generate original soda product concepts and production-ready visual directions for carbonated soft drinks. Use when the user wants soda brand names, flavors, can or bottle packaging, labels, product renders, advertising concepts, flavor systems, launch assets, or soda-focused image prompts.
---

# Soda Product Generator

Create original products for **soda and carbonated soft drinks only**. Treat each request as a product-development and visual-branding task, not as a general food-and-beverage task.

## Scope

Include:

- Carbonated soft-drink brands and sub-brands
- Flavors, formulas at a high conceptual level, serving ideas, and variant systems
- Cans, bottles, multipacks, cartons, labels, caps, shrink sleeves, and point-of-sale packaging
- Product renders, shelf mockups, campaign key art, social ads, launch posters, and e-commerce imagery
- Brand names, taglines, color systems, typography direction, flavor architecture, and packaging copy

Do not generate non-soda product lines. Do not present invented nutrition facts, certifications, health claims, or regulatory approvals as factual. Flag regulatory review when copy includes ingredients, allergens, caffeine, functional claims, or age-sensitive marketing.

## Core workflow

Work incrementally and make the product commercially coherent:

1. **Define the brief.** Identify target audience, market or region, flavor, format, desired mood, price tier, and primary deliverable. If a choice materially changes the result, ask one focused clarification; otherwise make a sensible assumption and state it.
2. **Build the product concept.** Create a distinctive name, flavor description, positioning, short tagline, and a compact visual direction. Avoid confusing similarity to existing brands, logos, or trade dress.
3. **Design the package system.** Specify container format, front-panel hierarchy, logo treatment, flavor cue, color palette, pattern or illustration language, finish, and required visible text. Keep the flavor instantly legible.
4. **Create the requested asset.** For visual generation, read and follow the image-generation skill before generating. Use one final image per requested asset unless the user explicitly asks for a sheet or variations.
5. **Quality-check.** Confirm that the result clearly reads as soda, the product name and flavor are consistent, text is not misleading, packaging is physically plausible, and no unrelated beverage category has entered the design.
6. **Deliver clearly.** State what was created, include the exact file path for generated assets, and give the next useful product-development step.

## Product concept defaults

When details are missing, use these defaults:

- Category: sparkling carbonated soft drink
- Format: 330 ml slim can for a hero product, or 500 ml PET bottle for an everyday variant
- Positioning: modern, accessible premium
- Flavor: a clear fruit or botanical flavor with a recognizable color cue
- Audience: broad adult audience unless the user specifies otherwise
- Visual style: bold, shelf-readable, contemporary, high contrast, with a simple repeatable graphic device
- Tone: refreshing, optimistic, sensory, and concise

Use flavor names that communicate the taste quickly. Distinguish the product through a memorable combination of flavor, color, typography, and pack structure rather than by copying a famous soda identity.

## Packaging design checklist

Every packaging concept should consider:

- Brand name and logo placement
- Product descriptor such as “sparkling soda” or “carbonated soft drink”
- Flavor name and a clear visual flavor cue
- Container silhouette, proportions, closure, and material
- Front, side, and top/back information zones when a full pack view is requested
- Contrast and legibility at shelf distance and thumbnail size
- Color palette with primary, secondary, and accent colors in HEX when useful
- Print finish: matte, gloss, metallic ink, spot varnish, emboss, or transparent label
- Consistent family system for future flavors
- Plausible legal and informational placeholders without fabricating facts

Do not place dense tiny text into a generated hero image. For production mockups, use short readable copy and identify any remaining copy as placeholder text.

## Visual-generation instructions

When generating soda product imagery:

- Read the image-generation skill first.
- Specify camera angle, lens feel, composition, container geometry, condensation, lighting, background, surface, and brand mood.
- Keep the can or bottle as the hero subject and preserve label geometry.
- Use realistic materials: anodized aluminum, clear PET, glass, ink, varnish, foil, and water droplets as appropriate.
- Request accurate, minimal package text. If exact typography is important, generate the visual without small text and add final copy in a design tool afterward.
- State exclusions: no unrelated beverages, no extra logos, no illegible pseudo-text, no distorted cans or bottles.
- For isolated pack assets, prefer a clean background or transparent PNG when supported. For advertising key art, use 16:9 unless another aspect ratio is requested. For e-commerce pack shots, use a centered 1:1 or 4:5 composition.
- Save generated assets under a descriptive path such as `Art/Soda/Products/`, `Art/Soda/Packaging/`, or `Art/Soda/Campaigns/`.

### Reusable visual prompt structure

```text
Commercial product photograph of an original [flavor] sparkling soda in a [container format], branded “[brand name]”, [packaging design language], clear readable flavor cue, [color palette], realistic [material and finish], tiny condensation droplets, [lighting], [background], premium advertising composition, physically accurate proportions, no unrelated products, no extra logos, no illegible text.
```

## Naming and copy rules

Generate several names only when the user asks for options; otherwise provide one strong recommendation. Names should be pronounceable, distinctive, and suitable for a soda line. Avoid claims such as “healthy,” “detox,” “zero sugar,” “natural,” “organic,” “energy,” or “functional” unless the user supplied verified product facts and asks for compliant copy.

Keep copy concise:

- Product descriptor: 2–5 words
- Flavor line: 1–4 words
- Tagline: ideally under 8 words
- Back-of-pack story: 1–3 short sentences

Mark unverified details as placeholders, for example: `[ingredients pending]`, `[nutrition panel pending]`, or `[local compliance review]`.

## Persian-only design mode

When the user asks for Persian text or a Persian-language design, write every visible package word in Persian script only. Do not add English, Latin letters, Arabic numerals, pseudo-text, or unrelated logos. Keep the package copy short and exact; prefer one brand name, one product descriptor, one flavor line, and one short tagline. Use culturally coherent visual cues such as Persian geometric patterns, but avoid copying existing brands or trade dress.

Use this bundled reference concept as a visual direction when helpful: `templates/examples/bahar-pomegranate-lemon-persian.png`.

Reference concept: «بهار»، نوشابه گازدار با طعم «انار و لیمو»، با شعار «طراوت هر لحظه»؛ قوطی قرمز اناری با نقش هندسی فیروزه‌ای و جزئیات طلایی. Treat the reference as inspiration, not a fixed brand identity, and adapt the flavor, palette, and copy to the user's brief.

## Output format

Use the following compact structure for product concepts:

```markdown
## Soda Product: [name]

**Format:** [can or bottle]
**Flavor:** [flavor]
**Positioning:** [one sentence]
**Tagline:** [short line]

### Packaging direction
- **Hero colors:** [colors / HEX]
- **Graphics:** [pattern, illustration, or texture]
- **Typography:** [direction]
- **Finish:** [material / print finish]
- **Front-panel copy:** [short copy]

### Visual asset
**Purpose:** [hero render, pack shot, campaign key art, etc.]
**File:** [absolute Markdown link when generated]

### Quality check
[brief note on readability, plausibility, and any placeholder or compliance items]

### Next step
[next product, variant, or asset]
```

For a direct image request, prioritize the generated asset and provide only the brief concept context needed to use it. For a brand-system request, show how at least three flavors can share the same packaging architecture while remaining immediately distinguishable.
