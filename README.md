<h1 align="center">
    <br>
    <img width="200" src="Yomu/icon.png" alt="LOGO">
    <br>
    Yomu
    <h4 align="center">
        一个基于<a href="https://github.com/botuniverse/onebot">OneBot</a>协议的 <a href="https://dotnet.microsoft.com/download/dotnet/7.0">C#/.Net 7</a> 异步即时通讯服务端框架 | 
        <a href="#">
            框架文档（暂无）
        </a>
    </h4>
    <center>Logo 暂时来自<a href="http://www.pixiv.net/member_illust.php?mode=medium&illust_id=26599385">Pixiv</a></center>
    <h4 align="center">
        <a href="https://www.nuget.org/packages/Yomu/">
            <img src="https://img.shields.io/nuget/v/Yomu?style=flat-square" alt="nuget">
        </a>
        <a href="https://onebot.dev/">
            <img src="https://img.shields.io/badge/OneBot-v12-black?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAHAAAABwCAMAAADxPgR5AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAAxQTFRF////29vbr6+vAAAAk1hCcwAAAAR0Uk5T////AEAqqfQAAAKcSURBVHja7NrbctswDATQXfD//zlpO7FlmwAWIOnOtNaTM5JwDMa8E+PNFz7g3waJ24fviyDPgfhz8fHP39cBcBL9KoJbQUxjA2iYqHL3FAnvzhL4GtVNUcoSZe6eSHizBcK5LL7dBr2AUZlev1ARRHCljzRALIEog6H3U6bCIyqIZdAT0eBuJYaGiJaHSjmkYIZd+qSGWAQnIaz2OArVnX6vrItQvbhZJtVGB5qX9wKqCMkb9W7aexfCO/rwQRBzsDIsYx4AOz0nhAtWu7bqkEQBO0Pr+Ftjt5fFCUEbm0Sbgdu8WSgJ5NgH2iu46R/o1UcBXJsFusWF/QUaz3RwJMEgngfaGGdSxJkE/Yg4lOBryBiMwvAhZrVMUUvwqU7F05b5WLaUIN4M4hRocQQRnEedgsn7TZB3UCpRrIJwQfqvGwsg18EnI2uSVNC8t+0QmMXogvbPg/xk+Mnw/6kW/rraUlvqgmFreAA09xW5t0AFlHrQZ3CsgvZm0FbHNKyBmheBKIF2cCA8A600aHPmFtRB1XvMsJAiza7LpPog0UJwccKdzw8rdf8MyN2ePYF896LC5hTzdZqxb6VNXInaupARLDNBWgI8spq4T0Qb5H4vWfPmHo8OyB1ito+AysNNz0oglj1U955sjUN9d41LnrX2D/u7eRwxyOaOpfyevCWbTgDEoilsOnu7zsKhjRCsnD/QzhdkYLBLXjiK4f3UWmcx2M7PO21CKVTH84638NTplt6JIQH0ZwCNuiWAfvuLhdrcOYPVO9eW3A67l7hZtgaY9GZo9AFc6cryjoeFBIWeU+npnk/nLE0OxCHL1eQsc1IciehjpJv5mqCsjeopaH6r15/MrxNnVhu7tmcslay2gO2Z1QfcfX0JMACG41/u0RrI9QAAAABJRU5ErkJggg==" alt="onebot">
        </a>
        <a href="https://www.apache.org/licenses/LICENSE-2.0">
            <img src="https://img.shields.io/github/license/xh321/Yomu?style=flat-square&color=blueviolet" alt="license">
        </a>
        <img src="https://img.shields.io/github/stars/xh321/Yomu?style=flat-square" alt="stars">
        <img src="https://img.shields.io/github/actions/workflow/status/xh321/Yomu/nuget.yml?branch=master&&style=flat-square" alt="workflow">
    </h4>
</h1>



## 文档

**=====本框架只支持Array的上报格式!=====**

本页面不会对框架的特性做介绍，如果需要详细了解框架的功能**一定**要看**文档**！

->[Docs](#)<-暂无

->[更新日志](#)<-暂无

文档目前还没有进行编写

如需要查看最新自动生成的文档请前往 [![Sora on fuget.org](https://www.fuget.org/packages/Yomu/badge.svg)](https://www.fuget.org/packages/Yomu)

<details>
  <summary>支持的连接方式</summary>

- 通过Websocket正向连接

</details>

## 关于本框架

> 本框架仅支持Onebot协议，任何非Onebot协议并不会考虑进行支持

这是一个以轻量为主的支持 [onebot](https://onebot.dev/) 协议的即时通讯框架，目前计划支持 Onebot v12。

这个框架将会一直以简单易用为主，也会向着更加便捷的方向进行开发

如果有什么建议的话，可以在[Discussions](https://github.com/xh321/Yomu/discussions)里提出哦

## 开发注意事项

<details>
<summary>开源协议</summary>

本项目使用了 `Apache-2.0`开源协议

这意味着在引用/修改本类库时需要遵守相关的协议规定

</details>

<details>
<summary>类 Discord 二级群组支持</summary>

本框架的正式版本和正常发布版本目前将不会支持这类API。
这类API将在主要功能成熟后再进行支持考虑。

</details>

## 关于ISSUE

ISSUE 目前只接受bug的提交和新功能的建议

如果有使用问题或者不确定的问题请使用[Discussions](https://github.com/xh321/Yomu/discussions)

> 请注意, 开发者并没有**义务**回复您的问题. 您应该具备基本的提问技巧。
>
> 如果不知道该怎么样提问，那么请在提问前阅读 [提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/master/README-zh_CN.md)

以下ISSUE会被直接关闭

- 提交BUG时没有使用Template
- 提交当前版本下已经被修复的BUG
- 询问问题（为什么不用用[Discussions](https://github.com/xh321/Yomu/discussions)呢）

## 关于命名

Yomu，当然是妖梦啦~

## 鸣谢

感谢以下大佬对本框架开发的帮助

本框架直接基于 [Sora](https://github.com/Hoshikawa-Kaguya/Sora) 进行二次开发，感谢[Yukari316](https://github.com/Yukari316)的支持！

### 使用到的开源库

[Fleck](https://github.com/statianzo/Fleck) | WebSocket 服务器

[Newtonsoft.Json](https://www.newtonsoft.com/json) | JSON 序列化/反序列化

[protobuf-net](https://github.com/protobuf-net/protobuf-net) | ProtoBuf序列化/反序列化

[System.Reactive](https://github.com/dotnet/reactive) | 响应式异步API支持

[YukariToolBox](https://github.com/DeepOceanSoft/YukariToolBox) | Log，异步扩展工具箱

### 感谢 [JetBrains](https://www.jetbrains.com/?from=Yomu) 为开源项目提供免费的全家桶授权

> 本项目使用了免费的[ReSharper](https://www.jetbrains.com/resharper/)插件/[Rider](https://www.jetbrains.com/rider/?from=Yomu)开发环境

<a href="https://www.jetbrains.com/?from=Yomu">
    <img src=".github/jetbrains-variant-4.svg" alt="jetbrains">
</a>
<a href="https://www.jetbrains.com/ReSharper/?from=Yomu">
    <img src=".github/icon-resharper.svg" alt="jetbrains">
</a>
<a href="https://www.jetbrains.com/rider/?from=Yomu">
    <img src=".github/icon-rider.svg" alt="jetbrains">
</a>