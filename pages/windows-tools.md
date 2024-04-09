---
published: true
title: Windows工具
layout: page
---

记录了我在Windows下收集的工具，我偏爱portable的软件，这些基本都是free且portable的工具。这样重装windows的时候不需要再安装这些工具了，换电脑的时候，一个目录复制过去就可以了。


## 工具
1. [Clink](https://github.com/chrisant996/clink) 支持CMD记录历史，可以和Windows Terminal集成。
1. [Windows Terminal](https://github.com/microsoft/terminal) 微软自己的Terminal，对中文支持更好，但字体有时发虚。
1. [Google password](https://passwords.google.com/) 和Chrome和指纹集成后，管理密码变得非常方便和安全。
1. [7Zip](http://www.7-zip.org/) 压缩工具
1. [Everything](https://www.voidtools.com/) 快速文件搜索，内置的HttpServer也很好用。
1. [DocFetcher](https://http://docfetcher.sourceforge.net/) 文件内容搜索，支持指定目录做索引。
1. [F2](https://github.com/ayoisaiah/f2) 最好的命令行批量改名工具，支持预览和正则表达式。
1. [AutoHotKey](https://autohotkey.com/) 键盘快捷键自定义。 
3. [HxD](https://mh-nexus.de/en/hxd/) 十六进制编辑器
4. [Emeditor](https://www.emeditor.com/download/) 最好的通用编辑器，免费版够用了，Portable版本要在shell:sendto下面增加它的快捷方式。
5. [LibreOffice](https://www.libreoffice.org/) 代替微软Office，这个需要安装，不要用portable版本。
6. [Insomnia](http://dlaa.me/blog/post/10104830) 防止休眠
7. [Ditto](http://ditto-cp.sourceforge.net/) 多剪贴板，Windows10以后可以不需要了。
8. [CCleaner](https://www.piriform.com/ccleaner) 垃圾文件清理，老版本很好用，新版嵌入了垃圾软件，但我暂时没找到更好的，姑且留在这里。
9. [AllDup](http://www.alldup.de) 免费portable的重复文件查找，功能强大，图像重复查找很棒。
10. [TreeSizeFree](https://www.jam-software.com/treesize_free/) 磁盘空间管理，在shell:sendto下增加快捷方式后很好用。 
11. [Unison](http://unison-binaries.inria.fr/) 文件目录同步, 双向rsync
12. [CopyTranslator](https://github.com/CopyTranslator/CopyTranslator) 浮窗翻译，缺点是占用过多内存。
13. [rufus](https://rufus.akeo.ie/) 格式化usb启动盘
14. [nssm](https://nssm.cc/) 把任何程序转为Windows服务
15. [Scrcpy](https://github.com/Genymobile/scrcpy) 用pc控制手机，也可以同步剪贴板。
16. [Hourglass](https://chris.dziemborowicz.com/apps/hourglass/#downloads) 小巧的计时器
17. [gImageReader](https://github.com/manisandro/gImageReader) 也许比商用OCR软件差一点，但在开源OCR里，这个算很好的。


## 媒体
1. [SumatraPDF](https://www.sumatrapdfreader.org/free-pdf-reader.html): 轻量PDF/EPUB阅读工具，多标签页。
1. [cpdf](https://github.com/coherentgraphics/cpdf-binaries): PDF命令行工具，比如拆分、合并、增加页码等功能。
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
1. [Visual Studio Code](https://code.visualstudio.com/) 大部分项目的IDE，Markdown编辑也非常好用。
1. [DotPeek](https://www.jetbrains.com/decompiler/) Jetbrains的.net反编译器，对于小项目，[DnSpy](https://github.com/dnSpy/dnSpy)也很好用。
1. [git](https://git-scm.com/) 版本控制和linux工具集
1. [Sikulix](https://sikulix.github.io/) 最好的GUI自动化工具，通过图片识别来支持包括网页在内的任意GUI应用。
1. [gitui](https://github.com/extrawurst/gitui) 命令行下的git客户端，浏览版本历史挺好用的。
2. [stdump](https://github.com/odinserj/stdump) .net程序dump工具

## 设计
1. [Just Color Picker](http://annystudio.com/software/colorpicker/) 取色工具。
2. [draw.io](https://www.drawio.com/) 通用矢量图工具，对Latex/SVG支持非常好。
3. [yed](https://www.yworks.com/products/yed) 轻量流程图制作，内置的自动排版算法非常棒。
   

## 网络
1. [LocalSend](https://localsend.org) 局域网文件分享
1. [Aria2](https://github.com/aria2/aria2) 命令行下载工具
1. [ipScan](http://angryip.org/)  IP搜索
1. [Putty](http://www.putty.org/)  SSH/串口客户端
1. [MobaXTerm](http://mobaxterm.mobatek.net/)  SSH客户端，支持Mosh，以及一套cygwin工具集（rsync等）
1. [mongoose](https://www.cesanta.com/products/binary) 超轻量的Http服务器
2. [FileBrowser](https://filebrowser.org/) Go开发的单exe文件管理web服务，在Kindle上也很好用。
3. [syncthing](https://syncthing.net/) 多服务器同步
4. [eMule](https://www.emule-project.net) 下载非常冷门的资源 

## 数据库
1. [HeidiSql](https://www.heidisql.com/) Mysql/mariadb 客户端
1. [dbeaver](https://dbeaver.jkiss.org/) JDBC数据库管理客户端 

## 数据处理
1. [SciDAVis](http://scidavis.sourceforge.net/) 数据处理，替代Origin
2. [LaTeX-OCR](github.com/lukas-blecher/LaTeX-OCR) 一个Python命令行工具，将图片转换到Latex，可以支持直接粘贴剪贴板图片。

## 娱乐
1. [dosbox](https://sourceforge.net/projects/dosbox/) dos模拟器，玩老游戏和程序。
2. [BizHawk](https://github.com/TASEmulators/BizHawk) NES等模拟器，对蓝牙手柄支持相对较好。

## Windows修补
Windows总有一些用着不舒服的地方，可以找一些修补工具。
1. [Windows11 安装](https://4sysops.com/archives/install-windows-10-11-22h2-without-microsoft-account/) 跳过安装时的微软账号登录，简单的说就是Shift-F10加一条命令`oobe\BypassNRO`。 
1. [Windows11 恢复右键菜单](https://pureinfotech.com/bring-back-classic-context-menu-windows-11/) :简单的说就是一条命令: `reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve` 
1. [Classic Shell](http://www.classicshell.net/) Windows8下用来找回开始菜单，win10及以上可以不用了。
1. [VC运行时](https://github.com/abbodi1406/vcredist) 很多软件都依赖VC运行时，因为版本非常多，常常漏掉，这个包一次行全部安装。
1. Windows11更新了微软输入法会导致很多键盘快捷键失效(比如Shift-F6), 要在输入法设置里兼容老版本才可以。
