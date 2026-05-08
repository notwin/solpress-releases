# SolPress

> macOS 14+ 印刷拼版工具 · 朋友圈授权使用

把多张图按印刷模具的固定槽位拼到一张画布，导出 **300 DPI** PDF / PNG / JPG 给印刷厂。**单机离线**，激活后可使用。

## 下载

**[Latest release](https://github.com/notwin/solpress-releases/releases/latest)**

下载 `SolPress.dmg` 即可。

## 功能

- 7 个内置印刷模板（A5 / 320×320 / 197×92 / 88×88 / 210×88 等多尺寸）
- 拖放 PNG / JPG 填槽，长边自动对齐方向
- 单槽编辑：缩放 / 平移 / 90° 旋转 / 复制到 N 空槽
- 整版偏移 X/Y mm（per-template 持久化）
- 撤销 / 重做
- **300 DPI metadata** + 圆角 2mm 硬遮罩，所见即所印
- 会话恢复（意外退出后自动恢复槽位状态）
- 导出预检（未填槽 / 低 DPI 警告 / 缩略图预览）
- 打印偏移自校准（出十字 PDF → 量实测 → 自动算偏移）
- 文件夹批量导出（每 N 张一版自动出 PDF）

## 安装

1. 下载 `SolPress.dmg` 双击挂载
2. 把 `SolPress.app` 拖到 `Applications` 文件夹
3. **首次打开必须右键 → 打开**（绕过 macOS 安全限制，一次性，之后双击就行）
4. 启动后会弹激活窗口

详细步骤见 DMG 内附《首次打开必读.txt》。

## 申请激活

SolPress 仅授权给指定用户使用，**不公开发售**。需要 license 才能启动。

启动后激活窗口提供两种申请方式：

- **📧 邮件请求 license** — 一键打开邮件，自动预填好你的机器 UUID
- **📋 复制激活请求文本** — 贴到微信 / 飞书等 IM

填上你的姓名 + 选授权类型（永久 / 1 年订阅）发出，等开发者回 `license-XXX.json`。把这个文件拖到激活窗口的虚线框，自动激活。

## 系统要求

- macOS 14 (Sonoma) 或更新
- Intel x86_64 或 Apple Silicon (universal binary)

## 自动更新

启动时每天最多检查一次新版。有新版会在工具栏 toast 提示，从「帮助」菜单 →「检查更新…」也可手动触发。

## 联系

- 漏洞报告 / 问题反馈：见 [SECURITY.md](./SECURITY.md)
- 用户协议：见 [LICENSE.txt](./LICENSE.txt)
- 更新历史：[Releases](https://github.com/notwin/solpress-releases/releases)

---

本仓库仅托管 macOS DMG 发布物，不含源码。源码私有维护。
