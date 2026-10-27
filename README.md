# Seedance 漫剧制作 Skill

中文制作方法包 **v1.9.9-public**，从 v1.9.9 制作文档整理，帮助能读取 Markdown 的 AI 助手组织故事、分镜、参考素材、动作、镜头、声音和验收。

## 开始使用

免安装方式：将 [技能目录](skills/seedance-comic-production/) 提供给助手，请它先读 [SKILL.md](skills/seedance-comic-production/SKILL.md)，再按当前问题读取参考文档。

需要安装到支持技能发现的宿主时，将整个 `skills/seedance-comic-production` 目录复制到该宿主认可的技能目录，并保留 `references/`、`NOTICE.md` 和其他文件。将仓库的 [LICENSE](LICENSE) 一同复制到安装副本；安装路径和调用方式按所用宿主的当前文档配置。确认宿主实际发现技能名 `seedance-comic-production` 后再调用。上传 ZIP 本身不代表已经安装，本仓库没有验证各宿主的自动发现或原生命令。

可复制给助手：

> 请阅读 skills/seedance-comic-production/SKILL.md，按本包整理我的漫剧需求。故事目标：[填写]；必须保留的角色、内容与逐字台词：[填写]；素材及各自用途：[填写或暂无]；需要的交付：[提示词／分镜／制作方案]。缺素材先给未绑定草案；不要声称已经观看、生成或验证，也不要自动上传或付费。

- [包内使用说明](skills/seedance-comic-production/README.md)：输入和参考文档入口。
- [原创通用需求示例](examples/generic-brief.md)：虚构角色与纸风车短场，未生成验证。
- [版本来源与整理范围](skills/seedance-comic-production/CHANGELOG.md)。
- [贡献指南](CONTRIBUTING.md)。

## 适用范围与限制

本包交付文字方法与候选方案。它不是视频模型、模型权重、自动执行器或 Seedance 平台安装插件；不提供账户、API 密钥、媒体素材或付费权限。实际使用时独立核对所选产品入口、确切模型、输入模式、账户权限、价格与素材权利。

本公开版仅检查文档字节、结构、路径与内部链接。没有模型生成、宿主安装发现、连续视频、听音、口型、效果稳定性或成本收益测试。来源目录是继续查证的阅读链接，未重新验证所有外部页面，也未完成历史来源的逐句权利比对。

清理版移除非公开项目、私人反馈、会话历史和媒体检查记录；示例为新写虚构教学情境。本仓库不包含用户视频/图片、第三方媒体、书籍/手册 PDF、付费资产、外部代码或完整上游技能副本。

## 许可与关联

项目有权授权的原创内容采用 [MIT 许可证](LICENSE)，Copyright (c) 2026 1321dad-das。分发时保留版权和许可文本。外部链接、商标、模型、声音、肖像及第三方作品保留各自权利，不因本项目采用 MIT 而重新授权。详见 [NOTICE](skills/seedance-comic-production/NOTICE.md)。

本项目独立维护，非 ByteDance、Seedance、即梦、火山方舟或 Dreamina 官方产品或背书。
