<div align="center">

# 🧠 Happy-LLM-Learn

### ✨ 让大语言模型「看得见、摸得着、学得会」

<p>
  <em>基于 AI 能力，用 HTML 技术对《Happy-LLM》进行结构化 · 可视化 · 沉浸式呈现的学习项目</em>
</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square" alt="JavaScript">
  <img src="https://img.shields.io/badge/AI_Powered-22d68a?style=flat-square&logo=openai&logoColor=white" alt="AI Powered">
  <img src="https://img.shields.io/badge/Zero_Build-⚡-success?style=flat-square" alt="Zero Build">
  <img src="https://img.shields.io/badge/响应式-📱📱💻-blueviolet?style=flat-square" alt="Responsive">
  <img src="https://img.shields.io/badge/License-MIT-informational?style=flat-square" alt="License">
</p>

<p>
  <a href="#-快速开始"><strong>🚀 快速开始</strong></a> &nbsp;·&nbsp;
  <a href="#-章节总览"><strong>📚 章节总览</strong></a> &nbsp;·&nbsp;
  <a href="#-可视化方法论"><strong>🎨 方法论</strong></a> &nbsp;·&nbsp;
  <a href="#-项目结构"><strong>📁 结构</strong></a> &nbsp;·&nbsp;
  <a href="#-路线图"><strong>🗺️ 路线图</strong></a>
</p>

---

</div>

> **🎯 项目使命**：把厚重的《Happy-LLM》PDF 教材，转化为一页页**可点击、可播放、可交互**的动态网页——让抽象的模型架构和历史脉络，像电影一样在你眼前徐徐展开。

<br>

## 💡 这是什么？

传统教材是「静态」的：密密麻麻的文字、平铺的流程图、难以感知的维度变化。

**Happy-LLM-Learn** 是一次「视觉化学习」实验。我们借助 AI 的结构化能力，将《Happy-LLM》中晦涩的概念拆解为**逐帧动画、时间轴、组件拆解图**，封装进一个个独立的 HTML 文件中——

- 🎬 **逐帧播放**：复杂流程（如 Transformer 数据流）一步步「演」给你看，而不是一次性堆给你
- 🧭 **时间轴导航**：NLP 的发展史、词向量的演进，沿着时间轴徐徐展开
- 🧩 **组件透视**：把 Encoder / Decoder / Attention 拆成零件，逐个点亮
- 📱 **即开即用**：纯前端、零依赖、双击 HTML 即可在任何浏览器运行

> 简单说：**这是一本「会动」的 LLM 科普书** 📖✨

<br>

## ✨ 核心特性

| 特性 | 说明 |
|:---:|:---|
| 🎞️ **逐步可视化** | 每个知识点拆成多个步骤，点击「下一步」即可看到概念「动起来」 |
| 🕰️ **时间轴叙事** | 用纵向时间轴讲述 NLP 从 1940s 到深度学习时代的发展脉络 |
| 🔬 **架构解剖** | Transformer 各组件分层透视，数据流向一目了然 |
| 🌙 **沉浸式暗色主题** | 护眼的深色界面（`#0f1117`）+ 标志性薄荷绿高亮（`#22d68a`） |
| 🔍 **全文检索** | 首页侧边栏支持章节关键词过滤，秒级定位 |
| 📱 **响应式适配** | 桌面 / 平板 / 手机三端自适应，移动端可折叠侧栏 |
| ⚡ **零构建零依赖** | 无 Node、无 Webpack、无 npm install——纯静态文件，即开即看 |
| 🤖 **AI 驱动生成** | 内容结构化与可视化代码由 AI 按统一 Prompt 模板生成 |

<br>

## 📚 章节总览

