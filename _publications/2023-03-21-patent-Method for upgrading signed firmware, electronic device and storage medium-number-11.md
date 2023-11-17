---
title: "升级签名固件的方法、电子设备和存储介质"
collection: publications
permalink: /publication/2023-03-21-patent-Method for upgrading signed firmware, electronic device and storage medium-number-11
excerpt: '本发明公开了升级签名固件的方法、电子设备和存储介质，将公钥参数信息、数字签名算法类型和消息摘要算法类型保存在启动引导程序固件中，在对固件校验之前，对公钥参数信息进行了三次验证，并将数字摘要、消息摘要算法类型和数字签名算法类型写入命令行参数，实现了公钥参数信息合法性和正确性的多重验证，在确保了公钥信息本身是合法正确的前提下再对待升级固件进行校验，且无需依赖启动引导程序传递公钥参数，既解决了升级没签名或者错误签名的固件导致升级后设备无法启动问题，也解决了设备启动引导程序和系统之间没有额外的软硬资源而无法有效传递公钥信息的问题，从而提高了签名固件升级的可靠性.'
date: 2023-03-21
venue: '发明专利 Invention patent'
paperurl: 'https://patents.google.com/patent/CN115828255A'
citation: '纪大峣. (2023). &quot;升级签名固件的方法、电子设备和存储介质.&quot; <i>专利</i>. CN115828255A.'
citation: 'Dayao Ji. (2023). &quot;Method for upgrading signed firmware, electronic device and storage medium.&quot; <i>China patent</i>. CN115828255A.'
---
**升级签名固件的方法、电子设备和存储介质**

**摘要**：本发明公开了升级签名固件的方法、电子设备和存储介质，将公钥参数信息、数字签名算法类型和消息摘要算法类型保存在启动引导程序固件中，在对固件校验之前，对公钥参数信息进行了三次验证，并将数字摘要、消息摘要算法类型和数字签名算法类型写入命令行参数，实现了公钥参数信息合法性和正确性的多重验证，在确保了公钥信息本身是合法正确的前提下再对待升级固件进行校验，且无需依赖启动引导程序传递公钥参数，既解决了升级没签名或者错误签名的固件导致升级后设备无法启动问题，也解决了设备启动引导程序和系统之间没有额外的软硬资源而无法有效传递公钥信息的问题，从而提高了签名固件升级的可靠性。



**Method for upgrading signed firmware, electronic device and storage medium**

**Abstract:**The invention discloses a method for upgrading signature firmware, an electronic device and a storage medium, wherein public key parameter information, a digital signature algorithm type and a message digest algorithm type are stored in boot program firmware, the public key parameter information is verified for three times before the firmware is verified, and a digital digest, a message digest algorithm type and a digital signature algorithm type are written in command line parameters, so that multiple verification of the legality and the correctness of the public key parameter information is realized, the firmware to be upgraded is verified on the premise of ensuring that the public key information is legal and correct, the boot program is not required to be relied on to transmit the public key parameter, the problem that the equipment cannot be started after the firmware which is not signed or wrongly signed is upgraded is solved, the problem that the public key information cannot be effectively transmitted due to the fact that extra soft and hard resources do not exist between the boot program and a system of the equipment is solved, and the upgrading reliability of the signature firmware is improved. 



[Download paper here](https://patents.google.com/patent/CN115828255A)



**Recommended citation:** 

纪大峣. 升级签名固件的方法、电子设备和存储介质[P]. 中国：CN115828255A,2023-03-21.

D. Ji,"Method for upgrading signed firmware, electronic device and storage medium," China Patent CN115828255A, March 21,2023.



