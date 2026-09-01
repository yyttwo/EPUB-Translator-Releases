# 更新记录

## v1.0.0 — 2026-09-01

Initial public release.

- DRM-free 英文 EPUB 翻译为简体中文 EPUB
- 支持用户自己的 Qwen 与 DeepSeek API
- 直译、通畅、简洁意译和书面评论体四种模式
- 翻译单元识别、预计时间、进度与百分比
- 同一次运行中的中断继续
- 保持章节、图片、链接和基本格式
- 完成后保存译本并在 Finder 中显示
- API Key 仅在本次运行的内存中使用
- macOS 13+，Apple Silicon arm64

### 已知限制

- 退出 App 后不会保留 API Key；v1.0.1 计划加入 macOS Keychain 安全持久保存
- 仅支持 DRM-free EPUB，不支持 PDF、DOCX、MOBI、AZW 或 DRM 移除
- 当前安装包未做 Apple Developer ID 签名或 Apple 公证
- 复杂 EPUB 的视觉排版可能与原始文件存在细微差异
- 翻译质量、速度与费用取决于用户选择的第三方 AI 服务
