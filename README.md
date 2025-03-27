# noidilin scoop bucket

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer. Currently contains:

- [ ] [vivid](https://github.com/sharkdp/vivid), a generator for the `LS_COLOR` environment variable that controls the colorized output of `ls`, `tree`, `fd`, `bfs`, `dust` and many other tools.

Manifests should be submit to extra bucket in the future.

[![Tests](https://github.com/noidilin/scoop/actions/workflows/ci.yml/badge.svg)](https://github.com/noidilin/scoop/actions/workflows/ci.yml)
[![Excavator](https://github.com/noidilin/scoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/noidilin/scoop/actions/workflows/excavator.yml)

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```sh
scoop bucket add noidilin https://github.com/noidilin/scoop.git
scoop install noidilin/vivid
```

## How do I contribute new manifests?

- [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
- [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
