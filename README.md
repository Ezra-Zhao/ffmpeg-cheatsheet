# FFmpeg 命令速查表 · FFmpeg Cheatsheet

> 🌍 [Español](README.es.md) · [Português](README.pt.md)

一份**一页纸**的 FFmpeg 命令速查表：28 条真正常用的命令，每条只讲两件事——**它是干什么的、一条复制即用的命令**。转码、压缩、提音频、转 GIF、剪切拼接、加水印、推流、批量处理，全覆盖。不灌水，不凑数。

## 面向谁

视频创作者、开发者、运维，以及任何被音视频格式折磨过的人。如果你每次用 FFmpeg 都要现搜参数，这张表能让你以后直接复制粘贴。

## 怎么用

1. 直接看 **[CHEATSHEET.md](CHEATSHEET.md)** ——速查表正文，中英双语开发者都无压力。
2. 先装 FFmpeg：
   ```bash
   brew install ffmpeg          # macOS
   sudo apt install ffmpeg     # Debian/Ubuntu
   ```
3. 每条命令都可以直接复制运行，把 `input.mp4` / `output.mp4` 换成你自己的文件名即可。

## 收录了什么

| 分类 | 内容 |
|---|---|
| 📦 安装与检查 | 安装命令、版本与编码器检查 |
| 🔄 基础转码 | 任意格式→MP4、MP4→WebM、MKV→MP4 无损 remux |
| 🗜️ 压缩与画质 | CRF 压缩、preset 权衡、两遍编码定文件大小 |
| 🎵 提取音频 | 转 MP3 / M4A、无损提取原音频 |
| 🖼️ 视频转 GIF | palette 优化两步法，告别锯齿 GIF |
| ✂️ 剪切与拼接 | 快速剪切、精确剪切、concat 无损拼接 |
| 📐 缩放与裁剪 | scale 缩放、按宽等比、crop 裁剪 |
| 🎞️ 抽帧与信息 | 封面抽帧、视频转图片序列、替换音轨 |
| 💧 水印与字幕 | 图片水印 overlay、字幕烧录、文字叠加 |
| 📡 直播推流 | RTMP 推流命令模板 |
| 🔁 批量处理 | for 循环批量转码、批量提音频 |

所有命令均为真实可用的 FFmpeg 语法，逐条核实过参数。

## 为什么是这 28 条

- **覆盖 90% 的日常需求**：转码、压缩、提音频、转 GIF、剪切是开发者和创作者最常搜的 FFmpeg 用法。
- **从易到难**：前面是复制即用的一行命令，后面是 concat、两遍编码、批量循环等进阶用法，适合收藏后慢慢啃。

## 官方文档

- https://ffmpeg.org/documentation.html

## 欢迎 PR

命令写错了、翻译不到位、有更好的常用 recipe——欢迎提 Pull Request。新增条目请保持统一格式（功能 / 命令 / 标签），**提交前请确认命令真实可运行**。

## License

MIT © 2026 Guangyi Zhao，详见 [LICENSE](LICENSE)。
