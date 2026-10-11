<div align="center">
  <img src="./icon.png" width="100" height="100" alt="DeepSeek Whale Widget">
  <h1>DeepSeek Whale Widget</h1>
</div>

<p align="center">
  <a href="https://raw.githubusercontent.com/teressalodas/Deepseek-Whale-Widget/main/deepseek-whale-widget.user.js">
    <img src="https://img.shields.io/badge/GitHub-%E5%AE%89%E8%A3%85%E8%84%9A%E6%9C%AC-red?style=for-the-badge&logo=github" alt="安装脚本" />
  </a>
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=for-the-badge" alt="License: Apache License 2.0" />
  </a>
</p>

DeepSeek Whale Widget 是一款免费开源的用户脚本，在 DeepSeek 网页右下角放一只可拖动的小鲸鱼娘挂件，并附带当前对话的一键导出。挂件支持 Q 弹动画、音效、四边吸附、随机台词气泡，导出支持 Markdown 和 JSON，并保留思考过程与引用来源。

## 安装

先安装 Violentmonkey 或 Tampermonkey（Chrome / Edge / Firefox），然后点击下方链接，并在弹窗中确认安装：

**[安装 DeepSeek Whale Widget](https://raw.githubusercontent.com/teressalodas/Deepseek-Whale-Widget/main/deepseek-whale-widget.user.js)**

## 功能

- **可拖动的挂件**：拖动小鲸鱼到任意位置，松手后自动吸附到最近的边缘。
- **Q 弹动画与音效**：按下时挤压变形，松开时回弹；提供「小黄鸭」和「叮咚」两套音效。
- **随机台词气泡**：点击小鲸鱼弹出气泡，随机显示互动台词、表情动图，并会根据当前时段提示高峰或空闲。
- **一键导出对话**：导出当前打开的对话为 Markdown 或 JSON，Markdown 保留思考过程和引用来源，引用会统一编号并附在文末。
- **双击导出**：开启后双击小鲸鱼即可直接导出 Markdown，跳过菜单。
- **外观与行为设置**：可调挂件大小、音量、是否显示气泡、是否避让滚动条及避让宽度。

## 隐私与安全

- 挂件设置和位置仅保存在浏览器本地存储中。
- 导出时脚本只在 DeepSeek 站内发起请求，读取你自己的对话数据，不会上传到任何第三方。
- 导出的文件只保存在本地下载目录。

## 关于

- 挂件通过页面结构定位与注入，DeepSeek 改版可能导致挂件位置异常或导出失效，请保持脚本更新。
- 如果发现问题，请提交 [GitHub Issue](https://github.com/teressalodas/Deepseek-Whale-Widget/issues)，并注明浏览器和问题现象。
- 欢迎提交 Pull Request。如果觉得有趣，欢迎给仓库点 Star。
- 请遵守 DeepSeek 的服务条款，导出内容仅供个人备份和学习使用。

## 许可证

本项目基于 [Apache License 2.0 ](./LICENSE) 开源。
