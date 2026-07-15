---
version: alpha
name: NemoVideo
description: Exact design tokens from the current Nemo Video codebase. Normative source is packages/design/src/styles/globals.css and packages/design/tailwind.config.js.
colors:
  brand-1: "hsl(217 100% 60%)"
  brand-2: "hsl(217 100% 63%)"
  brand-3: "hsl(217 100% 65%)"
  brand-4: "hsl(217 100% 75%)"
  brand-5: "hsl(217 100% 87%)"
  brand-6: "hsl(217 100% 93%)"
  brand-7: "hsl(217 100% 97%)"

  text-1: "hsl(221 33% 11%)"
  text-2: "hsl(215 14% 34%)"
  text-3: "hsl(220 9% 46%)"
  text-4: "hsl(218 11% 65%)"
  line-1: "hsl(220 13% 93%)"
  mask-1: "hsl(0 0% 0% / 0.4)"

  gray-1: "hsl(220 14% 99%)"
  gray-2: "hsl(210 20% 98%)"
  gray-3: "hsl(220 14% 96%)"
  gray-4: "hsl(220 13% 93%)"
  gray-5: "hsl(216 12% 84%)"
  gray-6: "hsl(218 11% 65%)"
  gray-7: "hsl(220 9% 46%)"
  gray-8: "hsl(215 14% 34%)"
  gray-9: "hsl(217 19% 27%)"
  gray-10: "hsl(215 25% 17%)"
  gray-11: "hsl(221 33% 11%)"

  info-1: "hsl(217 100% 97%)"
  info-2: "hsl(217 100% 87%)"
  info-3: "hsl(217 100% 75%)"
  info-4: "hsl(217 100% 65%)"
  info-5: "hsl(217 100% 63%)"
  info-6: "hsl(213 100% 55%)"

  success-1: "hsl(140 60% 98%)"
  success-2: "hsl(145 80% 96%)"
  success-3: "hsl(141 79% 90%)"
  success-4: "hsl(145 75% 81%)"
  success-5: "hsl(145 65% 67%)"
  success-6: "hsl(152 69% 52%)"
  success-7: "hsl(154 82% 39%)"
  success-8: "hsl(158 96% 30%)"
  success-9: "hsl(160 96% 24%)"
  success-10: "hsl(155 90% 20%)"
  success-11: "hsl(153 88% 17%)"

  warning-1: "hsl(45 100% 98%)"
  warning-2: "hsl(45 100% 96%)"
  warning-3: "hsl(43 96% 89%)"
  warning-4: "hsl(43 98% 77%)"
  warning-5: "hsl(40 99% 65%)"
  warning-6: "hsl(36 98% 56%)"
  warning-7: "hsl(33 94% 50%)"
  warning-8: "hsl(28 96% 44%)"
  warning-9: "hsl(24 91% 37%)"
  warning-10: "hsl(21 84% 31%)"
  warning-11: "hsl(18 80% 27%)"

  error-1: "hsl(10 100% 99%)"
  error-2: "hsl(6 100% 97%)"
  error-3: "hsl(4 100% 94%)"
  error-4: "hsl(4 93% 89%)"
  error-5: "hsl(4 89% 80%)"
  error-6: "hsl(4 92% 69%)"
  error-7: "hsl(4 86% 58%)"
  error-8: "hsl(4 74% 49%)"
  error-9: "hsl(4 76% 40%)"
  error-10: "hsl(4 68% 33%)"
  error-11: "hsl(4 64% 29%)"

  fill-1: "hsl(217 100% 60%)"
  fill-2: "hsl(220 14% 96%)"
  background: "hsl(210 20% 98%)"
  foreground: "{colors.text-1}"
  border: "{colors.line-1}"
  input: "{colors.line-1}"
  ring: "{colors.brand-1}"
  card: "{colors.background}"
  card-foreground: "{colors.text-1}"
  popover: "{colors.background}"
  popover-foreground: "{colors.text-1}"
  primary: "{colors.brand-1}"
  primary-foreground: "{colors.gray-1}"
  secondary: "{colors.gray-3}"
  secondary-foreground: "{colors.text-1}"
  destructive: "{colors.error-7}"
  destructive-foreground: "{colors.gray-1}"
  muted: "{colors.gray-2}"
  muted-foreground: "{colors.text-3}"
  accent: "{colors.brand-6}"
  accent-foreground: "{colors.brand-1}"

  dark-brand-1: "hsl(217 100% 65%)"
  dark-brand-2: "hsl(217 100% 68%)"
  dark-brand-3: "hsl(217 100% 70%)"
  dark-brand-4: "hsl(217 100% 80%)"
  dark-brand-5: "hsl(217 100% 90%)"
  dark-brand-6: "hsl(217 100% 95%)"
  dark-brand-7: "hsl(217 100% 98%)"
  dark-text-1: "hsl(220 14% 96%)"
  dark-text-2: "hsl(216 12% 84%)"
  dark-text-3: "hsl(218 11% 65%)"
  dark-text-4: "hsl(224 10% 45%)"
  dark-line-1: "hsl(224 12% 18%)"
  dark-mask-1: "hsl(0 0% 0% / 0.7)"
  dark-gray-1: "hsl(220 17% 7%)"
  dark-gray-2: "hsl(225 14% 11%)"
  dark-gray-3: "hsl(224 12% 18%)"
  dark-gray-4: "hsl(222 10% 32%)"
  dark-gray-5: "hsl(224 10% 45%)"
  dark-gray-6: "hsl(218 11% 65%)"
  dark-gray-7: "hsl(216 12% 84%)"
  dark-gray-8: "hsl(220 13% 93%)"
  dark-gray-9: "hsl(220 14% 96%)"
  dark-gray-10: "hsl(210 20% 98%)"
  dark-gray-11: "hsl(220 14% 99%)"
  dark-info-1: "hsl(217 100% 98%)"
  dark-info-2: "hsl(217 100% 90%)"
  dark-info-3: "hsl(217 100% 80%)"
  dark-info-4: "hsl(217 100% 70%)"
  dark-info-5: "hsl(217 100% 68%)"
  dark-info-6: "hsl(213 100% 60%)"
  dark-success-1: "hsl(153 88% 20%)"
  dark-success-2: "hsl(155 90% 23%)"
  dark-success-3: "hsl(160 96% 27%)"
  dark-success-4: "hsl(158 96% 33%)"
  dark-success-5: "hsl(154 82% 42%)"
  dark-success-6: "hsl(152 69% 55%)"
  dark-success-7: "hsl(145 65% 70%)"
  dark-success-8: "hsl(145 75% 84%)"
  dark-success-9: "hsl(141 79% 92%)"
  dark-success-10: "hsl(145 80% 97%)"
  dark-success-11: "hsl(140 60% 99%)"
  dark-warning-1: "hsl(18 80% 30%)"
  dark-warning-2: "hsl(21 84% 34%)"
  dark-warning-3: "hsl(24 91% 40%)"
  dark-warning-4: "hsl(28 96% 47%)"
  dark-warning-5: "hsl(33 94% 53%)"
  dark-warning-6: "hsl(36 98% 59%)"
  dark-warning-7: "hsl(40 99% 68%)"
  dark-warning-8: "hsl(43 98% 80%)"
  dark-warning-9: "hsl(43 96% 91%)"
  dark-warning-10: "hsl(45 100% 97%)"
  dark-warning-11: "hsl(45 100% 99%)"
  dark-error-1: "hsl(4 64% 32%)"
  dark-error-2: "hsl(4 68% 36%)"
  dark-error-3: "hsl(4 76% 43%)"
  dark-error-4: "hsl(4 74% 52%)"
  dark-error-5: "hsl(4 86% 61%)"
  dark-error-6: "hsl(4 92% 72%)"
  dark-error-7: "hsl(4 89% 83%)"
  dark-error-8: "hsl(4 93% 91%)"
  dark-error-9: "hsl(4 100% 95%)"
  dark-error-10: "hsl(6 100% 98%)"
  dark-error-11: "hsl(10 100% 99%)"
  dark-fill-1: "hsl(217 100% 65%)"
  dark-fill-2: "hsl(224 12% 18%)"
  dark-background: "hsl(220 17% 7%)"

  website-brand1-1: "rgb(232 243 255)"
  website-brand1-2: "rgb(190 218 255)"
  website-brand1-3: "rgb(148 191 255)"
  website-brand1-4: "rgb(106 161 255)"
  website-brand1-5: "rgb(64 128 255)"
  website-brand1-6: "rgb(22 93 255)"
  website-brand1-7: "rgb(14 66 210)"
  website-purple: "#7145FE"
  website-logo-blue: "#308DFF"
  website-logo-cyan: "#38ADFF"
  website-logo-indigo: "#687CFF"
  website-logo-violet: "#6445FF"
  website-logo-magenta: "#AE62FF"

