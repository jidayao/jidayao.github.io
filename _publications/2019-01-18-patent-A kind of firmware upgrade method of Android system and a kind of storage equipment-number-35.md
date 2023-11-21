---
title: "一种安卓系统的固件升级方法及一种存储设备"
collection: publications
permalink: /publication/2019-01-18-patent-A kind of firmware upgrade method of Android system and a kind of storage equipment-number-35
excerpt: '本发明涉及嵌入式开发测试技术领域，特别涉及一种安卓系统的固件升级方法及一种存储设备。所述一种安卓系统的固件升级方法，包括步骤：获取升级包；在“引导通信分区”位置2写入升级引导信息；重启系统，若“引导通信分区”位置1和位置2都有Recovery标记，则引导“只读可信操作系统”和“只读二级引导程序”，并引导设备进入Recovery系统；根据固件升级操作指令，使用升级包对设备固件进行升级。通过以上方法，若在升级的过程中出现意外中断，当设备重新上电后，因为“引导通信分区”位置1和位置2的Recovery标记都存在，则“一级引导程序”仍可以顺利引导“只读可信操作系统”和“只读二级引导程序”，并对设备固件进行重新升级，避免设备变砖的问题.'
date: 2019-01-18
venue: '发明专利 Invention patent'
paperurl: 'https://patents.google.com/patent/CN109240720A'
citation: '纪大峣. (2019). &quot;一种安卓系统的固件升级方法及一种存储设备.&quot; <i>专利</i>. CN109240720A.'
citation: 'Dayao Ji. (2019). &quot;A kind of firmware upgrade method of Android system and a kind of storage equipment.&quot; <i>China patent</i>. CN109240720A.'
---
**一种安卓系统的固件升级方法及一种存储设备**

**摘要**：本发明涉及嵌入式开发测试技术领域，特别涉及一种安卓系统的固件升级方法及一种存储设备。所述一种安卓系统的固件升级方法，包括步骤：获取升级包；在“引导通信分区”位置2写入升级引导信息；重启系统，若“引导通信分区”位置1和位置2都有Recovery标记，则引导“只读可信操作系统”和“只读二级引导程序”，并引导设备进入Recovery系统；根据固件升级操作指令，使用升级包对设备固件进行升级。通过以上方法，若在升级的过程中出现意外中断，当设备重新上电后，因为“引导通信分区”位置1和位置2的Recovery标记都存在，则“一级引导程序”仍可以顺利引导“只读可信操作系统”和“只读二级引导程序”，并对设备固件进行重新升级，避免设备变砖的问题。



**A kind of firmware upgrade method of Android system and a kind of storage equipment**

**Abstract:**The present invention relates to embedded development the field of test technology, in particular to the firmware upgrade method of a kind of Android system and a kind of storage equipment.The firmware upgrade method of a kind of Android system, comprising steps of obtaining upgrade package；In " guidance COMMRGN communication region " write-in of position 2 upgrading guidance information；Restart system, if there are Recovery label in " guidance COMMRGN communication region " position 1 and position 2, guides " read-only trusted operating system " and " read-only second level bootloader ", and equipment is guided to enter Recovery system；It is instructed according to firmware upgrade operation, equipment firmware is upgraded using upgrade package.Pass through above method, if there is accidental interruption during upgrading, after equipment re-powers, because the Recovery label of " guidance COMMRGN communication region " position 1 and position 2 all exists, then " level-one bootstrap " still can smoothly guide " read-only trusted operating system " and " read-only second level bootloader ", and equipment firmware is upgraded again, avoid the problem that equipment becomes brick. 



[Download paper here](https://patents.google.com/patent/CN109240720A)



**Recommended citation:** 

纪大峣. 一种安卓系统的固件升级方法及一种存储设备[P]. 中国：CN109240720A,2019-01-18.

D. Ji,"A kind of firmware upgrade method of Android system and a kind of storage equipment," China Patent CN109240720A, January 18,2019.





