# LectureFlow Windows 更新

这是 **Windows 桌面版**的安装包和版本历史仓库，与手机、平板网页版独立。这里不保存课堂记录、API Key 或私人源码。

## 下载

[最新 Windows 安装包及更新说明](https://github.com/MLLeosf/lectureflow-desktop-releases/releases/latest)

首次安装一次后，可在 App 的“设置 → 桌面版本更新”中检查、下载并重启更新。录音、翻译或整理笔记时不会安装更新。已有本机记录和设置保留。

## 版本规则

修复：1.1.1 → 1.1.2；功能：1.1.x → 1.2.0；不兼容的大改动：2.0.0。每次创建新的 vX.Y.Z 发布并保留旧版本，安装包统一为 LectureFlow-Setup-X.Y.Z-x64.exe。

每个版本附带 Ed25519 签名的 update.json 和 SHA-512 校验。应用只信任内置公钥验证通过的版本，不依赖仓库中的可执行脚本。
