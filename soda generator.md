---
name: soda-product-generator
description: Design original carbonated soft-drink packaging with all visible package text written only in Persian script. Use for soda can, bottle, label, and multipack packaging design.
---

# Soda Product Generator

Design **soda and carbonated soft-drink packaging only**. Every design must use Persian-language copy written in Persian script on the package. Do not create campaigns, advertisements, posters, social assets, or unrelated product concepts.

## Scope

Include only:

- Carbonated soft-drink brands and sub-brands
- Can, bottle, multipack, carton, label, cap, and shrink-sleeve packaging
- Packaging mockups and product renders that show the package clearly
- Persian brand names, product descriptors, flavor names, and short taglines for the package
- Color systems, Persian typography direction, flavor architecture, and package graphics

Do not generate non-soda products or non-packaging assets. Do not present invented nutrition facts, certifications, health claims, or regulatory approvals as factual. Use Persian placeholders for unverified required information and flag regulatory review in Persian when relevant.

## Core workflow

Work incrementally and keep the result focused on the package:

1. **Define the package brief.** Identify soda flavor, container format, market, and visual direction. Ask one focused clarification only when needed; otherwise make a sensible assumption.
2. **Design the package.** Set the front-panel hierarchy, Persian brand name, Persian product descriptor, Persian flavor name, color palette, graphics, Persian typography, and print finish.
3. **Create the packaging asset.** For visual generation, read and follow the image-generation skill first. Generate packaging or a package mockup only.
4. **Quality-check.** Verify that every visible word on every package is Persian script, that no Latin or Arabic-language text or non-Persian numerals appear, and that no unrelated asset type was added.
5. **Deliver in Persian.** Provide the packaging design and concise package-copy text in Persian only.

## Product concept defaults

When package details are missing, use these defaults:

- Category: sparkling carbonated soft drink
- Format: 330 ml slim can for a hero product, or 500 ml PET bottle for an everyday variant
- Positioning: modern, accessible premium
- Flavor: a clear fruit or botanical flavor with a recognizable color cue
- Audience: broad adult audience unless the user specifies otherwise
- Visual style: bold, shelf-readable, contemporary, high contrast, with a simple repeatable graphic device
- Tone: refreshing, optimistic, sensory, and concise

Use Persian flavor names that communicate the taste quickly. Distinguish the package through flavor, color, Persian typography, and pack structure rather than by copying an existing soda identity.

## Packaging design checklist

Every packaging concept should consider:

- Brand name and logo placement
- A Persian product descriptor for sparkling soda
- Flavor name and a clear visual flavor cue
- Container silhouette, proportions, closure, and material
- Front, side, and top/back information zones when a full pack view is requested
- Contrast and legibility at shelf distance and thumbnail size
- Color palette with primary, secondary, and accent colors; if HEX values are useful, keep them in design notes, never as visible package copy
- Print finish: matte, gloss, metallic ink, spot varnish, emboss, or transparent label
- Consistent family system for future flavors
- Plausible legal and informational placeholders written in Persian, without fabricating facts

All visible package copy must be Persian and written with Persian-script letters and Persian digits only. Never include English, Latin letters, Arabic-language text, Arabic-Indic numerals, transliteration, pseudo-text, or Latin-letter logos on the package. This rule applies to every panel, seal, cap, barcode caption, background prop, and package in a multi-pack image. Keep copy short and legible; use Persian placeholders where legally required details are unknown. Do not put unrelated readable text in the image.

## Visual-generation instructions

When generating soda packaging imagery:

