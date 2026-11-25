# 鲸鱼湾 · Jingyuwan

鲸鱼湾——一款可切换人物的 AI 伴成长应用。  
Jingyuwan — an AI companion that grows with you, character switchable.

另见：[Gitee · Jingyuwan](https://gitee.com/AlbatrossCoder/Jingyuwan)

## 介绍

鲸鱼湾是面向 Android 的**本机优先** AI 陪伴：你先选好一位人物，再慢慢相处。她不是开局勾选性格菜单「捏」出来的，而是在聊天、记忆与日志里一点点长出来。

适合希望「有固定陪伴对象、记得住你说的事、人设可换可自建」的人。模型接口你自己接（自备 API Key），对话与成长材料主要留在手机里。

## 功能与特色

- **可切换人物**：内置样例、导入角色卡，或自己编辑新建；选定后进入全屏聊天。
- **伴成长**：相处中沉淀事实与倾向，她会写下**日志**；重要事也可以马上记一笔。
- **本机记忆**：回忆检索在本机完成；可选记忆增强包，让相关往事更容易被想起。
- **自备模型**：支持常见 OpenAI 兼容接入（默认 DeepSeek 等）；密钥进系统钥匙串，不经过鲸鱼湾服务器。
- **人物库**：设置里管理本机人物；导出 / 分享带鲸鱼湾水印的人物卡。
- **虚拟形象**：聊天页可显示可互动的形象，支持导入 Live2D / 帧动画包。
- **数据由你掌控**：可备份、导入；换人需先清空本地数据（不可恢复），接入密钥会保留。

## 下载

当前版本：**0.2.10**（`Jingyuwan_0.2.10_release.apk`）

建议使用蓝奏云下载，速度更快。

| 渠道 | 说明 |
| --- | --- |
| **GitHub Release** | [Releases](https://github.com/AlbatrossCoder/Jingyuwan/releases/tag/v0.2.10) |
| **Gitee 发行版** | [发行版](https://gitee.com/AlbatrossCoder/Jingyuwan/releases/tag/v0.2.10) |
| **蓝奏云**（国内） | [下载](https://wwbtb.lanzout.com/iakK44h9dmcd) · 密码：`3qu4` |

安装前可核对 SHA256：

`aa702eeed8f09be424c20b2d6fb15415907fbde02d70ea5fad53a1c3e44a7fde`

清单见根目录 [`latest.json`](./latest.json)。

> **说明**：安装包与形象资源包只作为 **Release 附件** 分发，**不要** commit 进本仓库 Git 树。GitHub / Gitee 挂同一 APK；蓝奏云仅作国内人手备用，**不进**应用内更新。

## 虚拟形象资源包

在 App「管理 → 虚拟形象」导入 ZIP。资源包本次未更新，下列包仍使用 **v0.2.9** Release 及原有蓝奏云链接。

**Live2D 鲸鱼娘**（约 3 MiB）· `ds-whale-girl-live2d-1.3.0.zip`  
GitHub：[下载](https://github.com/AlbatrossCoder/Jingyuwan/releases/download/v0.2.9/ds-whale-girl-live2d-1.3.0.zip) · Gitee：[下载](https://gitee.com/AlbatrossCoder/Jingyuwan/releases/download/v0.2.9/ds-whale-girl-live2d-1.3.0.zip) · 蓝奏云：[下载](https://wwbtb.lanzout.com/iTiF34gp2lgf)（密码 `ay5q`）

**帧动画精简**（23 段，约 99 MiB）· `dsh-whale-girl-frames-compact-0.1.1.zip`  
GitHub：[下载](https://github.com/AlbatrossCoder/Jingyuwan/releases/download/v0.2.9/dsh-whale-girl-frames-compact-0.1.1.zip) · Gitee：[下载](https://gitee.com/AlbatrossCoder/Jingyuwan/releases/download/v0.2.9/dsh-whale-girl-frames-compact-0.1.1.zip) · 蓝奏云：[下载](https://wwbtb.lanzout.com/iKObs4gp3b7c)（密码 `3rbh`）

**帧动画全量**（114 段，约 497 MiB）· `dsh-whale-girl-frames-full-0.1.0.zip`  
GitHub：[下载](https://github.com/AlbatrossCoder/Jingyuwan/releases/download/v0.2.9/dsh-whale-girl-frames-full-0.1.0.zip) · Gitee 单文件上限 100 MiB，请用 GitHub · 蓝奏云：暂无

素材授权随包内说明；非 DeepSeek 官方形象。

## 安装（Android）

1. 允许本机安装「未知来源」应用（设置路径因品牌而异，一般在安全 / 应用管理里）。
2. 打开下载的 APK 安装。包名：`app.dswhale`。
3. 若曾安装过旧包，可用同一签名覆盖安装；换签名则需先卸载（本地数据会清空）。

## 使用前准备

1. 在设置或开局「接入」里填上你的 API Key，并可检查连接。
2. 选一位人物（或导入 / 新建），开始聊天。
3. 设置入口在应用内管理页；长按气泡可引用或查看思考（若有）。
4. 需要虚拟形象时，导入上方资源包并在管理页启用。

## 隐私要点

- 对话与记忆优先存在本机。
- 网络请求指向你配置的模型服务商；本发布仓不托管你的密钥或聊天内容。

## 反馈

- 邮箱：`654294440@qq.com`
- QQ 群：`1109648974`

## 更新清单

仓库根目录 [`latest.json`](./latest.json) 供应用内检查更新；优先 Gitee，失败再回落 GitHub。双仓内容保持一致。
