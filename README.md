# VTG Theme Pack [a11y.fy]

> **Curated & Engineered by Voltaire Toledo** for high-contrast accessibility and zero-glare, fatigue-free coding.  
> **Published by [Proventuras](https://proventuras.com)**.

[![Visual Studio Marketplace](https://img.shields.io/badge/VS_Code_Marketplace-a11y.fy-blue?logo=visual-studio-code)](https://marketplace.visualstudio.com)
[![WCAG Level](https://img.shields.io/badge/WCAG_Compliance-Level_AAA_%2F_AA+-success)](#the-a11yfy-standard)
[![Author](https://img.shields.io/badge/Author-Voltaire_Toledo-ff75a0)](https://proventuras.com)

---

## Why [a11y.fy]?

Standard community dark themes are aesthetically pleasing but frequently suffer from severe visual accessibility defects:
* **The "Invisible Text" Trap**: Muted pastel status bars with white text yielding barely **1.47:1** contrast (failing WCAG).
* **Flat Panel Mud**: The Activity Bar, Sidebar, and Editor canvas sharing the exact same dark hex, creating a flat smear in ambient room lighting.
* **Ghost Comments & Dark Blue Drowning**: Murky olive comments and deep navy properties that disappear into dark backgrounds.
* **The "High Contrast" Harshness**: Built-in OS high-contrast themes often resort to neon-green borders and stark, blinding pure-black boxes.

**VTG Theme Pack `[a11y.fy]` solves this.** It applies **Accessibility Color Remediation** to the most popular community themes, precision-tuning them to **WCAG AAA (~7.0:1–11.0:1)** standards using subtle luminance stepping and luminous syntax tokens—without harsh borders or jarring neon outlines.

---

## Included Themes in the Pack

All editions retain the soul of the original design while eliminating visual fatigue:

| Theme Name | Focus & Calibration |
| :--- | :--- |
| **Pink Cat Boo [a11y.fy]** | Seamless `#302f42` window-blended status bar, luminous sky blue properties (`#93d5f8`), and silver-lavender comments (`#a2a8c2` at 6.2:1). |
| **Catppuccin Mocha [a11y.fy]** | Enhanced pastel definition and elevated gutter/comment contrast. |
| **Catppuccin Macchiato [a11y.fy]** | Mid-dark flavor with heightened token separation. |
| **Catppuccin Frappé [a11y.fy]** | Low-glare muted slate with WCAG AAA token calibrations. |
| **Tokyo Night [a11y.fy]** | Tokyo downtown neon palette with boosted comment and property contrast. |
| **Tokyo Night Storm [a11y.fy]** | Calibrated blue-gray canvas with high-legibility terminal ANSI palette. |
| **Dracula [a11y.fy]** | Iconic gothic contrast without eye-straining gutter washout. |
| **Dracula Soft [a11y.fy]** | Softened background with enhanced token legibility. |
| **One Dark Pro [a11y.fy]** | Atom-inspired classic with lifted dark blue properties and clean inactive tabs. |
| **One Dark Pro Darker [a11y.fy]** | Deep charcoal canvas with high-contrast UI chrome. |
| **Gruvbox Material Dark [a11y.fy]** | Warm retro-earthy palette with calibrated syntax luminances. |
| **SynthWave '84 [a11y.fy]** | Retro 80s outrun aesthetic tuned for daylight legibility. |

---

## The [a11y.fy] Standard

1. **Status Bar Comfort**: Eliminates uncalibrated glaring backgrounds; balances text to **WCAG AAA (>7.0:1)**.
2. **Luminous Sky Blues**: Replaces dark navy properties that drown on dark displays with clear sky blues (`#93d5f8`).
3. **Legible Comments**: Every comment scope is guaranteed at least **WCAG AA+ (>5.0:1)**.
4. **Git Decoration Legibility**: Canary yellow (`#fde047`) and emerald green (`#4ade80`) ensure modified/untracked files in the Explorer tree remain crisp even when out of focus.
5. **Tone Stepping Over Harsh Borders**: Clean, borderless visual hierarchy separating rails, sidebars, and workspaces.

---

## Interactive Comparison Landing Page

An interactive before-and-after comparison slider is available in [`docs/index.html`](./docs/index.html). Open it in any modern browser to inspect real-time split testing between original themes and the `[a11y.fy]` editions.

---

## Development & Local Installation

### Package Offline `.vsix`
```bash
npx @vscode/vsce package
```

### Install Locally
```bash
code --install-extension vtg-pub-vscode-themes-0.1.0.vsix
```

---

## Authors & Credits

* **Engineering & Curation**: [Voltaire Toledo](https://proventuras.com)
* **Publisher**: [ProVenturas](https://proventuras.com)
* **License**: MIT
