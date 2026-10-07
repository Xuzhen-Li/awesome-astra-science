# AI Model Works（AI 模型作品集）

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](README.md) · 中文

**只收 AI 模型自己真正做出来的作品**：演示和图像。每条配一张静帧，链接到一手来源；如果官方公开了提示词或任务说明，也一并给出。不收第三方「我用模型 X 做了……」演示，不收榜单分数，不收新闻评论。

仓库名 `awesome-astra-science` 沿用自只收 GPT-6 Astra 的时期。现在 GPT-6 Astra 只是其中一个模型分区，之后会有其他模型。

---

## 条目怎么组织

- **按模型分区。** 每个模型一个一级分区，标题写模型名和发布方。
- **按作品类型分组。** 同一模型内按作品类型分组（例如演示、3D 场景、游戏），只用该模型现有材料撑得起的类型。
- **每条条目**包含仓库 [`media/`](media/) 里的一张静帧、作品出处、公开过的提示词或任务说明（如有），以及一两句话说明模型做出了什么。
- 静帧为视频截帧或官方素材，版权归原作者（见 [NOTICE](NOTICE.md)）。

## 目录

- [GPT-6 Astra (OpenAI)](#gpt-6-astra-openai)：12 件
  - [电脑操控演示 (发布页)](#电脑操控演示-发布页)：5 件
  - [3D 场景与建筑可视化](#3d-场景与建筑可视化)：4 件
  - [游戏](#游戏)：3 件
  - [Astra 不收录的内容](#astra-不收录的内容)
- [新增模型作品的约定](#新增模型作品的约定)

---

## GPT-6 Astra (OpenAI)

只收 GPT-6 Astra 自己做出来的项目：OpenAI 官方演示和文章里，Astra 产出可指认制品的那些。

依据：[GPT-6 Astra 发布页](https://openai.com/index/gpt-6-astra/) 及其链接的 OpenAI 文章。

### 电脑操控演示 (发布页)

#### 细胞追踪工作流（Jupyter）

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/jupyter-cell-tracking.jpg" alt="JupyterLab 中的细胞追踪" width="100%"></a>

**出处：** OpenAI · [发布页 · Cell-tracking workflow](https://openai.com/index/gpt-6-astra/)

Astra 在 JupyterLab 里搭建并运行显微镜细胞追踪工作流（分割掩膜 → 轨迹 / 谱系）。这是浓缩的官方电脑操控演示，不是期刊论文。

#### KiCad 电路板（`chip_design`）

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/openai-kicad.jpg" alt="KiCad PCB 布局与 3D 电路板" width="100%"></a>

**出处：** OpenAI · [发布页](https://openai.com/index/gpt-6-astra/) · 视频 `chip_design_no_captions_15s.mp4`

Astra 在 KiCad 里摆放元件并布线，做出可制造的 PCB（2D 布局 + 3D 电路板）。这是发布页的电子设计桌面，**不是** MultiQC / 测序质控。

#### FreeCAD 五速变速箱

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/openai-freecad.jpg" alt="FreeCAD 变速箱" width="100%"></a>

**出处：** OpenAI · [发布页 · Car transmission](https://openai.com/index/gpt-6-astra/)

书面任务说明 → FreeCAD 里一套细化的五速变速箱概念设计。

#### 齿轮运动（FreeCAD → Blender）

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/freecad-motion.jpg" alt="运转中的变速箱齿轮" width="100%"></a>

**出处：** OpenAI · [发布页](https://openai.com/index/gpt-6-astra/) · 视频 `gear-motion.mp4`

同一条变速箱线：齿轮运转动画（在 FreeCAD 设计基础上用 Blender 接着做）。

#### Unity 城市场景

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/unity-city.jpg" alt="Astra 在 Unity 中搭建的城市" width="100%"></a>

**出处：** OpenAI · [发布页](https://openai.com/index/gpt-6-astra/) · 素材 `Unity-City-high-res.png`

在 Unity 里搭建的城市鸟瞰场景（官方电脑操控 / 游戏场景组装静帧）。

### 3D 场景与建筑可视化

#### Solace 住宅（Blender → Unreal）

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/solace-hero.jpg" alt="Solace 建筑可视化" width="100%"></a>

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/solace-ue5.jpg" alt="Unreal Engine 中的 Solace" width="100%"></a>

**出处：** OpenAI Developers · [Architectural visualization with Astra](https://developers.openai.com/blog/architectural-visualization-with-astra)

由 Astra 驱动的建筑可视化流程：从 Blender 里的调研 / 建模一直到 Unreal 展示（Solace）。

#### HELIOS 戴森集能器

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/helios-dyson.jpg" alt="HELIOS 戴森集能器概念" width="100%"></a>

**出处：** OpenAI Developers · 同一篇[建筑可视化](https://developers.openai.com/blog/architectural-visualization-with-astra)文章

同一篇官方建筑可视化文章里的概念作品（HELIOS / 戴森式集能器）。

#### Shipyard · AURELION-07 巡洋舰

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/aurelion-shipyard.jpg" alt="Blender 中的 AURELION-07 巡洋舰" width="100%"></a>

**出处：** OpenAI Developers · [Architectural visualization with Astra](https://developers.openai.com/blog/architectural-visualization-with-astra)

Astra 在 Blender 里建出 AURELION-07（Shipyard 项目）：收窄船体、分段环、四台推进器，几何和材质均可编辑。

#### Giverny 水上花园

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/giverny-garden.jpg" alt="受莫奈启发的 Giverny 花园" width="100%"></a>

**出处：** OpenAI Developers · [Architectural visualization with Astra](https://developers.openai.com/blog/architectural-visualization-with-astra)

Astra 在同一篇官方建筑可视化文章里建出受莫奈 / Giverny 启发的花园场景（睡莲池、拱桥、植栽）。

### 游戏

#### Void Explorer 飞船（Blender）

<a href="https://developers.openai.com/blog/how-to-build-games-with-astra"><img src="media/void-explorer-ship.jpg" alt="Blender 中建模的 AURORA 飞船" width="100%"></a>

**出处：** OpenAI Developers · [Building games with Astra](https://developers.openai.com/blog/how-to-build-games-with-astra)

Astra 为 Void Explorer 游戏在 Blender 里建出可编辑的飞船（AURORA：193 个网格 → 运行时资产）。

#### Sunwake 海面与船

<a href="https://developers.openai.com/blog/how-to-build-games-with-astra"><img src="media/sunwake-water.jpg" alt="Sunwake 程序化海面与船" width="100%"></a>

**出处：** OpenAI Developers · 同一篇[游戏](https://developers.openai.com/blog/how-to-build-games-with-astra)文章

Astra 写了自定义的 Three.js 水面渲染器，并在 Blender 里做了船，一起放进 Sunwake。

#### Hollowflux 水系 RPG

<a href="https://developers.openai.com/blog/how-to-build-games-with-astra"><img src="media/hollowflux-water.jpg" alt="Hollowflux 发光地下河" width="100%"></a>

**出处：** OpenAI Developers · [Building games with Astra](https://developers.openai.com/blog/how-to-build-games-with-astra)

Astra 迭代一款代码绘制的 2D 动作 RPG，核心是模拟的地下河（水体网格、水流、与战斗的耦合）。

### Astra 不收录的内容

已移除或从未收录：

- 第三方 X / 博客上的「我用 Astra 做了……」演示
- 榜单表格（GeneBench、OSWorld、EEBench……）：是分数，不是作品
- 新闻 / 「冷静看待」类评论
- 错误的 MultiQC 归属（从来不是 Astra 做的项目；发布页的电子设计桌面是 KiCad）
- 十项 Lean 数学文章（OpenAI 原文写的是**内部版** Astra，不能明确算作公开版 GPT-6 Astra 的产出）

更全的 Astra 链接合集：[helloianneo/awesome-gpt6-astra](https://github.com/helloianneo/awesome-gpt6-astra)。

---

## 新增模型作品的约定

这是给以后新增内容用的约定，目前还没有其他模型分区。

- **分区：** 在现有分区之后新增一级标题 `## <模型名> (<发布方>)`，并用一句话说明什么算该模型的产出、一手来源是什么。
- **类型：** 用 `###` 标题按作品类型分组（例如 `Demos`、`Figures`、`3D scenes`、`Games`），至少有一件真实作品才新增该类型。
- **文件：** 新模型的静帧放在 `media/<model-slug>/<work-slug>.<ext>`（小写、连字符分隔，例如 `media/<model-slug>/<work-slug>.jpg`）。Astra 现有静帧保留在 `media/` 根目录，现有链接不受影响。
- **每条条目写明：**
  - `####` 标题，写作品名；
  - 仓库内的一张静帧或图像，链接到出处；
  - **出处：** 发布方，以及模型产出该作品的一手来源链接（官方页面、论文或仓库）；
  - **提示词：** 官方公开过的提示词或任务说明，引用或链接；只有确实公开过才写；
  - 一两句话说明模型做出了什么，不写来源之外的指标或结论。
- **范围：** 只收模型自己做出来、有一手来源的作品。不收第三方社交媒体演示、榜单分数、评论。

---

**整理：** [Xuzhen Li](https://github.com/Xuzhen-Li) · [ORCID](https://orcid.org/0000-0003-3670-6657) · 编辑文字采用 [CC0 1.0](LICENSE)，详见 [NOTICE](NOTICE.md)。
