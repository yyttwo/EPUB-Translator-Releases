# EPUB Translator

一个免费的 macOS EPUB 英译中工具。

使用你自己的 Qwen 或 DeepSeek API，将英文 EPUB 翻译为简体中文，同时尽量保持原有章节、图片、链接和排版结构。

- 免费、无广告、无订阅
- 无需注册 EPUB Translator 账号
- 使用你自己的 Qwen 或 DeepSeek API
- API Key 仅保留在本次 App 运行的内存中，关闭 App 后自动清除
- 没有 EPUB Translator 项目服务器

![EPUB Translator 首页](screenshots/01-home.png)

## 功能

- DRM-free EPUB → 简体中文 EPUB
- 支持 Qwen 与 DeepSeek
- 四种全书翻译模式
- 同一次 App 运行中支持中断后继续翻译
- 保持章节、图片、链接及基本格式
- 显示翻译单元、预计时间、进度和百分比
- 翻译完成后保存 EPUB，并可在 Finder 中显示

## 四种翻译模式

- **直译版**：最大程度忠实原文结构和表达。
- **通畅版（推荐）**：准确保留原意，同时使用自然流畅的中文。
- **意译（更简洁有力）**：在不改变核心意思的情况下减少英语式冗余。
- **书面评论体**：更正式、更成熟的中文书面表达。

## 系统要求

- macOS 13 Ventura 或更高版本
- Apple 芯片 Mac（arm64）
- DRM-free 英文 EPUB
- 用户自己的 Qwen 或 DeepSeek API Key
- 翻译期间需要网络连接

## 下载和安装

正式发布后，请优先从 GitHub Releases 下载 `EPUB-Translator-v1.0.0.dmg`。完整步骤见 [安装说明](INSTALL.md)。

当前首发包使用本地签名，尚未经过 Apple Developer ID 公证。如果 macOS 阻止首次打开，请前往“系统设置 → 隐私与安全性”，找到 EPUB翻译并选择“仍要打开”。不需要关闭 Gatekeeper，也不需要运行 `sudo` 命令。

## API 申请

- [Qwen / 阿里云百炼 API Key 官方说明](https://help.aliyun.com/zh/model-studio/get-api-key/)
- [DeepSeek API 官方说明](https://api-docs.deepseek.com/zh-cn/)

服务商页面和收费政策可能变化，请以对应官方说明为准。

## 费用

EPUB Translator 本身免费，不销售 Token，也不收取 API 费用。

Qwen 或 DeepSeek 可能根据你的账户用量和服务商当前收费政策产生费用。这些费用由第三方服务商收取，与 EPUB Translator 无关。

## 隐私

EPUB 文件结构在本机处理。翻译所需的文本片段及少量相邻上下文会从你的 Mac 直接发送给你选择的 Qwen 或 DeepSeek；不会经过 EPUB Translator 项目服务器。详见 [隐私说明](PRIVACY.md)。

## 当前限制

- 仅支持 DRM-free EPUB，不支持 PDF。
- 不移除 Kindle、Apple Books 或其他 DRM。
- 复杂 EPUB 的排版可能与原书存在差异。
- AI 翻译质量、速度、可用性和费用取决于第三方服务商。
- 当前“继续翻译”只在同一次 App 运行中有效；退出 App 后不会保留 API Key 或翻译进度。
- 首个公开候选版本仅提供 Apple 芯片构建。

## 更多信息

- [隐私说明](PRIVACY.md)
- [安全报告方式](SECURITY.md)
- [获得支持](SUPPORT.md)
- [更新记录](CHANGELOG.md)
- [v1.0.0 发布说明](docs/RELEASE_NOTES_v1.0.0.md)

