# 主机配置
<br>CPU：英特尔 i7-10700k</br>
<br>内存：微星 MPG Z490 GAMING EDGE WiFi</br>
<br>核显：英特尔 超核芯显卡 630</br> 
<br>独显：AMD Radeon R9 380</br> 
<br>硬盘：西部数据 SN500 NVMe</br> 

# bios设置：  

## 最实用的微星主板BIOS快捷键攻略   
<br>开机按 F2或者Del 进入BIOS设置</br> 
<br>开机按 F11 快速选择启动项选择</br>
<br>F10 保存BIOS更改的所有设置</br> 
<br>F7  BIOS中切换简易模式到高级模式</br>   

## 黑苹果建议的BIOS设置 

### 关闭以下选项： 
<br>Fast Boot  快速启动</br> 
<br>secure boot 安全启动 CSM  （修改为纯UEFI）</br> 
<br>VT-d</br>     
<br>Thunderbolt 有则先关掉，无则略过</br>    
<br>serial port有则先关掉，无则略过</br> 
<br>Intel SGX （非常不建议修改此项）</br>  
<br>Intel Platform Trust</br>    
<br>CFG Lock(MSR 0xE2) ，有则先关掉，无则考虑手工解锁或调整OC配置</br>          

### 开启以下选项：
<br>VT-x</br>  
<br>X.M.P 开启内存XMP，一般默认enable或选profile 1</br> 
<br>Above 4G decoding</br> 
<br>Hyper-Threading</br>   
<br>USB---EHCI/XHCI Hand-off</br>    
<br>SATA mode— ahci 大部分默认开启 （关闭raid)</br> 
<br>OS type: other Legacy</br>  
<br>RTC Device(关联Z370+）</br>  
<br>要想使用核显的，必须开启intel graphics （IGPU monitor），要选enable，不要选auto，设置DVMT（share memory）为64、128，直接选最大值</br>


# 苹果小兵镜像下载：
<br>[网站链接](https://blog.daliansky.net/macOS-Catalina-10.15.7-19H2-Release-version-with-Clover-5122-original-image-Double-EFI-Version-UEFI-and-MBR.html)</br>
[天翼云盘](https://cloud.189.cn/t/jm6FJfmUVrue)

# U盘制作工具
[启动盘制作工具balenaEtcher下载](https://www.balena.io/etcher/)

# plist编辑工具
[OpenCore编辑器](https://github.com/ic005k/QtOpenCoreConfig/releases)

# 配置检测网站
[OpenCore排错](https://opencore.slowgeek.com/)

# 注意
<br>U盘启动插到2.0接口，3.0会报禁止安装图标。</br>

# 感谢：
<br>[b站HangzhouLoser](https://space.bilibili.com/15539533?spm_id_from=333.788.b_765f7570696e666f.1)</br>
<br>[黑果小兵](https://blog.daliansky.net/)</br>
<br>[opencore团队](https://dortania.github.io/OpenCore-Post-Install/)</br>


