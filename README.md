# 说明

## 为什么写这个教程

目前我的工作是将NumPy引入到Pyston中（一款Dropbox实现的Python编译器/解释器）。在工作过程中，我深入接触了NumPy源码，了解其实现并提交了PR修复NumPy的bug。在与NumPy源码以及NumPy开发者打交道的过程中，我发现当今中文NumPy教程大部分都是翻译或参考英文文档，因此导致了许多疏漏。比如NumPy数组中的broadcast功能，几乎所有中文文档都翻译为“广播”。而NumPy的开发者之一，回复到：

> broadcast is a compound -- native English speakers can see that it's " broad" + "cast" = "cast (scatter, distribute) broadly, I guess "cast (scatter, distribute) broadly" probably is closer to the meaning（NumPy中的含义）。

有鉴于此，我打算启动一个项目，以我对NumPy使用以及源码层面的了解编写一个系列的教程。

## 计划

打算每周更新一篇（一节），尽量从使用、实现两方面来介绍。个人总有局限性，文中**肯定**会有错误，到时候请发issue指正！同时也欢迎读者对写作风格提出建议。

## 许可

非商业用途可以在署名的情况下进行转载，不得用于商业用途。
