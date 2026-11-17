# 棱镜 Prism 发行下载

本仓库仅托管 Prism 安装包、签名业务资源包、更新清单与发行说明；产品源码仓及历史保持私有。

当前测试版：[0.0.7-beta](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.0.7-beta)

- [macOS Apple Silicon 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.0.7-beta/Prism-0.0.7-beta-mac-arm64.dmg)
- [Windows x64 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.0.7-beta/Prism-Setup-0.0.7-beta-win-x64.exe)
- [更新内容与已知限制](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.0.7-beta) · [历史版本](https://github.com/Sssovereign/prism-agent-releases/releases)

本次更新了桌面宿主。0.0.6-beta及更早版本请先结束任务、备份本机数据，退出旧版后使用完整安装包覆盖安装。仅更新业务资源包无法取得新的下载能力及依赖／数据库更新；当前不支持完整安装包自动替换。兼容宿主的业务更新可在设置 → 关于棱镜 → 应用内更新完成。

本版提供蓝色新版本提示与应用内完整安装包本地下载，修复登录状态竞态、并发限流、归档删除及MCP结果匹配问题，简化重复哈希并升级存在告警的依赖。完整构建、499项产品测试与43项桌面测试通过，生产及完整依赖扫描均为零告警。

Mac安装包与受控回归已验证；Windows本候选的原生界面、安装覆盖与卸载保留尚未完成实机验收。Mac尚未公证，Windows未配置代码签名。完整验证边界见发行说明。

安装后无需另装Node或pnpm。账号、模型配置、历史和凭据保存在本机。发行物包含可提取的编译后JavaScript，公开下载不表示整个工程已开源，也不新增整个工程的开源许可；第三方许可随安装包保留。
