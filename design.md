---
version: alpha
name: NemoVideo
description: AI video-editing agent design system. Ship/code tokens are normative; Figma tokens document original design intent and state mapping.
colors:
  primary: "#3369FF"
  primary-hover: "#4C8CFF"
  primary-pressed: "#4080FF"
  primary-soft: "#F0F7FF"
  primary-disabled: "#D9E8FF"
  primary-focus-dark: "#80AAFF"

  background: "#F9FAFB"
  foreground: "#101828"
  surface: "#FFFFFF"
  surface-muted: "#F2F4F7"
  border: "#EAECF0"
  input-border: "#D0D5DD"
  text-primary: "#101828"
  text-secondary: "#475467"
  text-tertiary: "#667085"
  text-placeholder: "#98A2B3"
  inverse-text: "#FFFFFF"

  dark-background: "#101828"
  dark-foreground: "#FCFCFD"
  dark-surface: "#1D2939"
  dark-surface-muted: "#344054"
  dark-border: "#344054"
  dark-input-border: "#475467"
  dark-text-primary: "#FCFCFD"
  dark-text-secondary: "#EAECF0"
  dark-text-tertiary: "#D0D5DD"
  dark-text-placeholder: "#98A2B3"

  success: "#12B76A"
  success-bg: "#ECFDF3"
  success-fg: "#027A48"
  warning: "#F79009"
  warning-bg: "#FFFAEB"
  warning-fg: "#B54708"
  error: "#F04438"
  error-bg: "#FEF3F2"
  error-fg: "#B42318"
  info: "#1776FF"
  info-bg: "#F0F7FF"
  info-fg: "#175CD3"

  figma-primary: "#165DFF"
  figma-primary-hover: "#4080FF"
  figma-primary-pressed: "#0E42D2"
  figma-primary-soft: "#E8F3FF"
  figma-gray-1: "#FFFFFF"
  figma-gray-3: "#F2F3F7"
  figma-gray-5: "#E5E6EC"
  figma-gray-8: "#B8BAC4"
  figma-gray-9: "#868B9C"
  figma-gray-10: "#4E5469"
  figma-gray-11: "#13141D"

typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: 800
    lineHeight: 1.12
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: 600
    lineHeight: 1.2
  title-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.25
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.3
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.45
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.35
  mono-label:
    fontFamily: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: 0.08em
  hero-serif-accent:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1.05

rounded:
  sm: 4px
  md: 6px
  lg: 8px
  full: 9999px

spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  panel-gap: 16px
  card-padding: 24px
  ai-chat-width: 336px

components:
  button-default:
    backgroundColor: "{colors.foreground}"
    textColor: "{colors.inverse-text}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 10px
    height: 40px
  button-default-hover:
    backgroundColor: "#1D2939"
    textColor: "{colors.inverse-text}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 10px
    height: 40px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.inverse-text}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 10px
    height: 40px
  button-primary-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.inverse-text}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 10px
    height: 40px
  button-secondary:
    backgroundColor: "{colors.surface-muted}"
    textColor: "{colors.text-primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.md}"
    padding: 10px
    height: 40px
  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 12px
    height: 36px
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.lg}"
    padding: "{spacing.card-padding}"
  badge-info:
    backgroundColor: "{colors.info-bg}"
    textColor: "{colors.info-fg}"
    typography: "{typography.caption}"
    rounded: "{rounded.md}"
    padding: 6px
  badge-success:
    backgroundColor: "{colors.success-bg}"
    textColor: "{colors.success-fg}"
    typography: "{typography.caption}"
    rounded: "{rounded.md}"
    padding: 6px
  alert-error:
    backgroundColor: "{colors.error-bg}"
    textColor: "{colors.error-fg}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    padding: 16px
---

# NemoVideo DESIGN.md

## Overview

NemoVideo is an AI video-editing agent: users describe what they want in chat, and the product helps discover trends, analyze viral references, write scripts, cut footage, and generate ready-to-post content.

The interface should feel confident, effortless, action-first, and creator-to-creator. Its visual identity is restrained rather than loud: one clear blue, quiet neutral surfaces, hairline borders, practical shadows, and generous but work-focused spacing.

