# MyApp

A WPF desktop application built with .NET Framework 4.8 and Visual Studio 2022.

## Features

- WPF user interface (project skeleton, features under active development)

## Requirements

- Windows 8 / 10 / 11 (.NET Framework 4.8 is included by default)

## Download

Prebuilt, code-signed releases are published on the [Releases page](https://github.com/stephen-chiang/MyApp/releases).

## Building from Source

1. Install [Visual Studio 2022](https://visualstudio.microsoft.com/) with the ".NET desktop development" workload
2. Clone this repository
3. Open `MyApp.sln` and build the **Release** configuration

```powershell
msbuild MyApp.sln /p:Configuration=Release
```

The executable is produced at `MyApp/bin/Release/MyApp.exe`.

## License

[MIT](LICENSE)

---

# MyApp（中文说明）

基于 .NET Framework 4.8 与 Visual Studio 2022 开发的 WPF 桌面应用程序。

## 功能特性

- WPF 图形界面（项目骨架，功能开发中）

## 运行环境

- Windows 8 / 10 / 11（系统默认内置 .NET Framework 4.8）

## 下载

经过代码签名的正式发布版本请前往 [Releases 页面](https://github.com/stephen-chiang/MyApp/releases) 获取。

## 从源码构建

1. 安装 [Visual Studio 2022](https://visualstudio.microsoft.com/)，勾选“.NET 桌面开发”工作负载
2. 克隆本仓库
3. 打开 `MyApp.sln`，以 **Release** 配置构建

```powershell
msbuild MyApp.sln /p:Configuration=Release
```

生成的可执行文件位于 `MyApp/bin/Release/MyApp.exe`。

## 许可证

[MIT](LICENSE)
