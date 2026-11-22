# 棱镜 Prism 发行下载

本仓库托管 Prism 安装包、签名业务资源包、更新清单与发行说明。可构建源码和研究复现说明见 [棱镜开源仓库](https://github.com/Sssovereign/prism-agent-open)。

当前测试版为 [0.2.1-beta](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.2.1-beta)

- [macOS Apple Silicon 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.2.1-beta/Prism-0.2.1-beta-mac-arm64.dmg)
- [Windows x64 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.2.1-beta/Prism-Setup-0.2.1-beta-win-x64.exe)
- [发行说明与已知限制](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.2.1-beta) · [历史版本](https://github.com/Sssovereign/prism-agent-releases/releases)

0.2.1-beta 让辩论与评审参与者共享任务助手的按需读取能力：可自行查看项目文件、图片材料、技能与项目规则，创建时可附图片并按角色模型预检。新研究任务卡分层呈现稳定规则、角色职责与输出契约，历史发言以限量摘要进入上下文、全文按需读取；整场预算默认放大到 240 次模型请求、480 次工具请求、90 分钟，匹配按需读取的真实消耗。

旧版本请退出棱镜后使用完整安装包覆盖安装。macOS 使用 DMG，Windows 使用 EXE。Windows 实机覆盖安装、自动重启和原生目录选择仍待验证。

617 项产品测试和 70 项桌面测试通过，隔离构建与 mac 打包冒烟通过。双平台安装包与业务更新包已通过完整性检查；四身份更新源发现验证通过（0.2.0 实测发现 0.2.1 完整安装，0.2.1 显示已是最新）。macOS 尚未公证，Windows 安装包未配置 Authenticode 签名。

安装后无需另装 Node 或 pnpm。账号、模型配置、历史和凭据保存在本机。第三方许可随安装包保留。开源源码的许可与适用范围见 [源码仓库](https://github.com/Sssovereign/prism-agent-open#许可)。
