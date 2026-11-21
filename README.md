# 棱镜 Prism 发行下载

本仓库托管 Prism 安装包、签名业务资源包、更新清单与发行说明。可构建源码和研究复现说明见 [棱镜开源仓库](https://github.com/Sssovereign/prism-agent-open)。

当前测试版为 [0.2.0-beta](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.2.0-beta)

- [macOS Apple Silicon 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.2.0-beta/Prism-0.2.0-beta-mac-arm64.dmg)
- [Windows x64 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.2.0-beta/Prism-Setup-0.2.0-beta-win-x64.exe)
- [发行说明与已知限制](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.2.0-beta) · [历史版本](https://github.com/Sssovereign/prism-agent-releases/releases)

0.2.0-beta 重做研究报告。辩论在首屏给出建议与依据，独立评审展示多数判定、通过条件及阻断项。用户可以提出异议、发起陪审复核、在同一会话续聊，或将决定交给任务助手执行。本版也修复了内嵌浏览器偶发不可用及面板位置偏移。

旧版本请退出棱镜后使用完整安装包覆盖安装。macOS 使用 DMG，Windows 使用 EXE。Windows 实机覆盖安装、自动重启和原生目录选择仍待验证。

581 项产品测试和 70 项桌面测试通过。macOS 已验证带数据升级，双平台安装包已通过完整性检查。macOS 尚未公证，Windows 安装包未配置 Authenticode 签名。

安装后无需另装 Node 或 pnpm。账号、模型配置、历史和凭据保存在本机。第三方许可随安装包保留。开源源码的许可与适用范围见 [源码仓库](https://github.com/Sssovereign/prism-agent-open#许可)。
