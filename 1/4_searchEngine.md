# 善用搜索引擎
实际上, 技术圈的能力**绝大多数**是"基于云"的. 与其说一个人的技术很强大, 倒不如说, 这个人的检索能力很强, 外加经验积累很丰富.

实话实说, 之前我做过关于程序开发圈子使用百度和谷歌频次的调查. 调查的结果很让我意外 —— 如果程序开发是在断网的环境下进行的, 那么程序开发所消耗的时间和精力将是平常的两倍以上. 更甚, 有些小众用户的需求是完全没有办法通过现有知识面的理解来完成的.

这一点同样命中了我自己. 当然我并不是说程序员必须离不开百度和谷歌, 而是说, 对于大多数程序员来说, 百度和谷歌是一个不可缺少的重要检索工具.

我们在日常的开发和调试当中, 不免要遇到各种各样的问题和需求. 如果将这些没有见过的需求和问题全部自己来研究/询问他人解决, 那么将浪费相当大的人力物力. 很多时候我们需要的是快速有效的定位和解决问题, 而不是将程序的框架结构全部自己重新再来一遍 -- 这费时费力. 程序开发圈子都流行着"不重复造轮子"的这种说法, 也正是因为这个道理.

而快速查找问题解决方法的途径, 就是通过搜索引擎检索网络上已有的内容. 换句话说, 什么不会就搜什么教程, 然后一步步按照教程走.

**这不是在开玩笑, 更不是说技术圈就是用百度谷歌搜出来的**. 这样做根本上是因为我们每个人的精力是有限的, 总有一些需求我们接触不到. 但是知识经验是有一定通用性的, 因此我们只需要了解基本的操作方式和操作思路, 就可以利用现有的经验顺利完成任务.


# 用关键词来检索
为什么要用关键词来检索? 我们知道, 至少在这篇文章编写的2018年, 真正的高级人工智能还没有被世界发明出来. 换句话说, **机器是不会知道你这句话是什么意思的**.

但是百度和谷歌是如何来搜索你需要的内容的呢? 实际上, 这是一个关键词匹配的过程. 百度和谷歌将你输入的内容与海量的数据进行对比查询, 试图找出最佳的匹配结果, 并按照匹配程度返回给你. 这就是搜索引擎的工作原理.

这样的话, 你应该会发现一个很重要的问题: 返回结果的可靠性, 取决于你输入的数据. 举几个例子:

如果要搜索关于“windows下字体文件安装在哪个位置”的相关结果, 我们可以搜索“windows 字体 路径”, 也可以搜索“windows字体安装在哪个路径里面”. 前者是对关键词的提炼, 后者是常规的自然语言.

很显然前者的搜索结果要明显的好于后者. 这是因为前者全部是由于关键词组成的, 3个关键词缺一不可. 这几乎准确的定位了被搜索的文章需要出现哪些必要的信息, 从而将我们的搜索范围确定下来. 而后者包含了大量无用的自然语言描述, 将会对搜索结果造成不必要的干扰.

所以, 在使用百度或谷歌搜索时, 准确的命中关键词, 这非常重要.


# 常见的关键词提取方法
不同的场合, 关键词的提取也不同. 通常, 关键词要能够简明扼要的描述问题的中心, 也就是说, 看到关键词就能够大概知道你在做什么. 其次就是, 关键词要有原子性, 即这是一个基本的单词或短语, 不可再拆, 且没有歧义.

