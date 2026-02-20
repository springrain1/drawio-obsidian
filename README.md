# 图表 (Draw.io) for Obsidian

[English](#english) | [中文](#中文)

---

## English

A plugin that integrates the full [Draw.io](https://www.diagrams.net/) diagramming engine natively into [Obsidian](https://obsidian.md/). Diagrams are stored as native `.svg` or `.drawio` files — always editable, always portable, 100% local.

### Features

- **Native `.svg` & `.drawio` file support** — double-click any diagram file to open the Draw.io editor directly inside Obsidian
- **Inline rendering for `.drawio` files** — embed `.drawio` files in your notes with `![[diagram.drawio]]` and see a live preview, just like images
- **Obsidian size syntax support** — `![[diagram.drawio|400]]`, `![[diagram.drawio|300x200]]`, `![[diagram.drawio|50%]]`
- **Right-click context menus** — create, insert, and edit diagrams from the editor, file explorer, and file context menus
- **High-res PNG export** — export diagrams at 2× resolution via Canvas API
- **Fully localized to Chinese (中文)** — all UI text, menus, and the Draw.io engine itself are displayed in Chinese
- **Chinese font presets** — 8 common Chinese fonts pre-configured (微软雅黑, 黑体, 宋体, 楷体, 仿宋, 苹方, 思源黑体, 思源宋体)
- **Auto-sync Obsidian fonts** — automatically reads your Obsidian font settings and adds them to Draw.io's custom font list

### Screenshots

![Screenshot 1](/docs/image/screenshot1.png)

![Insert new diagram](/docs/image/screenshot2.png)

![Edit existing diagram](/docs/image/screenshot3.png)

### Installation

#### Manual Installation

1. Download `main.js`, `manifest.json`, and `styles.css` from the [latest release](../../releases/latest)
2. Create a folder at `<your-vault>/.obsidian/plugins/drawio-obsidian/`
3. Copy the three files into that folder
4. Restart Obsidian and enable the plugin under **Settings → Community Plugins**

#### Usage

- **Create a new diagram**: Right-click in the editor → `创建新图表`
- **Create in a folder**: Right-click a folder in the file explorer → `新建图表`
- **Edit an existing diagram**: Double-click any `.svg` or `.drawio` file, or right-click → `编辑图表`
- **Embed in a note**: Use `![[diagram.svg]]` or `![[diagram.drawio]]`

---

## 中文

将完整的 [Draw.io](https://www.diagrams.net/) 绘图引擎原生集成进 [Obsidian](https://obsidian.md/) 的插件。图表存储为本地 `.svg` 或 `.drawio` 文件——随时可编辑，永久可迁移，100% 数据自主。

### 功能特性

- **原生支持 `.svg` 与 `.drawio` 文件** — 在 Obsidian 文件管理器中双击图表文件，直接在内部唤醒 Draw.io 编辑器
- **`.drawio` 文件内联渲染** — 在笔记中用 `![[diagram.drawio]]` 嵌入即可实时预览，告别"无法预览的附件"
- **完整支持 Obsidian 尺寸语法** — `![[diagram.drawio|400]]`、`![[diagram.drawio|300x200]]`、`![[diagram.drawio|50%]]`
- **右键菜单深度集成** — 从编辑器、文件夹、文件三处右键菜单一键创建、插入、编辑图表
- **高清 PNG 导出** — 通过 Canvas API 以 2 倍分辨率导出清晰图片
- **全面汉化** — 插件所有界面文本及 Draw.io 引擎内部菜单均为中文
- **中文字体预置** — 内置 8 款常用中文字体：微软雅黑、黑体、宋体、楷体、仿宋、苹方、思源黑体、思源宋体
- **自动同步 Obsidian 字体** — 读取 Obsidian 当前字体设置，自动追加到 Draw.io 字体列表

### 截图

![截图1](/docs/image/screenshot1.png)

![插入新图表](/docs/image/screenshot2.png)

![编辑已有图表](/docs/image/screenshot3.png)

### 安装方法

#### 手动安装

1. 从 [最新 Release](../../releases/latest) 下载 `main.js`、`manifest.json`、`styles.css`
2. 在你的 Vault 中创建目录 `<你的库>/.obsidian/plugins/drawio-obsidian/`
3. 将三个文件放入该目录
4. 重启 Obsidian，在 **设置 → 第三方插件** 中启用插件

### 使用方法

- **创建新图表**：在编辑器中右键 → `创建新图表`
- **在文件夹中创建**：文件管理器中右键文件夹 → `新建图表`
- **编辑已有图表**：双击 `.svg` 或 `.drawio` 文件，或右键 → `编辑图表`
- **嵌入笔记**：使用 `![[diagram.svg]]` 或 `![[diagram.drawio]]`

### AI 进阶玩法

配合 [Claudian](https://github.com/YishenTu/claudian) 插件与 Draw.io Skill，可实现用自然语言描述需求，由 AI 自动生成并渲染图表，最终导出为 `.drawio`/`.svg` 嵌入笔记。

---

## License

MIT License — see [LICENSE](LICENSE)

## Credits

- Original plugin by [Sam Greenhalgh](https://www.radicalresearch.co.uk/)
- Fork maintained by [springrain1](https://github.com/springrain1) with deep customizations for Chinese knowledge workers
