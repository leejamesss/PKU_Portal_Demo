## PKU门户静态网页

这是一个简单的使用说明，以运行 PKU 门户静态网页为例。

### 运行命令

在 Windows 操作系统中，可以打开命令提示符（Command Prompt）并输入以下命令：

```
cmd /c start index.html
```

在 Linux 操作系统中，可以运行 `run.sh` 文件。

### 样式美化

对样式进行自动整理美化，并增加 CSS 的美观可读性，使用 `clean-css-cli` 工具。使用以下命令进行安装：

```
npm install clean-css-cli -g
```

以下是 `clean-css-cli` 工具的示例代码，用于进行 Level 2 样式优化：

```
cleancss -O2 'all:off;removeDuplicateRules:on' one.css
```

