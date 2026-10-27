# SpringSense Homework 安装包

**SpringSense Homework** —— 用图形界面完成课程作业的全流程，不需要命令行：添加自己 fork 的作业库 → 作业看板（截止时间、提交状态、截止前提醒）→ 在应用里编辑作业（Markdown、公式、图片），在作业文件夹里开终端 → 勾选文件一键提交并推送，拉取课程更新时的冲突可视化解决。

- 这个仓库只放各版本的安装包（见 [Releases](https://github.com/Kevinnb66699/SpringSense-Homework-Releases/releases)），没有源代码。
- 每个版本改了什么：[CHANGELOG.md](CHANGELOG.md)

## 下载

到 [最新版本](https://github.com/Kevinnb66699/SpringSense-Homework-Releases/releases/latest) 下载：

| 平台 | 文件 |
| --- | --- |
| macOS（Apple 芯片 M1 及以后，macOS 13 及以上） | `SpringSense-Homework-<版本>-arm64.dmg` |

暂时没有 Windows 版和 Intel 芯片 Mac 的版本。

打开 dmg，把 SpringSense Homework 拖进「应用程序」。

## 第一次打开

应用没有 Apple 开发者证书签名，macOS 第一次打开时会提示「无法验证开发者」：

- **macOS 14 及更早**：在「应用程序」里右键（或按住 Control 点按）应用 →「打开」，在弹窗里再点「打开」。
- **macOS 15 及以后**：先双击一次（会被拦下），然后到「系统设置 → 隐私与安全性」，在页面下方找到这个应用，点「仍要打开」。

之后就可以正常双击打开了。

## 更新

装好以后不用每次重装：应用打开后会自动检查小更新（之后每 6 小时一次），在后台下载好后顶栏出现「新版本 x · 重启以更新」；也可以在「设置 → 关于与更新」里手动检查。需要换新安装包时应用里会提示。

已经装了旧版本的话，直接在应用里更新就行，不用重新下载安装包。重新安装（覆盖旧的应用）后，之前填的 GitHub Token、AI 的 Key 可能读不出来，到设置里重新填一次就好（应用会提示）；课程和作业文件不受影响。
