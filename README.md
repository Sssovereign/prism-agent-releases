# 棱镜 Prism 发行下载

本仓库仅托管 Prism 安装包、签名业务资源包、更新清单与发行说明；产品源码仓及历史保持私有。

当前测试版：[0.1.0-beta](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.1.0-beta)

- [macOS Apple Silicon 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.1.0-beta/Prism-0.1.0-beta-mac-arm64.dmg)
- [Windows x64 安装包](https://github.com/Sssovereign/prism-agent-releases/releases/download/v0.1.0-beta/Prism-Setup-0.1.0-beta-win-x64.exe)
- [更新内容、Windows 验证步骤与已知限制](https://github.com/Sssovereign/prism-agent-releases/releases/tag/v0.1.0-beta) · [历史版本](https://github.com/Sssovereign/prism-agent-releases/releases)

0.1.0-beta 正式进入 Windows 测试阶段，修复新建项目选择文件夹时报“请求参数不合法”的问题，并加固目录选择通道的启动重试。Windows 原生窗口、覆盖安装及更新交互由用户实测验收。

0.0.x 版本请先结束任务、备份本机数据，退出旧版后使用完整安装包覆盖安装。在设置 → 关于棱镜 → 应用内更新中检查并下载完整安装包，下载完成后打开安装器；应用不会自动覆盖安装。升级后再次检查应提示已是最新版本。兼容宿主的后续业务更新可在应用内完成；当前不支持完整安装包断点续传或重启后恢复下载。

完整构建、501 项产品测试与 43 项桌面测试通过，失败 0、跳过 0。macOS 尚未公证，Windows 未配置代码签名；验证范围及限制见发行说明。

安装后无需另装 Node 或 pnpm。账号、模型配置、历史和凭据保存在本机。发行物包含可提取的编译后 JavaScript，公开下载不表示整个工程已开源，也不新增整个工程的开源许可；第三方许可随安装包保留。
