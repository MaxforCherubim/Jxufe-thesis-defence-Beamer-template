[![jxufe](imgs/logos/江西财经大学-logo.svg)](https://www.jxufe.edu.cn/)

# 江西财经大学答辩Beamer模板

[![License](https://custom-icon-badges.demolab.com/github/license/MaxforCherubim/Jxufe-thesis-defence-Beamer-template?logo=law)](https://opensource.org/licenses/MIT) [![LaTeX](https://img.shields.io/badge/LaTeX-Beamer?logo=latex&logoColor=%23008080)](https://www.latex-project.org/) [![Quarto](https://img.shields.io/badge/Quarto-Beamer?logo=quarto&logoColor=%2339729E)](https://quarto.org/)

为酱菜学子提供方便好用的答辩Beamer形式Quarto模板

## 目录

- [项目概述​](#项目概述)
- [使用方法​](#使用方法)
- [注意事项​](#注意事项)
- [贡献指南​](#贡献指南)
- [联系方式​](#联系方式)
- [许可证信息​](#许可证信息)

## 项目概述​

- 本项目为[江西财经大学硕士毕业论文全流程]的子项目
- 项目起初源于开题答辩，使用的是Beamer形式的幻灯片进行开题答辩
- 本项目在[Github]和[Gitee]上同步更新，欢迎各位学弟学妹提交反馈，共同完善此模板

> [!TIP]
> [Beamer]是一款基于[$\LaTeX$]的幻灯片制作工具
>   1. Beamer优势是输出格式为PDF，具有较高的打印质量，同时不易更改，是个较为静态无交互的幻灯片。
>   2. 显然使用Beamer制作的幻灯片作为PDF，可以轻松在任何平台上浏览；你可以随意使用自己喜欢的字体、排版等风格；导出的幻灯片可以静态地呈现你的一切，不受设备因素影响。
>   3. 劣势是不太支持动画效果，也没有多少交互式体验，是挺适合数学类论文展示需求。

- 本项目特别之处在于使用[Quarto]来输出[Beamer]幻灯片
    1. 这样无需学习LaTeX语法或者少量学习，甚至AI输出部分，就可以轻松得到所需的Beamer幻灯片
    2. 本质是使用Quarto来驾驭Beamer输出，所以只需一个Quarto模版即可

> [!TIP]
> <a href="https://quarto.org/"><img src="imgs/logos/quarto.png" style="vertical-align: middle; margin-top: -2px" width="80"></a>是一款优秀的排版系统，可以输出HTML，PDF，Word等多种格式的文档
>   1. Quarto最大的优势是可以在一个文档中同时数学文字和代码，而且代码可以直接运行，其运行结果直接嵌入文档中，这就使得文档本身是可以自动化的。比如根据不同客户的数据输出各自的报告，只需要准备好Quarto模版和数据，就可以直接生成成百上千的客户报告，还是精排的。
>   2. 劣势是学习曲线较陡峭，且自定义程度不算高，有些个性化需求需要自己写代码实现。

## 使用方法​

1. 下载并安装Quarto，具体教程请参考[Get Started]

> [!TIP]
> MacOS的可以使用brew安装

2. 在Vscode（建议）中安装Quarto插件
3. Git clone本项目到本地
4. 在Vscode中打开本项目，修改Quarto模版文件内容为你自己的内容，运行后即可输出你的Beamer幻灯片

## 注意事项​

1. 强烈建议先仔细学习一下Quarto的Get Started章节，熟悉Quarto的基本用法
2. 本项目较为傻瓜，安装好Quarto和Vscode对应的Quarto插件后，就可以运行本项目了，排版自己的Beamer幻灯片了。如果在使用过程中产生了多种问题，请在[讨论区]创建相关讨论，我都会尽力解答的
3. 由于Quarto的不断更新，可能会导致本项目产生Bug，除此之外还可能会有其他Bug，请在Github上提交[issues]，我会及时修复
4. 本项目模版使用的字体是[霞鹜文楷]字体族中的[LXGW Bright]字体，本项目并没有附带该字体，感兴趣的可以自行根据链接下载使用，或者使用自己喜欢的字体

> [!NOTE]
> LXGW Bright 是由Ysabeau系列字体（英文）与霞鹜文楷系列字体（中文）合并而成的字体

## 贡献指南​

- 本项目强烈呼吁各位使用者即各位学弟学妹提交反馈，包括但不限于在使用过程中遇到的问题、想到的建议，甚至是小白问题都可以在讨论区创建讨论，我会及时参与讨论的！**我们的所有互动都会成为后来者的学习资料，请积极参加！**
- 如果对本项目感兴趣，甚至想要进一步开发，欢迎提交PR！

## 联系方式​

- 作者：[章迎潭]
- 导师：[马海强教授]
- 邮件：<EMAIL>bay237580157@outlook.com</EMAIL>

## 许可证信息​

本项目开源许可证为[MIT license]

[回到顶部](#目录)

<!-- 引用链接 -->
[江西财经大学硕士毕业论文全流程]: https://github.com/MaxforCherubim/Jxufe-master-thesis-process
[Github]: https://github.com/MaxforCherubim/Jxufe-thesis-defence-Beamer-template
[Gitee]: https://gitee.com/MaxforCherubim/Jxufe-thesis-defence-Beamer-template
[Beamer]: https://github.com/josephwright/beamer
[$\LaTeX$]: https://www.latex-project.org/
[Quarto]: https://quarto.org/
[Get Started]: https://quarto.org/docs/get-started/
[讨论区]: https://github.com/MaxforCherubim/Jxufe-thesis-defence-Beamer-template/discussions
[issues]: https://github.com/MaxforCherubim/Jxufe-thesis-defence-Beamer-template/issues
[霞鹜文楷]: https://github.com/lxgw/LxgwWenKai
[LXGW Bright]: https://github.com/lxgw/LxgwBright
[章迎潭]: https://github.com/MaxforCherubim
[马海强教授]: https://stat.jxufe.edu.cn/news-show-7166.html
[MIT license]: https://opensource.org/licenses/MIT
