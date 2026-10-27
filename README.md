## 0.6.1 正式发行 · 2026-10-27

[下载最新正式版](https://github.com/lyzbcy/laoyu-whale-downloads/releases/tag/v0.6.1)：Windows x64安装版/ZIP、Mac Apple Silicon ARM64 DMG/ZIP，无Intel Mac包。

已支持应用内更新和问题反馈；旧无更新器版本首次请手动安装一次。Mac未Apple公证，Windows未代码签名。当前QQ组件仅限非商业使用；Mac最终QQ/模型闭环未重新验收，详见发行说明。

以下保留原使用说明和历史记录；版本及平台以最新发行说明为准。

# 大肥鲸宠物助手

捞鱼工作室的 QQ AI 小宠物，Windows x64 公开测试版。

[下载与版本说明](https://github.com/lyzbcy/laoyu-whale-downloads/releases)

支持独立宠物 QQ 小号、绑定主人、人格与本机记忆、聊天回复、可选定时主动聊天；模型可选择本机已登录的 Codex CLI 或兼容 API。QQ 消息使用 WebSocket 推送，没有消息时不调用模型。

## 使用

完整安装 EXE → 填宠物小号和主人 QQ → 准备 QQ 并扫码 → 选择 Codex CLI / API 并测试连接 → 开始陪伴。

需要已安装官方 Windows QQ。Codex CLI 由用户自行安装登录，使用其当前账号额度；API 模式由用户填写自己的密钥。无需预装 Node.js/npm/Git。首次登录、模型服务和软件更新需要网络。

当前已验证 QQ 与 Codex CLI 的真实收发闭环。微信、抖音/B站浏览和分享尚未接入，Mac 尚未验收。

## 非商业限制与隐私

当前 QQ 组件 NapCat v4.18.41 的许可证禁止商业用途。本公开测试包仅供非商业使用，公开下载不代表商业授权；商业交付需另行解决相关授权。组件来源、版权和完整许可见 [第三方声明](THIRD_PARTY_NOTICES.md) 与 [原始许可证](licenses/NapCat-LICENSE.txt)。

不包含已登录账号、模型密钥或个人聊天。配置和记忆保留在用户本机，模型会接收用于生成回复的对话上下文；API 密钥由 Windows 系统凭据保护。模型与 QQ 服务遵循各自规则。

本仓库仅用于公开说明和干净发行包，不含开发工作区或用户数据。
