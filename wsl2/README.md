# WSL2

## 安装 WSL2

安装 WSL2 参见 [Windows Subsystem for Linux Installation Guide for Windows 10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

## 移动至数据盘

WSL2 是安装在 C 盘的，使用 [LxRunOffline](https://github.com/DDoSolitary/LxRunOffline) 将其移动至其他数据盘中。

使用管理员权限运行 PowerShell 运行

    PS D:\files\Downloads\LxRunOffline-v3j-%r@%h:%p.5.0-msvc> .\LxRunOffline.exe move -n <distro> -d <path>
    PS D:\files\Downloads\LxRunOffline-v3.5.0-msvc> .\LxRunOffline.exe  get-dir -n <distro>

## 安装 Windows Terminal

安装和配置 Windows Terminal 参见 [Install and set up Windows Terminal](https://docs.microsoft.com/en-us/windows/terminal/get-started)

配置文件见 `./windows-terminal-setting.json`

**注意** 在拷贝配置文件前，修改配置文件的 `startingDirectory` 部分，以配置新窗口的默认打开路径。
