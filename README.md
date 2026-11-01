# 快速收藏夹 · SceneFavorites

保存常用的文件和文件夹路径、网址、文字、AI 提示词（Prompt）和本地 Skill 入口，按当前程序显示对应收藏。支持搜索、分组、拖拽排序和图片悬停预览。

## 下载与启动

从 [Releases](https://github.com/RainskyCG/SceneFavorites/releases) 下载便携版 ZIP，解压到可写文件夹，运行 `SceneFavorites.exe`。不需要安装 Quicker。

- 默认快捷键：**Ctrl + Shift + Q**，可在设置中修改。
- 关闭窗口后保留在托盘；右键托盘可管理收藏或退出。
- Prompt 和 Skill 可添加参考图片；图片仅供预览，不自动发送给 AI。
- Skill 只提供本地调用入口，不自动安装、下载或更新技能。

## 备份和迁移

导出配置得到一个 ZIP，包含收藏数据和图片。在新电脑导入即可；导入会替换当前收藏，并先自动备份。

Skill 文件不打包，需自行准备并按需修改路径。旧 JSON 配置仍支持导入，需带上同名附件文件夹。

便携版数据存于程序旁的 `data/`。移动程序时复制整个文件夹；升级前先备份，保留原来的 `data/`。

## 系统要求与说明

Windows 10 / 11，.NET Framework 4.7.2 或更高版本。当前为未签名测试版，首次运行可能出现系统安全提示，请自行确认来源。

此仓库目前用于发布便携版和使用说明，不包含个人数据、完整开发源码或 Quicker 动作安装包。Quicker 动作另行发布。

图标来源：[Icons8](https://icons8.com/)。
