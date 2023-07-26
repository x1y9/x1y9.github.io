---
published: true
title: Power shell
layout: page
---

长久以来，我都是命令行的重度用户，在Windows下通常是使用cmd作为命令行工具，这里记录一下微软推荐的PowerShell的一点心得，虽然我还没有适应。

## 安装

* 在管理员模式下，先运行`set-executionpolicy remotesigned`以打开安全限制
* 安装fzf，然后安装wrapper，`Install-Module PSFzf`
`notead $profile`，加入以下内容

```
Import-Module PSFzf

# Override PSReadLine's history search
Set-PsFzfOption -PSReadlineChordProvider 'Ctrl+t' -PSReadlineChordReverseHistory 'Ctrl+r'

# Override default tab completion
Set-PSReadLineKeyHandler -Key Tab -ScriptBlock { Invoke-FzfTabCompletion }
```

## 优势

* 支持$()命令嵌套，这个对于提高效率非常有用。
* 支持跨Session的历史记录，F8查找很方便，和fzf集成后更方便。

## 缺点
* Powershell的管道，很多时候需要等待第一条命令完成，这就导致adb logcat|grep无法通过管道过滤查找了，好在可以这样：
```
adb logcat  | Select-String bandlog
```

## 从Cmd转换

* Powershell下Path缺省不包括当前目录，所以执行当前目录下的命令，需要加点。
* 连续多条命令，用分号连接，并且逻辑上不判断第一条命令是否成功，这和cmd不一样。

