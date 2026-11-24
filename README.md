# LocalChat for Windows

LocalChat 是 Windows x64 上的局域网聊天和文件传输工具。两台电脑可以直接互发文字、图片、文件和文件夹，也可以邀请多台设备加入群聊。聊天记录保存在自己的电脑上。

## 下载

打开最新发布页，下载 `LocalChat-版本号-windows-x64-setup.exe` 并双击运行。安装后可从开始菜单打开 LocalChat。[最新 Windows 安装包和发行说明](https://github.com/gshu55/local_chat_windows/releases/latest)

## 开始使用

在同一局域网的两台电脑上打开 LocalChat。点击左下角个人资料栏，进入「设置 → 设备」，找到对方并核对设备指纹。双方确认信任后即可聊天。拖入文件或文件夹可发送附件，在编辑框中粘贴图片可图文混排。「设置 → 群聊」可创建群组。

文件、文件夹和富文本原图优先通过 QUIC 传输。对方仅支持 HTTPS 或 UDP 不通时，应用会自动使用 HTTPS。下载中途切换可从上一个完整分片继续，群聊按成员分别协商。

## 更新

在「设置 → 软件更新」点击「检查更新」。发现新版后可打开安装包下载链接。升级前从托盘菜单退出 LocalChat，再运行新版安装包。原有身份、设置和聊天记录会继续使用。[历次版本和发行说明](https://github.com/gshu55/local_chat_windows/releases)

每个版本都附带 `latest.json`，其中列出本版安装包的下载地址、大小和 SHA-256。客户端从固定链接获取最新清单。[查看更新清单](https://github.com/gshu55/local_chat_windows/releases/latest/download/latest.json)
