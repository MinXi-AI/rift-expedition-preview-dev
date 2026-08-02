# 裂界远征开发 Pages Artifact

- 渠道：`dev`
- 当前里程碑：`M0 foundation`
- 源码仓：私有，不在本仓公开

此模板只部署已提交的 `site/`。它不得安装依赖、编译源码或接收 TypeScript、测试、源映射、资源包 ZIP、候选资料与秘密。

发布约束：

1. Pages Source 使用 GitHub Actions。
2. 工作流只上传并部署已提交的 `site/`。
3. `site/deployment-manifest.json` 固定源 commit、逐文件 SHA-256 与 artifact 摘要。
4. 本仓不得接收 TypeScript 源码、测试、源映射、ZIP、候选资料与秘密。
