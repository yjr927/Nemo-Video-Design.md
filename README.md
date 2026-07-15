# Nemo Video Design.md

> Bilingual design-system documentation for NemoVideo, written in the Google `DESIGN.md` format.
>
> NemoVideo 的中英文设计系统文档，遵循 Google `DESIGN.md` 格式。

## English

This repository contains a machine-readable and human-readable design-system reference for **NemoVideo**, an AI video-editing agent.

The document is organized in **three layers**, and every rule is tagged with the layer it belongs to:

1. **Current implementation inventory** — the exact tokens shipping in the Nemo Video codebase today.
2. **Target design rules** — marked **[Target]**, the direction all *new* design and code must follow. Where a Target rule conflicts with current code, the frontmatter token is already repointed to the Target value and the old value is preserved as inventory.
3. **Migration guidance** — how inventory moves to Target, with each conflicting item tagged **Deprecated**, **Temporary exception**, **Needs migration**, or **Needs audit** in the "Deprecation & Migration Ledger".

**Layer precedence:** when inventory and Target disagree, future work follows **Target**. This round edits only the design docs and the static preview; no product source code is changed yet, so the inventory tables still describe what renders in production until the migration lands.

The design system documents:

- Production design tokens copied from the current Nemo Video codebase (inventory).
- Light mode and dark mode semantic color rules from `@nemo/design`.
- The Target palette (black / white / gray product body + `#7145FE` purple as a spot color), radius scale, spacing grid, stroke, and nested-radius rules.
- Website-layer colors documented separately from the product UI palette.
- A static HTML preview tuned to the current Nemo Video product UI density: compact navigation, workspace-style panels, small metadata, and restrained shadows.

### Files

- [`design.md`](./design.md) — the design-system document in Google `DESIGN.md` format (inventory + Target + migration).
- [`design-preview.html`](./design-preview.html) — a static visual preview of the design system.
- [`README.md`](./README.md) — bilingual project overview.

### Design Source Priority

Two sources, two roles:

- **Inventory source of truth** (what ships today) is the production/code layer:
  - `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/styles/globals.css`
  - `/Users/yangjinru/Desktop/Nemo Video/packages/design/tailwind.config.js`
  - `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/components/ui/*`
- **Target source of truth** (what new work must follow) is the **[Target]** rules integrated into `design.md`. Future design and code follow Target even where it disagrees with the current code.

Important color rules:

- **[Target]** Product body is **black / white / gray** (neutral scale). The default primary action is black/white/gray — not blue, not purple.
- **[Target]** `#7145FE` purple is a **spot color**, used only in controlled scenarios: 信息通知 / Highlight / Selected / Active / Focus / AI 强调. A 7-step purple ramp (`brand-purple-1..7`) mirrors the blue ramp's lightness steps.
- **[Target]** Error / Warning / Success default to a gray-white-black expression (color carried on icon/text per the Alert pattern), not full colored backgrounds.
- **[Target]** Radius is a 4px-grid scale — xs 4 / sm 8 / md 12 / lg 16 / xl 20 / 2xl 24 / full. There is **no 6px** token and it must not be reintroduced. Spacing is a 4px grid (`space-0..space-12` = 0/4/8/12/16/20/24/32/40/48) and all padding references spacing tokens.
- **[Inventory]** Product code today still ships a blue `brand-*` ramp (`--brand-1: 217 100% 60%` ≈ `#3369FF`) as its accent, blue focus rings, colored status buttons, and 6px button radius. These are kept as inventory and marked for migration.
- **[Inventory]** Dark mode: semantic token switching under `.dark`.
- Website marketing colors such as `#7145FE` and `brand1-*` are separate website-layer tokens, not replacements for `@nemo/design`.
- Product UI examples should look like the editor/workspace experience, not a website landing page. Use dense panels, `text-sm`/`text-xs` metadata, `h-9` inputs, `h-10` buttons, and **[Target]** 8px controls / 16px cards from the 4px-grid radius scale.

### Preview

Open `design-preview.html` directly in a browser to review the design tokens visually. No dev server is required. The preview is a documentation view, but its spacing and hierarchy are intentionally aligned with the product workspace UI rather than marketing-page composition.

### Validation

The file follows the Google `DESIGN.md` structure:

```bash
npx -y @google/design.md lint design.md
```

The current document validates with zero structural errors. Remaining warnings are expected because the file intentionally keeps the complete inventory ramps/reference tokens (including the deprecated blue `brand-*` ramp and colored status tokens retained for migration), and because status button text colors are documented to match the current `@nemo/design` implementation even where the linter flags contrast follow-ups.

---

## 中文

这个仓库保存了 **NemoVideo** 的设计系统文档。NemoVideo 是一个 AI 视频剪辑 Agent，用户通过对话描述需求，系统辅助完成趋势分析、脚本、剪辑和生成。