gradients:
  product-brand: "linear-gradient(135deg, #3369ff 0%, #101828 100%)"
  shimmer-light: "linear-gradient(90deg, hsl(var(--gray-11)) 0%, hsl(var(--gray-11)) 40%, hsl(var(--gray-6)) 50%, hsl(var(--gray-11)) 60%, hsl(var(--gray-11)) 100%)"
  shimmer-dark: "linear-gradient(90deg, hsl(var(--gray-9)) 0%, hsl(var(--gray-9)) 40%, hsl(var(--gray-7)) 50%, hsl(var(--gray-9)) 60%, hsl(var(--gray-9)) 100%)"
  video-controls-overlay: "linear-gradient(180deg, rgba(0,0,0,0) 0%, rgba(0,0,0,0.4) 60%, rgba(0,0,0,0.75) 100%)"
  think-shine: "linear-gradient(90deg, transparent 0%, rgba(255, 255, 255, 0.8) 50%, transparent 100%)"
  glow-border-conic: "conic-gradient(from var(--glow-angle, 0deg), #67e8f9, #22d3ee, #06b6d4, #a78bfa, #8b5cf6, #c4b5fd, #a78bfa, #22d3ee, #67e8f9)"
  mobile-upload-background: "linear-gradient(to bottom, hsl(var(--gray-1)) 0%, hsl(var(--info-2)) 100%)"
  dotted-background-light: "radial-gradient(hsl(var(--gray-5)) 1px, transparent 1px)"
  dotted-background-dark: "radial-gradient(hsl(var(--gray-3)) 1px, transparent 1px)"
  top-scroll-mask: "linear-gradient(to bottom, black, transparent)"
  gallery-scroll-mask: "linear-gradient(to bottom, transparent 0px, black 48px)"
  ai-panel-light: "linear-gradient(180deg, rgba(91, 238, 222, 0.3) 0%, rgba(152, 219, 255, 0.2) 8%, transparent 25%)"
  ai-panel-dark: "linear-gradient(180deg, rgba(91, 238, 222, 0.15) 0%, rgba(152, 219, 255, 0.1) 8%, transparent 25%)"
  export-success-background: "linear-gradient(180deg, #FFFFFF 0%, #E8FFF0 100%)"
  seedance-ribbon: "linear-gradient(90deg, #9e61ff 0%, #619bff 50%, #6c52ee 100%)"
  seedance-discord-text: "linear-gradient(to right, #9e61ff, #619bff, #45d6c8)"
  seedance-discord-soft: "linear-gradient(to right, rgb(158 97 255 / 10%), rgb(97 155 255 / 10%), rgb(69 214 200 / 10%))"
  pro-dark-card: "linear-gradient(135deg, #7C3AED 0%, #13141D 100%)"
  pro-purple-card: "linear-gradient(135deg, #AE62FF 0%, #C88AFF 100%)"
  starter-light-card: "linear-gradient(135deg, #E8F4FF 0%, #D4ECFF 100%)"
  success-light-card: "linear-gradient(135deg, #E8FFEA 0%, #D4F5D7 100%)"
  plan-free-overlay: "linear-gradient(25.93deg, rgba(107, 114, 128, 0) 65.61%, rgba(107, 114, 128, 0.12) 98.99%)"
  plan-starter-overlay: "linear-gradient(25.93deg, rgba(93, 223, 224, 0) 65.61%, rgba(93, 223, 224, 0.25) 98.99%)"
  plan-pro-overlay: "linear-gradient(25.93deg, rgba(174, 98, 255, 0) 65.61%, rgba(174, 98, 255, 0.12) 98.99%)"
  plan-booster-overlay: "linear-gradient(25.93deg, rgba(229, 169, 19, 0) 65.61%, rgba(229, 169, 19, 0.12) 98.99%)"
  plan-progress-cyan: "linear-gradient(90deg, #0AFFBE 0%, #4EADF3 100%)"
  website-logo: "linear-gradient(90deg, #308DFF 0%, #38ADFF 25%, #687CFF 50%, #6445FF 75%, #AE62FF 100%)"
  website-nav-light: "linear-gradient(180deg, rgba(255, 255, 255, 0.4) 0%, rgba(255, 255, 255, 0) 115.72%)"
  website-nav-dark: "linear-gradient(180deg, rgba(30, 30, 50, 0.9) 0%, rgba(15, 15, 30, 0.95) 100%)"
  website-modal-teal: "linear-gradient(190.72deg, rgba(91, 238, 222, 0) 53.35%, rgba(91, 238, 222, 0.2) 103.33%), #ffffff"
  website-text-shimmer: "linear-gradient(90deg, var(--base-color) 0%, #7145FE 42%, #7145FE calc(50% - var(--spread)), #CD98FF calc(50% + var(--spread)), #CD98FF 58%, var(--base-color) 100%)"
  website-docs-text: "linear-gradient(90deg, #4B3F72 0%, #7B2FBE 50%, #A855F7 100%)"

