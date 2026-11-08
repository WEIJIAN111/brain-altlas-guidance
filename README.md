# Brain Altlas Guidance

> 小鼠脑区脑图查询器 · Mouse Brain Region Atlas Query Tool
>
> 当前版本：v0.2 ｜ 首次公开发布：2026 年 11 月 9 日
> 在线访问：https://weijian111.github.io/brain-altlas-guidance/

## 作者与版权

- **作者：韦计安（Jian-An Wei）**
- **单位：暨南大学（Jinan University）**
- **联系方式：jianwei@jnu.edu.cn**

本项目由作者独立完成并首次公开发布于此仓库，仓库的提交记录作为公开的时间凭证。

© 2026 韦计安. All rights reserved.

本项目未采用任何开源许可证；未经作者书面许可，请勿复制、分发、改编或将其用于商业用途。如需引用或合作，请联系作者。

---

## 项目简介

Brain Altlas Guidance 是一个单文件、离线可用的小鼠脑区脑图查询工具。打开 `index.html` 即可查询小鼠脑区的名称、位置、功能与连接信息，并对照 Paxinos 与 Allen 图谱的冠状面、矢状面图版与三维脑模型进行定位。

## 使用方法

### 在线使用

打开在线访问链接即可使用，无需安装、无需注册。

### 离线使用

下载本仓库的 `index.html`（单文件网页，包含全部数据与图版），用任意现代浏览器直接打开即可离线使用，无需联网。

## 功能

- **脑区检索**：按中文名、英文名或缩写检索脑区，点击确认按钮查询；输入时提供联想建议，支持模糊（部分）匹配；支持别名检索，例如 `BNST`。
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
> Current version: v0.2 | First public release: 9 November 2026
> Live demo: https://weijian111.github.io/brain-altlas-guidance/

## Author & Copyright

- **Author: 韦计安 (Jian-An Wei)**
- **Affiliation: 暨南大学 (Jinan University)**
- **Contact: jianwei@jnu.edu.cn**

This project was independently created by the author and is first publicly released in this repository; the commit history of this repository serves as public, timestamped evidence of that release.

© 2026 韦计安. All rights reserved.

This project is not released under any open-source license. Do not copy, distribute, adapt, or use it commercially without the author's written permission. For citation or collaboration, please contact the author.

## About

Brain Altlas Guidance is a single-file, offline-capable query tool for mouse brain regions. Open `index.html` to look up a brain region's name, location, function, and connectivity, and to locate it on Paxinos and Allen coronal/sagittal plates and in a 3D brain model.

## Usage

### Online

Open the live demo link above. No installation or sign-up is needed.

### Offline

Download `index.html` from this repository (a single self-contained file with all data and plates) and open it in any modern browser. No internet connection is required.

## Features

- **Search**: search brain regions by Chinese name, English name, or abbreviation, then click the confirm button. Autocomplete suggestions and partial (fuzzy) matching are supported, as are aliases such as `BNST`.
- **Brain region list**: a list of brain regions below the search bar; click any entry to view it.
- **Allen 3D brain positioning**: locate the queried region in the Allen 3D brain model.
- **Atlas plates**: coronal and sagittal plate series that can be browsed by horizontal sliding; click a plate to view it enlarged in-page. Pale-yellow markers on the plates indicate the region's position.
- **Region information**: function summaries, neuron-type composition, and STAM connectivity counts.
- **Abbreviation errata table**: a 766-entry Paxinos–Allen abbreviation errata table.

## Data Sources

This tool is built on the following atlas and data resources:

1. Paxinos & Franklin, *The Mouse Brain in Stereotaxic Coordinates* (the author's own atlas PDF; plates and abbreviation index).
2. Allen Institute Mouse Brain Atlas / Common Coordinate Framework v3 (CCFv3 structure ontology and official 3D meshes).
3. STAM single-cell projection atlas (atlas.brainsmatics.cn), for the connectivity and reconstructed-neuron count data.
