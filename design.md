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

## Do's and Don'ts

- Do use `@nemo/design/styles` and `@nemo/design/tailwind` as the source of truth for product UI.
- Do reference colors through Tailwind classes such as `bg-brand-1`, `text-text-1`, `border-line-1`, `bg-background`, and `text-foreground`.
- Do keep dark mode as `.dark` class switching through `ThemeProvider`.
- Do use the website layer tokens only for `apps/nemovideo-website`.
- Don't use the Figma `#165DFF` primary as product UI primary; the code primary is `--brand-1: 217 100% 60%`.
- Don't rewrite HSL channel values into approximate hex values in implementation docs.
- Don't mix website RGB `--gray-*` variables with product HSL `--gray-*` variables without naming the layer.
- Don't invent new component variants when `Button`, `Badge`, `Card`, `Input`, and `Alert` already define the variants in code.
