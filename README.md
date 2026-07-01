# Nemo Video Design.md

> Bilingual design-system documentation for NemoVideo, written in the Google `DESIGN.md` format.
>
> NemoVideo 的中英文设计系统文档，遵循 Google `DESIGN.md` 格式。

## English

This repository contains a machine-readable and human-readable design-system reference for **NemoVideo**, an AI video-editing agent.

The design system documents:

- Production design tokens copied from the current Nemo Video codebase.
- Light mode and dark mode semantic color rules from `@nemo/design`.
- Website-layer colors documented separately from the product UI palette.
- A static HTML preview for quickly reviewing the visual system in a browser.

### Files

- [`design.md`](./design.md) — the source-of-truth design-system document in Google `DESIGN.md` format.
- [`design-preview.html`](./design-preview.html) — a static visual preview of the design system.
- [`README.md`](./README.md) — bilingual project overview.

### Design Source Priority

The production/code layer is the source of truth. The current normative files are:

- `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/styles/globals.css`
- `/Users/yangjinru/Desktop/Nemo Video/packages/design/tailwind.config.js`
- `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/components/ui/*`

Important color rules:

- Product primary: `--brand-1: 217 100% 60%`, documented in code as `#3369FF`.
- Dark mode: semantic token switching under `.dark`.
- Website marketing colors such as `#7145FE` and `brand1-*` are separate website-layer tokens, not replacements for `@nemo/design`.

### Preview

Open `design-preview.html` directly in a browser to review the design tokens visually. No dev server is required.

### Validation

The file follows the Google `DESIGN.md` structure:

```bash
npx -y @google/design.md lint design.md
```

The current document validates with zero structural errors. Remaining warnings are expected because the file intentionally includes complete color ramps and reference tokens that are not all attached to component examples.

---

## 中文

这个仓库保存了 **NemoVideo** 的设计系统文档。NemoVideo 是一个 AI 视频剪辑 Agent，用户通过对话描述需求，系统辅助完成趋势分析、脚本、剪辑和生成。

这份设计系统包含：

- 从当前 Nemo Video codebase 读取的生产环境 token。
- `@nemo/design` 中白天模式和黑夜模式的语义色规范。
- 单独记录 website layer 的营销色，不把它和产品 UI 主色混在一起。
- 一个可直接在浏览器打开的静态 HTML 预览页。

### 文件说明

- [`design.md`](./design.md) — 设计系统源文件，遵循 Google `DESIGN.md` 格式。
- [`design-preview.html`](./design-preview.html) — 设计系统可视化预览页。
- [`README.md`](./README.md) — 当前中英文项目说明。

### 设计优先级

上线实现以代码/生产 token 为准。当前规范的来源文件是：

- `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/styles/globals.css`
- `/Users/yangjinru/Desktop/Nemo Video/packages/design/tailwind.config.js`
- `/Users/yangjinru/Desktop/Nemo Video/packages/design/src/components/ui/*`

重要颜色规则：

- 产品主色：`--brand-1: 217 100% 60%`，代码注释为 `#3369FF`。
- 黑夜模式：通过 `.dark` 下的语义 token 切换实现。
- Website 营销色，例如 `#7145FE` 和 `brand1-*`，是 website layer，不覆盖 `@nemo/design` 产品 UI。

### 如何预览

直接用浏览器打开 `design-preview.html` 即可查看可视化设计规范，不需要启动本地服务。

### 如何校验

可以使用 Google `DESIGN.md` 工具校验文档结构：

```bash
npx -y @google/design.md lint design.md
```

当前文档没有结构错误。剩余 warning 主要来自完整色阶和参考 token 没有全部直接绑定到组件示例，属于预期情况。
