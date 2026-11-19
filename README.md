# 棱镜 Prism 发行下载

本仓库仅托管 Prism 安装包、签名业务资源包、更新清单与发行说明；产品源码仓及历史保持私有。

当前测试版：[0.1.5-beta](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.1.5-beta)

- [macOS Apple Silicon 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.1.5-beta/Prism-0.1.5-beta-mac-arm64.dmg)
- [Windows x64 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.1.5-beta/Prism-Setup-0.1.5-beta-win-x64.exe)
- [更新内容、Windows 验证步骤与已知限制](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.1.5-beta) · [历史版本](https://github.com/Sssovereign/prism-agent-releases/releases)

0.1.5-beta 新增项目编辑与文件夹换绑：设置中可重命名项目、增删工作目录（1–10 项）并指定主要目录，被移除的目录保留历史供文件回溯；同时修复本机业务页复制按钮全部失效的权限问题。

旧版本请退出棱镜后使用完整安装包覆盖安装。macOS 使用 DMG 手动升级。Windows 支持完整安装包和应用内整包更新，自动覆盖安装仍待 Windows 真机验收。

514 项产品测试、61 项桌面测试、两端包内完整性检查和 macOS 打包启动验证通过。macOS 尚未公证，Windows 安装包未配置 Authenticode 签名。

安装后无需另装 Node 或 pnpm。账号、模型配置、历史和凭据保存在本机。发行物包含可提取的编译后 JavaScript，公开下载不表示整个工程已开源，也不新增整个工程的开源许可；第三方许可随安装包保留。
