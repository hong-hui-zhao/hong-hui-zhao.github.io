---
layout: page
title: Linux
nav_order: 5
permalink: /Linux/
---
# *Linux*

### Linux 的起源
1965年，为了解决服务器的终端连接数量的限制和处理复杂计算的问题，贝尔（Bell）实验室、通用电气（GE）公司以及麻省理工学院（MIT）决定联手打造一款全新的操作系统— MULTICS（多任务信息与计算系统）。但由于开发过程不顺利，遇到了诸多阻碍，后期连资金也出现了短缺现象，最终在1969年，随着贝尔实验室的退出，MULTICS 也终止了研发工作。而同年，MULTICS 的开发人员Ken Thompson使用汇编语言编写出了一款新的系统内核，当时被同事戏称为UNICS（联合信息与计算系统），在贝尔实验室内广受欢迎。

1973年时，C语言之父 Dennis M. Ritchie 了解到UNICS系统并对其非常看好，但汇编语言有致命的缺点—需要针对每一台不同架构的服务器重新编写汇编语言代码，才能使其使用 UNICS 系统内核。这样不仅麻烦而且使用门槛极高。于是 Dennis M. Ritchie 便决定使用 C 语言重新编写一遍 UNICS 系统，让其具备更好的跨平台性，更适合被广泛普及。开源且免费的 UNIX 系统由此诞生。

但是在1979年，贝尔实验室的上级公司AT&T看到了UNIX系统的商业价值和潜力，不顾贝尔实验室的反对声音，依然坚决做出了对其商业化的决定，并在随后收回了版权，逐步限制UNIX系统源代码的自由传播，渴望将其转化成专利产品而大赚一笔。崇尚自由分享的黑客面对冷酷无情的资本力量心灰意冷，开源社区的技术分享热潮一度跌入谷底。此时，人们也不能再自由地享受科技成果了，一切都以商业为重。

面对如此封闭的软件创作环境，著名的黑客Richard Stallman在1983年发起了GNU源代码开放计划，并在1989年起草了著名的GPL许可证。他渴望建立起一个更加自由和开放的操作系统和社区。之所以称之为GNU，其实是有“GNU’s Not Unix!”的含义，这暗戳戳地鄙视了一下被商业化的UNIX系统。但是，想法和计划只停留在口头上是不够的，还需要落地才行，因此Richard便以当时现有的软件功能为蓝本，重新开发出了多款开源免费的好用工具。在1987年，GNU计划终于有了重大突破，Richard和社区共同编写出了一款能够运行C语言代码的编译器—gcc（GNU C Compiler）。这使得人们可以免费地使用gcc编译器将自己编写的C语言代码编译成可执行文件，供更多的用户使用，这进一步发展壮大了开源社区。随后的一段时间里，Emacs编辑器和bash解释器等重磅产品陆续亮相，一批批的技术爱好者也纷纷加入GNU源代码开放计划中来。

在1984年时，UNIX系统版权依然被AT&T公司死死地攥在手里，AT&T公司明确规定不允许将代码提供给学生使用。荷兰的一位大学教授 Andrew（历史中被遗忘的大神）为了能给学生上课，竟然仿照UNIX系统编写出了一款名为Minix的操作系统。但当时他只是用于课堂教学，根本没有大规模商业化的打算，所以实际使用 Minix 操作系统的人数其实并不算多。

芬兰赫尔辛基大学的在校生 Linus Torvalds 便是其中一员，他在 1991 年 10 月使用 bash 解释器和 gcc 编译器等开源工具编写出了一个名为Linux的全新的系统内核，并且在技术论坛中低调地上传了该内核的 0.02 版本。该系统内核因其较高的代码质量且基于 GNU GPL 许可证的开放源代码特性，迅速得到了 GNU 源代码开放计划和一大批黑客程序员的支持，随后Linux正式进入如火如荼的发展阶段。

