# FR33-CH4T
[简体中文](README-zh_CN.md)   [English](README.md)

**新增FLUX-schnell作图支持！快去看看吧！（目前仅支持GPT系列模型，和搜索功能一样）**

**注意：目前Duckduckgo搜索插件默认不开启，有需要请打开设置勾选。插件不支持测试模型（LLaMa和Claude等）**

⭐️ **如果你喜欢本项目，请考虑在右上角给我加个星星！** ⭐️

欢迎来到为数不多的（几乎）无限制GPT-4o在线聊天！

这是一个允许你几乎无限使用ChatGPT的平台。同时，近期加入和对LLaMa和Claude Haiku的支持（暂时功能不完善）。

项目网站： [https://free-chat.davidx.us.kg](https://free-chat.davidx.us.kg)

现在就去试试吧！无需进行任何配置！

本项目的界面源于我的另一个项目[flask-gpt](https://github.com/Davidasx/flask-gpt)。然而，为了避免滥用，free-chat的源代码不对外公开。如果造成了任何不便，请您理解，谢谢！

## 重要提醒

由于这是一个完全免费的项目，我无法阻止滥用行为。尽管本项目提供了一个非常高的每日消息限额，当用户数量非常多或者有人滥用时，限制仍然会生效。本平台目前对外完全公开，但是如果发现大规模滥用行为，我可能会将其改成邀请使用。

我并不会追踪您使用本平台时的行为。然而，我不希望你进行滥用，因为这会危害整个用户群体的使用体验。

如果每个人都合理使用，该项目可以持续稳定运行若干年。

## 特性

- 使用UUID标识符跨设备同步。
- 无需额外注册登陆。第一次打开时，自动为您生成UUID。
- 来自GPT-4o快速、真实的回复。
- 使用FLUX-schnell作图。
- 使用Duckduckgo搜索插件获取最新信息。（需要在设置中开启）
- 终于支持流输出了！

## 正在施工

- 优化界面。（上游工程flask-gpt正在努力改进中……）
- 支持多行以及图片输入。
- 创作更好的账户、会话管理系统。

## 致谢

Azure翻译API提供界面翻译（法语，德语，西班牙语和中文繁体）支持。

界面均采用Python Flask框架，利用GitHub Copilot辅助编程。

FLUX-schnell作图模型由CloudFlare Workers AI提供。（参考[这篇文章](https://developers.cloudflare.com/workers-ai/models/flux-1-schnell/)，可以自己免费搞一个）

## 参与贡献

如果您愿意参与本项目：

- 如果您希望改进界面，请加入[flask-gpt](https://github.com/Davidasx/flask-gpt)项目。您的贡献将被合并入本项目中。
- 如果您有任何提升消息限额的办法，请私下联系我。
