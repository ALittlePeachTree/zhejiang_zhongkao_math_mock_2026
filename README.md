# Zhejiang Province 2026 Junior High School Mathematics Mock Exam (Chinese Context)

> 🇨🇳 **This is a Chinese-language mock exam for the Zhejiang Zhongkao (Grade 9 graduation exam).**  
> Full documentation in Chinese below. Source files (GeoGebra, LaTeX) are reusable.


# 浙江省2026年初中学业水平模拟考试 · 数学卷

> **正式试卷下载** 👉 [zhejiang-zhongkao-math-mock-2026.docx](zhejiang-zhongkao-math-mock-2026/zhejiang-zhongkao-math-mock-2026.docx)

本卷面向初三学生，整体难度略高于中考，压轴题达到竞赛入门水平，适合拔高训练。

---

## 📖 创作缘起

最初并无编制整张试卷的计划。这一想法起源于2025年11月月考复习期间：我一时兴起随手画了一个几何图形，意外发现其蕴含丰富的命题可能——该图形后来发展为第24题，由此萌生了创作整份试卷的念头。

本模拟卷最早于2026年3月下旬启动命题工作，绝大部分题目由本人原创。

---

## 🧠 题目灵感来源

- **第13题**：源自一道高中解三角形题，图形虽相似，但条件已完全重构；
- **第14题**：改编自平面向量单元的一道考试题，原题较为简单，我借此思路重新设计，提升了综合性；
- **第16题**：最初来自班级数学测试。当时我未能用几何方法解答，老师讲解时采用余弦定理结合代数转化。后来，我偶然发现了一种纯几何解法，并意识到初中生亦可掌握，于是对原题进行改造，适当提高了难度；
- **第20题**：由一位参加生物竞赛的同学提供原始思路，我对其进行了微调，并绘制了配套的统计图表；
- **第21题**：源于一次做化学作业时“偷懒”的经历：为避免繁琐计算，我尝试了某种简化方法。虽属错误示范，但其背后蕴含有趣的数学逻辑，便将其改编为题目；
- **第22题**：灵感诞生于语文摘抄课上——抄写疲倦时随手折纸，意外发现了一些几何规律，遂整理成题；
- **第23题**：受同学所出的一道二次函数题启发。尽管原题模型较传统、计算量偏大，但我尝试转换设问角度，最终形成一道思路巧妙的新题。该题若采用命题预设的数形结合方法，解答简洁高效；也有同学尝试求导等高阶工具，但均不如原设计路径快捷。

其余较难题目均邀请班级同学试做，并根据反馈对难度梯度、语言表述及逻辑严谨性进行了多轮调整。此外，几位正在我校参加强基计划培训、专注数学与信息学竞赛的初三同学，以及我的数学老师，也提供了宝贵建议。

---

## 🛠️ 所用工具

| 用途 | 工具 |
|------|------|
| JavaScript 代码辅助、LaTeX 初稿撰写及语言润色 | 通义千问、DeepSeek |
| LaTeX 公式转 Word/WPS 格式 | [Mathpix](https://mathpix.com/) |
| 图形绘制 | [GeoGebra 经典版](https://www.geogebra.org/classic) |
| 文档整合与排版 | WPS 文字 |

> 💡 所有制作过程中的源文件（`.ggb`, `.txt`, 图片等）均已开源！

---

## 🙏 特别感谢

感谢我的数学老师、三班四班同学及强基培训学弟学妹们的建议与鼓励！

---

## 📂 项目结构说明 / Project Structure

```
zhejiang-zhongkao-math-mock-2026/
├── LICENSE                                ← 开源许可证（CC BY-NC-SA 4.0）  
│                                          ← Open source license (CC BY-NC-SA 4.0)
├── README.md                              ← 本说明文档  
│                                          ← This documentation file
├── zhejiang-zhongkao-math-mock-2026.docx  ← ✅ 正式试卷（推荐直接使用）  
│                                          ← Final exam paper (ready to print or share)
│
├── assets/                                ← 所有配套资源  
│                                          ← All supporting assets
│   ├── diagrams/          ← 静态配图（如 5.geo.png）  
│                          ← Static diagram images (e.g., 5.geo.png)
│   ├── geogebra/          ← 动态 GeoGebra 文件（如 5.ggb）  
│                          ← Interactive GeoGebra files (.ggb)
│   └── paper-scans/       ← 试卷原始扫描件  
│                          ← Scanned copies of original papers
│
├── draft/                                 ← 未排版中间稿  
│                                          ← Unformatted intermediate draft
│   └── paper-draft.docx   ← Mathpix 导出的草稿  
│                          ← Raw output from Mathpix
│
├── snippets/                              ← 创作过程中的代码片段  
│                                          ← Authoring code snippets
│   └── latex-draft-for-mathpix.txt  ← LaTeX 题目源码  
│                                    ← LaTeX source for Mathpix conversion
│
└── workflows/                             ← 工作流快捷入口  
                                           ← Workflow shortcuts
    ├── open-geogebra.txt   ← 快捷打开 GeoGebra 网站  
                            ← Opens https://www.geogebra.org/classic
    └── open-mathpix.txt    ← 快捷打开 Mathpix 网站  
                            ← Opens https://mathpix.com/
```

---

## 📜 开源许可 / License

本试卷采用 **[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-sa/4.0/)**。  
This work is licensed under a **[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)**.

✅ 欢迎使用、分享与改编，请注明出处  
✅ You are free to use, share, and adapt — **with attribution**  
❌ 不得用于商业用途  
❌ **Not for commercial use**  
🔄 若进行改编，请以相同许可协议发布  
🔄 Adaptations must be shared under the **same license terms**

---

## 📥 获取资料 & 后续更新 / Get Resources & Updates

- **GitHub 开源地址**：[（https://github.com/ALittlePeachTree/zhejiang-zhongkao-math-mock-2026）]  
  **Source code & all files**: [https://github.com/ALittlePeachTree/zhejiang-zhongkao-math-mock-2026]
- 若下载困难，欢迎私信索要全套资料！  
  Having trouble downloading? Feel free to message me for the full package!
- **参考答案将于近期上传，敬请期待！**  
  **Answer key coming soon!**