Linux 系统的吉祥物名为 Tux，是一只呆萌的小企鹅。相传 Linus Torvalds 在童年时期去澳大利亚的动物园游玩时，不幸被一只企鹅咬伤，所以为了“报复”就选择了这个物种作为吉祥物。这个故事是否可信无从考证，但万幸是只企鹅，而不是老虎或者狮子，否则就不是换个 Logo 这么简单的事了。

1994年，红帽（Red Hat）公司创始人Bob Young在Linux系统内核的基础之上，集成了众多的常用源代码和程序软件，随后发布了红帽操作系统并开始出售技术服务，这进一步推动了Linux系统的普及。1998年以后，随着GNU源代码开放计划和Linux系统的继续火热，以IBM和Intel为首的多家IT巨头企业开始大力推动开放源代码软件的发展，很多人认为这是一个重要转折点。2012年，红帽公司成为全球第一家年收入10亿美元的开源公司，后来是20亿、30亿……不断刷新纪录。

目前比较常用的 Linux 系统有 Ubuntu、RedHat、CentOS、Debian、Fedora、SuSE、OpenSUSE、Arch Linux、SolusOS 等


### Linux 的使用场所
- 嵌入式设备
- 个人电脑
- 超级计算机
- 服务器领域
- 手机操作系统
- 最典型的是搜索引擎 Google和手机操作系统 Android
- 目前 Linux 不仅在家庭与企业中使用，并且在政府中也很受欢迎。中国/印度/德国/法国/俄罗斯/西班牙/葡萄牙…等.


### Linux 的基本思想
一切都是文件；就是系统中的所有都归结为一个文件，包括命令、硬件和软件设备、操作系统、进程等等对于操作系统内核而言，都被视为拥有各自特性或类型的文件,每个文件都有确定的用途！


### Linux 的特点
- 完全开源免费
- Linux同时具有字符界面和图形界面
- 多用户、多任务
- 支持多种平台
- 强大的网络功能
- 系统的稳定性和安全性好
- 缺点：需要使用“命令行”终端模式进行系统管理


### Linux 与 Windows 的区别
![image](https://github.com/hong-hui-zhao/hong-hui-zhao.github.io/assets/114247925/5fd7efa5-ea5a-4bba-adf9-00adbb6a288c)


### 如何在虚拟机上安装Linux

如果使用Linux和Mac OS操作系统，可以直接在终端（Terminal）练习命令行的操作。如果使用Windows系统，可以用虚拟机，也可以从Windows应用商店安装Ubuntu子系统学习。

#### 虚拟机下载及安装
- > [VMware](https://www.vmware.com/content/vmware/vmware-published-sites/us/products/workstation-pro/workstation-pro-evaluation.html.html)
- > [安装](https://blog.csdn.net/weixin_74195551/article/details/127288338)
  
### Ubuntu 下载及安装
- > [中国科学技术大学](https://mirrors.ustc.edu.cn/)
- > [兰州大学](https://mirror.lzu.edu.cn/)
- > [浙江大学](https://mirrors.ustc.edu.cn/)
- > [清华大学](https://mirrors.tuna.tsinghua.edu.cn/)
- > [阿里云](https://developer.aliyun.com/mirror/)
- > [安装](https://blog.csdn.net/qq_43374681/article/details/129248167)
- > [使用 WSL 在 Windows 上安装 Linux](https://learn.microsoft.com/zh-cn/windows/wsl/install)

### Linux 学习资料
#### 推荐：
- [《Linux命令行大全-第二版》(The Linux Command Line, 2nd edition)。pdf下载,密码 kd67](https://pan.baidu.com/s/1Jr99oJmH9THsSAsjQT9hrg)
- [Linux命名大全（手册）](https://www.linuxcool.com/)
- [Linux 教程](https://www.w3cschool.cn/linux/)
- [《Linux就该这样学》](https://www.linuxprobe.com/)

-----
