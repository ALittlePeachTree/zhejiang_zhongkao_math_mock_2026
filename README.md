# Zhejiang Province 2026 Junior High School Academic Proficiency Examination · Mathematics Mock Paper

> *This is a Chinese-language mock exam for the Zhejiang Zhongkao (Grade 9 graduation exam).*
> *Full documentation in Chinese below. Source files (GeoGebra, LaTeX) are reusable.*

# 浙江省2026年初中学业水平模拟考试 · 数学卷

> *📥 正式试卷下载 (Word)* *Download Paper (Word)* 👉

> [zhejiang_zhongkao_math_mock_2026.docx](zhejiang_zhongkao_math_mock_2026.docx)

> *📄 正式试卷下载 (PDF)* *Download Paper (PDF)* 👉

> [zhejiang_zhongkao_math_mock_2026.pdf](zhejiang_zhongkao_math_mock_2026.pdf)

> *🔑 参考答案下载 (Word)* *Download Answer Key (Word)* 👉

> [zhejiang_zhongkao_math_mock_2026_answer.docx](zhejiang_zhongkao_math_mock_2026_answer.docx)

> *📄 参考答案下载 (PDF)* *Download Answer Key (PDF)* 👉

>  [zhejiang_zhongkao_math_mock_2026_answer.pdf](zhejiang_zhongkao_math_mock_2026_answer.pdf)

*本卷面向初三学生，整体难度略高于中考，压轴题达到竞赛入门水平，适合拔高训练。* 

***配套参考答案已同步发布，包含详细步骤。***

---

## 🏛️ 命题手记与创作缘起

这不仅是一份模拟卷，更是一次长达半年的命题实践。

最初并无编制整张试卷的计划。这一想法起源于2025年11月月考复习期间：我一时兴起随手画了一个几何图形，意外发现其蕴含丰富的命题可能——该图形后来发展为***第24题（压轴题）***。

从2025年11月的灵光乍现，到2026年定稿，这道题历经了约6个月的打磨。中间虽逢寒假搁置，但开学后我又重新投入优化。这道题是全卷的精华，很多巧妙的辅助线和结论并非刻意设计，而是图形本身蕴含的“神来之笔”，这种自然的几何美感让我深感震撼。

基于此，我于2026年3月下旬正式启动命题工作，最终完成了这份作品。

---

## 🧠 题目灵感与设计哲学

本试卷绝大部分题目由本人原创，灵感来源于跨学科的学习生活与对数学本质的思考。

* ***第13题***：源自一道高中解三角形题，图形虽相似，但条件已完全重构；
* ***第14题***：改编自平面向量单元的一道考试题，原题较为简单，我借此思路重新设计，提升了综合性；
* ***第16题***：最初来自班级数学测试。当时我未能用几何方法解答，老师讲解时采用余弦定理结合代数转化。后来，我偶然发现了一种纯几何解法，并意识到初中生亦可掌握，于是对原题进行改造，适当提高了难度；
* ***第20题***：由一位参加生物竞赛的同学提供原始思路，我对其进行了微调，并绘制了配套的统计图表；
* ***第21题***：源于一次做化学作业时“偷懒”的经历：为避免繁琐计算，我尝试了某种简化方法。虽属错误示范，但其背后蕴含有趣的数学逻辑，便将其改编为题目；
* ***第22题***：灵感诞生于语文摘抄课上——抄写疲倦时随手折纸，意外发现了一些几何规律，遂整理成题；
* ***第23题***：受同学所出的一道二次函数题启发。尽管原题模型较传统、计算量偏大，但我尝试转换设问角度，最终形成一道思路巧妙的新题。该题若采用命题预设的数形结合方法，解答简洁高效；也有同学尝试求导等高阶工具，但均不如原设计路径快捷；
* ***第24题（压轴）***：***全卷心血所在***。从11月到次年定稿，耗时半年。图形的巧合与辅助线的安排浑然天成，非刻意雕琢，却得自然之妙。

其余较难题目均邀请班级同学试做，并根据反馈对难度梯度、语言表述及逻辑严谨性进行了多轮调整。

---

## 🛠️ 制作工艺与工具链

