<img align="left" src="https://github.com/system-informer-patched-repo/v3.2.25011.2103/raw/master/SystemInformer/resources/systeminformer-128x128.png" width="128" height="128" style="max-width: 100%;padding-right: 20px;">

## System Informer

一款免费、功能强大、用途广泛的工具，可帮助您监控系统资源、调试软件和检测恶意软件。由 Winsider Seminars & Solutions, Inc. 出品。

[项目官网](https://systeminformer.com/) - [软件下载](https://systeminformer.com/downloads.php)

## 系统要求

Windows 10 或更高版本，32 位或 64 位。

## 功能

* 系统活动概览，并带有高亮显示。
* 图表和统计信息可帮助您快速追踪占用大量系统资源和异常进程。
* 无法编辑或删除文件？查找正在使用该文件的进程。
* 查看哪些程序具有活动的网络连接，并在必要时关闭它们。
* 获取磁盘访问的实时信息。
* 查看支持内核模式、WOW64 和 .NET 的详细堆栈跟踪。
* 超越 services.msc：创建、编辑和管理服务。
* 小巧便携，无需安装。
* 100% [自由软件](https://www.gnu.org/philosophy/free-sw.en.html) ([MIT](https://opensource.org/licenses/MIT))


## 构建项目

需要 Visual Studio（2022 或更高版本）。

克隆仓库后，运行位于 `build` 目录下的 `build_init.cmd` 文件。除非工具或第三方库有更新，否则此文件不会再次运行。

执行位于 `build` 目录下的 `build_release.cmd` 文件来编译项目，或者如果您希望使用 Visual Studio 构建项目，则可以加载 `SystemInformer.sln` 和 `Plugins.sln` 解决方案。

您可以下载免费的 [Visual Studio Community Edition](https://www.visualstudio.com/vs/community/) 来构建 System Informer 源代码。

有关更多信息或构建问题，请参阅 [构建说明](./build/README.md)。

## 功能增强/错误报告

请使用 [GitHub 问题跟踪器](https://github.com/system-informer-patched-repo/v3.2.25011.2103/issues) 报告问题或提出新功能建议。


## 设置

如果您是从 USB 驱动器运行 System Informer，您可能希望将 System Informer 的设置也保存到该驱动器上。为此，请在与 SystemInformer.exe 相同的目录中创建一个名为“SystemInformer.exe.settings.xml”的空白文件。您可以使用 Windows 资源管理器执行此操作：

1. 确保在“工具”>“文件夹选项”>“查看”中取消选中“隐藏已知文件类型的扩展名”。
2. 右键单击​​文件夹，然后选择“新建”>“文本文档”。
3. 将文件重命名为 SystemInformer.exe.settings.xml（删除“.txt”扩展名）。

## 插件

插件可在“选项”>“插件”中进行配置。

如果遇到任何与插件相关的崩溃问题，请确保插件已更新至最新版本。

ExtendedTools 插件提供的磁盘和网络信息仅在以管理员权限运行 System Informer 时可用。