typography:
  ui-body:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  button-label:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1
  card-title:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: -0.025em
  card-description:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  outfit-display:
    fontFamily: Outfit, Inter, -apple-system, BlinkMacSystemFont, sans-serif
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.1

rounded:
  sm: 4px
  md: 6px
  lg: 8px
  base: "0.5rem"
  full: "9999px"

spacing:
  base: 4px
  card-padding: 24px
  card-header-gap: 6px
  button-sm-height: 36px
  button-default-height: 40px
  button-lg-height: 44px
  icon-button-sm: 36px
  icon-button-default: 40px
  icon-button-lg: 44px

components:
  button-default:
    backgroundColor: "{colors.gray-11}"
    textColor: "{colors.gray-1}"
    typography: "{typography.button-label}"
    rounded: "{rounded.md}"
    height: "{spacing.button-default-height}"
    padding: "8px 16px"
  button-outline:
    backgroundColor: "{colors.background}"
    textColor: "{colors.gray-11}"
    typography: "{typography.button-label}"
    rounded: "{rounded.md}"
    height: "{spacing.button-default-height}"
    padding: "8px 16px"
  button-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.secondary-foreground}"
    typography: "{typography.button-label}"
    rounded: "{rounded.md}"
    height: "{spacing.button-default-height}"
    padding: "8px 16px"
  button-success:
    backgroundColor: "{colors.success-7}"
    textColor: "{colors.gray-1}"
    typography: "{typography.button-label}"
    rounded: "{rounded.md}"
    height: "{spacing.button-default-height}"
    padding: "8px 16px"
  button-warning:
    backgroundColor: "{colors.warning-7}"
    textColor: "{colors.gray-1}"
    typography: "{typography.button-label}"
    rounded: "{rounded.md}"
    height: "{spacing.button-default-height}"
    padding: "8px 16px"
  button-info:
    backgroundColor: "{colors.info-5}"
    textColor: "{colors.gray-1}"
    typography: "{typography.button-label}"
    rounded: "{rounded.md}"
    height: "{spacing.button-default-height}"
    padding: "8px 16px"
  button-error:
    backgroundColor: "{colors.error-7}"
    textColor: "{colors.gray-1}"
    typography: "{typography.button-label}"
    rounded: "{rounded.md}"
    height: "{spacing.button-default-height}"
    padding: "8px 16px"
  input:
    backgroundColor: "{colors.background}"
    textColor: "{colors.text-1}"
    typography: "{typography.card-description}"
    rounded: "{rounded.md}"
    height: 36px
    padding: "4px 12px"
  card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.card-foreground}"
    rounded: "{rounded.lg}"
    padding: "{spacing.card-padding}"
  badge-default:
    backgroundColor: "{colors.gray-11}"
    textColor: "#FFFFFF"
    typography: "{typography.card-description}"
    rounded: "{rounded.md}"
    padding: "2px 10px"
---

# NemoVideo DESIGN.md

## Overview

This file now follows the current Nemo Video codebase exactly. The normative source is:

- `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/styles/globals.css`
- `/Users/yangjinru/Desktop/Nemo Video/packages/design/tailwind.config.js`
- `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/components/ui/*`

The product UI design system is `@nemo/design`: a shadcn/Radix/Tailwind component library with CSS variables, class-based dark mode, Inter as the default UI font, and an Untitled-UI-style gray/status palette.

The website app also has a marketing layer with `brand1-*` RGB variables, logo gradients, and `#7145FE` purple accents. Those are documented as website-layer tokens, but they are not the core product UI palette.

## Colors

The production UI consumes color through CSS variables in HSL channels:

```css
color: hsl(var(--text-1));
background: hsl(var(--background));
border-color: hsl(var(--line-1));
```

Do not replace these with Figma hex values. The current code uses `--brand-1: 217 100% 60%` for product brand color, which corresponds to `#3369FF` in the code comment.

### Product Light Theme

| Token | Code value | Code comment |
|---|---:|---|
| `--brand-1` | `217 100% 60%` | `#3369FF` |
| `--brand-2` | `217 100% 63%` | `#4080FF` |
| `--brand-3` | `217 100% 65%` | `#4C8CFF` |
| `--brand-4` | `217 100% 75%` | `#80AAFF` |
| `--brand-5` | `217 100% 87%` | `#BDD6FF` |
| `--brand-6` | `217 100% 93%` | `#D9E8FF` |
| `--brand-7` | `217 100% 97%` | `#F0F7FF` |
| `--background` | `210 20% 98%` | `#F9FAFB` |
| `--text-1` | `221 33% 11%` | `#101828` |
| `--text-2` | `215 14% 34%` | `#475467` |
| `--text-3` | `220 9% 46%` | `#667085` |
| `--text-4` | `218 11% 65%` | `#98A2B3` |
| `--line-1` | `220 13% 93%` | `#EAECF0` |
| `--mask-1` | `0 0% 0% / 0.4` | `#00000066` |

Gray scale is exactly the `@nemo/design` Untitled UI blue-gray ramp:

| Token | Code value | Code comment |
|---|---:|---|
| `--gray-1` | `220 14% 99%` | `#FCFCFD` |
| `--gray-2` | `210 20% 98%` | `#F9FAFB` |
| `--gray-3` | `220 14% 96%` | `#F2F4F7` |
| `--gray-4` | `220 13% 93%` | `#EAECF0` |
| `--gray-5` | `216 12% 84%` | `#D0D5DD` |
| `--gray-6` | `218 11% 65%` | `#98A2B3` |
| `--gray-7` | `220 9% 46%` | `#667085` |
| `--gray-8` | `215 14% 34%` | `#475467` |
| `--gray-9` | `217 19% 27%` | `#344054` |
| `--gray-10` | `215 25% 17%` | `#1D2939` |
| `--gray-11` | `221 33% 11%` | `#101828` |

