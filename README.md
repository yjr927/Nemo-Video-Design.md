# Nemo Video Design.md

> Bilingual design-system documentation for NemoVideo, written in the Google `DESIGN.md` format.
>
> NemoVideo 的中英文设计系统文档，遵循 Google `DESIGN.md` 格式。

## English

This repository contains a machine-readable and human-readable design-system reference for **NemoVideo**, an AI video-editing agent.

The design system documents:

- Production design tokens for colors, typography, spacing, radius, and components.
- Light mode and dark mode semantic color rules.
- Figma reference colors and component intent from the original design layer.
- A static HTML preview for quickly reviewing the visual system in a browser.

### Files

- [`design.md`](./design.md) — the source-of-truth design-system document in Google `DESIGN.md` format.
- [`design-preview.html`](./design-preview.html) — a static visual preview of the design system.
- [`README.md`](./README.md) — bilingual project overview.

### Design Source Priority

The production/code layer is the source of truth. Figma values are preserved as reference for original design intent, component anatomy, and state mapping.

- Production primary: `#3369FF`
- Figma reference primary: `#165DFF`
- Dark mode: semantic token switching under `.dark`

### Preview

Open `design-preview.html` directly in a browser to review the design tokens visually. No dev server is required.

### Validation

The file follows the Google `DESIGN.md` structure:

```bash
npx -y @google/design.md lint design.md
```

The current document validates with zero structural errors. Some orphan-token warnings are expected because the file intentionally includes a complete color palette, including reference tokens that are not directly attached to component examples.

---

## 中文

这个仓库保存了 **NemoVideo** 的设计系统文档。NemoVideo 是一个 AI 视频剪辑 Agent，用户通过对话描述需求，系统辅助完成趋势分析、脚本、剪辑和生成。

这份设计系统包含：

- 生产环境使用的颜色、字体、间距、圆角和组件 token。
- 白天模式和黑夜模式的语义色规范。
- 从原始 Figma 设计层提取的参考色、组件结构和状态意图。
- 一个可直接在浏览器打开的静态 HTML 预览页。

### 文件说明

- [`design.md`](./design.md) — 设计系统源文件，遵循 Google `DESIGN.md` 格式。
- [`design-preview.html`](./design-preview.html) — 设计系统可视化预览页。
- [`README.md`](./README.md) — 当前中英文项目说明。

### 设计优先级

上线实现以代码/生产 token 为准。Figma 数值用于保留原始设计意图、组件结构和状态映射，不直接覆盖生产 token。

- 生产主色：`#3369FF`
- Figma 参考主色：`#165DFF`
- 黑夜模式：通过 `.dark` 下的语义 token 切换实现

### 如何预览

直接用浏览器打开 `design-preview.html` 即可查看可视化设计规范，不需要启动本地服务。

### 如何校验

可以使用 Google `DESIGN.md` 工具校验文档结构：

```bash
npx -y @google/design.md lint design.md
```

当前文档没有结构错误。部分未被组件直接引用的 token 会产生 warning，这是因为文档保留了完整色板和 Figma 参考 token，属于预期情况。
