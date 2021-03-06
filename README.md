Rime输入法简中用户新手套餐
==========

<a href="http://rime.im/">Rime输入法</a>新手入门“套餐”。目前主要针对windows平台（小狼毫）的简体中文全拼用户（这也区分得太细了吧！）


<h1>使用方法：</h1>

1.点击右侧【<a href="https://github.com/ACsediment/RimeNewbie/archive/master.zip">download ZIP</a>】按钮下载压缩包。

2.安装rime输入法后，复制user-folder下的文件，点击开始菜单-小狼毫输入法-【小狼毫】用户文件夹，粘贴替换其中文件<del> ，将app-folder下的文件放到程序文件夹的data文件夹中</del>。

3.点击开始菜单-小狼毫输入法-【小狼毫】重新部署。

警告：本“套餐”是针对首次使用者设计的，可能会替换您之前做的自定义设置（但不会影响用户词典——用户积累的词），请留意。

（涉及文件：default.custom.yaml，luna_pinyin_simp.extended.dict.yaml，symbols.yaml，weasel.custom.yaml）
（附带影响到：default.yaml，luna_pinyin_simp.custom.yaml，weasel.yaml）

<h2>自定义</h2>
需要修改自定义设置的用户，只需要修改用户文件夹下的default.custom.yaml、weasel.custom.yaml和luna_pinyin_simp.extended.dict.yaml即可。常见的自定义选项都已经备好了，并有注释，应该很好理解。

各文件作用说明：

default.custom.yaml 定义rime输入法的输入特性，包括输入方案，选词，按键，符号，快捷键等。

luna_pinyin_simp.extended.dict.yaml 添加自定义词，增删细胞词库。（细胞词库选择方法：打开文件，选择你要使用的细胞词库，去掉该行的注释符号[#号]。注意，如果你开启了不存在的细胞词库，可能会导致重新部署无效）

weasel.custom.yaml：定义输入法的外观（横排显示竖排显示，长宽高，右下角图标等），并可以在指定程序中关闭中文输入。


<h1>套餐内容：</h1>

*默认启用“朙月拼音·简化字”方案。

*开启symbols.yaml方便输入特殊符号。

*开启候选词横排。

*将多数可以自定义的设置部署到了default.custom.yaml和weasel.yaml中，并加以注释说明，方便用户进行自定义，避免新手从零开始时，被语法错误打退。

*默认开启“朙月拼音·简化字”方案的自定义文件luna_pinyin_simp.custom.yaml。

*默认开启“朙月拼音·简化字”扩展词典luna_pinyin_simp.extended.dict.yaml，方便用户添加自造词。

*设定了一套“细胞词库”使用方法并提供一些词库，方便用户选择使用细胞词库，并教会用户添加新“细胞词库”的方法。

*提供颜文字，但默认不开启。可以在luna_pinyin_simp.extended.dict.yaml非常方便地开启之。

*兼容<a href="https://github.com/rime-aca">rime翰林院</a>的<a href="https://github.com/rime-aca/dictionaries/tree/master/luna_pinyin.dict">朙月拼音扩充词库</a>项目。设置已经完成，下载所需词库放在“用户文件夹”中即可。




<h1>附录</h1>
<h2>参考项目</h2>
<h3>Rime分类词库</h3>
介绍：http://tieba.baidu.com/p/3295182428

项目地址：https://tower.im/projects/7948b427066f46b498aa711c4732c92b/

该项目成果将汇总至<a href=https://github.com/rime-aca>rime翰林院</a>的词典项目https://github.com/rime-aca/dictionaries
并发布到朙月拼音扩充词库中

<h3>Rime自动配置工具</h3>
可以自动配置weasel.custom.yaml 和 default.custom.yaml

http://tieba.baidu.com/p/3169492032

<h3>深蓝词库转换器</h3>
用于将各个输入法的词库进行相互转换。
项目地址：<a href="https://code.google.com/p/imewlconverter/">深蓝词库转换器</a>
注意事项： <a href="http://tieba.baidu.com/p/2757690418">关于导入词库及「深蓝词库转换」的正...</a>

<h2>编辑yaml文件一些经验</h2>
建议使用notepad++，UltraEdit，vim之类的纯文本编辑工具进行编辑。

井号“#”后面的内容，比如本条，都是注释，不起代码的作用，只是用于说明。

使用两个空格作为一个缩进，不能使用tab。

文件中使用的符号几乎都是英文符号。

避免混乱，建议统一搞成UTF-8编码。

<h2>更新日志</h2>

2014.11.3 项目建立。创建细胞词库：植物学 化学化工 金融 地理地质 股票基金 中西医 纳兰性德185首 诗经全文 魔兽争霸与dota 颜文字

2015.6.1 为symbols文件添加帮助，输入/help显示该文件定义的各类代码。

<h2>todo</h2>

自定义字符。需要修改与symbols.yaml相关的内容并添加注释

<h2>已知问题及解决</h2>

*使用notepad2打开词库时，需要按F8进行编码转换才能正确显示（或者在files-encoding-recode中选择UTF-8）

*在luna_pinyin_simp.extended.dict.yaml中调用不存在的子词库时，会导致重新部署异常。建议注释掉/删掉不存在的词库引用

<h1>致谢</h1>
（不仅是项目的致谢，也是作为个人表示由衷感谢...所以有一点多）

佛振 等Rime全体贡献者

Rime翰林院全体成员

<a href="https://code.google.com/p/imewlconverter/">深蓝词库转换器</a>作者及全体贡献者

百度Rime贴吧大小吧主，以及全体活跃大神

同时参考了他们的作品：

百度Rime贴吧  半月湾C  <a href="http://tieba.baidu.com/p/3288634121">《致第一次安装 RIME 的你之修订版》</a>

百度Rime贴吧  文科980195412  颜文字码表

百度Rime贴吧  just4u1314  <a href="http://tieba.baidu.com/p/2757690418">《关于导入词库及「深蓝词库转换」的正...》</a>

搜狗细胞词库工作人员及贡献者

诗词名句网
