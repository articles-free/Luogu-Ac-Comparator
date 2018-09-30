# Luogu-Ac-Comparator

比较洛谷上你和其他用户之间通过的题目异同。

可以方便你和同学之间相互竞争、了解，促进进步。

顺便把所有千题神犇的通过转化为精确数字。

**这是一个用户脚本，在使用之前，请确保你的浏览器安装了 Tampermonkey 插件。**

[访问这里安装脚本](https://greasyfork.org/zh-CN/scripts/371669-%E6%B4%9B%E8%B0%B7%E9%80%9A%E8%BF%87%E9%A2%98%E7%9B%AE%E6%AF%94%E8%BE%83%E5%99%A8-yyfcpp)

## 使用方法
进入要比较对象的洛谷个人主页。稍等片刻即可。

红色显示你未 AC 的题目，绿色显示也通过的题目。橙色显示你尝试过的题目。

示例：（顺便膜拜 lk、Sooke）

![example1](https://s1.ax1x.com/2018/09/30/i1P59K.png)

![example2](https://s1.ax1x.com/2018/09/30/i1P59K.png)

**注意：如果对方开启了完全隐私保护，此脚本不可用。**

## TODO
- [x] 改进脚本，以在个人主页修改文字样式（如颜色、粗体、斜体）的方式突出显示用户之间的通过差异
- [x] 增加比较「尝试过的题目」（by qq1010903229）
- [x] 修复页面结构随机性导致的部分题号染色失败问题
- [ ] 优化 AC 列表的获取算法，尽量降低网络原因导致的速度慢问题。

## 感谢
感谢 @abc1763613206 协助我发布脚本。

感谢 @Legendword 帮助我染色。

感谢 @qq1010903229 帮助完善功能。
