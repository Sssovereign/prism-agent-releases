# 棱镜 Prism 发行下载

本仓库仅托管 Prism 安装包、签名业务资源包、更新清单与发行说明；产品源码仓及历史保持私有。

当前测试版：[0.1.1-beta](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.1.1-beta)

- [macOS Apple Silicon 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.1.1-beta/Prism-0.1.1-beta-mac-arm64.dmg)
- [Windows x64 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.1.1-beta/Prism-Setup-0.1.1-beta-win-x64.exe)
- [更新内容、Windows 验证步骤与已知限制](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.1.1-beta) · [历史版本](https://github.com/Sssovereign/prism-agent-releases/releases)

0.1.1-beta 集中交付修复与更新体验改造：模型上下文窗口未知不再乱填、新增接口级联网搜索能力勾选、修复 Windows 双击启动偶发 30 秒超时（可观测+超时放宽）、应用内静默更新链路、壳层右键菜单。Windows 原生窗口、覆盖安装、静默更新及启动修复由用户实测验收。

0.1.0 及更早版本请先结束任务、备份本机数据，退出旧版后使用完整安装包覆盖安装（本版含桌面宿主改动，业务资源包不适用）。升级后应用内更新将优先走静默链路：确认后在空闲时自动安装并重启，失败回落手动安装包路径。升级后再次检查应提示已是最新版本；当前不支持完整安装包断点续传或重启后恢复下载。

完整构建、508 项产品测试与 58 项桌面测试通过，失败 0、跳过 0。macOS 尚未公证，Windows 未配置代码签名；验证范围及限制见发行说明。

安装后无需另装 Node 或 pnpm。账号、模型配置、历史和凭据保存在本机。发行物包含可提取的编译后 JavaScript，公开下载不表示整个工程已开源，也不新增整个工程的开源许可；第三方许可随安装包保留。