<table>
  <thead>
    <tr>
      <th width="80">章节</th>
      <th>标题</th>
      <th>可视化亮点</th>
      <th width="120" align="center">状态</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><b>第一章</b></td>
      <td><b>🚩 NLP 基础概念</b></td>
      <td>
        • NLP 发展时间轴（1940s 早期探索 → 符号主义与统计 → 深度学习时代）<br>
        • 词表示演进：VSM / One-Hot → N-gram → Word2Vec → ELMo<br>
        • NLP 任务全景：中文分词、子词切分、词性标注、文本分类、实体识别、关系抽取、文本摘要、机器翻译、自动问答
      </td>
      <td align="center">🟢 已发布</td>
    </tr>
    <tr>
      <td align="center"><b>第二章</b></td>
      <td><b>🔧 Transformer 架构</b></td>
      <td>
        • 端到端数据流逐步演示：原始输入 → Tokenizer → Embedding → Self-Attention → Encoder 加工 → 输出 → Mask Attention → Cross Attention → 生成<br>
        • 组件拆解：Encoder Layer、LayerNorm、Multi-Head Attention、MLP 前馈网络、Decoder、Masked Self-Attention、Cross Attention、Embedding + 位置编码<br>
        • 完整流程总结视图
      </td>
      <td align="center">🟢 已发布</td>
    </tr>
    <tr>
      <td align="center"><b>第三章</b></td>
      <td><b>🚀 预训练语言模型</b></td>
      <td>
        • BERT/RoBERTa/ALBERT/T5/GPT/LLaMA/GLM 七大经典模型<br>
        • 三大架构分支：Encoder-Only、Decoder-Only、Encoder-Decoder<br>
        • 两类预训练任务：MLM（掩码语言模型）、CLM（因果语言模型）<br>
        • 演进时间线：2018-2024 六年发展史
      </td>
      <td align="center">🟢 已发布</td>
    </tr>
  </tbody>
</table>

<br>

## 🎬 在线预览

<div align="center">

```
 ┌─────────────────────────────────────────────────────────┐
 │  🧠 文档中心                                  🔍 搜索...  │
 ├───────────────┬─────────────────────────────────────────┤
 │  📂 Happy-LLM  │                                         │
 │   ▸ 第一章 NLP │     ╭───────────────────────────╮       │
 │   ▸ 第二章 TF  │     │   🎞️  逐步可视化动画      │       │
 │  📂 进阶       │     │   沿时间轴徐徐展开…        │       │
 │  📂 其他       │     ╰───────────────────────────╯       │
 │                │            [ 上一步 ]  [ 下一步 → ]      │
 └───────────────┴─────────────────────────────────────────┘
```

*图：首页文档中心交互界面示意（暗色主题 + 薄荷绿高亮）*

</div>

<br>

## 🚀 快速开始

本项目是**纯静态网站**，无需安装任何环境。三种方式任选其一：

### 方式一：直接双击（最简单 ⭐）

```bash
# 1. 下载本项目
git clone https://github.com/<your-name>/Happy-LLM-learn.git

# 2. 双击打开首页
#    Windows:  在资源管理器中双击 index.html
#    macOS:    open index.html
#    Linux:    xdg-open index.html
```

### 方式二：本地起一个服务器（推荐，避免跨域限制）

```bash
# Python 3
python -m http.server 8000

# 或 Node.js (需先 npm i -g serve)
serve .

# 然后浏览器访问 👉 http://localhost:8000
```

### 方式三：直接看某一章

每章都是**独立、自包含**的单文件 HTML，可单独打开：

```
chapters/unit-1.html   ← 第一章：NLP 基础概念
chapters/unit-2.html   ← 第二章：Transformer 架构
chapters/unit-3.html   ← 第三章：预训练语言模型
```

> 💡 **Tip**：每个章节文件内嵌了全部 CSS 与 JS，无外部依赖（仅引用 Google Fonts 与 Font Awesome CDN），断网也可离线浏览主体内容。

<br>

## 🎨 可视化方法论

本项目不是「手写」出来的，而是**用一套标准化的 Prompt 模板 + AI 协作**生成的。我们沉淀了一份可视化方法论，保证每一章风格统一、体验一致。

### 🔁 生成流水线

```
   ┌──────────────┐     ┌─────────────────┐     ┌──────────────────┐
   │ Happy-LLM    │ ──▶ │  AI 结构化拆解   │ ──▶ │  逐帧可视化 HTML  │
   │ .pdf 原始教材 │     │ (按 Prompt 模板) │     │  (单文件·可交互)  │
   └──────────────┘     └─────────────────┘     └──────────────────┘
                                ▲                         │
                                │                         ▼
                         ┌──────┴───────┐          ┌──────────────┐
                         │ 可视化 Prompt │ ◀────────│  人工校对打磨  │
                         │   模板.md     │          └──────────────┘
                         └──────────────┘
```

### 📐 设计原则（Prompt 模板约定）

- **渐进披露**（Progressive Disclosure）：信息不一次倾倒，按步骤揭示
- **一图胜千言**：能用图示表达的，绝不堆文字
- **一致视觉语言**：统一的暗色主题、字体、动效曲线、配色变量
- **单文件交付**：每个知识点一个自包含 HTML，便于分享与归档

