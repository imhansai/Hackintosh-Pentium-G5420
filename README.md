# Hackintosh-Pentium-G5420
奔腾金牌G5420,华硕 PRIME H310M-F R2.0 (300 Series 芯片组),NVIDIA GT-710(后更换为AMD RX560),opencore 引导 黑苹果

## 2022-08-31 修改内容

1. 在从Big Sur 升级到 Monterey 时，显卡由之前的英伟达 GT-710 更换为 AMD RX560D(盈通极速版),所以配置中 设备属性 模块有个小修改
    > 如果想继续使用 GT-710 的话，需要参阅下这个项目: https://github.com/chris1111/Geforce-Kepler-patcher
2. 注意针对自己的usb进行定制。可以根据这个仓库进行: https://github.com/corpnewt/USBMap

3. BIOS 目录只针对特定的配置，可以根据 https://dortania.github.io/OpenCore-Install-Guide/ 摸索