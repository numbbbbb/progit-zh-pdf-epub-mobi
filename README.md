progit-zh-pdf&epub&mobi
=============

latest progit-zh-pdf and progit-zh-epub and progit-zh-mobi

#WHY

我使用的是mac系统，今天第一次看到这本书。

看到别人的推荐感觉很不错，所以想做成PDF放到移动设备上来看。

但是麻烦来了。。。

按照progit的readme安装完各种软件之后，makepdfs还是会失败，提示缺少pandoc和xelatex。

pandoc很容易安装，但是xelatex很难安装，甚至根本搜不到要装什么。

最后终于在google上发现需要安装MaxTex。

安装包2G，安装要占用4G。

安装好之后，提示font-not-found，研究了半天发现是config.yml里面的中文语言mac没有，于是改成mac有的Hei，这才成功生成pdf。

整个过程历时一上午。

为了方便大家，省去各种安装设置的过程，所以我建了一个repo，随时更新最新版本的pdf。

#epub
增加了epub格式，欢迎大家提各种意见和建议。

#mobi
增加了mobi格式
