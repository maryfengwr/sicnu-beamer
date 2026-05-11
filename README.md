# 四川师范大学 Beamer 模板

基于 [SINTEF Presentation](https://www.overleaf.com/latex/templates/sintef-presentation/jhbhdffczpnx) 主题及中国科学院大学风格改编版本，适配为四川师范大学风格。

## 主题色

`#2b614d`（RGB 43, 97, 77）

## 使用方法

```latex
\documentclass{beamer}
\usetheme{sicnu}
\usepackage{xeCJK}

\title{报告标题}
\subtitle{报告副标题}
\author{作者一、作者二}
\date{\today}

\titlebackground*{assets/background}

\begin{document}
\maketitle
% ...
\end{document}
```

## 文件说明

- `beamerthemesicnu.sty` — 主题样式文件
- `sicnucolor.sty` — 颜色定义文件
- `beamersicnu.tex` — 示例演示文稿
- `assets/` — 素材目录（logo、背景图等）

## 编译

建议使用 XeLaTeX：

```bash
xelatex beamersicnu.tex
xelatex beamersicnu.tex  # 第二次编译以生成目录
```

## License

GNU GPL v3
