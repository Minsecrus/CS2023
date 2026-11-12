# CS2023 中文全译本与排版项目

**《计算机科学课程体系 2023》（Computer Science Curricula 2023, CS2023）**
由国际计算机学会（ACM）、电气电子工程师学会计算机学会（IEEE-CS）和国际人工智能促进协会（AAAI）联合研制发布。

本项目提供 CS2023 完整规范的中文高质量翻译与出版级 LaTeX 双栏排版源码及编译好的 PDF 文件。

- **译者**：Minsecrus
- **目标发布文件**：`CS2023.pdf`（125 页，双栏排版，中文字体支持）

## 项目结构

```text
├── CS2023.tex          # LaTeX 主控文件
├── CS2023.pdf          # 编译成品的出版级 PDF（125页）
├── chapters/           # 19 个知识领域与前言的完整章节 LaTeX 源码
│   ├── 00_preface.tex
│   ├── 01_al.tex
│   ├── 02_ar.tex
│   ├── ...
│   └── 18_curriculum.tex
├── extracted_images/   # 官方图表资源
├── terminology.json    # 核心术语与知识单元对照表
├── .gitignore          # 忽略 LaTeX 编译中间文件
└── README.md
```

## 编译方式

本项目推荐使用 XeLaTeX 进行编译：

```bash
xelatex -interaction=nonstopmode CS2023.tex
xelatex -interaction=nonstopmode CS2023.tex
```
