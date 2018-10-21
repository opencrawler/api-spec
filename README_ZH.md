# The Open Crawler Specification

**该规范目前还处在商讨阶段，目前最新版是草案版本。如果你目前就想在正式的生产环境中使用该规范，请务必知悉随后因规范发生改变而带来的损失。最后更新于21/10/2018。**

[![Build Status](https://travis-ci.org/opencrawler/api-spec.svg?branch=master)](https://travis-ci.org/opencrawler/api-spec)

![](https://avatars0.githubusercontent.com/u/44334826?s=200&v=4)

**其他语言版本**
- [English](README.md)

> open-crawler api-spec 是基于 [Open API](https://github.com/OAI/OpenAPI-Specification)规范衍生而来。

我们在制定open-crawler api-spec规范时尽可能地于Open API保持一致，并且大部分功能是优先从Open API进行直接使用，其次是进行修改，最后才是增加我们单独的定义。

我们将一直更随着 Open API规范的版本。 目前的Open API最新版本是`3.0.2`，我们的open-crawler api-spec 最新版号也将是`3.0.2`. 之后Open API会升级到`3.0.3`，届时open-crawl api-spec也会尽快地升级到最新版。 有时候，如果Open API的版本变动内容不会影响 open-crawler api-spec，那么我们可以选择不更新版本号。

[在这里可以查看详细的open-crawler api-spec规范的内容。](versions/3.0.2.md)

## 简介

open-crawler api-spec 包含两个部分的规范定义:
1. 站点请求路径的定义；
2. 站点请求的响应内容的抽取规则定义。

open-crawler api-spec规范的目的就是使得每一个站点或者http服务都能通过统一的规则生产出规范的API接口。 其他人就可以像使用自有的API接口一样地去使用所有站点，或者是直接取得想要的数据。

## 社区

目前我们支持在一下社群中进行讨论:
- [Gitter](https://gitter.im/Open-Crawler/Lobby)
- 添加微信，发送`open-crawler`，拉入群聊 ![Open Crawler Group](https://github.com/jiusanzhou/jiusanzhou.github.io/raw/master/static/WeChat-JohnCx.jpeg)

## 参与

open-crawler api-spec 目前的开发进度可以在[开发指南](DEVELOPMENT.md)中查看。
The TSC holds weekly web conferences to review open pull requests and discuss open issues related to the evolving open-crawler api-spec. Participation in weekly calls and scheduled working sessions is open to the community. You can view the [TSC calendar online](https://opencrawler.groups.io/g/tsc/calendar).

The open-crawler api-spec encourages participation from individuals and companies alike. If you want to participate in the evolution of the open-crawler api-spec, consider taking the following actions:

* Review the [current specification](versions/3.0.2.md). The human-readable markdown file _is the source of truth_ for the specification.
* Review the [development](DEVELOPMENT.md) process so you understand how the spec is evolving.
* Check the [issues](https://github.com/opencrawler/api-spec/issues) and [pull requests](https://github.com/opencrawler/api-spec/pulls) to see if someone has already documented your idea or feedback on the specification. You can follow an existing conversation by adding a comment to the existing issue or PR.
* Create an issue to describe a new concern. If possible, propose a solution.

更多详情可以查看[贡献指南](.github/CONTRIBUTING.md)。

Not all feedback can be accommodated and there may be solid arguments for or against a change being appropriate for the specification.

## Licensing

See: [License (Apache-2.0)](https://github.com/opencrawl/api-spec/blob/master/LICENSE)