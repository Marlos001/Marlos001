# Profile tooling

Reviewed October 21, 2026. The profile emphasizes experience rather than treating
public repository statistics as a complete account of someone's work.

## Tools used

### Skill Icons

[tandpfun/skill-icons](https://github.com/tandpfun/skill-icons) generates themed SVG
technology icons. The profile stores light and dark SVGs in this repository,
so viewing the profile does not depend on the live icon service. The icon list
reflects technologies used in project work, not a language-ranking algorithm.

- [Official usage and theme documentation](https://github.com/tandpfun/skill-icons#themed-icons)
- [MIT license](https://github.com/tandpfun/skill-icons/blob/7f7e691e71aec64e8354bf697835e009d1ad80f8/LICENSE)
- Local notice: `assets/LICENSE.skill-icons`.
- Generated from `skillicons.dev` with `i=ts,react,nodejs,postgres,docker,gcp,py,githubactions`,
  `perline=8`, and separate `light` and `dark` themes.

### Contribution artwork

[Platane/snk](https://github.com/Platane/snk) generates an animated SVG from a
GitHub user's contribution calendar. This is decoration, not a measure of
experience or a claim to count every private contribution.

The workflow runs daily at 09:17 UTC and can also be run manually. It generates
light and dark assets, validates both SVGs, and commits only when they change.
It is not triggered by pushes, so its own commits do not create a loop.

- [Official workflow instructions](https://github.com/Platane/snk#github-action)
- [Pinned action definition](https://github.com/Platane/snk/blob/d8f6715049803e982ee5ff501b6b9b7d5deeb09b/svg-only/action.yml)
- Generator: `Platane/snk/svg-only`, v3.5.0, pinned to its full commit SHA.
- Checkout: `actions/checkout`, v7.0.1, pinned to its full commit SHA.
- Authentication: GitHub's automatic, repository-scoped `GITHUB_TOKEN`.
- Permissions: contents write only for the artwork job in this profile repository.
- No personal access token or access to private source repositories is configured.

## Other projects considered

### lowlighter/metrics

[lowlighter/metrics](https://github.com/lowlighter/metrics) offers customizable
profile visualizations and plugins. It is an option for richer generated
statistics. Private-repository access and plugin output need an explicit review
before providing a token or publishing generated data. It is not configured here.

[Official setup documentation](https://github.com/lowlighter/metrics/blob/master/.github/readme/partials/documentation/setup/shared.md)

### GitHub Stats Extended

[stats-organization/github-stats-extended](https://github.com/stats-organization/github-stats-extended)
is the successor recommended by the original GitHub Readme Stats project.
It is a candidate for future cards, but public-only statistics are not a suitable
summary of primarily private work. No self-hosted instance or private-data token
has been configured.

[Original project's migration notice](https://github.com/anuraghazra/github-readme-stats#github-readme-stats)

### Original GitHub Readme Stats

[anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
currently states that it is no longer maintained. Its documentation also warns
that public cards omit private statistics by default, the public service can be
unreliable, and the language chart is not a measure of skill. It was not added.

## Content privacy

The experience summary describes broad engineering work from private projects.
It deliberately excludes private repository identifiers, client identities,
internal URLs, source code, financial figures, and unverified impact metrics.
The public-project section remains a sample, not a complete portfolio.
