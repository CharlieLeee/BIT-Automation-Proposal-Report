# Proposal Report 开题报告

此文件夹中包含了北京理工大学毕业设计（论文）的开题报告提交内容。

### 关于本模板

源项目为[BITHESIS](https://github.com/BITNP/BIThesis)中的[proposal-report](https://github.com/BITNP/BIThesis-scaffold/tree/main/proposal-report)，模板根据自动化学院2017级的要求有所更改 

### 教程

哔哩哔哩弹幕网：[BIThesis —— 教你优雅地撰写论文 | LaTeX 毕设模板系列教程](https://www.bilibili.com/video/BV1GT4y1V78d/)

[BIThesis Wiki: 毕业设计论文](https://bithesis.bitnp.net/Guide/3-Templates/Final-Graduation-Thesis.html)

### 项目结构

```
├── main.tex: 开题报告的开始文件（主文件）
├── misc: 
│   ├── cover.tex：开题报告封面
│   ├── logo.pdf: 北理logo矢量图
│   └── reviewTableBlank.pdf：开题报告 PDF 格式的「评审表」
├── main.pdf：开题报告编译得到的 PDF 文件
└── ref.bib: 开题报告的参考文献 BibTeX 数据库
```

### 编译方式
```
-> xelatex
-> biber
-> xelatex
-> xelatex
```
