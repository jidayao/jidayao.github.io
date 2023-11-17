---
title: "固件分区升级方法、电子设备和存储介质"
collection: publications
permalink: /publication/2023-08-25-patent-Firmware partition upgrading method, electronic equipment and storage medium-number-5
excerpt: '本发明公开了固件分区升级方法、电子设备和存储介质。该方法包括：接收固件升级包,所述固件升级包包括与设备启动存储介质中的预设分区表区域相关联的固件分区表的镜像文件；设备启动时,从所述固件分区表的镜像文件中获取固件的物理分区信息,并将所述固件的物理分区信息添加至操作系统内核的命令行；以及进入升级模式时,根据所述命令行中的物理分区信息枚举出各个物理分区对应的块设备节点,根据固件升级指令提取固件升级包中待升级的固件分区表的镜像文件,以对待升级的固件分区表的镜像文件对应的块设备节点进行升级。本发明能够通过分区表块设备节点来对分区表进行升级,极大方便了分区表的升级.'
date: 2023-08-25
venue: '发明专利 Invention patent'
paperurl: 'https://patents.google.com/patent/CN116643770A'
citation: '纪大峣. (2023). &quot;固件分区升级方法、电子设备和存储介质.&quot; <i>发明专利</i>. CN116643770A.'
citation: 'Dayao Ji. (2023). &quot;Firmware partition upgrading method, electronic equipment and storage medium.&quot; <i>Invention patent</i>. CN116643770A.'
---
**固件分区升级方法、电子设备和存储介质**

**摘要**：本发明公开了固件分区升级方法、电子设备和存储介质。该方法包括：接收固件升级包,所述固件升级包包括与设备启动存储介质中的预设分区表区域相关联的固件分区表的镜像文件；设备启动时,从所述固件分区表的镜像文件中获取固件的物理分区信息,并将所述固件的物理分区信息添加至操作系统内核的命令行；以及进入升级模式时,根据所述命令行中的物理分区信息枚举出各个物理分区对应的块设备节点,根据固件升级指令提取固件升级包中待升级的固件分区表的镜像文件,以对待升级的固件分区表的镜像文件对应的块设备节点进行升级。本发明能够通过分区表块设备节点来对分区表进行升级,极大方便了分区表的升级。



**Firmware partition upgrading method, electronic equipment and storage medium**

**Abstract:**The invention discloses a firmware partition upgrading method, electronic equipment and a storage medium. The method comprises the following steps: receiving a firmware upgrade package, wherein the firmware upgrade package comprises an image file of a firmware partition table associated with a preset partition table area in a device start storage medium; when the device is started, the physical partition information of the firmware is obtained from the image file of the firmware partition table, and the physical partition information of the firmware is added to a command line of an operating system kernel; when the system enters an upgrade mode, enumerating block device nodes corresponding to all physical partitions according to the physical partition information in the command line, extracting an image file of a firmware partition table to be upgraded in a firmware upgrade package according to a firmware upgrade instruction, and upgrading the block device nodes corresponding to the image file of the firmware partition table to be upgraded. The invention can upgrade the partition table through the partition table block equipment node, thereby greatly facilitating the upgrade of the partition table. 



[Download paper here](https://patents.google.com/patent/CN116643770A)



**Recommended citation:** 

纪大峣. 固件分区升级方法、电子设备和存储介质[P]. 中国：CN116643770A,2023-08-25.

D. Ji,"Firmware partition upgrading method, electronic equipment and storage medium," China Patent CN116643770A, August 25,2023.