Status colors follow the full `success-*`, `warning-*`, and `error-*` ramps in `globals.css`. The default Tailwind semantic mappings are `success` -> `success-7`, `warning` -> `warning-7`, `error/destructive` -> `error-7`, and `info` -> `info-5`.

### Product Dark Theme

Dark mode is activated by the `.dark` class on the root element. `ThemeProvider` supports `light`, `dark`, and `auto`, stores the mode in `localStorage` under `nemo-theme`, and temporarily adds `disable-transitions` during theme changes.

| Token | Code value |
|---|---:|
| `--brand-1` | `217 100% 65%` |
| `--brand-2` | `217 100% 68%` |
| `--brand-3` | `217 100% 70%` |
| `--brand-4` | `217 100% 80%` |
| `--brand-5` | `217 100% 90%` |
| `--brand-6` | `217 100% 95%` |
| `--brand-7` | `217 100% 98%` |
| `--background` | `220 17% 7%` |
| `--text-1` | `220 14% 96%` |
| `--text-2` | `216 12% 84%` |
| `--text-3` | `218 11% 65%` |
| `--text-4` | `224 10% 45%` |
| `--line-1` | `224 12% 18%` |
| `--mask-1` | `0 0% 0% / 0.7` |

Dark gray scale is not a guessed inversion; it is exactly the code:

| Token | Code value | Code comment |
|---|---:|---|
| `--gray-1` | `220 17% 7%` | `#0F1115` |
| `--gray-2` | `225 14% 11%` | `#181A20` |
| `--gray-3` | `224 12% 18%` | `#292C34` |
| `--gray-4` | `222 10% 32%` | `#494E5A` |
| `--gray-5` | `224 10% 45%` | `#676D7D` |
| `--gray-6` | `218 11% 65%` | `#98A2B3` |
| `--gray-7` | `216 12% 84%` | `#D0D5DD` |
| `--gray-8` | `220 13% 93%` | `#EAECF0` |
| `--gray-9` | `220 14% 96%` | `#F2F4F7` |
| `--gray-10` | `210 20% 98%` | `#F9FAFB` |
| `--gray-11` | `220 14% 99%` | `#FCFCFD` |

Dark status ramps are also defined explicitly in `globals.css`, not generated at runtime:

| Token | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 |
|---|---|---|---|---|---|---|---|---|---|---|---|
| `--success-*` | `153 88% 20%` | `155 90% 23%` | `160 96% 27%` | `158 96% 33%` | `154 82% 42%` | `152 69% 55%` | `145 65% 70%` | `145 75% 84%` | `141 79% 92%` | `145 80% 97%` | `140 60% 99%` |
| `--warning-*` | `18 80% 30%` | `21 84% 34%` | `24 91% 40%` | `28 96% 47%` | `33 94% 53%` | `36 98% 59%` | `40 99% 68%` | `43 98% 80%` | `43 96% 91%` | `45 100% 97%` | `45 100% 99%` |
| `--error-*` | `4 64% 32%` | `4 68% 36%` | `4 76% 43%` | `4 74% 52%` | `4 86% 61%` | `4 92% 72%` | `4 89% 83%` | `4 93% 91%` | `4 100% 95%` | `6 100% 98%` | `10 100% 99%` |

### Website Layer

`apps/nemovideo-website/src/app/globals.css` imports `@nemo/design/styles`, then defines additional website variables. Important website tokens:

- `--brand1-1` through `--brand1-7`: `232 243 255`, `190 218 255`, `148 191 255`, `106 161 255`, `64 128 255`, `22 93 255`, `14 66 210`.
- Logo gradient: `#308DFF -> #38ADFF -> #687CFF -> #6445FF -> #AE62FF`.
- Marketing purple used in many website CTAs and blog surfaces: `#7145FE`.
- Website shadcn defaults also define `--primary: 0 0% 9%`, `--background: 0 0% 100%`, etc.; do not confuse those with `@nemo/design` product tokens.

## Gradients

Gradients are part of the codebase visual system and must be documented with direction, stops, and source layer. Repeated uses of the same gradient are documented once. Gradients from proposals, docs-only examples, generated SEO HTML data, and Storybook-only demos are not normative.

### Product Design Gradients

| Token | Gradient | Source / usage |
|---|---|---|
| `product-brand` | `linear-gradient(135deg, #3369ff 0%, #101828 100%)` | `packages/design/src/styles/globals.css` `.bg-gradient-brand`; blue-to-ink brand utility |
| `shimmer-light` | `linear-gradient(90deg, hsl(var(--gray-11)) 0%, hsl(var(--gray-11)) 40%, hsl(var(--gray-6)) 50%, hsl(var(--gray-11)) 60%, hsl(var(--gray-11)) 100%)` | `packages/design/src/styles/globals.css` `.animate-shimmer` light text shimmer |
| `shimmer-dark` | `linear-gradient(90deg, hsl(var(--gray-9)) 0%, hsl(var(--gray-9)) 40%, hsl(var(--gray-7)) 50%, hsl(var(--gray-9)) 60%, hsl(var(--gray-9)) 100%)` | `packages/design/src/styles/globals.css` `.dark .animate-shimmer` |
| `video-controls-overlay` | `linear-gradient(180deg, rgba(0,0,0,0) 0%, rgba(0,0,0,0.4) 60%, rgba(0,0,0,0.75) 100%)` | `packages/design/src/components/ui/video-player/constants.ts`; video control overlay fade |
| `think-shine` | `linear-gradient(90deg, transparent 0%, rgba(255, 255, 255, 0.8) 50%, transparent 100%)` | `packages/design/src/components/ui/think/components/ThinkTitle.tsx`; thinking-title shine sweep |
| `glow-border-conic` | `conic-gradient(from var(--glow-angle, 0deg), #67e8f9, #22d3ee, #06b6d4, #a78bfa, #8b5cf6, #c4b5fd, #a78bfa, #22d3ee, #67e8f9)` | `packages/nemovideo-business/components/src/GlowBorder/GlowBorder.css`; animated AI glow border |

