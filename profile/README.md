# Julia-XAI: Explainable AI in Julia
This organization hosts [Explainable AI (XAI) methods][wiki-xai] 
written in the [Julia programming language][julia-url],
with a focus on post-hoc, local input-space explanations of black-box models.
In simpler terms, methods that try to answer the question 
*"Which part of the input is responsible for the model's output?"*.

**New users:**
Our recommended starting point into the Julia-XAI ecosystem is the 
[ExplainableAI.jl documentation][docs-expl].

**New developers:**
If you want to implement a method, take a look at the common interface
defined in [XAIBase.jl][repo-base].

## Contributing
We welcome all contributions to the Julia-XAI ecosystem.
Please contact us if you want your package to be included in this organization.

## Package overview

| Name                           | Latest release                           | Status                                                                      | Summary                                       |
|:-------------------------------|:-----------------------------------------|:----------------------------------------------------------------------------|:----------------------------------------------| 
| [ExplainableAI.jl][repo-expl]  | [![Release][rel-bdg-expl]][rel-url-expl] | [![CI][ci-bdg-expl]][ci-url-expl] [![Coverage][cov-bdg-expl]][cov-url-expl] | Collection of Explainable AI methods in Julia |
| [XAIBase.jl][repo-base]        |                                          | [![CI][ci-bdg-base]][ci-url-base] [![Coverage][cov-bdg-base]][cov-url-base] | Core package defining the Julia-XAI interface |
| [TextHeatmaps.jl][repo-txth]   | [![Release][rel-bdg-txth]][rel-url-txth] | [![CI][ci-bdg-txth]][ci-url-txth] [![Coverage][cov-bdg-txth]][cov-url-txth] | Heatmaps for language models                  |
| [VisionHeatmaps.jl][repo-vish] |                                          | [![CI][ci-bdg-vish]][ci-url-vish] [![Coverage][cov-bdg-vish]][cov-url-vish] | Heatmaps for vision models                    |

[wiki-xai]: https://en.wikipedia.org/wiki/Explainable_artificial_intelligence
[julia-url]: https://julialang.org
[docs-expl]: https://julia-xai.github.io/ExplainableAI.jl/stable/

[repo-expl]: https://github.com/Julia-XAI/ExplainableAI.jl
[repo-base]: https://github.com/Julia-XAI/XAIBase.jl
[repo-txth]: https://github.com/Julia-XAI/TextHeatmaps.jl/
[repo-vish]: https://github.com/Julia-XAI/VisionHeatmaps.jl

[rel-bdg-expl]: https://juliahub.com/docs/General/ExplainableAI/stable/version.svg
[rel-url-expl]: https://github.com/Julia-XAI/ExplainableAI.jl/releases
[rel-bdg-base]: https://juliahub.com/docs/General/XAIBase/stable/version.svg
[rel-url-base]: https://github.com/Julia-XAI/XAIBase.jl/releases
[rel-bdg-txth]: https://juliahub.com/docs/General/TextHeatmaps/stable/version.svg
[rel-url-txth]: https://github.com/Julia-XAI/TextHeatmaps.jl/releases
[rel-bdg-vish]: https://juliahub.com/docs/General/VisionHeatmaps/stable/version.svg
[rel-url-vish]: https://github.com/Julia-XAI/VisionHeatmaps.jl/releases

[ci-bdg-expl]: https://github.com/Julia-XAI/ExplainableAI.jl/workflows/CI/badge.svg
[ci-url-expl]: https://github.com/Julia-XAI/ExplainableAI.jl/actions
[ci-bdg-base]: https://github.com/Julia-XAI/XAIBase.jl/workflows/CI/badge.svg
[ci-url-base]: https://github.com/Julia-XAI/XAIBase.jl/actions
[ci-bdg-txth]: https://github.com/Julia-XAI/TextHeatmaps.jl/workflows/CI/badge.svg
[ci-url-txth]: https://github.com/Julia-XAI/TextHeatmaps.jl/actions
[ci-bdg-vish]: https://github.com/Julia-XAI/VisionHeatmaps.jl/workflows/CI/badge.svg
[ci-url-vish]: https://github.com/Julia-XAI/VisionHeatmaps.jl/actions

[cov-bdg-expl]: https://codecov.io/gh/Julia-XAI/ExplainableAI.jl/branch/master/graph/badge.svg
[cov-url-expl]: https://codecov.io/gh/Julia-XAI/ExplainableAI.jl
[cov-bdg-base]: https://codecov.io/gh/Julia-XAI/XAIBase.jl/branch/main/graph/badge.svg
[cov-url-base]: https://codecov.io/gh/Julia-XAI/XAIBase.jl
[cov-bdg-txth]: https://codecov.io/gh/Julia-XAI/TextHeatmaps.jl/branch/main/graph/badge.svg
[cov-url-txth]: https://codecov.io/gh/Julia-XAI/TextHeatmaps.jl
[cov-bdg-vish]: https://codecov.io/gh/Julia-XAI/VisionHeatmaps.jl/branch/main/graph/badge.svg
[cov-url-vish]: https://codecov.io/gh/Julia-XAI/VisionHeatmaps.jl