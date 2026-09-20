# Open Path for Alfred

通过 Alfred 打开文件路径、文件夹路径或 URL。

## 安装方法

到 Release 页面下载 .alfredworkflow 文件，双击安装 (前提是你的macOS安装了Alfred并且有Powerpack)

## 使用方式

1. 呼出 Alfred，输入 `go `，再输入路径或 URL。
2. 按一次 Return。

**细节**:

* 如果路径是文件夹，则会在 Finder 中直接打开；
* 如果路径是文件，则会在 Finder 中显示并被选中，但不会启动关联应用打开文件；
* URL (网址,http://... OR https://...)会使用 macOS 的默认处理程序打开。无效路径会显示错误提示。
* 支持带单引号，和双引号的路径，比如在访达拷贝的带有空格的路径会用单引号引起来，本程序支持打开这种
* 不存在的路径 (文件夹或文件结尾) 会提示 `Path does not exist`

## 源码与发布

`src/info.plist` 是工作流定义源码。本地的 `Open Path.alfredworkflow` 是可导入的安装包，刻意由 Git 忽略，之后可作为 GitHub Release 附件提供下载。
