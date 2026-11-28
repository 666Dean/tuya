# 图丫

图丫是一款 Windows 照片管理软件，支持亮/暗双主题、相册整理、分级标签、人物人工确认、按拍摄日期归档导入、日期日历浏览、离线位置地图聚类筛选，以及照片、RAW、PSD/PSB 和视频预览。

本仓库仅用于分发 EXE 安装包、配套第三方开源组件源码归档与更新公告，不提供图丫应用源码。安装包不包含维护者的照片、图库数据库、账号或个人配置。

## 下载与更新公告

当前正式版为 **图丫 3.2.0 独立版**。

- [下载 Windows 精简安装包（74.88 MiB）](https://github.com/666Dean/tuya/releases/download/v3.2.0/Tuya-3.2.0-Windows11-x64-AVX2-Setup.exe)
- [3.2.0 更新公告与验收说明](https://github.com/666Dean/tuya/releases/tag/v3.2.0)
- [SHA-256 校验文件](https://github.com/666Dean/tuya/releases/download/v3.2.0/SHA256SUMS.txt)
- [第三方组件对应源码归档（按需下载）](https://github.com/666Dean/tuya/releases/download/v3.2.0/Tuya-3.2.0-ThirdParty-Sources.zip)
- [查看所有版本](https://github.com/666Dean/tuya/releases)

3.2.0 带来亮/暗双主题与圆形扩散切换动效、无裁剪原比例网格、相册/标签/人物墙、独立暗房预览、按拍摄日期归档导入（自动跳过同名同大小重复）、离线地图聚类区域筛选、应用内流式 SHA-256 校验一键升级，以及精简安装包分发（体积由 ~1.03 GiB 缩减至 74.88 MiB）。

系统要求：Windows 11 x64，支持 AVX2 的 Intel 或 AMD 处理器。

正常关闭图丫后运行安装程序。升级保留已有照片位置、个人索引与设置。支持更新检查的版本可在“设置 → 软件更新”查看公告、下载并校验安装程序；没有更新检查功能的旧版本需要先手动安装新版。

本轮通过 7 组 CTest、8 项分发隐私单测、737 个分发文件与 5 个外置第三方源码归档审计（工作站路径残留复扫 0 命中）及隔离安装/重装/卸载 18 项 QA。详细范围见 Release 附件。第三方组件许可证文本保留在安装目录 `licenses` 内，对应上游源码归档随本版本 Release 单独提供。
