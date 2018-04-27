# 北京邮电大学本科学位论文模板
* 作者：Caspar Zhang <casparant@gmail.com>
* 修改：Bing Hsu <hello@antinucleon.com>
* 修改：Guohua Wu <ghmeta@163.com>
* 修改：Qiang Sheng<sqyx008@outlook.com>

# 主要修改
- 加入外文译文和原文板块
- 将附录合并于主文件
- 将封面、诚信声明改为PDF导入
- 修正了部分参考文献的格式
- 修正正文行间距为1.2倍
- 其它部分格式依据2018年的本科毕设指导手册修改。

# 系统需求
Windows + XeLaTeX

建议直接安装TeX Live（其中已包含需要的XeLaTeX和BibTeX），同时安装TeXworks

传送门：https://www.tug.org/texlive/

流量不多的同学可以到BYRBT去下载

直接打开main.tex即可操作

# 如何使用
编辑以下文件

- main.cfg: 包含了论文中需要填写的项目，比如论文名称等。论文的致谢部分也放在了这里

- abstract.cfg: 包含了论文的中英文摘要

- main.tex: 论文的主体、附录、外文译文

- bib.ref: 论文的参考文献库

用素材填充以下文件夹

- pictures:将图片放入该文件夹

- docs：将封面、诚信声明、外文文献原文的PDF放入该文件夹，为了保持清晰度，请在从Word输出PDF时尽可能选择**高质量**的设置（修正官方缺陷的封面、诚信声明的word版已放入该文件夹，编辑并保存为PDF即可）

# 编译

在TeX Live环境下

先用XeLaTeX编译一遍；

再用BibTeX编译一遍；

再用XeLaTeX编译一遍。

（如果里面引用号码没有显示，就再XeLaTeX编译一遍。）

# 初始发布日期
2018/4/24

# FAQ
- **Q：为什么我在TeXworks中编译，到“Require XeLaTeX”处就不动了？**

 A:正如编译提示所言，它需要XeLaTeX。请注意编辑器左上角是否选择“XeLaTeX”，默认状态下是pdfLaTeX。
 
- **Q:引用文献的BibTeX文件可以从哪里获取？**

 A:几乎任何学术文献库都会提供BibTeX格式的引用数据，你可以使用**JabRef**来管理和自动生成你引用文献的BibTeX。但在引用量不大的情况下，直接去学术搜索引擎和数据库（Google Scholar/IEEEXplore/ACM digital library/Springer Link/必应学术/百度学术）或学术组织官网（CVF）去复制也不麻烦。

# BTW
希望能有北邮的开源组织来维护和模块化本科生毕设LaTeX模板……

（当然更希望北邮的教务部门**锐意进取、大胆创新、敢为人先**地提供**官方**的毕设LaTeX模板）
