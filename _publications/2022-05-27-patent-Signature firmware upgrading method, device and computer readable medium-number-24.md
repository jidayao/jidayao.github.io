---
title: "签名固件升级方法、设备及计算机可读介质"
collection: publications
permalink: /publication/2022-05-27-patent-Signature firmware upgrading method, device and computer readable medium-number-24
excerpt: '本发明公开了签名固件升级方法、设备和计算机可读介质，对待升级固件进行签名，将签名后的待升级固件存储至固件升级包中，并进入固件升级模式；通过待升级固件中的启动引导程序固件，将数字签名算法和公钥参数传递至内存的设备树中，并且将熔断标记和锁定标记传递至命令行参数中；若命令行参数中熔断标记表示设备熔断或者锁定标记表示设备锁定，则对签名后的待升级固件进行校验升级。因此在设备熔断或者锁定的情况下对待升级固件进行签名校验，确保固件校验通过之后才进行升级，避免固件升级后得到没有签名或者签名出错，从而保证设备升级能够正常启动，提高固件升级的可靠性.'
date: 2022-05-27
venue: '发明专利 Invention patent'
paperurl: 'https://patents.google.com/patent/CN114547620A'
citation: '纪大峣. (2022). &quot;签名固件升级方法、设备及计算机可读介质.&quot; <i>专利</i>. CN114547620A.'
citation: 'Dayao Ji. (2022). &quot;Signature firmware upgrading method, device and computer readable medium.&quot; <i>China patent</i>. CN114547620A.'
---
**签名固件升级方法、设备及计算机可读介质**

**摘要**：本发明公开了签名固件升级方法、设备和计算机可读介质，对待升级固件进行签名，将签名后的待升级固件存储至固件升级包中，并进入固件升级模式；通过待升级固件中的启动引导程序固件，将数字签名算法和公钥参数传递至内存的设备树中，并且将熔断标记和锁定标记传递至命令行参数中；若命令行参数中熔断标记表示设备熔断或者锁定标记表示设备锁定，则对签名后的待升级固件进行校验升级。因此在设备熔断或者锁定的情况下对待升级固件进行签名校验，确保固件校验通过之后才进行升级，避免固件升级后得到没有签名或者签名出错，从而保证设备升级能够正常启动，提高固件升级的可靠性。



**Signature firmware upgrading method, device and computer readable medium**

**Abstract:**The invention discloses a signature firmware upgrading method, equipment and a computer readable medium, wherein a firmware to be upgraded is signed, the signed firmware to be upgraded is stored in a firmware upgrading package, and a firmware upgrading mode is entered; transmitting a digital signature algorithm and a public key parameter to a device tree of a memory through a boot program firmware to be upgraded, and transmitting a fusing mark and a locking mark to a command line parameter; and if the fusing mark in the command line parameters indicates that the equipment is fused or the locking mark indicates that the equipment is locked, verifying and upgrading the signed firmware to be upgraded. Therefore, the signature verification is carried out on the firmware to be upgraded under the condition that the equipment is fused or locked, the upgrading is carried out only after the firmware verification is passed, no signature is obtained or the signature is wrong after the firmware is upgraded, the normal starting of the equipment upgrading is ensured, and the reliability of the firmware upgrading is improved. 



[Download paper here](https://patents.google.com/patent/CN114547620A)



**Recommended citation:** 

纪大峣. 签名固件升级方法、设备及计算机可读介质[P]. 中国：CN114547620A,2022-05-27.

D. Ji,"Signature firmware upgrading method, device and computer readable medium," China Patent CN114547620A, May 27,2022.