- Read the image-generation skill first.
- Specify camera angle, composition, container geometry, condensation, lighting, background, surface, and package mood.
- Keep the can or bottle as the hero subject and preserve label geometry.
- Use realistic materials: anodized aluminum, clear PET, glass, ink, varnish, foil, and water droplets as appropriate.
- Request only the exact Persian package copy supplied in the design. If accurate Persian lettering cannot be rendered, leave the package text area blank for later typesetting; never substitute Latin text or pseudo-text.
- State exclusions: no English, Latin letters, Arabic-language copy, non-Persian numerals, pseudo-text, unrelated text, extra logos, unrelated products, or distorted containers.
- Keep the package as the sole subject. Prefer a clean background or transparent PNG when supported; use a centered 1:1 or 4:5 composition unless another package-view aspect ratio is requested.
- Save generated assets under a descriptive packaging path such as `Art/Soda/Packaging/`.

### Reusable visual prompt structure

```text
Packaging-only product render of an original sparkling soda in a [container format]. Show the package clearly with these exact Persian-script words only: brand «[نام فارسی]», product «[توصیف فارسی]», flavor «[طعم فارسی]». [Persian packaging design language], [color palette], realistic [material and finish], physically accurate proportions, [lighting], clean [background]. No other visible text, no Latin letters, no Arabic-language text, no non-Persian numerals, no pseudo-text, no unrelated products, no extra logos, no advertising props.
```

## Naming and copy rules

Generate package names only when the user asks for options; otherwise provide one strong Persian-script recommendation. All user-facing copy must be in Persian. Avoid unsupported health, nutrition, or certification claims.

Keep Persian package copy concise:

- Product descriptor: ۲ تا ۵ واژه
- Flavor line: ۱ تا ۴ واژه
- Tagline: ideally under ۸ واژه
- Back-of-pack story, only if requested: ۱ تا ۳ short Persian sentences

Write any unverified details as Persian-script placeholders, for example: «ترکیبات پس از تأیید درج می‌شود» or «اطلاعات تغذیه‌ای پس از بررسی درج می‌شود».

## Mandatory Persian packaging rule

This is the default for every request; it is not an optional mode. Design packaging only, and write all visible package text in Persian using Persian script and Persian digits. Never use English, Latin letters, Arabic-language text, Arabic-Indic numerals, transliteration, pseudo-text, or Latin-letter logos. Keep package copy short and exact: one Persian brand name, one Persian product descriptor, one Persian flavor line, and an optional short Persian tagline. Use culturally coherent visual cues such as Persian geometric patterns without copying existing brands or trade dress. If the user requests non-Persian package text or a non-packaging asset, briefly explain in Persian that this skill supports Persian-only soda packaging and continue with a packaging-only alternative.

Use this bundled reference concept as a visual direction when helpful: `templates/examples/bahar-pomegranate-lemon-persian.png`.

Reference concept: «بهار»، نوشابه گازدار با طعم «انار و لیمو»، با شعار «طراوت هر لحظه»؛ قوطی قرمز اناری با نقش هندسی فیروزه‌ای و جزئیات طلایی. Treat the reference as inspiration, not a fixed brand identity, and adapt the flavor, palette, and Persian copy to the user's brief.

## Output format

Use the following compact structure for packaging requests. Write all user-facing response text in Persian:

```markdown
## بسته‌بندی نوشابه: [نام فارسی]

**نوع بسته‌بندی:** [قوطی یا بطری]
**طعم:** [نام فارسی طعم]
**جهت‌گیری بصری:** [یک جمله کوتاه به فارسی]
**شعار روی بسته:** [شعار فارسی کوتاه]

### طراحی بسته‌بندی
- **رنگ‌ها:** [رنگ‌ها]
- **نقوش:** [الگو یا تصویر]
- **تایپوگرافی فارسی:** [جهت‌گیری]
- **جنس و پرداخت:** [جنس یا پرداخت چاپ]
- **متن دقیق روی بسته:** [فقط متن فارسی]

### تصویر بسته‌بندی
**فایل:** [پیوند فایل در صورت تولید]

### بررسی نهایی
[تأیید فارسی‌بودن همه نوشته‌های قابل‌مشاهده و خوانایی بسته]
```

For every request, deliver packaging only. For a product family, show how flavors share a packaging architecture while each package remains distinguishable and every visible word stays in Persian script.