*本试卷的制作遵循严谨的“数字化命题”工作流，确保图形精准、排版专业。*

*The workflow follows a rigorous digital authoring process to ensure precision and professional typesetting.*


| 环节 | 工具/平台 | 说明 |
| :-- | :-- | :-- |
| **技术支持** | 通义千问、*DeepSeek* | *JavaScript* 代码辅助、*LaTeX* 初稿撰写、语言润色以及*OCR*识别手写过程 |
| **文档转换** | *[Mathpix Snip](https://mathpix.com/)* | 将 *LaTeX* 代码批量转换为 *Word* 可编辑格式 |
| **图形绘制** | *[GeoGebra 经典版](https://www.geogebra.org/classic)* | 绘制所有几何、函数以及统计图表，保证一定精准度 |
| **最终排版** | *WPS* 文字 | 进行人工排版、分栏、、公式对齐、精修及最终校对 |

> 💡 **开源承诺**：所有制作过程中的源文件（`.ggb`, `.txt`, 原始扫描件等）均已开源，你可以复现每一道题的诞生过程。

> *All source files (`.ggb`, `.txt`, original scans, etc.) have been open-sourced, so you can reproduce the creation process of each and every question.*
---

## 📂 项目结构说明 / Project Structure

*本仓库不仅包含成品，更完整保留了从草稿到定稿的所有中间产物，供研究与复用。*

*This repository contains not only the final product, but also all intermediate files from draft to final version, for study and reuse.*

```text
zhejiang-zhongkao-math-mock-2026/
├── LICENSE                                  ← 开源许可证
│
├── README.md                                ← 本说明文档
│
├── zhejiang_zhongkao_math_mock_2026.docx                 ← ✅ 正式试卷 (Word版)
├── zhejiang_zhongkao_math_mock_2026.pdf                  ← ✅ 正式试卷 (PDF版)
├── zhejiang_zhongkao_math_mock_2026_answer.docx          ← ✅ 参考答案 (Word版)
├── zhejiang_zhongkao_math_mock_2026_answer.pdf           ← ✅ 参考答案 (PDF版)
├── signature_page_template.docx                          ← 签字页模板
│
├── assets/                                  ← 所有配套资源
│   ├── diagrams/                                        ← 静态配图 (如.jpg)
│   ├── geogebra/                                        ← 动态 GeoGebra 源文件 (.ggb)
│   └── paper_scans/                                     ← 试卷原始扫描件
│
├── draft/                                   ← 排版过程中的中间稿
│   ├── paper_draft.docx                                 ← Mathpix 导出的试卷初稿
│   └── answer_draft.docx                                ← Mathpix 导出的答案初稿
│
├── q24_legacy_draft/                        ← 第24题历史版本
│                                          
│
├── snippets/                                ← 辅助脚本与代码片段
│   ├── geogebra_italic_labels.txt                       ←GeoGebra 标签转斜体代码
│   └── latex_draft_for-mathpix.txt                      ← LaTeX 题目源码 (用于转换 Word)
│
└── workflows/                               ← 工作流快捷入口
    ├── open_geogebra.txt                                 ← 快捷打开 GeoGebra 绘图网站
    ├── open_mathpix.txt                                  ← 快捷打开 Mathpix 识别网站
    └── open_qianwen.txt                                  ← 快捷打开通义千问 AI 助手
```


---

## 🙏 特别感谢

几位正在我校参加***强基计划培训、专注数学与信息学竞赛的初三同学，以及我的数学老师和我的同班同学***，也提供了宝贵建议。感谢他们的建议与鼓励！特别感谢大家在试做第24题时提供的宝贵反馈，让这道题最终得以完善。

---

## 📜 开源许可 / License

*本试卷采用* ***[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议 (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)***。

*This work is licensed under a* ***[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)***.

✅ **署名 (BY)**：*请保留原作者声明*。
**Attribution**: *Please credit the original author*.

❌ **非商业 (NC)**：*不得用于商业盈利活动。*
**NonCommercial**: *Not for commercial use.*

🔄 **相同方式共享 (SA)**：*若改编发布，必须沿用相同许可协议。*
**ShareAlike**: *Adaptations must be shared under the same license.*

---
