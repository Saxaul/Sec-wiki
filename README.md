# 引言
在整理我的面试题目时，看到了@WebBreacher 的红队面试问题整理，感觉非常不错，因此征求了他的同意，翻译成中文，有的地方词不达意我都附上了英文原文，如果想更好地理解他的意思，建议查看 [英文项目](https://github.com/Leezj9671/offensiveinterview) ，感谢 @WebBreacher @doctorj 等优秀红队人员的整理。

另外，由于该面试问题是国外的红队渗透面试题，跟国内有少许区别，但是大体类似，知识点相同，如果想查看我的面试问题，欢迎到 [Leezj9671/Pentest_Interview](https://github.com/Leezj9671/Pentest_Interview) 拍砖。

另外，这些只是面试问题，翻译的工作我可以很好地完成，但是问题都是没有答案的，所以我希望各位有能力的可以编写回答或提出 issue ，每个 PR 我都会看噢。

以下是英文翻译：

# 该项目的目的
收集大量的面试问题，以筛选攻击方面（红队/渗透测试）的面试者。

如果您是面试者，想找到一些好问题去问面试官，请访问 @doctorj 的页面：[https://gitlab.com/doctorj/interview-questions/interview-questions.yml](https://gitlab.com/doctorj/interview-questions/interview-questions.yml)

# 怎么贡献该项目
1. 使用分支此存储库的标准方法，进行更改并执行 `pull` 请求以添加您的内容
   - 如果您想要归档，请将您的问题格式化为编号列表，问题，您的姓名（* @姓名*），然后以斜体字*表示面试官*的任何指示。 这些是关于要查找什么或如何提出问题的指示，而不是问题的答案。
   - 例子：
      1. "What is CSRF and how is it different from XSS?" *@webbreacher* （什么是CSRF，它和XSS有什么区别？ *@webbreacher*）
      1. "I have a /24 subnet on the Internet. You are a pentester. Tell me, start to finish, how you would execute this assessment." *@webbreacher* *Look for everything from scoping meeting and rules of engagement to the depth/detail of their responses.*（我在互联网上有一个/24子网，你将如何执行这项评估。” * @ webbreacher * *寻找从范围界定会议和参与规则到其回复的深度/细节的所有内容。*）

2. 如果你想直接复制问题过来的话，可以发你的面试问题到 [Issue](https://github.com/leezj9671/offensiveinterview/issues)，我们会审核后添加到该库中，并说明你是否想要署名。

# 问题分类

现在问题应该遵循以下分类和格式，对应不同的文件。

1. [开放式问题](https://github.com/Leezj9671/offensiveinterview/blob/translate-zhcn/open.md)
   - 这些问题有很多解答，无固定解答
   - 例子：
      - “描述如何使用网络钓鱼攻击危害受害者的笔记本电脑。”
      - “一旦你在数据库服务器上成功获得shell，你会做什么？”
2. [基于知识的问题](https://github.com/Leezj9671/offensiveinterview/blob/translate-zhcn/knowledge.md)
   - 这些问题有一个特定的正确和错误的答案。
   - 例子：
      - “什么是CSRF，它与XSS有什么不同？”
      - “```netcat```和```ncat```之间的主要区别是什么？”
3. [基于场景的问题](https://github.com/Leezj9671/offensiveinterview/blob/translate-zhcn/scenario.md)
   - 这些问题是面试官设定情况并允许面试者回答的问题。在他们的回答中，面试官会步步紧逼，给出更多信息|模拟客户|告诉面试者他们采取行动时会发生什么，以便更全面地了解面试者知识的广度和深度。
   - 例子：
      - “我在互联网上有一个/24子网，你是测试者，你将如何执行这项评估？从头到尾的流程都要说一遍”
      - “你刚刚在企业用户子网中黑了一台 Mac OS X 笔记本电脑。你的目标是渗透Active Directory（[活动目录](https://www.cnblogs.com/IFire47/p/6672176.html)，可理解为域渗透），你是如何做到这一点的？”
4. [其他问题](https://github.com/Leezj9671/offensiveinterview/blob/translate-zhcn/other.md)
   - 除了前三项归类的其它问题
   - 例子：
      -  *暂无例子*

# License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.