The production layer is the source of truth. Values from `packages/design` and the exported codebase documentation override older Figma values. The Figma file remains important because it documents original Arco component states, color roles, and interaction intent.

Signature copy:

- **English:** Chat Your Way to Virality
- **Chinese:** 对话即爆款
- **Positioning:** Pro AI Video Editing Agent / 专业 AI 视频剪辑 Agent

## Colors

The shipped palette uses `#3369FF` as the production primary. Use it for focus rings, links, active states, and the single most important CTA in a view. The default solid button is intentionally neutral black/white, not blue, so blue remains meaningful.

Production color roles:

- **Primary (`#3369FF`):** Brand action color for one primary CTA, focus, links, and selected states.
- **Primary hover (`#4C8CFF`):** Hover state for primary action surfaces.
- **Primary soft (`#F0F7FF`):** Subtle selected backgrounds, info-tinted panels, and low-emphasis active states.
- **Background (`#F9FAFB`):** Light app canvas.
- **Surface (`#FFFFFF`):** Cards, popovers, panels, and controls.
- **Foreground (`#101828`):** Strong text and default solid button background.
- **Border (`#EAECF0`):** Hairline dividers and card boundaries.
- **Muted surface (`#F2F4F7`):** Secondary fills and low-priority UI.

Dark mode uses the same semantic token names under `.dark`. Do not create separate dark-only component variants when token switching is enough.

- **Dark background (`#101828`):** App canvas in dark mode.
- **Dark surface (`#1D2939`):** Cards, popovers, and panels.
- **Dark muted surface (`#344054`):** Secondary fills and low-emphasis containers.
- **Dark primary text (`#FCFCFD`):** Main foreground.
- **Dark secondary text (`#EAECF0`):** Secondary labels and body copy.
- **Dark focus (`#80AAFF`):** Brighter brand ring for dark surfaces.

Status colors are semantic and should not be used as decoration:

- **Success (`#12B76A`, bg `#ECFDF3`):** Completed, valid, positive result.
- **Warning (`#F79009`, bg `#FFFAEB`):** Non-blocking caution.
- **Error (`#F04438`, bg `#FEF3F2`):** Destructive, failed, invalid.
- **Info (`#1776FF`, bg `#F0F7FF`):** Guidance and neutral notices.

Figma reference values:

- **Figma primary (`#165DFF`):** Original Arco default primary. Use as design-history reference, not production replacement.
- **Figma hover (`#4080FF`) and pressed (`#0E42D2`):** State intent for the original component library.
- **Figma gray 11 (`#13141D`), gray 10 (`#4E5469`), gray 9 (`#868B9C`), gray 8 (`#B8BAC4`):** Original text hierarchy.
- **Decorative colors:** Teal `#5BEEDE`, pink `#F7AEF3`, purple `#7145FE`, and logo gradients are for illustration and brand art only, not UI primitives.

## Typography

The production UI uses **Inter**. It should feel efficient, modern, and readable inside dense workbench surfaces. Figma contains Roboto and project-local Chinese styles, but new production UI should use the shipped font stack.

- **Headlines:** Inter ExtraBold or SemiBold for page and section titles.
- **Body:** Inter Regular at 16px for primary reading and 14px for dense panels.
- **Labels:** Inter Medium at 14px for controls and compact UI.
- **Metadata:** 12px mono labels for tokens, timestamps, and technical identifiers.
- **Chinese:** Use the system Chinese stack, typically PingFang SC on macOS/iOS.
- **Serif accent:** Bodoni Moda Italic is reserved for the hero phrase `to Virality`. Do not use it in product chrome.

Avoid viewport-scaled type in application UI. Keep letter spacing at `0` in dense controls and panels; only token labels or metadata may use wider tracking.

## Layout

NemoVideo follows a VSCode-style pluggable workbench. Product features contribute views into named containers instead of creating isolated page layouts.

Core shells:

- **WorkspaceLayout:** Home/workspace routes such as viral, uploaded, generated, and subscription.
- **TaskLayout:** Editing workspace with a task header, left icon rail, resizable panels, and right AI chat.
- **PendingTaskLayout:** Transitional and loading task states.

