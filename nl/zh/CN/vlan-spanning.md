---
copyright:
  years: 1994, 2017
lastupdated: "2017-12-27"
---
{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# 启用或禁用 VLAN 生成

有时，单个客户帐户可能存在多个专用网络 VLAN。但是，如果网络设备不存在于同一个 VLAN 中，那么这些设备无法在专用网络上相互通信。VLAN 生成支持帐户中的所有设备通过专用网络相互通信，而不管设备分配给哪个 VLAN。 

VLAN 生成服务将应用于帐户中的所有设备；生成不得应用于特定的 VLAN 或特定的设备。VLAN 生成可以根据需要启用或禁用；一旦对设置进行了更改，大约需要 15 分钟时间进行处理。执行本文章中提供的步骤来启用或禁用帐户上的 VLAN 生成。


1. 在浏览器中，打开[客户门户网站 ![外部链接图标](../../icons/launch-glyph.svg "外部链接图标")](https://control.softlayer.com/){: new_window} 并登录到您的帐户。
2. 在客户门户网站导航中，选择**网络 > IP 管理 > VLAN**。
3. 选择**生成**选项卡，以访问“VLAN 生成”部分。
4. 选择**启用**单选按钮以启用 VLAN 生成。选择**禁用**单选按钮以禁用 VLAN 生成。

## 后续操作

更新 VLAN 生成选择后，处理请求可能最长需要 15 分钟。更改确认会显示在“生成”选项卡下方。如果启用了 VLAN 生成，那么设备可以使用专用网络跨 VLAN 进行相互通信。如果禁用了生成，那么仅当设备位于同一个 VLAN 中时，才能相互连接；不再启用跨 VLAN 通信。通过重复本文章中提供的步骤，可随时更新 VLAN 生成设置。**注：**在短时间内切换 VLAN 生成设置可能会导致延迟应用设置。
