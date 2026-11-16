# Design Console 安装包

Windows 桌面版 **Design Console**（AI 设计工作台）的官方下载仓库。这里只放安装包与发布说明，不存放源码。

## 下载

| 版本 | 说明 |
| --- | --- |
| `DesignConsole-Setup-<版本>.exe` | 安装版，装到系统里，开始菜单可见 |
| `DesignConsole-Portable-<版本>.exe` | 免安装版，双击即用，数据存在程序目录旁的 `data` 文件夹 |

- 最新发布：<https://github.com/AI-wantuju/design-console-package/releases/latest>
- 官网（含 SHA256 校验值）：<https://www.tujuyun.com/#install>

## 要求

- Windows 10 / 11（x64）
- 无需账号，项目文件与密钥都留在本机

## 校验下载

PowerShell 里执行，与官网公布的 SHA256 比对：

```powershell
Get-FileHash .\DesignConsole-Setup-<版本>.exe -Algorithm SHA256
```
