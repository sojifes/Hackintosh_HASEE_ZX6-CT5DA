# Hackintosh_HASEE_ZX6-CT5DA
这是神舟战神 zx6-ct5da 的 OpenCore 引导的 EFI，希望借此可以分享我的经验，给更多同模具或同机型带来方便  
本机型适于 NB60TA 模具，NB50/60 其他系列未经测试，移动版 UHD630 的机型，不适合台式机，或其他较老的机器

这个是我研究了几天的教程才做出的，参考了各路大神教程的指点，依旧存在很多不足之处  
如有不足，漏缺错误等，请批评指正，新人刚了解黑苹果，涉猎无多

参考过的教程（顺序不分先后，对事不对人）：  
xjn: https://blog.xjn819.com/  
黑果小兵：https://blog.daliansky.net/OpenCore-BootLoader.html  
宪武：https://github.com/daliansky/OC-little  
独行秀才：https://shuiyunxc.gitee.io/2020/03/10/instru/index/  
等等

注意：虽然目前已经经过实机的测试，但仍处于待完善的状态，仅供学习研究之用，  
本人对可能产生的不良后果不负任何责任，亦与苹果公司无任何关联

（以下仅根据目前个人已知的情况述说）  
正常：  
UHD 630 正常，显存 2048  
HDMI 输出正常，但不可热插拔；若内屏不亮，请尝试开合一次盖子（1080p 60fps/ 4k 30fps）  
WiFi & 蓝牙正常，WiFi 请使用 [HeliPort](https://github.com/OpenIntelWireless/HeliPort/releases) 前端  
音频输入输出正常  
触摸板，键盘正常  
摄像头正常

问题：  
亮度调节快捷键无法使用  
无法正常睡眠、降频（就是频率不能降得比基频低，暂时不知道原因，手动睡眠直接黑屏）  
动画掉帧，在实装各 EFI 上均有出现（貌似核显性能不能完全利用，白果也有类似情况)  
读卡器，雷电接口不能使用  

动向：  
个人目前在了解 OC 的补丁内容，希望能解决更多问题，带来更好体验
