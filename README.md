# homebrew-tap

Homebrew formulae for [Pini Shvartsman](https://pinishv.com)'s tools.

## Install

```bash
brew install pinishv/tap/aidentity
```

Or tap once and use the short name:

```bash
brew tap pinishv/tap
brew install aidentity
```

## What's here

| Formula | What it does |
|---|---|
| [`aidentity`](Formula/aidentity.rb) | Run several accounts of the same Mac app at the same time — [repo](https://github.com/PiniShv/aidentity) |

## Why a tap and not homebrew-core

`homebrew-core` has notability requirements a brand-new project does not meet,
and it generally declines single-script tools without wider adoption. A tap is
the normal home for a formula until then.

The formula pins the `sha256` of a tagged release, so what you install is fixed
at review time rather than whatever `main` happens to hold.

## Licence

Each formula installs software under its own licence. The formulae are MIT.
