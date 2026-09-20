# Open Path for Alfred

通过 Alfred 打开文件路径、文件夹路径或 URL。

## 使用方式

1. 呼出 Alfred，输入 `go `，再输入路径或 URL。
2. 按一次 Return。

文件夹会在 Finder 中直接打开；文件会在 Finder 中显示并被选中，但不会启动关联应用；URL 会使用 macOS 的默认处理程序打开。无效路径会显示错误提示。

## 源码与发布

`src/info.plist` 是工作流定义源码。本地的 `Open Path.alfredworkflow` 是可导入的安装包，刻意由 Git 忽略，之后可作为 GitHub Release 附件提供下载。
