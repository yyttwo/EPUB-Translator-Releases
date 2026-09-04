# 隐私说明

最后更新：2026-09-05

EPUB Translator 的设计目标是让书籍处理尽量留在用户自己的 Mac 上，同时准确说明云端 AI 翻译所必需的数据流向。

## 我们不运营的服务

- 不要求创建 EPUB Translator 用户账号。
- 没有用于上传、保存或处理书籍的 EPUB Translator 项目服务器。
- 不通过 EPUB Translator 收取 API 或 Token 费用。

## API Key

EPUB翻译不会持久保存您的 API Key。
API Key 仅在当前 App 运行期间使用，退出 App 后即清除。
下次启动时需要重新输入。

API Key 由用户在 App 内自行输入，仅保留在当前 App 进程的内存中，用于调用用户选择的第三方 AI 服务。App 不读取或写入 macOS 钥匙串，也不会把 API Key 写入文件、偏好设置、翻译进度或翻译 Helper。

## EPUB 与翻译文本

- EPUB 文件结构、图片、链接和打包工作在用户 Mac 本地完成。
- 完整 EPUB 不会上传到 EPUB Translator 项目服务器，因为我们没有这样的服务器。
- 为完成翻译，正文文本片段以及为保持上下文所需的少量相邻文本，会从用户 Mac 直接发送到用户选择的 Qwen 或 DeepSeek API。
- 翻译结果返回用户 Mac，并在本地组装为新的 EPUB。

## 第三方服务

当用户选择 Qwen 或 DeepSeek 时，对应服务商会接收 API 请求，并可能依据其自身条款、隐私政策、数据保留方式和收费规则处理请求。用户应在使用前阅读并接受所选服务商的最新政策。

- [Qwen / 阿里云百炼官方文档](https://help.aliyun.com/zh/model-studio/get-api-key/)
- [DeepSeek 官方 API 文档](https://api-docs.deepseek.com/zh-cn/)

## 我们不收集的内容

EPUB Translator 产品本身不建立用于收集以下内容的项目后台：

- 用户 API Key
- 完整 EPUB
- 翻译结果
- 用户书库或阅读记录

操作系统、网络提供商以及用户选择的第三方 AI 服务商可能按各自政策处理必要的技术信息；这些行为不由 EPUB Translator 控制。
