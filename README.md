# colorosshowtw

让ColorOS显示🇹🇼(中华民国)国旗

## 怎么用

需要注意 在新版kernelsu或其衍生版本中 默认情况下不会修改系统文件

为了解决这个问题 需要安装[这个东西](https://github.com/Hybrid-Mount/meta-hybrid_mount) 

然后打开 选择我的模块 overlayfs即可

如果你是KernelSU系管理器 需要关闭设置中的“默认卸载模块” 否则模块会不生效

最后 像安装普通模块一样安装这个模块 [点击这里下载此模块](https://github.com/moaeiou/colorosshowtw/releases)

## 项目简介

ColorOS由于监管要求 从16.0.10版本开始将不显示🇹🇼(TW)

但是 16.0.9可以正确显示

在一阵分析之后 得出结论 oddo只把字体文件里面的旗帜变成了一个空图片

所以我把没有污染的字体文件提取并做成了Magisk和KernelSU模块

只要你的ColorOS手机root了都可以吃到🇹🇼旗帜

## 许可条款

该项目只用于学习和讨论使用，请遵守您所在地区的法律法规

作者不对使用该项目产生的一切后果承担责任

除此之外 项目使用AGPL-v3.0授权
