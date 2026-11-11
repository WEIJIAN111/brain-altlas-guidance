# Brain Altlas Guidance

> 小鼠脑区脑图查询器 · Mouse Brain Region Atlas Query Tool
>
> 当前版本：v0.5 ｜ 首次公开发布：2026 年 11 月 9 日
> 在线访问：https://weijian111.github.io/brain-altlas-guidance/

## 更新说明

### v0.5 — 2026-11-11

- 新增深色/浅色模式切换——页面右上角图标按钮一键切换，深色模式下白底图版保留白色衬底与边框以便辨认，主题偏好会在本地记住。

### v0.4 — 2026-11-10

- 逐区文献复核——按质量标准筛出 293 个脑区逐个检索文献，改写功能简介 302 条、神经元类型 260 条，纠正束间核/旁黑质核递质标注（5-羟色胺能→多巴胺能）等错误，21 个确无专门文献的脑区如实标注不作功能断言。

### v0.3 — 2026-11-09

- 补齐全部 605 个脑区的功能简介与神经元类型构成（此前仅 84 个脑区有功能简介、79 个脑区有神经元类型构成）。
- 28 个热门脑区按较新文献共识复核。
- 纤维束、分层与室周结构如实标注为无神经元胞体，不套用神经元分类。

## 项目简介

Brain Altlas Guidance 是一个单文件、离线可用的小鼠脑区脑图查询工具。打开`index.html`即可查询小鼠脑区的名称、位置、功能与连接信息，并对照 Paxinos 与 Allen 图谱的冠状面、矢状面图版与三维模型进行定位。

## 使用方法

### 在线使用

打开在线访问链接即可使用，无需安装、无需注册。

### 离线使用

下载本仓库的`index.html`（单文件网页，包含全部数据与图版），用任意现代浏览器直接打开即可离线使用，无需联网。

## 功能

- **脑区检索**：按中文名、英文名或缩写检索脑区，点击确认按钮查询；输入时提供联想建议，支持模糊（部分）匹配；支持别名检索，例如`BNST`。
- **脑区列表**：搜索栏下方列出脑区，点击即可查看该脑区。
- **Allen 3D 脑定位**：在 Allen 三维脑模型中定位所查询的脑区。
- **图谱切面**：提供冠状面与矢状面系列图版，可横向滑动浏览；点击图版可在站内放大查看。图版上的淡黄色标记指示该脑区所在位置。
- **脑区信息**：展示功能概述、神经元类型组成与 STAM 连接计数。
- **缩写勘误表**：766 条 Paxinos–Allen 缩写对照勘误表。

## 数据来源

本工具建立在以下公开图谱与数据资源之上：

1. Paxinos & Franklin，《The Mouse Brain in Stereotaxic Coordinates》（作者自有图谱 PDF；图版与缩写索引）。
2. Allen Institute Mouse Brain Atlas / Common Coordinate Framework v3（CCFv3 结构本体与官方 3D 网格）。
3. STAM 单细胞投射图谱（atlas.brainsmatics.cn），提供连接数据与重建神经元计数。

---

# Brain Altlas Guidance (English)

> Mouse Brain Region Atlas Query Tool
>
> Current version: v0.5 | First public release: 9 November 2026
> Live demo: https://weijian111.github.io/brain-altlas-guidance/

## Update Notes

### v0.5 — 11 November 2026

- Added dark/light mode toggle — switch with one click on the icon button at the top-right of the page; in dark mode, white-background plates keep a white backing and border so they remain recognisable; the theme preference is remembered locally.

### v0.4 — 10 November 2026

- Region-by-region literature review: 293 regions were screened against quality criteria and each was checked against the literature; 302 function summaries and 260 neuron-type entries were rewritten; transmitter annotations were corrected (including interfascicular nucleus / paranigral nucleus: serotonergic → dopaminergic), among other errors; 21 regions with no dedicated literature are labelled as such, with no functional claims made for them.

### v0.3 — 9 November 2026

- Completed the function summaries and neuron-type composition for all 605 brain regions (previously, only 84 regions had function summaries and 79 had neuron-type composition).
- Reviewed 28 popular brain regions against recent literature consensus.
- Fiber tracts, laminar and periventricular structures are labelled as having no neuronal somata, and neuron classification is not applied to them.

## About

Brain Altlas Guidance is a single-file, offline-capable mouse brain region atlas query tool. Open `index.html` to search for mouse brain regions by name, location, function and connectivity, and cross-reference Paxinos and Allen atlas plates, vector diagrams and 3D models for localization.

## Usage

### Online

Open the live demo link to use it — no installation or registration needed.

### Offline

Download `index.html` from this repository (a single-file web page containing all data and plates) and open it directly in any modern browser to use it offline, no internet connection needed.

## Features

- **Region Search**: Search regions by Chinese name, English name or abbreviation; click the confirm button to query. Suggestions appear as you type, with support for fuzzy (partial) matching and alias search, e.g. `BNST`.
- **Region List**: Regions are listed below the search bar; click one to view it.
- **Allen 3D Brain Localization**: Locate the queried region in the Allen 3D brain model.
- **Atlas Plates**: A series of coronal and sagittal plates that can be scrolled horizontally; click a plate to zoom in within the site. A pale-yellow marker indicates the region's location on the plate.
- **Region Information**: Shows a function overview, neuron-type composition and STAM connection counts.
- **Abbreviation Errata**: A 766-entry Paxinos–Allen abbreviation cross-reference errata table.

## Data Sources

This tool is built on the following public atlases and data resources:

1. Paxinos & Franklin, *The Mouse Brain in Stereotaxic Coordinates* (author's own atlas PDF; plates and abbreviation index).
2. Allen Institute Mouse Brain Atlas / Common Coordinate Framework v3 (CCFv3 structural ontology and official 3D meshes).
3. STAM single-cell projection atlas (atlas.brainsmatics.cn), providing connection data and reconstructed neuron counts.
