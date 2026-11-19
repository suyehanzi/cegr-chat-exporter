# CEGR 聊天导出

将 ChatGPT 和 Claude 对话保存为 Word、PDF、LaTeX 或 Markdown，也可以单独打包可读取的原附件与代码。

**[下载 0.2.9 安装包](https://github.com/suyehanzi/cegr-chat-exporter/releases/download/v0.2.9/cegr-chat-exporter-v0.2.9.zip)** · [查看发行说明](https://github.com/suyehanzi/cegr-chat-exporter/releases/tag/v0.2.9)

## 安装和使用

1. 下载 `cegr-chat-exporter-v0.2.9.zip` 并解压。使用 Chrome 112 或更新版本，打开 `chrome://extensions`。
2. 打开右上角的「开发者模式」，点击「加载已解压的扩展程序」，选择直接包含 `manifest.json` 的文件夹。请保留该文件夹。
3. 打开或刷新 ChatGPT / Claude 对话页，点击右上角的「导出」。导出单段聊天时选「导出当前聊天」，合并时勾选要导出的聊天。浏览器工具栏里的 CEGR 插件也有合并入口。导出 PDF 时，在打印窗口选择「另存为 PDF」。

ixBrowser 如果已经分配了 CEGR 聊天导出插件，正常关闭并重开对应窗口即可加载更新。

会话内容在浏览器内处理。导出能读取的图片和附件，个别资源读取失败时会提示，其他内容仍可保存。若对话很长，请检查预览是否包含需要的消息。

如果面板提示只能导出当前页面，可以先重新检查客户归属。核验通过后，列表只显示当前客户的聊天。未安装隔离插件时，列表来自侧栏已加载的聊天。
