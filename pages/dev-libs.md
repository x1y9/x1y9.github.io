---
published: true
title: 开发者工具箱
layout: page
order: 5
---

## Hybrid desktop 
桌面普通应用，不和OS紧密集成，可以考虑下面两个方案：
* [Wails](https://wails.io/) Webview+Go
* [Tauri](https://v2.tauri.app/) Webview+Rust，比Wails有更好的Native支持。

这两个框架在windows下生成的应用在10M左右。

## Hybrid all
移动平台，跨OS方案主要是
* [Flutter](https://flutter.dev/) 更成熟
* [KMM](https://kotlinlang.org/docs/multiplatform.html) Jetbrain的全平台框架
  
## Web框架 
* [Vue](https://vuejs.org/)和[Svelte](https://svelte.dev/), 一般认为Svelte更简洁，Vue的第三方库更多（比如UI库）。
  
## Web UI
Web UI的选择太多：

* Vue可以用 [PrimeVue](https://primevue.org/)
* Svelte可以用 [Shadcn](https://www.shadcn-svelte.com/)，基于[Bits UI](https://bits-ui.com/)和Me
* 表单，有复杂的表单需求可以看看单独的表单库。
* 还有一些基于css的ui库通常可以和任何框架配合，比如[daisyUI](https://daisyui.com/) 

## TUI
* Python有一个[Textual](https://github.com/textualize/textual/)

## 即时UI
即时UI是实时刷新的UI，适合于游戏，图表类应用。
* [Dear ImGui](https://github.com/ocornut/imgui)
  
## 其他UI
* Go有[fyne](https://fyne.io/)，但缺少Common Dialog等关键特性，也不好看，基础版本也不小（22M），好处是可以兼容更多的系统，比如win7、移动端。
* Python有[CustomTkinter](https://github.com/tomschimansky/customtkinter) 比标准的Tk好看很多。
* Python的[NiceGUI](https://github.com/zauberzeug/nicegui/) 很有趣，基于Vue+Quasar，但是做了python封装，同时支持前后端开发。
* Java的Swing，其实很好，并且[更好看](https://github.com/JFormDesigner/FlatLaf)，但和Python一样，发布要考虑jre的问题。
* .Net主要是Winform和WPF，总体上Winform轻量，WPF更强大，比如独立线程UI，高速绘图，但WPF有不少小坑。

## PDF提取
* [pdftotext](https://www.xpdfreader.com/) 单exe，1M，提取中文要加-enc UTF-8参数，表格/图片/公式都不支持，其他没问题。
* [docling](https://github.com/DS4SD/docling) IBM开源的工具，基于AI，表格/图片/公式统统支持，但中文稍有瑕疵（比如数字一很容易识别为连字符)，比marker效果好不少。

## chrome
* 禁用https证书检查，可以用：`--ignore-certificate-errors`
* 禁用CORS，可以用：`--disable-site-isolation-trials --disable-web-security --user-data-dir="d:/temp"`

## git
* 如果有本地代理，可以加速github， `git config --global http.https://github.com.proxy socks5://127.0.0.1:8888`
* 如果本地git库没有ssl证书，可以`git config --global http.sslVerify false`

## Windows
* 启用LocalDump，`reg add "HKLM\SOFTWARE\Microsoft\Windows\Windows Error Reporting\LocalDumps" /f`
