# LaTeX Template For NPU thesis in CTex

[![License](https://img.shields.io/badge/license-GNU_General_Public_License_v3.0-blue.svg)](LICENSE)

本模板主要基于开源库[polossk/LaTeX-Template-For-NPU-Thesis](https://github.com/polossk/LaTeX-Template-For-NPU-Thesis) 之上修改而成，采用 ctex 对原模板重构。

## 新特性

- 使用 ctex 的 ctexbook 文档类
- 校徽可以选择采用[西北工业大学形象识别系统](https://news.nwpu.edu.cn/xcb/index/xxsbxt.htm)中提供的标准色矢量图（[彩色](cover/logo.pdf) or [黑白](cover/logo-black.pdf)）
- 字体默认使用系统字体，也可以在文档类配置中改变
- 参考文献使用 biblatex 提供的 gb7714-2015 标准支持
- nwpuname.ttf 使用相对位置无需安装
- 字体和字号使用 ctex 提供的接口
- 封面建议对学校的 Word 模版进行修改后导出为 PDF，再导入进 main.tex 文件

## 注意事项

- 间距和缩进和原版有一些差别，必要时根据最新论文标准进行修正
- 注意使用粗体字体，或者开启伪粗体
- 注意校徽使用可能的版权问题
