# sony-vaio-svf15217-hackintosh


引导版本:opencore0.8


测试系统:macOS11.6.6/macOS12.4


efi不包含wifi和蓝牙驱动！！！


使用方法for Monterey：只能使用默认的config.plist安装，安装完成后由于没显卡驱动操作起来会特别卡，直接重启进恢复模式，打开恢复模式里的终端输入两条关闭sip的代码，然后重启到系统
，进 https://github.com/dortania/OpenCore-Legacy-Patcher/releases/   下载.pkg补丁，打开补丁直接下一步下一步安装即可，安装完成后系统可能会自动重启，这时候可以删掉config.plist了，将config.plist.bak的.bak后缀删除然后重新注入自己的三码即可。


使用方法for Big Sur:删除config.plist，将config.plist.bak的.bak后缀删除然后重新注入自己的三码直接安装。


