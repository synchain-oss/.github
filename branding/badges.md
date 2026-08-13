# Badge 模板 / Badge template

> 三仓库 README 的 badge 行必须**同顺序、同风格**(`flat-square`),仅仓库名与专属 badge 不同。复制后把 `<repo>` 替换为实际仓库名。
> All three repositories' README badge lines must share the same order and style (`flat-square`); only the repo name and repo-specific badges differ. Replace `<repo>` with the actual repo name.

## SCVB / Bridge

```markdown
<!-- SCVB / Bridge -->
[![License](https://img.shields.io/github/license/synchain-oss/<repo>?style=flat-square)](LICENSE)
[![Build](https://img.shields.io/github/actions/workflow/status/synchain-oss/<repo>/build-vst3.yml?branch=dev&style=flat-square&label=build)](../../actions)
[![pluginval](https://img.shields.io/badge/pluginval-strictness%205-brightgreen?style=flat-square)](https://github.com/Tracktion/pluginval)
[![Release](https://img.shields.io/github/v/release/synchain-oss/<repo>?style=flat-square)](../../releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%20x64%20%C2%B7%20VST3-blue?style=flat-square)](#requirements)
```

## CLI(额外 / 替换 / additions / replacements)

```markdown
[![npm](https://img.shields.io/npm/v/@synchain/cli?style=flat-square)](https://www.npmjs.com/package/@synchain/cli)
[![node](https://img.shields.io/node/v/@synchain/cli?style=flat-square)](#requirements)
```

## 约定 / Rules

- 不放 star/fork 数 badge(噪音,且开源初期数字难看)。/ No star/fork count badges (noise, and unflattering early on).
- `Platform` badge 在 macOS 支持落地前写 `Windows x64 · VST3`(D1:Windows 先行),不预告未实现的支持。/ Until macOS support lands, `Platform` reads `Windows x64 · VST3` (D1: Windows first); do not advertise unimplemented support.
