# 搭手 Dashou

## 让 ChatGPT 进入你授权的本地工作区，把事情做完

搭手是一款桌面工具。你选择工作文件夹后，可以在 ChatGPT 里让它读取文件、修改内容、运行命令和执行测试，不再反复复制粘贴。

![搭手 Dashou 创始内测](images/dashou-founder-pilot.png)

## 五步开始

1. **收到安装包**：首批 Mac 安装包由测试联系人通过微信发送；Windows 用户按联系人提供的安装包安装。只使用你确认来源的文件。
2. **安装搭手**：[Mac 图文安装](docs/mac-install.md) · [Windows 安装](docs/windows-install.md)。
3. **打开搭手**：点击 **开始使用搭手**，等待准备完成，再选择一个或多个工作文件夹。
4. **连接 ChatGPT**：点击 **去 ChatGPT 连接**，按页面提示创建搭手连接，需要密码时回到客户端点击 **复制授权密码**。详细步骤见 [连接 ChatGPT](docs/chatgpt-connect.md)。
5. **完成第一个任务**：在 ChatGPT 中选中搭手，先发送一个只读任务：

```text
请列出我已经选择的项目，并告诉我每个项目是做什么的。先不要修改文件。
```

连接完成后，你可以继续在 ChatGPT 网页版、电脑端或手机端对话，搭手会在这台电脑上处理你授权的工作文件夹。

## 第一次使用最重要的四件事

- **只选择愿意授权的文件夹**，不要直接选择整个个人目录或含有密码、证件的目录。
- **运行命令前看清任务内容**。文件读取和修改限制在你选择的文件夹中；项目命令会使用当前电脑账户的权限，搭手不是完整的系统沙箱。
- **连接地址和授权密码只在自己的 ChatGPT 连接页面使用**，不要发到群聊、Issue 或公开网页。
- **关闭窗口不会退出搭手**。真正停止时，请从 Mac 菜单栏或 Windows 系统托盘选择 **退出搭手**。

## 遇到问题，先做这一件事

打开搭手中的 **搭手排查卡**，点击 **复制排查信息**，把下面三项发给测试联系人：

1. 当前页面截图；
2. 复制的排查信息；
3. 你卡在哪一步。

排查信息不包含授权密码、连接凭据、文件夹路径、文件内容或 ChatGPT 对话。常见问题见 [故障排查](docs/troubleshooting.md)。

## 使用手册

- [Mac 安装与首次打开](docs/mac-install.md)
- [Windows 安装与升级](docs/windows-install.md)
- [连接 ChatGPT](docs/chatgpt-connect.md)
- [故障排查](docs/troubleshooting.md)
- [给自动化助手读取的安装清单](docs/install-manifest.json)

当前仍是小范围体验。版本更新、已知问题和安装包记录以 [GitHub Releases](https://github.com/winston003/dashou-releases/releases/) 为准。
