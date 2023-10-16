# Hackintosh-Pentium-G5420
奔腾金牌G5420,华硕 PRIME H310M-F R2.0 (300 Series 芯片组),NVIDIA GT-710(后更换为AMD RX560),opencore 引导 黑苹果

## 2022-08-31 修改内容

1. 在从Big Sur 升级到 Monterey 时，显卡由之前的英伟达 GT-710 更换为 AMD RX560D(盈通极速版),所以配置中 设备属性 模块有个小修改
    > 如果想继续使用 GT-710 的话，需要参阅下这个项目: https://github.com/chris1111/Geforce-Kepler-patcher
2. 注意针对自己的usb进行定制。可以根据这个仓库进行: https://github.com/corpnewt/USBMap

3. BIOS 目录只针对特定的配置，可以根据 https://dortania.github.io/OpenCore-Install-Guide/ 摸索

## 2023-10-16 
1. 谨慎升级到Sonoma，博通网卡驱动被移除，需要使用OCLP来处理，但是有「严重的后遗症」  
远景: https://bbs.pcbeta.com/viewthread-1975545-1-1.html  
黑锅小兵: https://mp.weixin.qq.com/s/4RosLtK2W7L9T4CJEHgVKw    
注意⚠️: 由于关闭了SIP,所以会带来一些问题，比如iphone作为摄像头在chrome中无法授权导致无法使用等等