### Product App Gradients

| Token | Gradient | Source / usage |
|---|---|---|
| `mobile-upload-background` | `linear-gradient(to bottom, hsl(var(--gray-1)) 0%, hsl(var(--info-2)) 100%)` | mobile upload page background |
| `dotted-background-light` | `radial-gradient(hsl(var(--gray-5)) 1px, transparent 1px)` with `background-size: 16px 16px` | workspace/task/API page dotted background in light mode |
| `dotted-background-dark` | `radial-gradient(hsl(var(--gray-3)) 1px, transparent 1px)` with `background-size: 16px 16px` | workspace/task/API page dotted background in dark mode |
| `top-scroll-mask` | `linear-gradient(to bottom, black, transparent)` | workspace top mask and fade overlays |
| `gallery-scroll-mask` | `linear-gradient(to bottom, transparent 0px, black 48px)` | task gallery scroll mask; 48px equals `GALLERY_SCROLL_MASK_FADE_LENGTH_PX` |
| `ai-panel-light` | `linear-gradient(180deg, rgba(91, 238, 222, 0.3) 0%, rgba(152, 219, 255, 0.2) 8%, transparent 25%)` | task AI panel background in light mode |
| `ai-panel-dark` | `linear-gradient(180deg, rgba(91, 238, 222, 0.15) 0%, rgba(152, 219, 255, 0.1) 8%, transparent 25%)` | task AI panel background in dark mode |
| `export-success-background` | `linear-gradient(180deg, #FFFFFF 0%, #E8FFF0 100%)` | export modal success surface |
| `seedance-ribbon` | `linear-gradient(90deg, #9e61ff 0%, #619bff 50%, #6c52ee 100%)` | Seedance 2 top banner and website Seedance ribbon; Tailwind form is `bg-gradient-to-r from-[#9e61ff] via-[#619bff] to-[#6c52ee]` |
| `seedance-discord-text` | `linear-gradient(to right, #9e61ff, #619bff, #45d6c8)` | Seedance Discord floating banner text |
| `seedance-discord-soft` | `linear-gradient(to right, rgb(158 97 255 / 10%), rgb(97 155 255 / 10%), rgb(69 214 200 / 10%))` | Seedance Discord floating banner background; hover uses 15% alpha stops |
| `pro-dark-card` | `linear-gradient(135deg, #7C3AED 0%, #13141D 100%)` | user card, usage modal, Seedance lock, premium dark card surfaces |
| `pro-purple-card` | `linear-gradient(135deg, #AE62FF 0%, #C88AFF 100%)` | usage modal business/pro purple surface |
| `starter-light-card` | `linear-gradient(135deg, #E8F4FF 0%, #D4ECFF 100%)` | usage modal starter/free light blue surface |
| `success-light-card` | `linear-gradient(135deg, #E8FFEA 0%, #D4F5D7 100%)` | usage modal success/green surface |
| `plan-free-overlay` | `linear-gradient(25.93deg, rgba(107, 114, 128, 0) 65.61%, rgba(107, 114, 128, 0.12) 98.99%)` | upgrade/payment free plan card overlay |
| `plan-starter-overlay` | `linear-gradient(25.93deg, rgba(93, 223, 224, 0) 65.61%, rgba(93, 223, 224, 0.25) 98.99%)` | upgrade/payment starter plan card overlay |
| `plan-pro-overlay` | `linear-gradient(25.93deg, rgba(174, 98, 255, 0) 65.61%, rgba(174, 98, 255, 0.12) 98.99%)` | upgrade/payment pro plan card overlay |
| `plan-booster-overlay` | `linear-gradient(25.93deg, rgba(229, 169, 19, 0) 65.61%, rgba(229, 169, 19, 0.12) 98.99%)` | credit booster pack overlay |
| `plan-progress-cyan` | `linear-gradient(90deg, #0AFFBE 0%, #4EADF3 100%)` | plan card progress/active meter |

### Website Gradients

| Token | Gradient | Source / usage |
|---|---|---|
| `website-logo` | `linear-gradient(90deg, #308DFF 0%, #38ADFF 25%, #687CFF 50%, #6445FF 75%, #AE62FF 100%)` | website logo/brand mark gradient stops |
| `website-nav-light` | `linear-gradient(180deg, rgba(255, 255, 255, 0.4) 0%, rgba(255, 255, 255, 0) 115.72%)` | `apps/nemovideo-website/src/app/globals.css` `.nemo-home-nav` |
| `website-nav-dark` | `linear-gradient(180deg, rgba(30, 30, 50, 0.9) 0%, rgba(15, 15, 30, 0.95) 100%)` | Seedance dark navbar override |
| `website-modal-teal` | `linear-gradient(190.72deg, rgba(91, 238, 222, 0) 53.35%, rgba(91, 238, 222, 0.2) 103.33%), #ffffff` | website mobile/PC auth modal surfaces |
| `website-text-shimmer` | `linear-gradient(90deg, var(--base-color) 0%, #7145FE 42%, #7145FE calc(50% - var(--spread)), #CD98FF calc(50% + var(--spread)), #CD98FF 58%, var(--base-color) 100%)` | `apps/nemovideo-website/src/components/text-shimmer.tsx` |
| `website-docs-text` | `linear-gradient(90deg, #4B3F72 0%, #7B2FBE 50%, #A855F7 100%)` | docs page headline/accent text gradient |

## Typography

The product UI font family is defined in `packages/design/tailwind.config.js`:

- `font-sans`: `Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif`
- `font-outfit`: `Outfit, Inter, -apple-system, BlinkMacSystemFont, sans-serif`

The app imports Inter and Outfit in `apps/nemovideo/src/index.css`. Button text uses `text-sm font-medium`. Card titles use `font-semibold leading-none tracking-tight`. Card descriptions use `text-sm text-text-3`.

## Layout

The root app uses `bg-background text-foreground`, so the page canvas is `hsl(var(--background))` and text defaults to `hsl(var(--text-1))`.

Spacing and sizing come from Tailwind plus `packages/design/src/lib/sizes.ts`:

