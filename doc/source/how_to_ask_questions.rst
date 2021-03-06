如何正确提问
============

感谢大家的使用和建议，我们会持续改进。为了更高效地解决问题，请在提问时遵循一定的规范。

总结
----

附上代码、附上报错信息、附上Python版本和系统信息。

提问模板
--------

::

    What steps will reproduce the problem? 
    该问题的重现步骤是什么？
    1. 
    2. 
    3. 

    What is the expected output? What do you see instead? 
    你期待的结果是什么？实际看到的又是什么？


    What version of the product are you using? On what operating system? 
    你正在使用产品的哪个版本？在什么操作系统上？

    Please provide any additional information below.
    如果有的话，请在下面提供更多信息。

具体解释
--------

什么是“最短代码-错误重现”提问方式？

帖子标题 = 帖子内容的提炼
~~~~~~~~~~~~~~~~~~~~~~~~~

简洁清晰，言之有物。让他人看了标题就能大概知道是否能帮助你，切勿使用“求助、急、帮忙、新手、高手、在线等”等无任何意义的词语。

    | 我遇到了一个 DataView的问题
    | TradeApi 在我的系统上运行不了

上面的标题很糟糕，光看标题作者无法知道发生了什么事。当开源社区的问题很多时，上面这类标题，经常会让作者直接忽视或将优先级降到很低。更妥当的标题是

    | DataView 在prepare\_data时报NotLoginError
    | TradeApi 在 Ubuntu 14.04 上运行时提示-1,no connection

帖子正文 = 场景描述 + 代码 + 报错信息
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  粘贴一个简单的程序程序代码
-  贴出你的错误或警告信息（特别重要），以及你已经尝试过的方法、步骤（必要的时候，可以上传一些截图）；
-  写上你使用的是哪个MATLAB版本（如：64位R2012a等），以及操作系统（如：32位XP系统、64位Windows
   7系统等）。

描述事实、而不是猜测
^^^^^^^^^^^^^^^^^^^^

事实是指，依次进行了哪些操作、产生了怎样的结果。比如

    我在 Windows 10 下用 pip 打开JAQS后报错no
    snappy，按照安装指南安装python-snappy后，pandas包无法使用。

上面是一段比较好的事实描述（更好的是把错误提示也截图上来），而不要像下面这样猜测：

    安装JAQS导致pandas报错，我怀疑项目对Win10的兼容不好。

上面的描述，会让作者一头雾水。尽量避免猜测性描述，除非你能先描述事实，在事实描述清楚之后，再给出合理的猜测是欢迎的。

描述目标、而不是过程
^^^^^^^^^^^^^^^^^^^^

经常会有这种情况，提问者在脑袋里有个更高层次的目标，他们在自以为能达到目标的特定道路上卡住了，然后跑来问该怎么走。举一个生活中的例子

    咖啡馆应该为每种咖啡提供5档不同甜度的版本

上面这个问题的背后，提问者认为不同顾客对甜度有不同偏好，咖啡馆在做咖啡时应满足。但事实上，正确的方式是提供糖，让顾客自己选择加多少。如果只是描述过程（提供不同甜度的咖啡）不描述目的（满足人们的甜度偏好），往往会把其他人也绕进去。

即很多情况下，对于要解决的问题，实际上有更好的方式。这种情况下，描述清楚目标，讲清楚要干什么非常重要。

本文参考了：\ `如何向开源社区提问题 <https://github.com/seajs/seajs/issues/545>`__