> 想了解我们如何「指挥」AI 产出这些页面？查看 [`dcos/可视化Prompt模板.md`](./dcos/可视化Prompt模板.md) 📄

<br>

## 🛠️ 技术栈

| 层 | 技术 | 用途 |
|:---|:---|:---|
| 🏗️ 结构 | **HTML5** | 语义化骨架 |
| 🎨 样式 | **CSS3** + CSS 变量 | 暗色主题、动效、响应式布局 |
| ⚙️ 逻辑 | **原生 JavaScript** | 步骤切换、时间轴渲染、组件交互 |
| 🔤 字体 | **Noto Sans SC** (Google Fonts) | 中文排版 |
| 🎯 图标 | **Font Awesome 6.5** | 界面图标体系 |
| 🤖 生产 | **AI 协作** | 内容结构化与可视化代码生成 |

> **没有** React / Vue / Node / Webpack / Tailwind —— 故意保持极简，让任何人都能读懂源码、自由改造。🌱

<br>

## 📁 项目结构

```
Happy-LLM-learn/
├── index.html                  # 🏠 网站首页（文档中心 + 侧边栏导航）
├── chapters/                   # 📚 可视化章节（每章一个自包含 HTML）
│   ├── unit-1.html             #    第一章：NLP 基础概念
│   └── unit-2.html             #    第二章：Transformer 架构
├── dcos/                       # 📦 源材料与方法论（原始 PDF + Prompt 模板）
│   ├── Happy-LLM.pdf           #    《Happy-LLM》原始教材
│   └── 可视化Prompt模板.md      #    AI 可视化生成的标准化 Prompt
└── README.md                   # 📖 你正在看的这个文件
```

> 📝 注：源材料目录名为 `dcos/`（保留项目既有命名）。所有可视化页面均由该目录下的 PDF 与 Prompt 模板协同产出。

<br>

## 🗺️ 路线图

我们计划持续把《Happy-LLM》后续章节「视觉化」。欢迎在 Issues 区许愿你最想看的章节 👇

- [x] ✅ 第一章 · NLP 基础概念
- [x] ✅ 第二章 · Transformer 架构
- [ ] 🚧 第三章 · （规划中）
- [ ] 🔲 大模型预训练流程可视化
- [ ] 🔲 指令微调（SFT）与 RLHF 互动演示
- [ ] 🔲 推理优化（量化 / KV Cache）图解
- [ ] 🔲 全站暗 / 亮主题切换
- [ ] 🔲 章节进度记忆（localStorage）

<br>

## 🤝 参与贡献

这是一个开放的视觉化学习项目，欢迎任何形式的参与：

- 🐛 **报告问题**：发现 Bug 或显示异常，请提 [Issue](../../issues)
- 💡 **许愿章节**：想看哪个主题被可视化？在 Issue 里告诉我们
- ✍️ **改进内容**：欢迎提交 PR 优化文案、动效或新增章节
- 🎨 **设计打磨**：UI / 动效 / 配色方面的建议都非常欢迎

### 生成一个新章节

1. 阅读 [`dcos/可视化Prompt模板.md`](./dcos/可视化Prompt模板.md)，理解可视化规范
2. 取《Happy-LLM.pdf》中相应章节，按模板「指挥」AI 拆解
3. 产出自包含的 `chapters/unit-N.html`
4. 在 `index.html` 的 `CHAPTERS` 数组中登记新章节
5. 提交 PR 🎉

<br>

## 📖 关于 Happy-LLM

《Happy-LLM》是一本面向大众的大语言模型科普 / 学习读物，致力于用通俗的语言讲清楚 LLM 的原理。本项目在其内容基础上进行**二次视觉化创作**，以辅助学习理解。原始教材版权归原作者所有。

<br>

## 📄 许可证

本项目代码与可视化作品采用 **MIT License** 开源。

原始《Happy-LLM》PDF 教材版权归原作者所有，本项目仅用于学习交流目的。

<br>

---

<div align="center">

**如果这个项目对你学习 LLM 有所帮助，给个 ⭐ Star 是对我们最大的鼓励！**

<p>
  <sub>Built with ❤️ &nbsp;·&nbsp; Powered by AI &nbsp;·&nbsp; Crafted for Learners</sub>
</p>

<p>
  <a href="#-happy-llm-learn">⬆ 回到顶部</a>
</p>

</div>
