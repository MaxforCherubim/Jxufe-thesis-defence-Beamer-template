![jxufe](imgs/logos/江西财经大学-logo.svg)

# 江西财经大学答辩Beamer模板

为酱菜学子提供方便好用的答辩Beamer形式Quarto模板

## 项目概述​

- 本项目为江西财经大学硕士毕业论文全流程的子项目
- 项目起初源于开题答辩，使用的是Beamer形式

> [Beamer](https://github.com/josephwright/beamer)是一款基于[$\LaTeX$](https://www.latex-project.org/)的幻灯片制作工具

    1. Beamer优势是输出格式为PDF，具有较高的打印质量，同时不易更改，是个较为静态无交互的幻灯片。
    2. 显然使用Beamer制作的幻灯片作为PDF，可以轻松在任何平台上浏览；你可以随意使用自己喜欢的字体、排版等风格；导出的幻灯片可以静态地呈现你的一切，不受设备因素影响。
    3. 劣势是不太支持动画效果，也没有多少交互式体验，是挺适合数学类论文展示需求。

- 本项目特别之处在于使用[Quarto](https://quarto.org/)来输出Beamer
    1. 这样无需学习LaTeX语法或者少量学习乃至AI输出部分，就可以轻松得到所需的Beamer幻灯片
    2. 本质是使用Quarto来驾驶Beamer输出，所以只需一个Quarto模版即可

> <a href="https://quarto.org/"><img src="imgs/logos/quarto.png" style="vertical-align: middle; margin-top: -2px" width="80"></a>是一款优秀的排版系统，可以输出HTML，PDF，Word等多种格式的文档

    1. Quarto最大的优势是可以在一个文档中同时数学文字和代码，而且代码可以直接运行，其运行结果直接嵌入文档中，这就使得文档本身是可以自动化的。比如根据不同客户的数据输出各自的报告，只需要准备好Quarto模版和数据，就可以直接生成成百上千的客户报告，还是精排的。
    2. 劣势是学习曲线较陡峭，且自定义程度不算高，有些个性化需求需要自己写代码实现。

## 使用方法​

1. 下载并安装Quarto，具体教程请参考[Get Started](https://quarto.org/docs/get-started/)
> MacOS的可以使用brew安装
2. 在Vscode（建议）中安装Quarto插件
3. Git clone本项目到本地
4. 在Vscode中打开本项目，修改Quarto模版文件内容为你自己的内容，运行后即可输出你的Beamer幻灯片

## 注意事项​

1. 强烈建议先仔细学习一下Quarto的[Get Started](https://quarto.org/docs/get-started/)章节，熟悉Quarto的基本用法
2. 本项目较为傻瓜，安装好Quarto和Vscode对应的Quarto插件后，就可以运行本项目了，排版自己的Beamer幻灯片了。如果过程中产生了多种问题，请在讨论区创建相关讨论[点击前往讨论区](discussions)，我都会尽力解答的
3. 由于Quarto的不断更新，可能会导致本项目产生Bug，除此之外还可能会有其他Bug，请在Github上提交issue，我会及时修复

## 贡献指南​

<!-- 鼓励用户对模板提出改进建议、报告格式错误或不规范处。​
说明贡献方式，如提交 Pull Request、在 Issues 中反馈等。​
对贡献者表示感谢并提及贡献会带来的积极影响。​ -->

## 联系方式​

<!-- 留下模板维护者或项目发起人的邮箱等联系方式，方便交流。​ -->

## 许可证信息​

<!-- 说明模板所采用的开源许可证类型及相关权益规定。 -->
