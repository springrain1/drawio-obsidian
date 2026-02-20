# Changelog

All notable changes to this project will be documented in this file.

## [1.5.4] - 2026-02-20

### Added
- `.drawio` file inline rendering (`DrawioEmbedProcessor`) — embed diagrams in Markdown notes with live preview
- Obsidian image size syntax for `.drawio` embeds: `|width`、`|widthxheight`、`|percent%`
- SVG cache and render queue to avoid redundant parsing on note load
- 8 pre-configured Chinese fonts: 微软雅黑、黑体、宋体、楷体、仿宋、苹方、思源黑体、思源宋体
- Auto-sync Obsidian font settings to Draw.io custom font list
- Full Chinese (中文) localization — plugin UI and Draw.io engine menus
- Right-click context menus: "插入新图表" (editor), "新建图表" (folder), "编辑图表" (file)
- `.drawio` registered as native Obsidian editable file type (double-click to edit)
- High-resolution PNG export at 2× resolution via Canvas API

### Fixed
- PNG export failing for XML-format `.drawio` files
- Empty shape sidebar in Sketch and Compact themes

### Changed
- Rewrote `saveAsPng()` using `DrawioClient.exportSvg()` + Canvas API rasterization

---

## [1.5.0] - (upstream baseline)

Original release by Sam Greenhalgh. See upstream repository for prior history:  
https://github.com/zapthedingbat/drawio-obsidian
