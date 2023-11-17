---
title: "升级签名固件的方法、电子设备和存储介质"
collection: publications
permalink: /publication/2023-01-24-patent-Method for upgrading signed firmware, electronic device and storage medium-number-12
excerpt: '本发明公开了升级签名固件的方法、电子设备和存储介质，在固件升级包和启动固件根文件系统中均存放公钥文件，并且将消息摘要、消息摘要算法类型和数字签名算法类型写入操作系统内核命令行参数中，另外在对签名后的待升级固件进行校验之前，先基于操作系统内核命令行参数对固件升级包和启动固件根文件系统中的公钥文件进行校验，实现了公钥信息多重验证，确保公钥信息本身是安全的前提下再对待升级固件进行校验，且无需依赖设备启动引导程序传递公钥参数信息，既解决了升级没签名或者错误签名的固件导致升级后设备无法启动问题的，也解决了没有额外的软硬资源导致无法有效传递公钥信息的问题，从而提高了签名固件升级的可靠性.'
date: 2023-01-24
venue: '发明专利 Invention patent'
paperurl: 'https://patents.google.com/patent/CN115640582A'
citation: '纪大峣. (2023). &quot;升级签名固件的方法、电子设备和存储介质.&quot; <i>专利</i>. CN115640582A.'
citation: 'Dayao Ji. (2023). &quot;Method for upgrading signed firmware, electronic device and storage medium.&quot; <i>China patent</i>. CN115640582A.'
---
**升级签名固件的方法、电子设备和存储介质**

**摘要**：本发明公开了升级签名固件的方法、电子设备和存储介质，在固件升级包和启动固件根文件系统中均存放公钥文件，并且将消息摘要、消息摘要算法类型和数字签名算法类型写入操作系统内核命令行参数中，另外在对签名后的待升级固件进行校验之前，先基于操作系统内核命令行参数对固件升级包和启动固件根文件系统中的公钥文件进行校验，实现了公钥信息多重验证，确保公钥信息本身是安全的前提下再对待升级固件进行校验，且无需依赖设备启动引导程序传递公钥参数信息，既解决了升级没签名或者错误签名的固件导致升级后设备无法启动问题的，也解决了没有额外的软硬资源导致无法有效传递公钥信息的问题，从而提高了签名固件升级的可靠性。



**Method for upgrading signed firmware, electronic device and storage medium**

**Abstract:**The invention discloses a method for upgrading signature firmware, electronic equipment and a storage medium, wherein public key files are stored in a firmware upgrading packet and a firmware starting root file system, and a message digest, a message digest algorithm type and a digital signature algorithm type are written into kernel command line parameters of an operating system, in addition, before the signed firmware to be upgraded is verified, public key files in the firmware upgrading packet and the firmware starting root file system are verified based on the kernel command line parameters of the operating system, so that multiple verification of public key information is realized, the firmware to be upgraded is verified on the premise of ensuring the safety of the public key information, and a device starting bootstrap program is not required to be relied to transmit public key parameter information, so that the problem that the equipment cannot be started after upgrading due to upgrading of the firmware without signature or false signature is solved, the problem that the public key information cannot be effectively transmitted due to the absence of additional software and hardware resources is solved, and the upgrading reliability of the signature firmware is improved. 



[Download paper here](https://patents.google.com/patent/CN115640582A)



**Recommended citation:** 

纪大峣. 升级签名固件的方法、电子设备和存储介质[P]. 中国：CN115640582A,2023-01-24.

D. Ji,"Method for upgrading signed firmware, electronic device and storage medium," China Patent CN115640582A, January 24,2023.



