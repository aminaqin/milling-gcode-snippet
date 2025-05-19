# 欢迎使用VS Code扩展开发

## 目录结构说明

* 本目录包含扩展所需的所有文件
* `package.json` - 声明语言支持并定义语法文件位置的清单文件
* `syntaxes/gcode.tmLanguage.json` - 用于语法标记的TextMate语法文件
* `language-configuration.json` - 语言配置文件，定义注释和括号等语法标记

## 快速开始

* 确保`language-configuration.json`中的语言配置准确
* 按`F5`键加载扩展并打开新窗口
* 创建后缀名匹配您语言的新文件
* 验证语法高亮和语言配置是否生效

## 修改调整

* 修改上述文件后，可通过调试工具栏重新启动扩展
* 也可使用快捷键（Mac: `Cmd+R` / 其他: `Ctrl+R`）重载VS Code窗口应用更改

## 扩展语言功能

* 如需添加智能提示、悬停文档和验证等功能，请参考VS Code扩展API文档：
  https://code.visualstudio.com/api/language-extensions/overview

## 安装扩展

* 本地使用：将扩展复制到`<用户目录>/.vscode/extensions`后重启VS Code
* 发布共享：请参阅发布指南
  https://code.visualstudio.com/api/working-with-extensions/publishing-extension
