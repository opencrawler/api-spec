<div align="right">

[EN](/README.md) | [中文](/docs/README_ZH.md)

</div>

<div align="center">

![Open Crawler](https://avatars0.githubusercontent.com/u/44334826?s=200&v=4)

# Open Crawler Specification

Specification to transform normal site or App to an API.

</div>

---

**:warning: The open crawler api specification is based on [Open API](https://github.com/OAI/OpenAPI-Specification).**

We create open-crawler api-spec by modified some section of Open API.

We are always following the stable version of OAI. For now the version of OAI is `3.0.2`, and our open-crawler api-spec also is `3.0.2`. In the feature the stable of OAI will be `3.0.3`, at that time we will update our open-crawl-spec version to follow the newer version as soon as possible. At sometime, maybe the changes of newer version of OAI have zero feature for our open-crawler api-spec, and we will not to update the version.

[The detail of specification can be found here.](/versions/3.0.2.md)

## Abstract

The open-crawler api-spec contains 2 parts of specifications:
1. API defines of site's paths;
2. Data parser schema for each path's response.

The open-crawler api-spec is trying to make every sites served as API service. Then everyone can use the API to create their APPs or just take the data away like a thief.

## Community

For now we only supported:

:fire: We are trying to create a community. 

## Participation

The current process for development of the open-crawler api-spec is described in [Development Guidelines](DEVELOPMENT.md).

The TSC holds weekly web conferences to review open pull requests and discuss open issues related to the evolving open-crawler api-spec. Participation in weekly calls and scheduled working sessions is open to the community. You can view the [TSC calendar online](https://opencrawler.groups.io/g/tsc/calendar).

The open-crawler api-spec encourages participation from individuals and companies alike. If you want to participate in the evolution of the open-crawler api-spec, consider taking the following actions:

* Review the [current specification](versions/3.0.2.md). The human-readable markdown file _is the source of truth_ for the specification.
* Review the [development](DEVELOPMENT.md) process so you understand how the spec is evolving.
* Check the [issues](https://github.com/opencrawler/api-spec/issues) and [pull requests](https://github.com/opencrawler/api-spec/pulls) to see if someone has already documented your idea or feedback on the specification. You can follow an existing conversation by adding a comment to the existing issue or PR.
* Create an issue to describe a new concern. If possible, propose a solution.

More detail you can check the [CONTRIBUTING](.github/CONTRIBUTING.md)

Not all feedback can be accommodated and there may be solid arguments for or against a change being appropriate for the specification.

## Licensing

See: [License (Apache-2.0)](https://github.com/opencrawl/api-spec/blob/master/LICENSE)