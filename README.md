# beautyOS
> simple is beauty.
>
> 简单就是美啊，我就是小漂亮！

## 时间轴

想做一个很简约的，符合我的审美的轻量级OS。因为这个世界上已经有很多的RTOS了，所以也会借鉴一些。主要会借鉴中国移动的[OneOS-Lite](https://gitee.com/cmcc-oneos/OneOS-Lite)，非常感谢。

### 1.工具链选择

工欲善其事，必先利其器。因此，我的第一步就是选择好工具链。因为`arm`和`risc-v`在嵌入式领域举足轻重。因此，我将会在这两个`arch`上努力。

再次，在嵌入式`RTOS`中，仍然选择`C`语言作为主要语言。以后会考虑出一般`rust`，现在还是踏踏实实写好`c`，步子不能迈太大哦。

因此，对于C工具链，我则沿用了[OneOS-Lite](https://gitee.com/cmcc-oneos/OneOS-Lite)所使用的工具：[OneOS-Cube](https://gitee.com/cmcc-oneos/one-os-cube)

具体使用方法可见：[工具简介 (oneos-lite.com)](https://oneos-lite.com/#/docs/tools/README)

### 2.第一步

能打印输出，第一步也算是完成了！现在还没有任何代码，任重而道远也( •̀ ω •́ )y




## 参考

[OneOS-Lite: OneOS-Lite代码结构简单，配置方便，极易上手，非常适合用以进行RTOS的学习和研究。基于精简稳定的内核、适配广泛的外设驱动、丰富多样的组件，只需简单几步就可以快速实现应用开发，方便高效，尤其在资源紧张的MCU上更显游刃有余。 (gitee.com)](https://gitee.com/cmcc-oneos/OneOS-Lite)