<div align="right">

[EN](/README.md) | [中文](/docs/README_ZH.md)

</div>

<div align="center">

![Open Crawler](https://avatars0.githubusercontent.com/u/44334826?s=200&v=4)

# Open Crawler Specification

将站点或App转换成API接口的规范。

**:warning: 暂不可生产使用。**

</div>

---

**:warning: OpenCrawler-API 规范是基于 [Open API](https://github.com/OAI/OpenAPI-Specification)规范衍生而来。**

我们在制定OpenCrawler-API 规范时尽可能地与Open API保持一致，并且大部分功能是优先从Open API进行直接使用，其次是进行修改，最后才是增加我们单独的定义。

我们将一直更随着 Open API规范的版本。 目前的Open API最新版本是`3.0.2`，我们的OpenCrawler-API 规范最新版号也将是`3.0.2`. 之后Open API会升级到`3.0.3`，届时OpenCrawler-API 规范也会尽快地升级到最新版。 有时候，如果Open API的版本变动内容不会影响 OpenCrawler-API 规范，那么我们可以选择不更新版本号。

[在这里可以查看详细的OpenCrawler-API 规范的内容。](/versions/3.0.2.md)

## 简介

OpenCrawler-API 规范包含两个部分的规范定义:
1. 站点请求路径的定义；
2. 站点请求的响应内容的抽取规则定义。

OpenCrawler-API 规范的目的就是使得每一个站点或者http服务都能通过统一的规则生产出规范的API接口。 其他人就可以像使用自有的API接口一样地去使用所有站点，或者是直接取得想要的数据。

## 社区

目前我们支持在一下社群中进行讨论:

*:warning: 目前正在积极地创建社区，如果你是中文用户并且对开放爬虫项目有兴趣，欢迎添加项目发起人周筱鲁的微信: `JohnCx`，备注: `open crawler`。*

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

## 协议

查看: [License (Apache-2.0)](https://github.com/opencrawl/api-spec/blob/master/LICENSE)