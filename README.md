# Awesome Kaiheila [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> 😎 Awesome things related to kaiheila.

## 目录

- [官方资源](#官方资源)
  - [文档](#文档)
  - [官方服务器](#官方服务器)
- [SDK](#SDK)
- [框架](#框架)
- [应用案例](#应用案例)
- [社区资源](#社区资源)
  - [教程](#教程)
  - [社区服务器](#社区服务器)
- [贡献](#贡献)

## 官方资源

### 文档

**开发者酒馆**: <http://developer.kaiheila.cn/>

在开发者酒馆，你可以对自己的机器人进行管理，也可以查阅机器人的开发文档。

**开发文档源代码**: <https://github.com/kaiheila/api-docs>

开黑啦开发者中心文档的源代码。

### 官方服务器

- [「开黑啦」吐槽中心](https://kaihei.co/1r4VkB)

## 适配器

> 「适配器」收集了各机器人框架连接开黑啦平台所使用的插件。

平台|项目|包|文档
-|-|-|-
Koishi|[@koishijs/plugin-adapter-kaiheila](https://github.com/koishijs/koishi/tree/master/plugins/adapter/kaiheila)|[![npm](https://img.shields.io/npm/v/@koishijs/plugin-adapter-kaiheila?style=flat-square)](https://www.npmjs.com/package/@koishijs/plugin-adapter-kaiheila)|[适配器：开黑啦](https://koishi.js.org/plugins/adapter/kaiheila.html)
Nonebot|[nonebot-adapter-kaiheila](https://github.com/Tian-que/nonebot-adapter-kaiheila)|[![PyPI](https://img.shields.io/pypi/v/nonebot-adapter-kaiheila?style=flat-square)](https://pypi.org/project/nonebot-adapter-kaiheila/)|[Kaiheila Adapter 使用指南](https://github.com/Tian-que/nonebot-adapter-kaiheila/blob/master/MANUAL.md)

## SDK

语言/平台|项目|包|介绍|文档
-|-|-|-|-
PHP|[php-bot](https://github.com/kaiheila/php-bot)||开黑啦机器人的php版本|
PHP|[Kaiheila PHP EasyDev](https://github.com/hugoshao/Kaiheila_PHP_EasyDev)||面向开黑啦编程，由开黑啦开发者交流中心提供的PHP-SDK，可简称为PED|
Python|[khl.py](https://github.com/TWT233/khl.py)|[![PyPI](https://img.shields.io/pypi/v/khl.py?style=flat-square)](https://pypi.org/project/khl.py/)|SDK for kaiheila.cn in python|[文档](https://github.com/TWT233/khl.py/tree/main/example)
Node.js|[BotRoot](https://github.com/shugen002/BotRoot)|[![npm](https://img.shields.io/npm/v/kaiheila-bot-root?style=flat-square)](https://www.npmjs.com/package/kaiheila-bot-root)|开黑啦机器人JavaScript SDK|
Node.js|[KaiheilaWS](https://github.com/853Lab/KaiheilaWS)|[![npm](https://img.shields.io/npm/v/kaiheila-ws?style=flat-square)](https://www.npmjs.com/package/kaiheila-ws)|开黑啦机器人v2和v3 API的收发SDK，基于ECMAScript|
C# .NET|[kaiheila-dotnet](https://github.com/kaiheila-community/kaiheila-dotnet)|[![Nuget](https://img.shields.io/nuget/v/Kaiheila?style=flat-square)](https://www.nuget.org/packages/Kaiheila/)|开黑啦的 .NET 5 SDK。|[Kaiheila.NET](https://khl-net.vbox.moe)
易语言|[kaiheila-sdk-EL](https://github.com/dust0517/kaiheila-sdk-EL)||从0开始实现的易语言开黑啦机器人SDK|
C# .NET|[KaiheilaSharp](https://github.com/kaiheila-community/KaiheilaSharp)|[![Nuget](https://img.shields.io/nuget/v/KaiheilaSharp.Web.Webhook?style=flat-square)](https://www.nuget.org/packages/KaiheilaSharp.Web.Webhook/)|开黑啦 .NET 库，基于 .NET 6.0|[KaiheilaSharp.Web.Webhook](https://github.com/kaiheila-community/KaiheilaSharp/blob/main/src/Web/KaiheilaSharp.Web.Webhook/README.md)
Java|[rabbit](https://github.com/FightingGuys/rabbit)||开黑啦机器人Java软件开发工具SDK|[rabbit](https://github.com/FightingGuys/rabbit)
Go|[khl](https://github.com/lonelyevil/khl)|[![Go](https://img.shields.io/github/go-mod/go-version/lonelyevil/khl?style=flat-square)](https://pkg.go.dev/github.com/lonelyevil/khl)|A library for interacting with khl bot API.|[khl](https://pkg.go.dev/github.com/lonelyevil/khl)

## 框架

> 经过配置后即可运行的可执行程序统一归于「框架」分类内。

语言/平台|项目|包|介绍|文档
-|-|-|-|-
Node.js|[kBotify](https://github.com/fi6/kBotify)|[![npm](https://img.shields.io/npm/v/kbotify?style=flat-square)](https://www.npmjs.com/package/kbotify)|基于botRoot的开黑啦Bot开发框架|
C# .NET|[kaiheila-onebot](https://github.com/kaiheila-community/kaiheila-onebot)|[![Nuget](https://img.shields.io/nuget/v/Kaiheila.OneBot?style=flat-square)](https://www.nuget.org/packages/Kaiheila.OneBot/)|OneBot（原CQHTTP）的开黑啦（kaiheila）平台实现。|
Node.js|[koishi](https://github.com/koishijs/koishi)|[![npm](https://img.shields.io/npm/v/koishi?style=flat-square)](https://www.npmjs.com/package/koishi)|跨平台机器人框架，支持 QQ / Telegram / 开黑啦，支持账号互通|https://koishi.js.org|
Node.js|[kaiheila.ts](https://github.com/SakuraBot-dev/kaiheila.ts)|[![npm](https://img.shields.io/npm/v/khts?style=flat-square)](https://www.npmjs.com/package/khts)|插件式/命令式的开黑啦机器人框架，目前版本支持了大部分常用的API|https://github.com/SakuraBot-dev/kaiheila.ts|
C# .NET|[KHLBotSharp](https://github.com/PoH98/KHLBotSharp)|[![Nuget](https://img.shields.io/nuget/v/KHLBotSharp.Core?style=flat-square)](https://www.nuget.org/packages/KHLBotSharp.Core/)|开黑啦机器人运行器，支持多机器人以及插件模式运行，插件框架使用.NET Standard 2.0扩大支持度|[KHLBotSharp](https://github.com/PoH98/KHLBotSharp)

## 应用案例

机器人可以实现许多实用或娱乐性的功能。如果你开发了一个「开黑啦」机器人，请自由地提交 Issue 或 PR。

语言/平台|项目|介绍|邀请
-|-|-|-
C# .NET 5|[kaiheila-inspector](https://github.com/kaiheila-community/kaiheila-inspector)|检查/Inspector  开发人员工具|
Node.js|[SKDiceBot](https://github.com/ShenKSPZ/SKDiceBot)|深空的跑团骰子娘开源代码|

## 社区资源

### 教程

如果你编写了一份与「开黑啦」相关的开发教程，请自由地提交 Issue 或 PR。

- [Kaiheila.NET 教程](https://khl-net.vbox.moe/articles/tutorials/index.html)

### 社区服务器

- [「开黑啦」cracker 联盟](https://kaihei.co/O9A5AY)
- [【开黑啦】 开发者交流平台](https://kaihei.co/XGtqwD)
- [机器人社区 - Bot Community](https://kaihei.co/XoL2WY)

## 贡献

如果你发现或创作了一个与「开黑啦」相关的项目，请自由地提交 Issue 或 PR。

- 提交时请注意使用最基础的 Markdown 格式，不要对列表等元素进行不必要的格式化。
- 包图标请统一使用 [Shields.io - Version](https://shields.io/category/version)，请注意加上 `?style=flat-square`。

如果你想要在这个组织内创建新的项目，请加入 [这个](https://kaihei.co/XoL2WY) 服务器告诉我。