常见的关键词可以通过这些方法来提炼:

  1. 找到问题的中心词. 比如“windows下字体文件安装在哪个位置”这个问题, 关键点在于“windows系统”, “字体文件”, “安装字体文件的路径”. 而“windows系统”和“windows”作用是相同的, 因此“系统两个字”是冗余的. 以此类推, 我们可以提炼出“windows 字体 路径”这三个关键词.
  2. 用准行业术语. 还是“windows下字体文件安装在哪个位置”这个问题, 计算机术语“路径”相对于“位置”要明显的准确的多, 其搜索结果也会更专业和准确. 而行业术语可以通过日常积累逐渐了解.
  3. 对于一些程序的报错信息, 比如“不是有效的win32应用程序”, 其报错信息本身就是一个关键词. 因此我们可以搜索程序名+错误信息. 比如“mysql 不是有效的win32应用程序”.
  4. 对于一些编译器的报错, 其报错信息也本身就是一个关键词. 例如“PHP Fatal error: Call to undefined function mb_detect_encoding() in E:\Site\phpMyAdmin\libraries\php-gettext\gettext.inc on line 177”这个php报错, 我们直接搜索“Call to undefined function mb_detect_encoding”即可找到解决方法.
  5. 如果要对文章进行查重, 或者搜索某个句子段落在别的站点有没有出现过, 直接搜索这个句子即可. 典型的用法是搜题的时候, 比如“c++求n个数中的最大值和最小值”. 如果你在试卷上见到了这个题, 请直接原封不动直接搜索原句. 这样短时间内可以找到大量的网站转载, 且内容几乎完全相同, 其中总有一个是有标准答案的.


# 能搜索就别问别人
听着, 搜索引擎可能是你解决问题最快的办法. 能搜索的就不要问别人, 这样一方面锻炼了你的动手能力, 另一方面别人不会觉得你很烦. 甚至有个附带的buff, 那就是别人感觉你啥都会, 从而进一步抬高了你的身份地位.

还是那句话, 很多小问题搜索引擎完全应对的了, 没有必要再去送一个人情. 而很多大问题别人也未必见过, 问了对方也只能说一个不知道. 这是毫无意义的. 在这上面浪费时间, 完全不如想办法自己解决.

搜索引擎也是锻炼你自力更生的一个重要方法, 同样也是学习技术知识的一个重要来源. 搜索引擎更大的一个优势是, 它能让你接触到较为前沿的技术知识点, 而不是课本上固定的老知识.

要知道, 课本大部分都是5年前编写的, 而5年的时间足够让技术本身脱胎换骨. 很多技术早已淘汰, 与时俱进才是唯一办法. 所以, 就凭这一点, 我也建议你多用搜索引擎, 不要迷信课本和权威.


# 百度搜不到那就去谷歌
虽然谷歌被墙了, 但是还是有很多办法可以过掉的. 出于法律原因, 这里不讨论翻墙. 但这个问题直接百度搜是不可能搜到的, 如果你是新手, 建议咨询一下你比较有经验的朋友. 了解大概用到了哪些软件即可. **尽量不要伸手要软件, 这样你的下场会很难看.**

因为百度的特殊原因, 很多优秀资料难以第一时间被收录, 这时候谷歌就显得非常重要. 谷歌搜索能搜索到很多因为知名度原因而难以被发现的网站, 而这些网站大部分是个人博客等, 拥有极高的技术研究价值.

当然, 使用谷歌的另一个方面就是会搜索到很多负面信息和垃圾信息. 这是因为谷歌出于学术需要, 是对源信息不加筛选和过滤的. 这就要你有足够的自我判断能力, 如搜索到黄赌毒邪教这类的, 请直接无视.

**尤其是菠菜和邪教, 有着很强的洗脑能力, 切勿信以为真. 墙谷歌一定程度上也是为了你好, 请理解国家一直以来为了你的成长环境而背负的骂名.**


# 积累每次搜索获得的经验
如果搜索引擎解决了你的问题, 你可以将问题归纳总结, 学习别人的思路. 当然你也可以总结你学习到了哪些关键词, 哪些技术术语等等. 这将对你的下一次搜索有一定的帮助.

当然, 如果你喜欢, 你也可以在你的博客或空间内写出你解决问题的过程和收获. 一方面这是你对知识的掌握和巩固, 另一方面这也方便了别人来搜索同样的问题. **互联网就是通过不断地分享, 从而定义了其本身.**

在你的知识面不断扩大的同时, 你总有一天会知道, 你动手做过的知识点, 实际上是互相穿插, 互相关联的. 知识面最终会成为一个网络, 从而进一步加深你对你所在行业的整体理解. 而这才是学习技术的最终境界.