文档采用 **三层结构**，每条规则都会标注它属于哪一层：

1. **现状实现盘点（Inventory）** — 当前 Nemo Video codebase 里实际上线的 token。
2. **目标设计规则（Target）** — 用 **[Target]** 标记，是所有*新*设计和代码必须遵循的方向。当 Target 与现状代码冲突时，frontmatter token 已经改指到 Target 值，旧值作为 inventory 保留。
3. **迁移指引（Migration）** — 说明 inventory 如何过渡到 Target，每个冲突项在 "Deprecation & Migration Ledger" 里标注 **Deprecated**、**Temporary exception**、**Needs migration** 或 **Needs audit**。

**层级优先级**：当 inventory 和 Target 冲突时，未来的工作以 **Target** 为准。本轮只修改设计文档和静态预览，不改产品源码，所以 inventory 表格仍然描述迁移落地前生产环境的实际渲染。

这份设计系统包含：

- 从当前 Nemo Video codebase 读取的生产环境 token（inventory）。
- `@nemo/design` 中白天模式和黑夜模式的语义色规范。
- Target 调色板（黑 / 白 / 灰产品主体 + `#7145FE` 紫色作为 spot color）、圆角刻度、间距栅格、Stroke 和嵌套圆角规则。
- 单独记录 website layer 的营销色，不把它和产品 UI 主色混在一起。
- 一个可直接在浏览器打开的静态 HTML 预览页，并且预览页的密度更接近当前 Nemo Video 产品工作台：紧凑导航、面板式信息、小号 metadata、克制阴影。

### 文件说明

- [`design.md`](./design.md) — 设计系统源文件，遵循 Google `DESIGN.md` 格式（inventory + Target + migration）。
- [`design-preview.html`](./design-preview.html) — 设计系统可视化预览页。
- [`README.md`](./README.md) — 当前中英文项目说明。

### 设计优先级

两个来源，两种角色：

- **Inventory 来源（当前上线现状）** 以代码/生产 token 为准：
  - `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/styles/globals.css`
  - `/Users/yangjinru/Desktop/Nemo Video/packages/design/tailwind.config.js`
  - `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/components/ui/*`
- **Target 来源（新工作必须遵循）** 是整合进 `design.md` 的 **[Target]** 规则。即使与现状代码冲突，未来的设计和代码也以 Target 为准。

重要颜色规则：

- **[Target]** 产品主体是 **黑 / 白 / 灰**（中性色阶）。默认主操作用黑白灰 —— 不是蓝色，也不是紫色。
- **[Target]** `#7145FE` 紫色是 **spot color**，只用于受控场景：信息通知 / Highlight / Selected / Active / Focus / AI 强调。7 阶紫色 ramp（`brand-purple-1..7`）沿用蓝色 ramp 的明度步进。
- **[Target]** Error / Warning / Success 默认用灰白黑表达（颜色只落在 icon / 文字上，遵循 Alert 模式），不用整块彩色背景。
- **[Target]** 圆角是 4px 栅格刻度 —— xs 4 / sm 8 / md 12 / lg 16 / xl 20 / 2xl 24 / full。**没有 6px** token，且禁止重新引入。间距是 4px 栅格（`space-0..space-12` = 0/4/8/12/16/20/24/32/40/48），所有 padding 都引用 spacing token。
- **[Inventory]** 产品代码目前仍然使用蓝色 `brand-*` ramp（`--brand-1: 217 100% 60%` ≈ `#3369FF`）作为强调色、蓝色 focus ring、彩色状态按钮和 6px 按钮圆角。这些作为 inventory 保留并标记待迁移。
- **[Inventory]** 黑夜模式：通过 `.dark` 下的语义 token 切换实现。
- Website 营销色，例如 `#7145FE` 和 `brand1-*`，是 website layer，不覆盖 `@nemo/design` 产品 UI。
- 产品 UI 示例应该像 editor/workspace，而不是官网落地页。优先使用密集面板、`text-sm`/`text-xs` 信息层级、`h-9` 输入框、`h-10` 按钮，以及 **[Target]** 4px 栅格圆角里的 8px 控件 / 16px 卡片。

### 如何预览

直接用浏览器打开 `design-preview.html` 即可查看可视化设计规范，不需要启动本地服务。这个预览仍然是文档视图，但间距、层级和面板风格已经按产品工作台方向收紧，不再按营销页 hero 方式呈现。

### 如何校验

可以使用 Google `DESIGN.md` 工具校验文档结构：

```bash
npx -y @google/design.md lint design.md
```

当前文档没有结构错误。剩余 warning 主要来自文档刻意保留了完整的 inventory 色阶 / 参考 token（包括为迁移保留的、已弃用的蓝色 `brand-*` ramp 和彩色状态 token），以及状态按钮文字色按当前 `@nemo/design` 代码实现记录时触发的对比度提醒，属于预期情况。