Task layout:

- **AI chat panel:** Fixed at `336px`.
- **Panels:** Media, Script, Storyboard, Preview.
- **Panel behavior:** Draggable, resizable, collapsible, and able to auto-expand when AI acts on them.
- **Workflow phases:** Upload, script, planning, confirm elements, storyboard ready, generating, timeline-only, completed.

Spacing uses a 4px base. Standard card padding is 24px. Controls in the same row should share the same size ramp so icon buttons, avatars, status dots, and buttons align cleanly.

## Elevation & Depth

Depth is restrained. Separate surfaces with borders and quiet shadows rather than heavy outlines or decorative glow.

- **Cards:** `0 1px 3px rgba(16,24,40,.1), 0 1px 2px rgba(16,24,40,.06)`.
- **Inputs:** `0 1px 2px rgba(16,24,40,.05)`.
- **Popovers/dialogs:** Use a stronger but still practical shadow, equivalent to `shadow-lg`.
- **Focus:** Use a visible brand ring, normally `ring-2` with `#3369FF` in light mode and `#80AAFF` in dark mode.
- **Overlay mask:** Light mode uses `rgba(0,0,0,.40)`; dark mode uses `rgba(0,0,0,.70)`.

The AI action glow is the only expressive glow. It should identify the panel the agent is acting on, not decorate static surfaces.

## Shapes

The shape language is practical and slightly soft.

- **Cards:** 8px radius.
- **Buttons:** 6px radius.
- **Inputs:** 6px radius.
- **Badges:** 6px radius.
- **Avatars and pills:** Fully rounded.

Borders are 1px hairlines using the semantic border token. Do not restyle scrollbars per view; use the shared thin scrollbar treatment with a transparent track.

## Components

Build with `@nemo/design` shadcn-style components. The Figma `oc-*` component sets are the origin and a richer reference for state roles, but they are not the production implementation target.

Component mapping:

- **Button:** Figma `oc-button` -> code `Button`.
- **Badge/tag:** Figma `oc-tag` -> code `Badge`.
- **Input:** Figma `oc-input` -> code `Input`.
- **Select:** Figma `oc-select-title` -> code `Select`.
- **Checkbox:** Figma `oc-checkbox` -> code `Checkbox`.
- **Radio:** Figma `oc-radio-group-item` -> code `RadioGroup`.
- **Switch:** Figma `oc-switch` -> code `Switch`.
- **Progress:** Figma `oc-progress` -> code `Progress`.
- **Tooltip:** Figma `oc-tooltip` -> code `Tooltip`.
- **Banner:** Figma `oc-banner` -> code `Alert`.
- **Navigation:** Figma nav items -> code `NavigationMenu` or `Tabs`.

Button variants should use existing names: `default`, `outline`, `secondary`, `ghost`, `link`, `success`, `warning`, `info`, and `error`. Do not invent names like `primaryBlue` or `darkOutline`.

Inputs use surface backgrounds, semantic borders, `text-placeholder` for placeholders, and brand focus rings. Cards use `surface`, `border`, `rounded-lg`, and quiet shadow. Avoid nesting cards inside cards unless the inner card is a repeated item, modal, or framed tool surface.

## Do's and Don'ts

- Do use ship/code tokens as the production source of truth.
- Do use Figma values to understand design intent, state roles, and component anatomy.
- Do keep brand blue scarce: links, focus, active state, and one primary CTA per view.
- Do support light and dark mode through semantic token switching under `.dark`.
- Do keep text hierarchy explicit: primary, secondary, tertiary, placeholder.
- Do use status colors only for their semantic meaning.
- Don't replace production `#3369FF` with Figma `#165DFF` without an intentional migration.
- Don't use decorative teal, pink, purple, or logo gradients as UI component colors.
- Don't hardcode hex values inside components when a token exists.
- Don't create dark-only component variants when semantic tokens can solve the state.
- Don't use the serif accent outside the hero phrase.
- Don't add new primitives before checking `@nemo/design`.