- Button: `sm h-9 px-3`, `default h-10 px-4 py-2`, `lg h-11 px-8`, `xl h-12 px-6 py-3`, `2xl h-14 px-8 py-4`.
- Icon button: `sm h-9 w-9`, `default h-10 w-10`, `lg h-11 w-11`, `xl h-12 w-12`, `2xl h-14 w-14`.
- Icon: `sm h-3.5 w-3.5`, `default h-4 w-4`, `lg h-5 w-5`, `xl h-6 w-6`, `2xl h-8 w-8`.
- Avatar: `sm h-8 w-8`, `default h-10 w-10`, `lg h-12 w-12`, `xl h-16 w-16`, `2xl h-20 w-20`.
- Status dot: `sm h-2 w-2`, `default h-3 w-3`, `lg h-4 w-4`, `xl h-5 w-5`, `2xl h-6 w-6`.

### Product App UI Alignment

The current Nemo Video product UI is a compact editor/workspace surface, not a marketing landing page. Documentation previews and handoff examples should reflect that product shape:

- Use a full application canvas with left navigation, a central workspace/media area, and right-side task/history/material panels when showing product UI examples.
- Keep controls dense and operational: `h-9` inputs, `h-10` default buttons, `text-sm` labels, `text-xs` metadata, 8px maximum card radius from `rounded-lg`.
- Use `bg-background`, `bg-card`, `bg-gray-1`, `border-line-1`, and restrained shadows for panels. Avoid oversized hero typography, decorative card stacks, or broad marketing gradients in product workspace examples.
- Product feature previews such as brush editing, assets, generated versions, and edited history should look like tool panels inside the workspace, not website sections.

## Elevation & Depth

Depth follows Tailwind/shadcn defaults in the component classes:

- `Card`: `rounded-lg border border-line-1 bg-card text-card-foreground shadow`.
- `Input`: `shadow-sm`.
- Buttons in status variants use `shadow`; default and outline buttons do not add custom shadow.
- Focus states use `focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2` for buttons and `focus-visible:ring-1 focus-visible:ring-brand-1` for inputs.

The code also defines `.bg-gradient-brand` as `linear-gradient(135deg, #3369ff 0%, #101828 100%)` and `animate-shimmer` text gradients based on `gray-*`.

## Shapes

The base radius is exact code: `--radius: 0.5rem`.

Tailwind radius mapping:

- `rounded-lg`: `var(--radius)`
- `rounded-md`: `calc(var(--radius) - 2px)`
- `rounded-sm`: `calc(var(--radius) - 4px)`

Button, Input, Badge, Card, Alert, and related primitives use these shared radius tokens. Do not replace them with arbitrary pixel values unless the component code does so explicitly.

## Components

`@nemo/design` components are the implementation source. Important exact classes:

- `Button` base: `inline-flex items-center justify-center gap-2 whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50`.
- `Button default`: `bg-gray-11 text-gray-1 hover:opacity-90`.
- `Button outline`: `border border-input bg-background text-gray-11 hover:bg-gray-3`.
- `Button secondary`: `bg-secondary text-secondary-foreground hover:bg-secondary/80`.
- `Button ghost`: `text-gray-11 hover:bg-gray-3`.
- `Button link`: `text-primary underline-offset-4 hover:underline`.
- `Button success/warning/info/error`: status background, `text-gray-1`, `shadow`, `hover:opacity-90`.
- `Badge default`: `border-transparent bg-gray-11 text-[hsl(0,0%,100%)] hover:opacity-90`.
- `Card`: `rounded-lg border border-line-1 bg-card text-card-foreground shadow`.
- `Input`: `h-9 rounded-md border border-input bg-background px-3 py-1 text-sm shadow-sm placeholder:text-text-3 focus-visible:ring-1 focus-visible:ring-brand-1`.
- `Alert`: `relative w-full rounded-lg border p-4 flex items-start gap-3`; variants color only the icon.

Use the exported component variants instead of creating new variant names. If a page needs marketing-specific purple (`#7145FE`), keep that in the website layer; do not feed it back into `@nemo/design` product primitives.

The rest of this section is a complete inventory of the shipped components. It is grouped into `@nemo/design` primitives (Overlays & Popups, Form Controls, Data Display, Feedback) and composite product components (Banners, Modals & Dialogs, Cards, Dropdowns & Notifications, Panels & Navigation, Effects). Class strings are copied from the component source; primitives are mostly Radix UI, except Drawer (`vaul`) and toast (`sonner`).

### Primitives — Overlays & Popups

All modal-type overlays share a Radix `Overlay` of `fixed inset-0 z-50 bg-black/80` with `data-[state=open]:animate-in / data-[state=closed]:animate-out` fade, and a centered `Content` that adds zoom + slide animation.

| Component | Primitive | Key classes |
|---|---|---|
| `Dialog` | Radix Dialog | Content `fixed left-1/2 top-1/2 z-50 grid w-full max-w-lg -translate-x-1/2 -translate-y-1/2 gap-4 border bg-background p-6 shadow-lg sm:rounded-lg max-h-[90vh]`; close button has `circle` (`rounded-full`) and `square` (`rounded-sm`) shape variants, `opacity-70 hover:opacity-100` |
| `AlertDialog` | Radix AlertDialog | Same Content geometry as Dialog; footer `flex-col-reverse sm:flex-row sm:justify-end`; actions reuse `buttonVariants` (default action + `outline` cancel); optional leading status icon sized via `alertDialogIconSizeClasses` |
| `Drawer` | `vaul` | Content `fixed inset-x-0 bottom-0 z-50 mt-24 flex h-auto flex-col rounded-t-[10px] border bg-background`; drag handle `mx-auto mt-4 h-2 w-[100px] rounded-full bg-muted` |
| `Sheet` | Radix Dialog | CVA `side` variants: `top`/`bottom` full-width slide, `left`/`right` `h-full w-3/4 sm:max-w-sm` slide; `bg-background p-6 shadow-lg` |
| `Popover` | Radix Popover | Content `z-50 w-72 rounded-md border border-gray-4 bg-popover p-4 text-popover-foreground shadow-md` with zoom/slide-by-side animation |
| `DropdownMenu` | Radix DropdownMenu | Content `z-50 min-w-[8rem] overflow-hidden rounded-md border bg-popover p-1 shadow-md`; item `rounded-sm px-2 py-1.5 text-sm focus:bg-accent focus:text-accent-foreground`; supports inset, sub-menu, checkbox/radio items, `DropdownMenuShortcut` |
| `ContextMenu` | Radix ContextMenu | Same content/item styling as DropdownMenu, triggered on right-click |
| `Select` | Radix Select | Trigger `flex h-9 w-full items-center justify-between rounded-md border border-input bg-background px-3 py-2 text-sm`; Content `rounded-md border bg-popover shadow-md`; item `py-1.5 pl-8 pr-2` with check indicator |
| `Tooltip` | Radix Tooltip | Content `z-50 overflow-hidden rounded-md bg-gray-11 dark:bg-gray-2 px-3 py-1.5 text-xs text-gray-1 dark:text-gray-11 shadow-md` |
| `HoverCard` | Radix HoverCard | Content `z-50 w-64 rounded-md border bg-popover p-4 shadow-md`; used for WeChat QR and user previews |
| `Toast` (`Sonner`) | `sonner` | `<Toaster>` themed via `toast group`, `group-[.toaster]:bg-background group-[.toaster]:text-foreground group-[.toaster]:border-border group-[.toaster]:shadow-lg`; description `text-muted-foreground` |

