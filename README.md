﻿# XBOFS.win
**XBOFS.win** allows you to use your **XBO Fight Stick** controller on Windows without having to install ancient, beta drivers 
and rewire buttons

## IMPORTANT
If you ended here looking to download and use **XBOFS.win** with your *XBO arcade stick* then you've landed in the wrong place.

Head over to the [main website](https://xbofs.win) to view the installation instructions and download the application.

## Dependencies

In order to compile this project you will need:
* [Microsoft Visual Studio Community 2019](https://visualstudio.microsoft.com)
* [Qt 5.x](https://www.qt.io/download-qt-installer)
* [Windows SDK 10.0.19041.0](https://download.microsoft.com/download/1/c/3/1c3d5161-d9e9-4e4b-9b43-b70fe8be268c/windowssdk/winsdksetup.exe)
* [WDK for Windows 10, version 2004](https://docs.microsoft.com/en-ca/windows-hardware/drivers/download-the-wdk)
* [vcpkg](https://github.com/microsoft/vcpkg)
    * [spdlog](https://github.com/gabime/spdlog) installed using vcpkg: `vcpkg install spdlog:x64-windows`

## Compilation

Compilation is quite simple:

1. Open the **XBOXFS.win.sln** file using Visual Studio
2. In *Solution Explorer*, right-click on the **XBOFS.win.qt5** project and click *Build*