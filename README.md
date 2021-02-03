# 主机配置
CPU：英特尔 i7-10700k. 
内存：微星 MPG Z490 GAMING EDGE WiFi. 
核显：英特尔 超核芯显卡 630. 
独显：AMD Radeon R9 380. 
硬盘：西部数据 SN500 NVMe. 

# bios设置：  

## 最实用的微星主板BIOS快捷键攻略   
开机按 F2或者Del 进入BIOS设置 
开机按 F11 快速选择启动项选择
F10 保存BIOS更改的所有设置 
F7  BIOS中切换简易模式到高级模式   

## 黑苹果建议的BIOS设置 

### 关闭以下选项： 
Fast Boot  快速启动. 
secure boot 安全启动 CSM  （修改为纯UEFI）. 
VT-d.     
Thunderbolt 有则先关掉，无则略过.    
serial port有则先关掉，无则略过. 
Intel SGX （非常不建议修改此项）.  
Intel Platform Trust.    
CFG Lock(MSR 0xE2) ，有则先关掉，无则考虑手工解锁或调整OC配置          

### 开启以下选项：
VT-x.  
X.M.P 开启内存XMP，一般默认enable或选profile 1. 
Above 4G decoding. 
Hyper-Threading.   
Above 4G decoding. 
Above 4G decoding. 
USB---EHCI/XHCI Hand-off.    
Above 4G decoding. 
SATA mode— ahci 大部分默认开启 （关闭raid).  
OS type: other Legacy.  
RTC Device(关联Z370+）.  
要想使用核显的，必须开启intel graphics （IGPU monitor），要选enable，不要选auto，设置DVMT（share memory）为64、128，直接选最大值。


# 苹果小兵镜像下载：
[网站链接](https://blog.daliansky.net/macOS-Catalina-10.15.7-19H2-Release-version-with-Clover-5122-original-image-Double-EFI-Version-UEFI-and-MBR.html)
[天翼云盘](https://cloud.189.cn/t/jm6FJfmUVrue)

# U盘制作工具
[启动盘制作工具balenaEtcher下载](https://www.balena.io/etcher/)

# plist编辑工具
[OpenCore编辑器](https://github.com/ic005k/QtOpenCoreConfig/releases)

# 配置检测网站
[OpenCore排错](https://opencore.slowgeek.com/)


# 感谢：
b站：[HangzhouLoser](https://space.bilibili.com/15539533?spm_id_from=333.788.b_765f7570696e666f.1)
[黑果小兵](https://blog.daliansky.net/)
[opencore团队](https://dortania.github.io/OpenCore-Post-Install/)


