---
title: "升级签名固件的方法、电子设备和存储介质"
collection: publications
permalink: /publication/2022-11-18-patent-Method for upgrading signed firmware, electronic device and storage medium-number-14
excerpt: '本发明公开了一种升级签名固件的方法、电子设备和存储介质，获取公钥参数信息、数字签名算法类型和消息摘要算法类型，并基于消息摘要算法类型计算与数字签名算法类型和公钥参数信息相对应的消息摘要；将消息摘要和系统标记写入命令行参数中，并将公钥参数信息、数字签名算法类型和熔断标记写入引导通信分区的第一位置；将加密后的消息摘要和消息摘要算法类型写入引导通信分区的第二位置；若根据系统标记和熔断标记确定需要校验，则对签名后的待升级固件进行校验；校验成功则对签名后的待升级固件进行升级，确保固件签名正确的前提下才对固件进行升级，且避免了升级没有签名的固件或使用错误密钥签名的固件，从而提高签名固件升级的可靠性.'
date: 2022-11-18
venue: '发明专利 Invention patent'
paperurl: 'https://patents.google.com/patent/CN115357293A'
citation: '纪大峣. (2022). &quot;升级签名固件的方法、电子设备和存储介质.&quot; <i>专利</i>. CN115357293A.'
citation: 'Dayao Ji. (2022). &quot;Method for upgrading signed firmware, electronic device and storage medium.&quot; <i>China patent</i>. CN115357293A.'
---
**升级签名固件的方法、电子设备和存储介质**

**摘要**：本发明公开了一种升级签名固件的方法、电子设备和存储介质，获取公钥参数信息、数字签名算法类型和消息摘要算法类型，并基于消息摘要算法类型计算与数字签名算法类型和公钥参数信息相对应的消息摘要；将消息摘要和系统标记写入命令行参数中，并将公钥参数信息、数字签名算法类型和熔断标记写入引导通信分区的第一位置；将加密后的消息摘要和消息摘要算法类型写入引导通信分区的第二位置；若根据系统标记和熔断标记确定需要校验，则对签名后的待升级固件进行校验；校验成功则对签名后的待升级固件进行升级，确保固件签名正确的前提下才对固件进行升级，且避免了升级没有签名的固件或使用错误密钥签名的固件，从而提高签名固件升级的可靠性。



**Method for upgrading signed firmware, electronic device and storage medium**

**Abstract:**The invention discloses a method for upgrading a signature firmware, an electronic device and a storage medium, which are used for acquiring public key parameter information, a digital signature algorithm type and a message digest algorithm type, and calculating a message digest corresponding to the digital signature algorithm type and the public key parameter information based on the message digest algorithm type; writing the message abstract and the system mark into a command line parameter, and writing public key parameter information, a digital signature algorithm type and a fusing mark into a first position of a guide communication partition; writing the encrypted message digest and the message digest algorithm type into a second position of the pilot communication partition; if the verification is determined to be needed according to the system mark and the fusing mark, verifying the signed firmware to be upgraded; if the verification is successful, the signed firmware to be upgraded is upgraded, the firmware is upgraded on the premise of ensuring correct signature of the firmware, and the upgrading of the firmware without signature or the firmware signed by using a wrong secret key is avoided, so that the upgrading reliability of the signed firmware is improved. 



[Download paper here](https://patents.google.com/patent/CN115357293A)



**Recommended citation:** 

纪大峣. 升级签名固件的方法、电子设备和存储介质[P]. 中国：CN115357293A,2022-11-18.

D. Ji,"Method for upgrading signed firmware, electronic device and storage medium," China Patent CN115357293A, November 18,2022.



