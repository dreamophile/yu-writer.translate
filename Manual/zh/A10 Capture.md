---
flag: blue
---
# 资料收集工具

Yu Writer 自动资料收集工具，可以帮助你很方便地收集感兴趣的或者有保存价值的文字图片资料。

当你在浏览网页、阅读电子书、PDF 发现感兴趣的内容时，选中其中的文字、图片、表格等等，再按下资料收集工具的全局快捷键，则选中的内容会被自动保存在 `Inbox` 文档库里。

## 全局快捷键

快捷键是 `Shift+Command+1`，这是一个系统级别的全局快捷键，也就是说你可以在任何时候按下它，比如在浏览网页时，在用 Word 编辑文档时、在阅读电子书时等等。当然如果当前活动窗口的 Yu Writer 本身，按此快捷键是无效的。

除了快捷键，你也可以通过点击屏幕右上角状态栏的 Yu Writer 小图标，然后选择 `Capture Selection` 来实现资料收集操作。

## 工作原理

当按下资料收集快捷键之后，实际上 Yu Writer 是模拟了一次 `Command+C` 键盘操作，把选中的内容复制到了系统剪贴板，然后 Yu Writer 再从剪贴板读取内容并转换为 Markdown 格式文档。
