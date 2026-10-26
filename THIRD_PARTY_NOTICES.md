# Third-party notices / 第三方来源

本软件由捞鱼工作室制作，与 DeepSeek 官方无隶属关系。

## 0.2.7 公开测试版
- 本包公开提供测试下载；QQ组件当前仅限非商业使用。自有代码许可不改变第三方限制。
- 包含自有宠物引擎、ws 8.22.0（MIT）、yauzl 3.4.0（MIT）及未修改的官方 NapCat Shell v4.18.41 归档。
- NapCat Copyright © 2024 Mlikiowa，由 NapNeko/NapCatQQ 贡献者开发，适用 Limited Redistribution License，禁止商业用途。完整许可在 licenses/NapCat-LICENSE.txt，原包许可证保留；商业使用须另外取得作者授权。
- 上游：https://github.com/NapNeko/NapCatQQ ，原包：https://github.com/NapNeko/NapCatQQ/releases/download/v4.18.41/NapCat.Shell.zip
- SHA-256：6801f93e533846cea05f4f531874a0e84371ab2331c5585b57cd7e3b869cf96b。
- 不捆绑旧 DSH/Node 运行树。下列 DSH 来源描述 0.1.0 历史版本和保留的高级工具代码。

## DeepSeek Harness
- 来源：https://github.com/deepseek-ai/deepseek-harness
- 使用：官方 npm `@deepseek-ai/dsh` 0.2.1-rc.2 及锁定依赖。
- 许可证：MIT，Copyright (c) 2026 DeepSeek。完整文本见 licenses/DSH-LICENSE.txt；上游依赖声明见 licenses/DSH-THIRD-PARTY.md。
- 构建时覆盖修复依赖 zod 4.6.7、undici 8.12.3、fflate 0.8.3、@modelcontextprotocol/client 2.4.0；没有修改 DSH 源码。覆盖前后审计保存在开发 verification/，完整 lockfile 在 reference/runtime-package-lock.json。
- 内核为候选版本，兼容性可能变化。依赖许可索引在 licenses/runtime-dependencies.json，原始 LICENSE/NOTICE 随 runtime/node_modules 对应包保留。

## 社区桌面方案
- 来源：https://github.com/LodeKennes/deepseek-harness-desktop
- 参考 commit：b4ee43cb37cbeb34a867743d76a9950d78ef9ea0。
- 许可证：MIT，完整文本在 licenses/desktop-MIT.txt。
- 复用：electron/sidecar-entry.mjs 的 stdin 退出和父进程存活监控；路径改为 npm 包位置，针对 DSH 0.2.1 显式调用 runCli。参考独立 Node 运行时布局、固定版本、单独服务进程设计。
- 不含该项目的订阅代理、品牌素材及账号资料。

## Node.js / Electron
- Node.js v24.19.0 Windows x64，来源 https://nodejs.org/dist/v24.19.0/ ，构建核验官方 SHASUMS256.txt；原始发行 ZIP SHA-256：57f71ab3652e797d84acddc79c81cc9ff1c6ddb2a1974cdb83f00fee9bff4c73。
- Node.js 完整许可证随 resources/runtime/NODE-LICENSE.txt 分发。
- Electron 45.0.0，https://github.com/electron/electron ，MIT；Electron/Chromium 原始 LICENSE 与 LICENSES.chromium.html 在安装目录保留。

## 原创美术
图标使用捞鱼工作室精选原创「第17弹-决定了.png」，登记在共享软件 logo 台账。角色素材不因代码采用 MIT 而自动获得第三方二次分发授权。
