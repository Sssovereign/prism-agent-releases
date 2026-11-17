# 棱镜 Prism 发行下载

本仓库仅托管 Prism 安装包、签名业务资源包、更新清单与发行说明；产品源码仓及历史保持私有。

当前测试版：[0.0.6-beta](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.0.6-beta)

- [macOS Apple Silicon 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.0.6-beta/Prism-0.0.6-beta-mac-arm64.dmg)
- [Windows x64 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.0.6-beta/Prism-Setup-0.0.6-beta-win-x64.exe)
- [更新内容与已知限制](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.0.6-beta) · [历史版本](https://github.com/Sssovereign/prism-agent-releases/releases)

本次更新了桌面宿主。0.0.5-beta及更早版本请先结束任务、备份本机数据，退出旧版后使用完整安装包覆盖安装。仅更新业务资源包无法取得新标题栏等宿主功能；当前不支持完整安装包自动替换。兼容宿主的业务更新可在设置 → 关于棱镜 → 应用内更新完成。

本版修复独立评审累计资料600KB门槛、旧业务包遮蔽新安装版本及Windows危险命令常见写法漏判，合并系统标题行与应用顶栏，并提供账号改密、原生目录选择及平台快捷键适配。

Mac安装包与受控回归已验证；Windows本候选的原生界面、安装覆盖与卸载保留尚未完成实机验收。Mac尚未公证，Windows未配置代码签名。完整验证边界见发行说明。

安装后无需另装Node或pnpm。账号、模型配置、历史和凭据保存在本机。发行物包含可提取的编译后JavaScript，公开下载不表示整个工程已开源，也不新增整个工程的开源许可；第三方许可随安装包保留。
