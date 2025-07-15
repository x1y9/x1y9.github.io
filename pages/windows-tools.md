---
published: true
title: Windows工具箱
layout: page
order: 1
---

记录了我在Windows下收集的工具，我偏爱portable的软件，这些基本都是free且portable的工具。这样重装windows的时候不需要再安装这些工具了，换电脑的时候，一个目录复制过去就可以了。

## AI
1. [Ollama](https://github.com/ollama/ollama) 本地运行DeepSeek等开源AI模型。

## 工具
1. [Clink](https://github.com/chrisant996/clink) 支持CMD记录历史，可以和Windows Terminal集成。
1. [Windows Terminal](https://github.com/microsoft/terminal) 微软自己的Terminal，对中文支持更好，但字体有时发虚。
1. [Google password](https://passwords.google.com/) 和Chrome和指纹集成后，管理密码变得非常方便和安全。
1. [7Zip](http://www.7-zip.org/) 压缩工具，高级用户推荐[zstd](https://github.com/mcmilk/7-Zip-zstd)扩展版本，zstd算法非常快。
1. [Everything](https://www.voidtools.com/) 快速文件搜索，内置的HttpServer也很好用。
1. [F2](https://github.com/ayoisaiah/f2) 最好的命令行批量改名工具，支持预览和正则表达式。
1. [AutoHotKey](https://autohotkey.com/) 键盘快捷键自定义。 
3. [HxD](https://mh-nexus.de/en/hxd/) 十六进制编辑器
4. [Emeditor](https://www.emeditor.com/download/) 最好的通用编辑器，免费版够用了，Portable版本要在shell:sendto下面增加它的快捷方式。
5. [LibreOffice](https://www.libreoffice.org/) 代替微软Office，这个需要安装，不要用portable版本。
6. [Insomnia](http://dlaa.me/blog/post/10104830) 防止休眠
7. [Ditto](http://ditto-cp.sourceforge.net/) 多剪贴板，Windows10以后可以不需要了。
8. [CCleaner](https://www.piriform.com/ccleaner) 垃圾文件清理，老版本很好用，新版嵌入了垃圾软件，但我暂时没找到更好的，姑且留在这里。
9. [AllDup](http://www.alldup.de) 免费portable的重复文件查找，功能强大，图像重复查找很棒。
10. [TreeSizeFree](https://www.jam-software.com/treesize_free/) 磁盘空间管理，在shell:sendto下增加快捷方式后很好用，[WizTree](https://diskanalyzer.com/)也不错。 
11. [Unison](http://unison-binaries.inria.fr/) 文件目录同步, 双向rsync
12. [CopyTranslator](https://github.com/CopyTranslator/CopyTranslator) 浮窗翻译，缺点是占用过多内存。
13. [rufus](https://rufus.akeo.ie/) 格式化usb启动盘。
14. [nssm](https://nssm.cc/) 把任何程序转为Windows服务。
15. [Scrcpy](https://github.com/Genymobile/scrcpy) 用pc控制手机，也可以同步剪贴板。
16. [Hourglass](https://chris.dziemborowicz.com/apps/hourglass/#downloads) 小巧的计时器
17. [gImageReader](https://github.com/manisandro/gImageReader) 也许比商用OCR软件差一点，但在开源OCR里，这个算很好的。
18. [NTop](https://github.com/gsass1/NTop) 开源的控制台HTop工具，非常轻量。
19. [Deskreen](https://github.com/pavlobu/deskreen) 将手机或其他pc上的浏览器变成扩展屏。
20. [HWiNFO](https://www.hwinfo.com/) 硬件检测。

## 文档
1. [SumatraPDF](https://www.sumatrapdfreader.org/free-pdf-reader.html): 轻量PDF/EPUB阅读工具，多标签页。
1. [DocFetcher](https://http://docfetcher.sourceforge.net/) 文档内容搜索，支持指定目录做索引。
1. [cpdf](https://github.com/coherentgraphics/cpdf-binaries): PDF命令行工具，比如拆分、合并、增加页码等功能。
1. [XpdfReader](https://www.xpdfreader.com/) 一个阅读器，但包括一组高质量的pdf提取工具，比如pdftotext转文本，pdftopng转图片，非常轻量。
1. [Docling](https://github.com/DS4SD/docling): 基于AI的PDF/WORD文档提取工具，支持公式，表格。

## 媒体
1. [MPC-HC](https://mpc-hc.org/) 非常轻量的播放器，CPU占用极低，适合笔记本使用。
1. [Vlc](http://www.videolan.org/vlc/) 兼容性很好的播放器
1. [IrfanView](http://www.irfanview.com/) 超轻量且支持格式极多的图片查看器。
1. [ImageMagick](https://imagemagick.org/index.php) 如果要在命令行处理图片，比如缩放、格式转换，就这个了。
1. [GreenShot](http://getgreenshot.org/) 截屏工具，picpick也很不错，Windows10内置的Win+shift+S一般也够用。
1. [LICEcap](https://www.cockos.com/licecap/) 录制动态GIF。
1. [FFmpeg](https://ffmpeg.org/) 转换音视频格式的命令行工具。
1. [WaveShop](http://waveshop.sourceforge.net/) 轻量的音频编辑工具。
1. [OBS](https://obsproject.com/) 直播和录制视频，比ShareX性能要好。
1. [MeshLab](https://www.meshlab.net/) 各种3d文件查看，编辑和算法处理。

## 编程
1. [WinPython](https://winpython.github.io/) Python环境和第三方库，比Anaconda更portable，且License友好。
1. [Java](https://adoptium.net/) 一般情况下Openjdk就可以了，这个网站下载比Oracle方便很多。
1. [Eclipse](https://www.eclipse.org/) Java IDE，虽然IntelliJ很好用，这个胜在免费。
1. [CodeBlocks](http://www.codeblocks.org/) 跨平台的c++ IDE，比visual studio小多了，做些小东西可以用。
1. [lazarus](https://www.lazarus-ide.org/) Delphi的开源版本，做GUI小工具不错。
1. [Visual Studio Code](https://code.visualstudio.com/) 大部分项目的IDE，Markdown编辑/AI插件Cline也非常好用。
1. [DotPeek](https://www.jetbrains.com/decompiler/) Jetbrains的.net反编译器，对于小项目，[DnSpy](https://github.com/dnSpy/dnSpy)也很好用。
1. [git](https://git-scm.com/) 版本控制和linux工具集
1. [Sikulix](https://sikulix.github.io/) 最好的GUI自动化工具，通过图片识别来支持包括网页在内的任意GUI应用。
2. [stdump](https://github.com/odinserj/stdump) .net程序dump工具。
3. [procdump](https://learn.microsoft.com/en-us/sysinternals/downloads/procdump) 可以强制dump的小工具，比如crash dump。
4. [CPU Grab Ex](https://www.the-sz.com/products/cpugrabex/) 模拟CPU占用的工具，精确到指定的核。
5. [RamMap](https://learn.microsoft.com/en-us/sysinternals/downloads/rammap) 内存工具，可以清理Windows缓存，支持命令行。

## 设计
1. [Just Color Picker](http://annystudio.com/software/colorpicker/) 取色工具。
2. [draw.io](https://www.drawio.com/) 通用矢量图工具，对Latex/SVG支持非常好。
3. [OpenSCAD](https://openscad.org/) 通过简单的脚本编程设计3D模型，也有一个简易的[在线](https://github.com/openscad/openscad-playground)版本。
4. [yed](https://www.yworks.com/products/yed) 轻量流程图制作，内置的自动排版算法非常棒。
   
## 网络
1. [LocalSend](https://localsend.org) 局域网文件分享
2. [tailscale](https://tailscale.com/) 神器，跨网直连，全平台客户端。
3. [Aria2](https://github.com/aria2/aria2) 命令行下载工具
4. [ipScan](http://angryip.org/)  IP搜索
5. [Putty](http://www.putty.org/)  SSH/串口客户端
6. [MobaXTerm](http://mobaxterm.mobatek.net/)  SSH客户端，支持Mosh，以及一套cygwin工具集（rsync等）
7. [mongoose](https://www.cesanta.com/products/binary) 超轻量的Http服务器
8. [FileBrowser](https://filebrowser.org/) Go开发的单exe文件管理web服务，在Kindle上也很好用。
9. [syncthing](https://syncthing.net/) 多服务器同步
10. [mitmproxy](https://mitmproxy.org/) Http代理，用来抓包非常好用。
11. [eMule](https://www.emule-project.net) 下载非常冷门的资源 

## 数据库
1. [HeidiSql](https://www.heidisql.com/) Mysql/mariadb 客户端
1. [dbeaver](https://dbeaver.jkiss.org/) JDBC数据库管理客户端 

## 数据处理
1. [SciDAVis](http://scidavis.sourceforge.net/) 数据处理，替代Origin
2. [LaTeX-OCR](https://github.com/lukas-blecher/LaTeX-OCR) 一个Python命令行工具，将图片转换到Latex，可以支持直接粘贴剪贴板图片，比在线的Mathpix稍差一些。
3. [jq](https://jqlang.org/) json数据处理，也可以转换到csv

## 娱乐
1. [dosbox](https://sourceforge.net/projects/dosbox/) dos模拟器，玩老游戏和程序。
2. [BizHawk](https://github.com/TASEmulators/BizHawk) NES等模拟器，对蓝牙手柄支持相对较好。

## Windows修补
Windows总有一些用着不舒服的地方，可以找一些修补工具。
1. Windows更新虽然可以暂停，但时间太短，可以通过这个修改最长暂停时间：`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings" /v FlightSettingsMaxPauseDays /t reg_dword /d 9999 /f`
1. [Windows11 安装](https://4sysops.com/archives/install-windows-10-11-22h2-without-microsoft-account/) 跳过安装时的微软账号登录，简单的说就是Shift-F10加一条命令`oobe\BypassNRO`。 
1. [Windows11 恢复右键菜单](https://pureinfotech.com/bring-back-classic-context-menu-windows-11/) :简单的说就是一条命令: `reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`
1. 硬盘从休眠启动会导致系统正在运行时忽然的卡顿，如果不希望，可以这样关闭：`powercfg /change disk-timeout-ac 0`
1. Windows的'快速启动'功能会使用注销+休眠代替关机，因此会带来一些稳定性问题，可以直接关闭系统休眠功能从而禁用快速启动: `powercfg /h off`
1. [Classic Shell](http://www.classicshell.net/) Windows8下用来找回开始菜单，win10及以上可以不用了。
1. [VC运行时](https://github.com/abbodi1406/vcredist) 很多软件都依赖VC运行时，因为版本非常多，常常漏掉，这个包一次行全部安装。
1. Windows11更新了微软输入法会导致很多问题，比如键盘快捷键失效(比如Shift-F6), 远程时VSCode卡顿等，要在输入法设置里兼容老版本可以修复。

## Windows自定义安装
现代Windows(10/11)的自定义安装主要通过应答文件，应答文件是一个xml文件，并支持调用脚本，标准的Windows安装盘iso文件中涉及自定义的文件如下：
* sources下的install.wim存储了Windows的完整系统映像，并可能包含多个Windows版本（比如家庭版、专业版等）。
* autounattend.xml应答文件，放在iso根目录下就好，缺省的iso里是没有的。

Windows的初始镜像iso可以从微软下载，但旧版本的iso，微软网站下载不方便，可以从[这里](https://os.click) 下载，但Windows11中文版本的iso需要从英文的iso和一个svf文件通过merge来完成，用这个[工具](https://www.smartversion.com/download.htm)来合并得到中文版iso。

下一步是自定义应答文件，可以通过[这里](https://schneegans.de/windows/unattend-generator/)去定制，大概能做的自定义包括：
* 集成安装Key
* 选择Windows版本，比如专业版
* 是否创建本地账户
* 是否禁止oobe，可以做到无人值守安装
* 是否禁止自动更新和更新后的自动重启
* 卸载一些onedrive之类的附加软件
* 优化windows操作体验
* 运行指定的脚本

下载得到的autounattend.xml，然后从原版iso中解出install.wim去集成想要的额外的驱动，驱动必须是inf格式的，但大部分exe格式的驱动直接解压缩就可以得到inf格式的驱动。下面的脚本完成驱动集成，第一步中index:4就表示要修改wim里的哪个windows版本，可以预先通过`dism /get-wiminfo /wimfile:install.wim`列举。 

```
dism /Mount-Wim /WimFile:install.wim /index:4 /MountDir:wim-mount
dism /image:wim-mount /add-driver /driver:dell-drivers /recurse
dism /Unmount-Wim /MountDir:wim-mount /commit
```
  
执行完成后install.wim会被更新，现在就可以通过[Anyburn工具](https://www.anyburn.com/)生成自定义镜像iso了，打开原版iso，做以下修改：
* 将sources下的install.wim替换
* 在根目录下添加autounattend.xml
* 修改卷标(可选)

生成得到的这个镜像可以随时通过rufus制作可引导u盘来装机：
* U盘分区可以用MBR或GPT格式，有些电脑可以用MBR格式U盘启动，但有些则必须用GPT格式，比如微软surface。如果无法做不到U盘启动，也可以在原windows下启动安装，速度稍慢。
* rufus自己也可以设置应答文件，但我们已经设置过了，所以rufus的应答文件选项全部不选即可。

如果想将最终U盘设为只读，有几个方法：
* 用U盘量产工具分只读区或CDROM区，但很难找工具。
* 用diskpart工具，设置attributes disk readonly，但只对当前计算机生效。
* 用diskpart工具，设置attributes volume readonly，但只对硬盘生效，u盘不能设置。
* 用NTFS文件系统，取消everyone的写权限（可能会报一个System Volume Information的错误，忽略就好）。

上面的方法是基本不修改wim（只加驱动）的基础上做的，还有一个方法就完全自定义wim，通过虚拟机裁剪好所有windows内容，再封装为wim，灵活性高，但可维护性差，我不是很推荐。
