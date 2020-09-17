# LTUThesis 文档类

<font color=blue>**辽宁工程技术大学博士学位论文 LaTeX 模板**</font>

## 概述

由于辽宁工程技术大学没有提供学位论文 LaTeX 模板，用其提供的 Word 模板排版学位论文异常痛苦，本人在此毕业之际编写了此 LTUThesis LaTeX 文档类作为辽宁工程技术大学博士学位论文 LaTeX 模板，旨在简化博士学位论文排版工作，希望此绵薄之力对广大辽工大博士有所帮助。

本模板严格按照辽宁工程技术大学<font color=magenta>研究生院</font>发布的 <font color=magenta>2018 年版博士学位论文 Word 模板</font>的要求编制而成，辽工大 2018 版博士学位论文 Word 模板适用的场景均能使用本模板。

## 使用方法

本模板支持 <font color=cyan>xeTeX</font> 和 <font color=cyan>xeLaTeX</font> 编译器，提供的源码文件为 <font color=cyan>LTUThesis.dtx</font>，可生成的文件包括：

+ README.MD   LTUThesis 文档类概述及使用说明，也就是本文件。
+ LTUThesis.ins   LTUThesis 文档类安装文件。为了与标准的 LaTeX 宏包/文档类文件组织架构接轨，本模板提供的 LTUThesis.dtx 文件可以生成 .ins 安装文件。
+ <font color=magenta>LTUThesis.cls</font>   LTUThesis 文档类文件，这是本模板的<font color=magenta>核心文件</font>，作为博士学位论文模板使用。
+ <font color=magenta>LTUThesis.pdf</font>   LTUThesis 文档类的<font color=magenta>用户手册文件</font>，详细介绍本模板提供的接口及使用方法。

本模板支持的两种编译器生成的文件不同，具体来讲：

+ <font color=cyan>使用 xeTeX 编译</font>(<font color=red>在终端中使用命令 xetex LTUThesis.dtx</font>)，生成除 LTUThesis.pdf 以外的其它文件。
+ <font color=cyan>使用 xeLaTeX 编译</font>(<font color=red>在终端中使用命令 xelatex LTUThesis.dtx</font>)，生成本模板所能生成的全部文件。

## 许可声明

本作品可在[LaTeX Project Public License(LPPL)](http://www.latex-project.org/lppl.txt)的 1.3c 或更高版本许可下分发或修改。

版权所有 (C) 2020&ndash;2025 王万里 <wwlswj@163.com>