# 搭手 Desktop

搭手（Dashou）把你选择的本地文件夹，通过一条由服务器批准的安全连接，交给 ChatGPT 使用。

## v0.1.0

- 仅支持 macOS Apple Silicon（`darwin-aarch64`）。
- 首次安装使用 `dashou_0.1.0_aarch64.dmg`。
- Tauri updater 使用 `dashou.app.tar.gz`、对应的 `.sig` 和 `latest.json`。
- 当前版本提供服务器计时的 30 分钟试用；试用从用户点击“启动安全连接”开始。
- 正式开通前不会建立 Cloudflare Tunnel；客户端不会要求用户填写服务器地址或 Cloudflare 凭据。
- 这是受控内测包，当前尚未完成 Apple Developer ID 签名和 notarization；正式对外前请勿把它当作普通用户安装包。

## 安装

1. 下载 DMG 并将“搭手”拖入 Applications。
2. 打开搭手，选择允许访问的文件夹并提交申请。
3. 申请获批后点击“启动安全连接”。
4. 点击“去 ChatGPT 完成最后一步”，按页面提示添加专属连接地址。

## 更新

客户端在“遇到问题”区域可以检查更新。更新清单固定来自本仓库的 GitHub Release，更新包由 Tauri updater 签名验证；不要把 updater 私钥提交到仓库或发给用户。

## 校验

`SHA256SUMS.txt` 记录本 Release 中 DMG、updater archive、签名和清单的 SHA-256。当前仅发布 Apple Silicon 包，不要在 Intel Mac 上安装此版本。