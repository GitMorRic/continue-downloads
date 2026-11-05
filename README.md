# 续行下载

[打开手机友好的下载页](https://gitmorric.github.io/continue-downloads/)

此仓库提供安装包、签名固件、编译后的自托管运行时与版本说明，不包含私人源码工程、账号、笔记或密钥。

当前跨设备开发测试版：

- Android 0.3.0-dev：支持 Android 13 及以上，与已发布旧版签名一致。
- Windows 0.16.25：下载 EXE 后保存工作并退出旧版再升级。
- 墨水屏 1.0.42：仅 continue-2026-10-18 / SE0368。先升级桌面，再通过 USB 更新。
- 自托管云 1.33-preview：Windows / Linux Docker，解压后阅读 deploy/README.md，需要自己的有效 HTTPS 域名。
- 浏览器扩展 0.3.0：选中文字 → 续行预览 → 确认保存，支持 Chrome / Edge。
- iPhone：使用部署后的网页版，可添加到主屏幕；当前没有原生 iOS 包。

![公开下载页二维码](download-qr.svg)

本次云 1.33 和浏览器扩展为候选交付，不替换 Windows 稳定自动更新通道。已完成软件、容器和模拟链路验证；实体 K80、墨水屏与付费供应商仍需验收。文件带 SHA256 校验，桌面更新和固件分别验证签名。


2026-11-05 开发验证：Windows 0.16.34 与固件 1.0.58 已提供，支持笔记内追加与 Action 电脑听写；需要匹配云代码契约 1.42。已验证真实本机 GPU、Windows 输入框及固件读回，物理 REC/Action 联动待验收。稳定自动更新保持 0.16.33，旧云安装包仍为 1.35，暂不包含此轮功能。见 [版本说明](https://github.com/GitMorRic/continue-downloads/releases/tag/0.16.34)。
