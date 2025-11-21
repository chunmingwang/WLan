# WLan
WlanAPI example for VisualFBEditor

Windows WLANAPI扫描程序，用于扫描和显示可用的WiFi网络及其详细信息。

# 主要功能包括：

1. 打开WLAN API句柄
2. 注册WLAN通知回调
3. 枚举系统中的WiFi接口
4. 扫描并显示可用网络列表
5. 获取每个网络的BSS（基本服务集）详细信息
6. 代码结构解析

# 通知回调函数：

1. WlanNotificationCallback：处理扫描完成和失败的通知

# 主要流程：

1. 初始化WLAN API
2. 创建同步事件
3. 注册通知回调
4. 枚举WiFi接口
5. 对每个接口执行扫描
6. 获取并显示网络列表
7. 获取每个网络的BSS详细信息
