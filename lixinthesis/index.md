# lixinthesis
A non-official LaTeX template for LIXIN


# 免责声明
本模板为作者免费编写制作, 由于个人精力有限, 难免有疏漏之处. **本人不对通过本模板撰写的毕业论文可以通过格式审查作任何明示或暗示的保证.** 编译之后的文档是否符合毕业论文的格式要求,需要使用者自行判断.

# 模板下载
请[点击这里下载](/docs/lixinthesis.zip)模板，里面包括具体使用说明以及示例文档：

* 模板使用说明 (main.pdf)
* 示例文档 (main.tex)

# TeXLive版本说明
目前可以确认的是，在TeX Live 2023可以正常运行本模板，如您电脑上的版本无法运行或者运行报错，请先检查版本，如版本有误，可以先自行下载安装TeX LiVe，如您对手动安装package不太熟悉，建议安装完整版本的。

# 常见错误及解决方法
1. 中文显示乱码， 检查编码方式需要设置为utf8.
2. 没有所需字体， 下载字体。
3. 如使用overleaf，请将simkai.ttf, simsun.ttf, times.ttc, simhei.ttf, timesbd.ttf几种种字体上传至主文件夹下。

# 修改记录

2024-5：

1. 第一次提交代码：在GitHub建立Project。
2. 第二次提交：
- 修改封面中的表格及提交日期，原因：Word中宋体加粗不是黑体。
- 修改各级标题格式，原因：模板中标题编号之后紧跟标题，不空行。
- 修改目录、参考文献格式，原因：参考文献、目录一倍行距。
- 修改摘要，原因：只要中的关键字是宋体加黑而非黑体。
- 修改脚注，原因：脚注编号为带圆圈的阿拉伯数字。
- 修改四级标题设置，原因：四级标题单独占一行，而非跟后文紧接。
- 加入listings宏包和tcolorbox宏包。
- 打开ctex的粗体设置，而不是重新定义字体，原因：overleaf 上没有simkai.ttf和simsun.ttcd等字体（overleaf的操作系统应该是ubuntu，其使用fandol字体代替win中的中易字体）。
- 添加使用说明。

2025-5
- 加入判断操作系统和字体是否存的句子，可以自动判断所需要的字体是否存在，如果存在，使用之；不存在使用CTEX在操作系统下的默认设置。
- Overleaf上可以运行，使用前请将simkai.ttf, simsun.ttf, times.ttc, simhei.ttf, timesbd.ttf几种种字体上传至主文件夹下。
- 将代码分为public和private两个版本，private仅供开发使用，public为公开版本。