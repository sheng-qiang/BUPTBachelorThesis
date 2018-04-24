# 北京邮电大学本科学位论文模板
* 作者：Caspar Zhang <casparant@gmail.com>
* 修改：Bing Hsu <hello@antinucleon.com>
* 修改：Guohua Wu <ghmeta@163.com>
* 修改：Qiang Sheng<sqyx008@outlook.com>

# 主要修改
* 加入外文译文板块，将附录合并于主文件，将封面、诚信声明改为PDF导入，修正了部分参考文献的格式；部分格式依据2018年的本科毕设指导手册修改。

# 系统需求
Windows + Xelatex

建议安装TexLive，同时安装TexWorks

直接打开main.tex即可操作

# 如何使用
编辑以下文件

- main.cfg: 包含了论文中需要填写的项目，比如论文名称等。论文的致谢部分也放在了这里。

- abstract.cfg: 包含了论文的中英文摘要。

- main.tex: 论文的主体、附录、外文译文

- bib.ref: 论文的参考文献库

用素材填充以下文件夹

- pictures:将图片放入该文件夹

- docs：将封面、诚信声明、外文文献原文的PDF放入该文件夹，为了保持清晰度，请在从Word输出PDF时尽可能选择**高质量**的设置

# 编译

在TexLive环境下

先用XeLatex编译一遍；

再用bibTex编译一遍；

再用XeLatex编译一遍。

（如果里面引用号码没有显示，就再XeLatex编译一遍。）

# 初始发布日期
2018/4/24

# BTW
希望能有北邮的开源组织来维护和模块化本科生毕设Latex模板……

（当然更希望北邮的教务部门**锐意进取、大胆创新、敢为人先**地提供**官方**的毕设Latex模板）
