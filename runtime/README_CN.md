# YuuMira Windows 运行库依赖

[English](./README.md) · [**简体中文**](./README_CN.md)

此目录提供 Microsoft Visual C++ Redistributable 运行库安装程序，用于排查 YuuMira 在 Windows 上因运行库缺失而无法安装、启动或正常工作的问题。

| 文件 | 用途 |
| --- | --- |
| `VC_redist.x64.exe` | 64 位 Windows 应用运行库 |
| `VC_redist.x86.exe` | 32 位 Windows 应用运行库 |

YuuMira 当前提供 **Windows 64 位**版本，因此通常只需安装 `VC_redist.x64.exe`。仅在技术支持明确要求 32 位运行库时安装 `VC_redist.x86.exe`。

## 安装步骤

1. 退出 YuuMira。
2. 运行对应安装程序；系统要求时允许管理员权限。
3. 按 Microsoft 安装程序提示完成安装，并在要求时重启 Windows。
4. 重新启动 YuuMira，确认问题是否解决。

运行前请在文件属性的“数字签名”中确认发布者为 **Microsoft Corporation**。若问题仍然存在，请通过[中文错误报告模板](../../../issues/new/choose)提交 YuuMira 版本、Windows 版本、错误提示和复现步骤，切勿附带凭据或敏感日志。
