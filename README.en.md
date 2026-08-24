<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 017 project banner" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 017

### Translate a photograph into bright, friendly Korean flat editorial illustration

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#four-outputs-one-korean-flat-logic)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#boundaries-and-trust)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> ROUNDED FORM · ROUGH BROKEN LINE · PURE FLAT FILL · BRIGHT FIELDS · LIVELY ASYMMETRY

XXD Panel 017 is an image-generation Skill for Codex and compatible agents. It preserves approximate source layout, object relations, core action, and at least three identity cues, then rebuilds them through rounded, slightly exaggerated forms, rough jittery locally broken black outlines, and high-value, high-purity flat fills.

One visual centre emerges through scale difference, offset, occlusion, light crop, large bright colour fields, whitespace, and imperfect asymmetry. Type follows contour, colour-block edge, whitespace, or picture axis as part of the illustration rather than an advertising headline pasted on later.

## Why it exists

“Flat children's illustration” easily collapses into generic cute characters, commercial stickers, fixed palettes, or template scenes that could accompany any photograph.

017 reverses that logic:

```text
lock layout / relations / action / three identity cues → simplify into rounded slightly exaggerated forms → draw rough jittery locally broken black outlines → use high-value high-purity flat fills → build one centre through scale / offset / occlusion / crop / whitespace → integrate title and microcopy into contour / colour edge / axis
```

If an unrelated photograph could replace the source without materially changing layout, relations, action, form, colour areas, or copy, the result is not 017.

## The 017 visual contract

- **Source identity:** preserve approximate layout, object relations, core action, and at least three specific cues; never replace the subject with a generic cute character.
- **Rounded simplification:** forms are simple and slightly exaggerated, with realistic light, perspective, and material detail removed while recognition remains immediate.
- **Rough broken outline:** black contours jitter, vary slightly, and break locally; no smooth vector edge or uniform comic inking.
- **Pure flat fill:** use clean opaque colour and express depth only through flat overlap, scale, and placement.
- **Bright source palette:** translate the photograph's most spirited colours into a limited high-value, high-purity set rather than a fixed blue-red-yellow-green card.
- **One visual centre:** scale, offset, occlusion, light crop, bright fields, whitespace, and imperfect asymmetry create a lively rhythm.
- **Illustrated type:** one short title and a few micro-notes follow contour, colour edge, whitespace, or axis, with restrained rotation, offset, split, or interlock.

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2090134963203223908) · 2026-08-19<br>
> GPT2 x 童趣 x 插画 x 笨拙 x 美学提示词 x VOL.017

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090134963203223908"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 017 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090134963203223908"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 017 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090134963203223908"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 017 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090134963203223908"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 017 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090134963203223908">View the original post and full prompt →</a></p>

These samples demonstrate the 017 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 017 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 017 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 017 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

## Copy must become part of the illustration

Before generation, choose automatic copy, custom copy, or text-free output. Name the target language or locale whenever copy is present.

Automatic copy distils one short title from subject, visible action, relation, established place, mood cue, or a grounded story relation. It binds tightly to this photograph and may create a quiet moment of recognition without inventing a story or forcing a pun.

The default is one title. Add zero to two short annotations only when they carry real information; never invent catalogue numbers, years, coordinates, or archival labels merely to look sophisticated. Copy must still pass the unrelated-image swap test.

Finished user wording stays verbatim. A direction or editable draft is refined only while preserving audience, purpose, mandatory words, tone, and implication.

Language follows the intended audience rather than the command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

A Japanese edition uses natural Japanese, a Korean-audience edition uses natural Korean and correct spacing, a UK edition uses British English, and Arabic defaults to natural Modern Standard Arabic with genuine right-to-left composition. The Skill never guesses nationality from appearance, clothing, scenery, or signs and never uses pseudo-foreign text.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-017.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-017" ~/.codex/skills/xxd-panel-017
```

Claude Code users may link the same directory to `~/.claude/skills/xxd-panel-017`. Restart the agent session after installation.

```text
$xxd-panel-017
Turn this photograph into a left-right composition. Derive the copy from the image and write it in natural Korean.
```

You may invoke the Skill with only a photograph. It first asks for one or more modes in a numbered multiline menu, then for copy settings; wallpaper mode also asks for linked/independent continuity and device sizes.

Full specifications:

- [Skill workflow](SKILL.md)
- [Chinese full prompt](references/xxd-panel-017-prompt.zh-CN.md)
- [English full prompt](references/xxd-panel-017-prompt.en.md)
- [Original style brief](references/017-source.md)

## Boundaries and trust

- Each photograph stays within its own task and never borrows subjects, colours, copy, or composition from other inputs, old results, or samples.
- Every invocation creates a fresh task directory; even identical sources and parameters must generate anew.
- Deliverables are PNG bitmaps, never SVG, HTML, Canvas, or programmatic-drawing substitutes.
- The configured bitmap bridge emits sanitised status only and does not expose providers, endpoints, headers, credentials, prompts, or response bodies.
- Each selected ordinary mode returns one file; selected `wallpaper-pack` adds four separate wallpapers. `all` returns seven PNGs per source across four sibling mode directories, never a contact sheet or overview.

Local composition needs Python 3 and Pillow. The safe bitmap bridge uses Python 3.11+ `tomllib`. Image generation still requires a host agent with built-in raster generation or an already configured compatible raster route.

## Repository

```text
xxd-panel-017/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/ (reserved for future local samples)
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-017-prompt.zh-CN.md
    ├── xxd-panel-017-prompt.en.md
    └── 017-source.md
```

## About XXD

XXD is the abbreviated brand name of Xiaoxiaodong. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and Membership

### In-depth Consultation · CNY 299/hour

One-to-one consultation for using the Skills is billed at CNY 299 per hour. Contact Xiaoxiaodong through the WeChat QR code below to book.

### Xiaoxiaodong Skills User Community · CNY 99 to join

A one-time CNY 99 fee joins the community for workflow sharing, work discussion, and peer support. It does not include hourly one-to-one consultation. Include “Skills User Community” in your WeChat message.

### Knowledge Planet + Member Prompt Library · CNY 699/year

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) and the [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) are one membership: **one annual payment unlocks both, with no second purchase required.**

1. Subscribe through [Knowledge Planet](https://wx.zsxq.com/group/15554814142882), then contact Xiaoxiaodong on WeChat for a Prompt Library redemption code.
2. Subscribe through the [Member Prompt Library](https://vip.xiaoxiaodong.ai/), then contact Xiaoxiaodong on WeChat for a Knowledge Planet invitation.

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD paid community WeChat QR code" width="320"></a>
</p>

<div align="center">

**Do not merely make the photograph cute: recognise it through fewer forms, brighter colour, and a freer broken line.**

</div>

---

<div align="center">
  <h2>☕ Support this open-source project</h2>
  <p>If this project saved you time, a Star, a share, or a coffee helps keep it moving.</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Support Xiaoxiaodong through Buy Me a Coffee" width="180"></a><br>
        <strong>Buy me a coffee</strong><br>
        <sub>Scan or open the QR code to support Xiaoxiaodong</sub>
      </td>
    </tr>
  </table>
  <p><sub>Support is entirely optional and never changes access to this open-source project.</sub></p>
</div>
