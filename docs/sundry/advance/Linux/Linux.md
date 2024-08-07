---
title: Linux 开服
slug: /Sundry/Advance/Linux
sidebar_position: 1
---

# Linux 开服

## 为什么选择 Linux 开服

1. 更快的发包速度和接收速度，接入服务器速度将提升数十毫秒起，当面对假人攻击/ DDOS 攻击时会更加稳定；
2. 更好的性能，根据测试TPS能提升 8-15 %；
3. 更低的内存占用，对于 Windows 服务器一般开机会占用1-2 GB 内存，而一般的 Linux 系统开机后占用往往不到 0.5 GB；
4. Linux 的稳定性是 Windows 无论如何也无法比拟的；
5. Linux 安全性更高，开源系统，有社区的支持；
6. Linux 支持文件占用直接删除（也就是说可以自动更新插件，不像 Windows 那样提示文件被占用）

:::info

可能会有小伙伴说:" Linux 太难操作了，根本不会用。" 其实大多数开 Linux 服务器的服主也不是纯纯使用 Linux 编辑插件配置，那么好，我们为小白推荐三个面板辅助我们开服。

1. [MCSM](https://docs.mcsmanager.com/zh_cn/) 全名 MCSManager 是一款开源，分布式，一键部署，支持 Minecraft 和 Steam 游戏服务器 的控制面板。
2. [1Panel](https://1panel.cn/) 是新一代的 Linux 服务器运维管理面板，支持 Web 图形界面管理、快速建站、应用商店、安全可靠、一键备份等功能。
3. [宝塔面板](https://www.bt.cn/) 是一款支持Linux和Windows系统的服务器运维管理工具，提供资源监控、文件管理、软件安装等功能。

:::

## 基础指令

在开始开服之前，你需要掌握的 Linux 常用指令

### vim

vim 是 Linux 上常用的文本编辑工具，在开服过程中会使用他进行插件配置的更改，开服脚本的编写等需要修改文字的地方

### tar

tar是Linux上常见的打包指令通常用于解包tar结尾的文件常见的文件格式是XXXX.tar.gz，解包的指令为 tar -zxf XXXX.tar.gz

在Linux中文件名称，指令等内容的大小写是有严格要求的，打指令的时候记得注意大小写

### systemctl

systemd 是 Linux 的进程服务管理程序，后期学到如何把mc作为进程进行自动启动，报错重启等会用到

### wget

wget 是 Linux 中常用的文件下载工具 方法为 wget + URL （PS :得是直链）

### cd

cd是切换目录的指令

### ls

ls是查看目录下有什么内容的指令

### mkdir

mkdir 是 Linux 用于创建目录的指令

### rm

rm 是 Linux 用于删除文件或目录的指令，在删除目录时要加上-rf的参数

（PS：当别人给你的指令中带有这个指令时一定要注意看清楚删除的是什么文件或目录，有的人会玩梗教你 rm -rf / 这个指令是删除所有文件，包括系统文件，会导致系统奔溃千万注意）

## 鸣谢

特别感谢 [冰奇](https://github.com/IceBingQI) 提供的本板块的文案及图片