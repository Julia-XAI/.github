# Julia-XAI: Explainable AI in Julia
[![Stable][docs-bdg]][docs-url]

This organization hosts [Explainable AI (XAI) methods][wiki-xai] 
written in the [Julia programming language][julia-url],
with a focus on post-hoc, local input-space explanations of black-box models.
In simpler terms, methods that try to answer the question 
*"Which part of the input is responsible for the model's output?"*.

![Julia-XAI ecosystem diagram](https://raw.githubusercontent.com/Julia-XAI/XAIDocs/getting-started/dev/assets/org.png)

The ecosystem is organized into several packages.
As a user, you only need to install the packages that implement the methods you want to use.

As a developer, you can make use of the [XAIBase.jl interface][docs-interface]
to quickly implement or prototype new methods without having to write boilerplate code.

## New users
Our recommended starting point into the Julia-XAI ecosystem is the 
[Getting started guide][docs-url] in the Julia-XAI documentation.

## New developers
If you want to implement an XAI method, take a look at the [common interface
defined in XAIBase.jl][docs-interface].

## Contributing
We welcome all contributions to the Julia-XAI ecosystem.
Please contact us if you want your package to be included in this organization.

## Package overview

| Name                                 | Latest release                           | Status                                                                      | Summary                                                            |
|:-------------------------------------|:-----------------------------------------|:----------------------------------------------------------------------------|:-------------------------------------------------------------------| 
| [ExplainableAI.jl][repo-expl]        | [![Release][rel-bdg-expl]][rel-url-expl] | [![CI][ci-bdg-expl]][ci-url-expl] [![Coverage][cov-bdg-expl]][cov-url-expl] | Collection of Explainable AI methods in Julia                      |
| [RelevancePropagation.jl][repo-relp] | [![Release][rel-bdg-relp]][rel-url-relp] | [![CI][ci-bdg-relp]][ci-url-relp] [![Coverage][cov-bdg-relp]][cov-url-relp] | Layerwise Relevance Propagation (LRP) and CRP for use with Flux.jl |
| [XAIBase.jl][repo-base]              | [![Release][rel-bdg-base]][rel-url-base] | [![CI][ci-bdg-base]][ci-url-base] [![Coverage][cov-bdg-base]][cov-url-base] | Core package defining the Julia-XAI interface                      |
| [VisionHeatmaps.jl][repo-vish]       | [![Release][rel-bdg-vish]][rel-url-vish] | [![CI][ci-bdg-vish]][ci-url-vish] [![Coverage][cov-bdg-vish]][cov-url-vish] | Heatmaps for vision models                                         |
| [TextHeatmaps.jl][repo-txth]         | [![Release][rel-bdg-txth]][rel-url-txth] | [![CI][ci-bdg-txth]][ci-url-txth] [![Coverage][cov-bdg-txth]][cov-url-txth] | Heatmaps for language models                                       |

[wiki-xai]: https://en.wikipedia.org/wiki/Explainable_artificial_intelligence
[julia-url]: https://julialang.org
[docs-url]: https://julia-xai.github.io/XAIDocs/
[docs-bdg]: https://img.shields.io/badge/Julia--XAI_docs-stable-blue.svg
[docs-interface]: https://julia-xai.github.io/XAIDocs/XAIBase/

[repo-expl]: https://github.com/Julia-XAI/ExplainableAI.jl
[repo-relp]: https://github.com/Julia-XAI/RelevancePropagation.jl
[repo-base]: https://github.com/Julia-XAI/XAIBase.jl
[repo-txth]: https://github.com/Julia-XAI/TextHeatmaps.jl/
[repo-vish]: https://github.com/Julia-XAI/VisionHeatmaps.jl

[rel-bdg-expl]: https://juliahub.com/docs/General/ExplainableAI/stable/version.svg
[rel-url-expl]: https://github.com/Julia-XAI/ExplainableAI.jl/releases
[rel-bdg-relp]: https://juliahub.com/docs/General/RelevancePropagation/stable/version.svg
[rel-url-relp]: https://github.com/Julia-XAI/RelevancePropagation.jl/releases
[rel-bdg-base]: https://juliahub.com/docs/General/XAIBase/stable/version.svg
[rel-url-base]: https://github.com/Julia-XAI/XAIBase.jl/releases
[rel-bdg-txth]: https://juliahub.com/docs/General/TextHeatmaps/stable/version.svg
[rel-url-txth]: https://github.com/Julia-XAI/TextHeatmaps.jl/releases
[rel-bdg-vish]: https://juliahub.com/docs/General/VisionHeatmaps/stable/version.svg
[rel-url-vish]: https://github.com/Julia-XAI/VisionHeatmaps.jl/releases

[ci-bdg-expl]: https://github.com/Julia-XAI/ExplainableAI.jl/workflows/CI/badge.svg
[ci-url-expl]: https://github.com/Julia-XAI/ExplainableAI.jl/actions
[ci-bdg-relp]: https://github.com/Julia-XAI/RelevancePropagation.jl/workflows/CI/badge.svg
[ci-url-relp]: https://github.com/Julia-XAI/RelevancePropagation.jl/actions
[ci-bdg-base]: https://github.com/Julia-XAI/XAIBase.jl/workflows/CI/badge.svg
[ci-url-base]: https://github.com/Julia-XAI/XAIBase.jl/actions
[ci-bdg-txth]: https://github.com/Julia-XAI/TextHeatmaps.jl/workflows/CI/badge.svg
[ci-url-txth]: https://github.com/Julia-XAI/TextHeatmaps.jl/actions
[ci-bdg-vish]: https://github.com/Julia-XAI/VisionHeatmaps.jl/workflows/CI/badge.svg
[ci-url-vish]: https://github.com/Julia-XAI/VisionHeatmaps.jl/actions

[cov-bdg-expl]: https://codecov.io/gh/Julia-XAI/ExplainableAI.jl/branch/master/graph/badge.svg
[cov-url-expl]: https://codecov.io/gh/Julia-XAI/ExplainableAI.jl
[cov-bdg-relp]: https://codecov.io/gh/Julia-XAI/RelevancePropagation.jl/branch/main/graph/badge.svg
[cov-url-relp]: https://codecov.io/gh/Julia-XAI/RelevancePropagation.jl
[cov-bdg-base]: https://codecov.io/gh/Julia-XAI/XAIBase.jl/branch/main/graph/badge.svg
[cov-url-base]: https://codecov.io/gh/Julia-XAI/XAIBase.jl
[cov-bdg-txth]: https://codecov.io/gh/Julia-XAI/TextHeatmaps.jl/branch/main/graph/badge.svg
[cov-url-txth]: https://codecov.io/gh/Julia-XAI/TextHeatmaps.jl
[cov-bdg-vish]: https://codecov.io/gh/Julia-XAI/VisionHeatmaps.jl/branch/main/graph/badge.svg
[cov-url-vish]: https://codecov.io/gh/Julia-XAI/VisionHeatmaps.jl
