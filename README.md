﻿# TrafficMonitor 11Patch
Traffic Monitor是一款用于Windows平台的网速监控悬浮窗软件，可以显示当前网速、CPU及内存利用率，支持嵌入到任务栏显示，支持更换皮肤、历史流量统计等功能。

修改，增加了 Windows 11 新任务栏的一点支持。

# [下载](https://github.com/ZetaSp/TrafficMonitor/releases/latest)：

修改自 1.80.3，点击上面下载

# 主要特性
* 显示当前实现网络传输速率、CPU和内存占用率
* 如果电脑有多个网卡，支持自动和手动选择网络连接
* 查看网络详细信息
* 支持嵌入到任务栏显示
* 支持更换皮肤和自定义皮肤
* 历史流量统计
* *增加对 Windows 11 的特别适配
* *其他系统可能失去适配，因为我只有 Win 11 的电脑可用

# 使用指南

√ 任务栏窗口现在已经支持【最左边】【任务栏左边】【任务栏右边】【最右边】，设置里调节左右后会弹出对话框选择。设置将保存。

可以在配置文件里手动调节偏移值（tbar_wnd_offset），默认0。

如果打开了 **背景透明** ，TrafficMonitor 任务栏会不可点击，如果没开则可以点击，但是是不透明的。

如果 TrafficMonitor 任务栏的交互对你很重要，不妨先关闭背景透明，开启 **根据任务栏颜色设置背景色** ，这个效果近似透明；如果你只看个数据，那么可以继续透明。

背景透明（没 Layer 的窗）不可交互，但是可以叠一个透明的背景不透明（有 Layer）在上面分离交互，到时候我试试。

### 更多信息请访问原储存库 [TrafficMonitor](https://github.com/zhongyang219/TrafficMonitor)
