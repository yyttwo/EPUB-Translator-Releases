# 更新记录

## v1.0.1 — 2026-09-05

- 更新翻译、API 管理、关于与帮助三个页面的视觉设计
- API 管理支持输入、验证、重新验证、更换、删除和取消验证
- API Key 仅在当前 App 运行期间保存在内存中；退出后清除，下次启动需重新输入
- 增强错误提示、脱敏诊断复制和由用户主动打开的 GitHub Issues 反馈入口
- 支持保存翻译进度，并在重新输入、验证 API Key 后继续未完成任务
- 改进长文本及被截断响应的拆分处理，减少后段漏翻或异常停止
- 纯网址、邮箱、文件名和编号等技术单元会原样保留，不再误判为漏翻
- 保持 EPUB 封面、书内图片、内嵌 SVG、章节、链接和基本排版结构
- 免费、无广告、无订阅；继续支持 Qwen、DeepSeek 与四种翻译模式

### 已知限制

- 仅支持 DRM-free EPUB，不支持 PDF、DOCX、MOBI、AZW 或 DRM 移除
- 仅提供 Apple 芯片构建
- 当前安装包未做 Apple Developer ID 签名或 Apple 公证
- 复杂 EPUB 的视觉排版可能与原始文件存在细微差异
- 翻译质量、速度、可用性和费用取决于用户选择的第三方 AI 服务

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

- 退出 App 后不会保留 API Key
- 仅支持 DRM-free EPUB，不支持 PDF、DOCX、MOBI、AZW 或 DRM 移除
- 当前安装包未做 Apple Developer ID 签名或 Apple 公证
- 复杂 EPUB 的视觉排版可能与原始文件存在细微差异
- 翻译质量、速度与费用取决于用户选择的第三方 AI 服务
