# What is Python ?

Python是一种“解释性语言”，优点在于“通俗易懂”，写代码就像日常生活中指挥别人干活一样。

1. Python：指挥团队/员工干活的语言
2. 对于新手而言，建议你全面加盟“Anaconda”。它已经为您将企业注册完毕，并聘请“pip”与“conda”两位总经理为你排忧解难。
3. 如果您有强迫症，希望自己亲手招聘人才，那么推荐您安装Miniconda或Python.

Python就是指挥你企业内的团队或个人为你干活的语言，因此它实际上与我们日常使用的汉语是一致的，只要你有指挥他人干活的逻辑能力，那么你完全可以胜任Python语言.

## Anaconda/Miniconda/Python 区别

对于很多新手来说，我们无法分辨到底使用Python为什么会有人推荐上述这三个名字呢？这里我简单的说明三个的区别。

实际上anaconda与miniconda是同一个东西，对于anaconda来说，它安装的速度很慢，并且体积比较大（1GB）的大小;而miniconda和Python的大小却小于100Mb。

这是因为anaconda你下载安装是把别人的整个企业都安装了，里面的员工甭管你用不用的到，都来到你的企业中，所以体积和安装速度都比较慢，但是对于懵懂无知的小白来说，一键安装才是最屌的！

当然，anaconda不是将世界上所有懂Python语言的团队招进来了，实际使用过程中，你还是会发现你的企业缺少一些团队或人才。这里我们称这些团队和人才为 **“库”**。

miniconda相对Python而言，就是安装的时候多了一个总经理“conda”，而原版的Python安装，只有一位总经理“pip”。

无论是“conda”亦或是“pip”都是招聘人才的总经理，对于“pip”来说，它招聘的人才是所有团队和人员，并没有经过认证的，你只要给他人才的地址(默认是“人才网址”是pypi)，他就去招聘这个人才替你干活。

而“conda”的强大之处在于，它招聘的人才都是经过“anaconda”这个公司审核过的人才，因此更专业更稳定更安全。当然不仅如此，它的强大在于他可以同时管理多个版本的Python。

一般而言，对于小白其实建立一家公司已经足够使用了，但是为了方便打包，为了方便人才的位置，我们会使用多个版本的Python，最新的Python版本为3.12.0，而许多老员工都不想去3.12.0这个最新的地方工作，那么conda的好处就是我可以同时管理多家不同版本的Python公司，而不互相影响。

简单来说，当你只有一家公司时，“pip”和“conda”都是你的总经理，他们并没有什么区别，区别仅仅在于招聘人才的渠道上罢了，而“pip”的渠道是最广的！但你需要多家公司时，“conda”是负责管理多个公司的好经理，而“pip”只能每一家公司有一个。废话少说，“anaconda”和“miniconda”选一个就好。

下载地址：（可以去官网，但是没有“翻墙”手段下载很慢）
（因此这是清华提供的下载地址）
Anaconda：https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/ (官网：https://www.anaconda.com/download/)
Miniconda：https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/ (官网：https://docs.conda.io/projects/miniconda/en/latest/)
Python：https://www.python.org/

## 认识IDE.

IDE:可以理解为你的公司地址，你叫别人干活的输入框。

假如你安装的是“Anaconda”，那么你只需要找到“jupyter notebook”打开即可。

是的，“jupyter notebook”的格式是“.ipynb”,建议所有学代码的都先使用该格式来写代码，因为他可以每个单元格独立，每个文件又可以联系起来。而不需要创建很多个“.py”格式。

方便调试，是“.ipynb”格式的优点。而如果安装的是miniconda是没有配备IDE的，需要手动安装，调用cmd命令

```python
conda install jupyter
```

而Python原版是有"IDLE"这个自带的输入框的。但是真的不好用。(它也可以使用 "pip install jupyter"来安装简单的IDE.)

个人是非常推荐Vscode的，因为可以搭配许多插件自由使用，不过IDE的选择全看个人兴趣爱好和习惯，有人喜欢用“记事本”写代码没无可厚非。


