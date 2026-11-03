# 砚藏

![砚藏横幅](assets/yanzang-release-banner.png)

把故事与角色，好好收藏。

砚藏是一款以 Android 为主要交付端的 SillyTavern 个人资源管理器，也提供 PC 版本。你可以分目录收纳角色卡、画师串、世界书、预设、快速回复、聊天记录、美化主题与壁纸，并通过本地 SillyTavern 或 TauriTavern 联动整理资源。

## 下载

- [下载砚藏 Android 最新版本](https://github.com/yanxu-orange/ST-Orange-Yancang/releases/latest)
- [下载砚藏 PC 版本](https://github.com/yanxu-orange/ST-Orange-Yancang-PC/releases/latest)

各端功能与安装说明请以对应下载页为准。

## 主要能力

### 角色卡库

- 历史版本切换、历史头像保存。
- 开场白备注与章节式阅读。
- 自定义 Tag，支持导入酒馆 Tag。
- 本地添加图片、文件与附件。
- 编辑、导入内嵌世界书与角色正则，绑定快速回复和聊天记录。
- 通过文件、文件夹、URL 或酒馆导入角色卡。仅文件夹导入支持将角色卡、世界书与快速回复自动分类到各自资源库。

### 酒馆联动

- 从本地 SillyTavern 导入角色卡、世界书、聊天补全预设与聊天记录。
- 向本地 SillyTavern 发送角色卡、世界书；同名世界书可覆盖或改名新增。
- 支持 TauriTavern 角色卡导入与发送。
- 支持 config 中配置的访问验证；这不等同于酒馆页面内的用户账号登录。

### 画师串库

- 文件、URL 导入，导入后自动解析画师串。
- 自定义标签，整理图片与提示词。

### 聊天记录库

- 小说式阅读与目录跳转，支持部分状态栏正则美化。
- 编辑聊天内容，导出原始记录、编辑副本或阅读文本。
- 通过结构标签排除与正则替换实现纯净阅读，保留原始文件。

### 美化库

- 收纳本地酒馆美化主题与壁纸，预览主题效果。
- 添加效果图与封面，查看和编辑主题 JSON。

### 其他资源库

- 世界书编辑与条目查找替换。
- 预设编辑与历史版本保存。
- 快速回复（QR）编辑。

## 独立小工具

**砚藏·观色**：选择本地主题 JSON，临时预览聊天外观，支持自选背景、头像、预览姓名与全屏查看。

[下载砚藏观色.html](https://github.com/yanxu-orange/ST-Orange-Yancang/raw/refs/heads/main/tools/%E7%A0%9A%E8%97%8F%E8%A7%82%E8%89%B2.html) · 下载后用浏览器打开，主题与选择仅用于本次预览。

## TauriTavern 联动

在官方TT扩展Git安装入口安装[砚藏联动](https://github.com/yanxu-orange/ST-Orange-Yancang-TT-Bridge)，具体步骤见砚藏设置内“使用说明”。已有ZIP桥时须避免两份同名桥同时启用，不删除角色资料。

连接每次最多十分钟，不自动重连或重放。首次初始化红警和手机后台暂失仍可能发生；部分未编辑回件仍可能判为另一个版本，保留预览选择。遇到持续问题，可从双端导出最近安全诊断，手动反馈；诊断不自动上传。

## 更新记录

[查看版本更新记录](https://github.com/yanxu-orange/ST-Orange-Yancang/releases)

## 使用边界

本项目仅供个人非商业使用，请勿二次分发或用于商业用途。

请勿使用砚藏保存、转换或传播付费购得、倒卖而来，或来自商业化平台的资源，包括将此类内容转换为 SillyTavern 格式后再行保存。

请尊重每一份创作及其原有的使用边界。愿你珍惜所爱，也祝你天天开心。

完整说明见 [使用边界](USAGE_BOUNDARIES.md)。

## 安装与更新

1. 从 Releases 下载 APK。
2. 在 Android 系统中允许当前文件来源安装应用。
3. 安装更新前，建议先在砚藏的“设置 → 数据管理”中导出完整备份。
4. 只有包名与签名证书一致的正式版本才能直接覆盖安装并保留应用数据；请使用本仓库 Releases 提供的 APK。

## 隐私与许可

- [隐私说明](PRIVACY.md)
- [砚藏个人非商业使用许可协议](LICENSE)
- [使用边界](USAGE_BOUNDARIES.md)
- [字体与第三方许可索引](THIRD_PARTY_NOTICES.md)

创作署名：砚梨

许可方与维护：绫（`yanxu-orange`）
