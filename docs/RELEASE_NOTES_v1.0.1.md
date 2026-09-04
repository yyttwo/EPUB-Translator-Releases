# EPUB翻译 v1.0.1

v1.0.1 更新了三个主要页面的视觉设计，并增强了翻译与错误恢复的可靠性。

## 本次更新

- 更新“翻译”“API 管理”“关于与帮助”页面的视觉设计。
- API 管理支持输入、验证、重新验证、更换、删除和取消验证。
- 提供更清楚的错误提示、可由用户主动复制的脱敏诊断，以及 GitHub Issues 反馈入口。
- 支持保存翻译进度；重新启动 App 后，重新输入并验证 API Key 即可继续未完成任务。
- 改进长文本及被截断响应的拆分处理，减少后段漏翻或异常停止。
- 纯网址、邮箱、文件名和编号等技术单元会原样保留。
- 保持 EPUB 封面、书内图片、内嵌 SVG、章节、链接和基本排版结构。

## API Key 与隐私

EPUB翻译不会持久保存您的 API Key。
API Key 仅在当前 App 运行期间使用，退出 App 后即清除。
下次启动时需要重新输入。

App 不读取或写入 macOS 钥匙串。EPUB 文件结构与重新打包在本机处理；翻译所需文本会从您的 Mac 直接发送给您选择的 Qwen 或 DeepSeek，不经过 EPUB Translator 项目服务器。

## 系统要求

- macOS 13 Ventura 或更高版本
- Apple 芯片 Mac（arm64）
- DRM-free 英文 EPUB
- 用户自己的 Qwen 或 DeepSeek API Key
- 翻译期间需要网络连接

## 安装提示

当前安装包未使用 Apple Developer ID 签名，也未经过 Apple 公证。如果 macOS 阻止首次打开，请前往“系统设置 → 隐私与安全性”，找到 EPUB翻译并选择“仍要打开”。不需要关闭 Gatekeeper，也不需要运行 `sudo` 命令。