### Primitives — Form Controls

| Component | Key classes |
|---|---|
| `Input` | `flex h-9 w-full rounded-md border border-input bg-background px-3 py-1 text-sm shadow-sm placeholder:text-text-3 focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-brand-1 disabled:opacity-50` |
| `Textarea` | `flex min-h-[60px] w-full rounded-md border border-input bg-background px-3 py-2 text-sm shadow-sm placeholder:text-text-3 focus-visible:ring-1 focus-visible:ring-brand-1` |
| `Label` | `text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70` |
| `Checkbox` | `h-4 w-4 shrink-0 rounded-sm border border-primary shadow focus-visible:ring-1 focus-visible:ring-ring data-[state=checked]:bg-brand-1 data-[state=checked]:text-primary-foreground` |
| `RadioGroup` | Item `aspect-square h-4 w-4 rounded-full border border-primary text-primary shadow`; indicator is a centered filled dot |
| `Switch` | Root `peer inline-flex h-5 w-9 shrink-0 rounded-full data-[state=checked]:bg-primary data-[state=unchecked]:bg-input`; thumb `h-4 w-4 rounded-full bg-background data-[state=checked]:translate-x-4` |
| `Slider` | Three CVA size maps — track `h-1.5/h-2/h-3 rounded-full bg-secondary`, range `bg-primary`, thumb `h-4 w-4 rounded-full border border-primary/50 bg-background shadow` |
| `Toggle` | Base `inline-flex items-center justify-center rounded-md text-sm font-medium hover:bg-muted data-[state=on]:bg-accent data-[state=on]:text-accent-foreground`; `default` + `outline` variants; sizes via `toggleSizeClasses` |
| `OtpInput` | Per-cell `w-14 h-16 rounded-xl border text-2xl text-center`, active cell adds `ring-2 ring-brand-1` |

### Primitives — Data Display

| Component | Key classes |
|---|---|
| `Avatar` | Root `relative flex shrink-0 overflow-hidden rounded-full` sized via `avatarSizeClasses` (sm `h-8 w-8` → 2xl `h-20 w-20`); fallback `flex h-full w-full items-center justify-center rounded-full bg-muted` |
| `Table` | Wrapper `relative w-full overflow-auto`; `table w-full caption-bottom text-sm`; row `border-b hover:bg-muted/50 data-[state=selected]:bg-muted`; head `h-10 px-2 text-left align-middle font-medium text-muted-foreground` |
| `Accordion` | Item `border-b`; trigger `flex flex-1 items-center justify-between py-4 text-sm font-medium [&[data-state=open]>svg]:rotate-180`; content uses `accordion-up/down` keyframes |
| `Tabs` | List `inline-flex h-9 items-center rounded-lg bg-muted p-1 text-muted-foreground`; trigger `rounded-md px-3 py-1 text-sm font-medium data-[state=active]:bg-background data-[state=active]:shadow` |
| `Separator` | `shrink-0 bg-border`; horizontal `h-[1px] w-full`, vertical `h-full w-[1px]` |
| `Kbd` | `inline-flex items-center rounded border bg-muted px-1.5 font-mono text-xs text-muted-foreground` |
| `Badge` | Base `inline-flex items-center rounded-md border px-2.5 py-0.5 text-xs font-semibold`; variants `default bg-gray-11 text-white`, `secondary`, `destructive`, `outline`, plus `success/warning/info` status fills |
| `Status` | Colored dot sized via `statusSizeClasses` (sm `h-2 w-2` → 2xl `h-6 w-6`); state colors `online`(success) / `offline`(gray) / `away`(warning) / `busy`(error) / `pro` / `premium` / `vip` |
| `Progress` | Track `relative h-2 w-full overflow-hidden rounded-full bg-primary/20`; indicator `h-full w-full flex-1 bg-primary transition-all` translated by value |

### Primitives — Feedback

| Component | Key classes |
|---|---|
| `Alert` | `relative w-full rounded-lg border p-4 flex items-start gap-3`; only the leading icon is tinted per `success/warning/info/error` variant, sized via `alertIconSizeClasses` |
| `Skeleton` | `animate-pulse rounded-md bg-muted dark:bg-gray-3` |
| `Spinner` | `size-4 animate-spin` (Lucide `Loader2`), inherits `currentColor` |

### Composite — Banners

| Component | Source | Key classes / behavior |
|---|---|---|
| `Seedance2TopBanner` | nemovideo-business | Full-width 40px strip, gradient `bg-gradient-to-r from-[#9e61ff] via-[#619bff] to-[#6c52ee]`, white text; on mount sets CSS var `--top-banner-height` so layout shifts down; dismissible |
| `Seedance2LockWatermark` | nemovideo-business | Locked-content overlay, gradient `linear-gradient(135deg, #7C3AED 0%, #13141D 100%)`, centered lock + upgrade CTA |
| Seedance Discord banner | nemovideo-extensions | Floating pill, text gradient `to-right #9e61ff → #619bff → #45d6c8`, soft bg `rgb(158 97 255 / 10%) …` (hover 15%) |
| `slogan-banner` | nemovideo-extensions | Hero typewriter headline in Outfit, brand text gradient; marketing-style intro surface |

### Composite — Modals & Dialogs

All wrap the shared `Dialog` primitive unless noted.

