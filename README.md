# PCL-SelfUpdater

基于 Plain Craft Launcher（PCL）开源代码的定制版 Minecraft 启动器的**自动更新发布仓库**。

## 文件说明

- `version.json`：更新清单（版本号、更新日志、下载地址、SHA-256 校验值）
- `PCLClean_<版本>.zip`：更新包（自动更新使用，仅包含需要替换的程序文件）

## 更新地址

- 清单（jsDelivr）：https://cdn.jsdelivr.net/gh/lin6035-star/PCL-SelfUpdater@main/version.json
- 清单（GitHub raw 备用）：https://raw.githubusercontent.com/lin6035-star/PCL-SelfUpdater/main/version.json

## 发布新版本

在本地运行 `publish_update.ps1` 生成 `version.json` 和更新包，上传覆盖本仓库对应文件即可。

> 本仓库仅用于分发更新文件，不包含启动器源代码。