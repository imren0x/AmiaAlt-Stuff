---
title: AxionOS-2.1-Vince-Baklava
description: Android 16 QPR0

date: 2025-11-02T20:12:52+08:00
lastmod: 2025-11-02T20:12:52+08:00
tags:
  - test
categories:
  - test
math: true
mermaid: true
---

![Alts Banner](https://raw.githubusercontent.com/KanadeAlt/RenzAlt-Banner/refs/heads/main/photo_2025-10-26_00-39-01.jpg)

{{< alertBlockquote type="warning" >}}
I'm not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed. 
Please do some research if you have any concerns about features included in the products you find here before flashing it! 
YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you. 
Your warranty will be void if you tamper with any part of your device / software.
{{< /alertBlockquote  >}}


```info
DEVICES : VINCE
BUILD DATE : 2 November 2025
TYPE : Vanila Build
```

**Changelog**
<ul>
    <li>October 2025 security patch</li>
    <li>fixed Camera & libgf_* missing depedency</li>
</ul>

{{< alertBlockquote type="note" >}}
It seems that AxionOS 2.1 is taking up too much system size so there is not enough space to install GAPPS, so how to install GAPPS?
{{< /alertBlockquote  >}}

{{< alertBlockquote type="tip" >}}
please follow these tips.
{{< /alertBlockquote  >}}

**Prerequisites**
- Unlocked Bootloader

**Flashing Instruction**
- Wipe System, Vendor, Cache and Dalvik
- Wipe Data (optional if from older build)
- Install Rom
- flash my personal kernel "20251024-kernel-vince-defconfig.img"
- Reboot
- install SukiSU manager apk to support KernelSU
- Flash LiteGapps "GMS Core, Playstore, GoogleServicesFramework" addons via SukiSU manager
- or if you want it easy, just repartition the system and flash as usual (optional)

## Screenshots

<tr>
  <td>
    <img src="https://raw.githubusercontent.com/RennAlt/shenprjkt.github.io/refs/heads/wip-4.19-vince/assets/images/screenshots/2023/Maret/05/miku-1.jpg" width="290" height="580" align="left" />
  </td>
  <td>
    <img src="https://raw.githubusercontent.com/RennAlt/shenprjkt.github.io/refs/heads/wip-4.19-vince/assets/images/screenshots/2023/Maret/05/miku-4.jpg" width="290" height="580" align="center" />
  </td>
</tr>

## Downloads

[20251024-kernel-vince-defconfig.img](https://t.me/RenzAlt_Archive/17)

[axion-2.1-NIGHTLY-20251102-COMMUNITY-VANILLA-vince.zip](https://pixeldrain.com/u/wWvrmK4w)

[Litegapps-addons gms/playstore/GoogleServicesFramework](https://sourceforge.net/projects/litegapps/files/addon/arm64/36/core/)

**Optional**
- [vince_increase_system_to_4.5gb.zip](https://t.me/MI8953/12/8126)

## Support Me

{{< alertBlockquote type="warning" >}}
If you like my work and my efforts so far, you can make a small donation here.
{{< /alertBlockquote  >}}

{{<externalLinkCard title="Support via PayPal" link="https://www.paypal.com/paypalme/ShandyReynaldi" cover="auto">}}

{{<externalLinkCard title="Support via trakteer.id" link="https://trakteer.id/rennalt/tip" cover="auto">}}