| Component | Source | Key classes / behavior |
|---|---|---|
| `ExportModal` | nemovideo-business | Success surface gradient `linear-gradient(180deg,#FFFFFF 0%,#E8FFF0 100%)`; CTAs `w-full h-12 rounded-xl` |
| `UpgradeModal` / `upgrade-modal` | nemovideo-business (root file is a re-export shim) | Content `min-w-[471px] !rounded-[20px]`, Outfit title, plan cards inside |
| `SwitchToPCModal` | nemovideo-business | `max-w-[320px] rounded-2xl`, prompts desktop for full editor |
| `BusinessPlanModal` | nemovideo-business | Business-tier plan grid built on `PlanCard` |
| `CancelPlanDialog` | nemovideo-business | `AlertDialog`-style confirm with destructive action |
| `auth-modal` | nemovideo-extensions | Dialog `sm:max-w-[500px] p-9 rounded-2xl`; `GlowButton` with mouse-follow radial `rgba(113,69,254,0.5)`; brand headline gradient `#000 → #7145FE → #CD98FF` |
| `onboarding-modal` | nemovideo-extensions | Hand-rolled overlay `fixed inset-0 z-[10000] bg-black/50 backdrop-blur-sm`; card `w-[520px] rounded-2xl`; scale-to-corner close animation (not the shared Dialog) |
| `mega-x-popup` | nemovideo-extensions | Dialog `sm:max-w-[500px] rounded-2xl p-9`; brand chip; Discord + primary CTAs `h-11 rounded-xl` |
| `phone-upload` | nemovideo-extensions | Dialog `sm:max-w-[400px]`; QR frame for handing an upload to mobile |
| `ReceiptModal` | nemovideo-extensions (subscription) | Receipt detail dialog within the subscription flow |

### Composite — Cards

| Component | Source | Key classes |
|---|---|---|
| `TaskCard` | nemovideo-business | `group rounded-xl`; cover `relative aspect-square bg-gray-2 rounded-lg overflow-hidden`; selected `ring-2 ring-brand-1`; title `text-sm font-medium text-gray-10`; time `text-xs text-gray-5`; delete `w-6 h-6 p-0 rounded bg-gray-10/70 opacity-0 group-hover:opacity-100`; loading skeleton `bg-gray-3 animate-pulse` |
| `VideoCard` | nemovideo-business | Thumbnail card with hover play affordance and metadata footer |
| `PlanCard` | nemovideo-business | Free / Starter / Pro / Business tiers; Starter shows a `MOST POPULAR` ribbon with gradient `#0AFFBE → #4EADF3`; each tier uses its plan-overlay gradient token |
| `CreditBoosterPack` | nemovideo-business | Gold surface accent `#E5A913` + `plan-booster-overlay` gradient |

### Composite — Dropdowns & Notifications

| Component | Source | Key classes / behavior |
|---|---|---|
| `TaskNotificationDropdown` | nemovideo-business | Panel `w-[400px] rounded-xl`; a `FlyingBall` element animates via the `fly-ball` / `fly-to-notification` keyframes toward the bell on completion |
| `help-menu` | nemovideo-extensions | Trigger tri-color Discord pill gradient `158,97,255 / 97,155,255 / 91,238,222`; DropdownMenu body; WeChat QR shown in a HoverCard |

### Composite — Panels & Navigation

| Component | Source | Key classes / behavior |
|---|---|---|
| `WorkspaceLayout` | nemovideo-business | Dotted canvas `radial-gradient(hsl(var(--gray-5)) 1px, transparent 1px)` at `background-size:16px 16px`; floating glass nav `fixed left-5 top-1/2 rounded-full bg-white/80 dark:bg-gray-3/80 backdrop-blur-lg p-1 shadow-lg border border-gray-4/50`; transparent absolute header; extension `Slot` mount points; z-order `z-[5] < z-20 < z-30` |
| `MobileHeader` | nemovideo-business | Compact top bar for mobile breakpoint |
| `SearchHeader` | nemovideo-extensions | Outfit title + `Input h-9` search field |
| `sidebar` | nemovideo-extensions | Nav item active state `bg-brand-1/[0.12] text-brand-1`, idle `text-gray-7 hover:bg-gray-3` |
| `user-card-header` / `user-card-sidebar` | nemovideo-extensions | Credits pill whose `bgColor` is chosen per plan tier; avatar + plan label |
| `payment-callback` | nemovideo-extensions | Logic-only route, renders `null` (no UI chrome) |

### Composite — Effects

| Component | Source | Key classes / behavior |
|---|---|---|
| `GlowBorder` | nemovideo-business | Animated AI border using conic gradient `glow-border-conic` rotated by `--glow-angle` via `glow-border-rotate 3s` linear infinite; wraps children in a padded gradient ring |

> Files that look like components but are not: the root `UpgradeModal.tsx`, `VideoUploadPanel.tsx`, and `UserCard.tsx` in nemovideo-business are re-export shims for the real implementations; there is no `SeedanceBanner/` directory or `Seedance2TopBanner.constants.ts` file. Document behavior from the real source modules, not the shims.

### Contrast Notes

The current implementation uses `text-gray-1` on solid status button backgrounds. Keep this document aligned with code. If the team decides to adjust status-button contrast targets later, that should be tracked as a product accessibility change in `packages/design/src/components/ui/button/buttonVariants.ts`, not silently changed in the design document first.

| Component token | Current background | Current text color | Source class |
|---|---|---|---|
| `button-success` | `success-7` | `gray-1` | `bg-success text-gray-1` |
| `button-warning` | `warning-7` | `gray-1` | `bg-warning text-gray-1` |
| `button-info` | `info-5` | `gray-1` | `bg-info text-gray-1` |
| `button-error` | `error-7` | `gray-1` | `bg-destructive text-gray-1` |

## Do's and Don'ts

- Do use `@nemo/design/styles` and `@nemo/design/tailwind` as the source of truth for product UI.
- Do reference colors through Tailwind classes such as `bg-brand-1`, `text-text-1`, `border-line-1`, `bg-background`, and `text-foreground`.
- Do keep dark mode as `.dark` class switching through `ThemeProvider`.
- Do use the website layer tokens only for `apps/nemovideo-website`.
- Do document product UI examples as compact workspace/editor surfaces rather than marketing pages.
- Do keep solid status button text as `gray-1` while the component implementation uses `text-gray-1`.
- Don't use the Figma `#165DFF` primary as product UI primary; the code primary is `--brand-1: 217 100% 60%`.
- Don't rewrite HSL channel values into approximate hex values in implementation docs.
- Don't mix website RGB `--gray-*` variables with product HSL `--gray-*` variables without naming the layer.
- Don't invent new component variants when `Button`, `Badge`, `Card`, `Input`, and `Alert` already define the variants in code.
