# OpenScreen 区域录制版

基于上游 OpenScreen 1.12.2，增加 macOS / Windows 拖动矩形框选录制范围。新录制默认使用原始比例，内边距为 0。

完整源码位于 `.sources/openscreen-region.tar.gz`，可通过 `tar -xzf .sources/openscreen-region.tar.gz` 解压后开发。
源码快照提交：`3b3b15866373338a209cc429e93b76e2600a38e8`。
源码 SHA-256：`8cce64af60fdeb9a2c41a5f7dc4eeaac06f64eeffd0ce73377c3bfc17e9771da`。

在 Actions 中手动运行 **Region recording Windows installer**，选择 `codex/region-installers` 分支。
构建会校验并解压源码，重新编译 Windows 录屏组件、字幕组件和编辑器，产出 x64 EXE 安装包。
安装包使用独立应用标识 `local.openscreen.region`，不自动发布到 Releases。

这是内部测试版，尚未完成真实 Windows 桌面录制测试。许可证及第三方声明包含于源码归档和安装包。
