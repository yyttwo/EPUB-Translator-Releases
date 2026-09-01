# 安装 EPUB Translator

## 使用 DMG 安装（推荐）

1. 从 [GitHub Releases](../../releases/tag/v1.0.0) 下载 `EPUB-Translator-v1.0.0.dmg`。
2. 双击打开 DMG。
3. 将“EPUB翻译.app”拖入 Finder 左侧的“应用程序”文件夹。
4. 从“应用程序”中打开“EPUB翻译”。

## 第一次启动被 macOS 阻止

v1.0.0 尚未经过 Apple Developer ID 签名或 Apple 公证，因此 macOS 可能阻止第一次启动。

1. 尝试打开“EPUB翻译”。
2. 打开“系统设置”。
3. 进入“隐私与安全性”。
4. 向下找到关于“EPUB翻译”被阻止的提示。
5. 点击“仍要打开”，再按系统提示确认。

不需要关闭 Gatekeeper，不需要使用 `sudo`，也不建议运行来源不明的终端命令。

## 使用 ZIP 安装

如果更习惯 ZIP，可下载 `EPUB-Translator-v1.0.0.zip`，解压后将“EPUB翻译.app”拖入“应用程序”文件夹。DMG 仍是推荐方式。

## 第一次使用

1. 打开 App 左侧的“API 管理”。
2. 选择 Qwen 或 DeepSeek。
3. 输入从对应服务商获得的 API Key。
4. 点击“使用此 API”，然后点击“验证”。
5. 返回“翻译”，选择 DRM-free 英文 EPUB。
6. 选择翻译模式并开始翻译。

API Key 只保留在本次 App 运行的内存中。关闭 App 后，下次使用需要重新输入。

v1.0.1 计划加入 macOS Keychain 安全持久保存；v1.0.0 当前没有此功能。
