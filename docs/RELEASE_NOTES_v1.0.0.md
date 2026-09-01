# EPUB翻译 v1.0.0

这是 EPUB翻译的首次公开版本。

## 主要功能

- 将 DRM-free 英文 EPUB 翻译为简体中文 EPUB
- 支持用户自己的 Qwen 或 DeepSeek API Key
- 四种全书翻译模式：直译、通畅、简洁意译、书面评论体
- 显示翻译单元、预计时间、进度和百分比
- 同一次运行中可在中断后继续
- 保持章节、图片、链接和基本格式
- 翻译完成后保存 EPUB，并可在 Finder 中显示

## 系统要求

- macOS 13 或更高版本
- Apple 芯片 Mac（arm64）
- DRM-free 英文 EPUB
- Qwen 或 DeepSeek API Key
- 翻译期间需要网络连接

## 安装

优先下载 `EPUB-Translator-v1.0.0.dmg`。打开 DMG 后，将“EPUB翻译.app”拖到“应用程序”文件夹。

此版本使用本地签名，未经过 Apple Developer ID 公证。如首次启动被拦截，请使用“系统设置 → 隐私与安全性 → 仍要打开”的 macOS 官方界面。

完整步骤见 [安装说明](https://github.com/yyttwo/EPUB-Translator-Releases/blob/main/INSTALL.md)。

## 隐私提醒

API Key 仅保留在本次 App 运行的内存中。翻译文本会直接发送至用户选择的 Qwen 或 DeepSeek；第三方服务商自己的隐私与收费政策适用。

## 已知限制

- 仅支持 DRM-free EPUB，不支持 PDF 或 DRM 移除。
- 复杂 EPUB 可能存在排版差异。
- 翻译质量和速度取决于第三方 AI 服务。
- 退出 App 后不会保留 API Key 或翻译进度。
- v1.0.1 计划加入 macOS Keychain API Key 安全持久保存。
- v1.0.0 仅提供 Apple 芯片构建。
- 目前没有 Apple Developer ID 签名或 Apple 公证。
