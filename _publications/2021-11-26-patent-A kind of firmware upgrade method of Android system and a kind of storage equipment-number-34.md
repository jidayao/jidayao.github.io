---
title: "一种安卓系统的固件升级方法及一种存储设备"
collection: publications
permalink: /publication/2021-11-26-patent-A kind of firmware upgrade method of Android system and a kind of storage equipment-number-34
excerpt: '本发明涉及嵌入式开发测试技术领域，特别涉及一种安卓系统的固件升级方法及一种存储设备。所述一种安卓系统的固件升级方法，包括步骤：获取升级包；在“引导通信分区”位置2写入升级引导信息；重启系统，若“引导通信分区”位置1和位置2都有Recovery标记，则引导“只读可信操作系统”和“只读二级引导程序”，并引导设备进入Recovery系统；根据固件升级操作指令，使用升级包对设备固件进行升级。通过以上方法，若在升级的过程中出现意外中断，当设备重新上电后，因为“引导通信分区”位置1和位置2的Recovery标记都存在，则“一级引导程序”仍可以顺利引导“只读可信操作系统”和“只读二级引导程序”，并对设备固件进行重新升级，避免设备变砖的问题.'
date: 2021-11-26
venue: '发明专利 Invention patent'
paperurl: 'https://patents.google.com/patent/CN109240720B'
citation: '纪大峣. (2021). &quot;一种安卓系统的固件升级方法及一种存储设备.&quot; <i>专利</i>. CN109240720B.'
citation: 'Dayao Ji. (2021). &quot;A kind of firmware upgrade method of Android system and a kind of storage equipment.&quot; <i>China patent</i>. CN109240720B.'
---
**一种安卓系统的固件升级方法及一种存储设备**

**摘要**：本发明涉及嵌入式开发测试技术领域，特别涉及一种安卓系统的固件升级方法及一种存储设备。所述一种安卓系统的固件升级方法，包括步骤：获取升级包；在“引导通信分区”位置2写入升级引导信息；重启系统，若“引导通信分区”位置1和位置2都有Recovery标记，则引导“只读可信操作系统”和“只读二级引导程序”，并引导设备进入Recovery系统；根据固件升级操作指令，使用升级包对设备固件进行升级。通过以上方法，若在升级的过程中出现意外中断，当设备重新上电后，因为“引导通信分区”位置1和位置2的Recovery标记都存在，则“一级引导程序”仍可以顺利引导“只读可信操作系统”和“只读二级引导程序”，并对设备固件进行重新升级，避免设备变砖的问题。



**A kind of firmware upgrade method of Android system and a kind of storage equipment**

**Abstract:**The invention relates to the technical field of embedded development and testing, in particular to a firmware upgrading method of an android system and storage equipment. The firmware upgrading method of the android system comprises the following steps: obtaining an upgrade package; writing upgrading guide information in a guide communication partition position 2; restarting the system, and if the position 1 and the position 2 of the 'boot communication partition' have Recovery marks, booting the 'read-only trusted operating system' and the 'read-only secondary bootstrap program', and booting the equipment to enter the Recovery system; and upgrading the equipment firmware by using the upgrading packet according to the firmware upgrading operation instruction. By the method, if unexpected interruption occurs in the upgrading process, after the equipment is powered on again, because the Recovery marks of the position 1 and the position 2 of the boot communication partition exist, the primary bootstrap program can still smoothly boot the read-only trusted operating system and the read-only secondary bootstrap program, and the firmware of the equipment is upgraded again, so that the problem of brick changing of the equipment is avoided. 



[Download paper here](https://patents.google.com/patent/CN109240720B)



**Recommended citation:** 

纪大峣. 一种安卓系统的固件升级方法及一种存储设备[P]. 中国：CN109240720B,2021-11-26.

D. Ji,"A kind of firmware upgrade method of Android system and a kind of storage equipment," China Patent CN109240720B, November 26,2021.





