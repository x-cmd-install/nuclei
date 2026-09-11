# nuclei

[中文版本](./README.cn.md)

Nuclei is a fast, customizable vulnerability scanner powered by the global security community and built on a simple YAML-based DSL, enabling collaboration to tackle trending vulnerabilities on the internet. It helps you find vulnerabilities in your applications, APIs, networks, DNS, and cloud configurations.

![nuclei](https://repo.x-cmd.io/nuclei.svg)

## Install

```sh
x install nuclei
```

## Code insight

Total: **125,980** lines of code across **1184** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 112,597 | 13,550 | 17,547 | 855 |
| Yaml | 8,044 | 444 | 1,085 | 289 |
| Json | 3,166 | 0 | 1 | 7 |
| TypeScript | 1,437 | 2,556 | 1,208 | 32 |
| Makefile | 252 | 9 | 40 | 1 |

## OpenSSF Scorecard

Overall score: **6.8 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## Source

- **Upstream**: <https://github.com/projectdiscovery/nuclei>
- **Homepage**: <https://docs.projectdiscovery.io/tools/nuclei>
- **License**: MIT

## Release

- **Latest**: `v3.11.1` (2026-08-08)
- **Last commit**: 2026-09-10
- **Assets in release**: 9

## Popularity

- **Stars**: 31,115 · **Forks**: 3,856 · **Open issues**: 2,956 · **Contributors**: 256

## Totals (cumulative)

- **Releases**: 147 · **Merged PRs**: 2789 · **Open PRs**: 43 · **Closed issues**: 2900 · **Open issues**: 56 · **Commits**: 6540

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 27 | 13 | 13 | 5 | 44 |
| last60d | 2026-07-13 | 1 | 66 | 36 | 45 | 11 | 104 |
| 90d | 2026-06-13 | 3 | 103 | 40 | 63 | 13 | 141 |
| last180d | 2026-03-15 | 5 | 192 | 42 | 113 | 16 | 267 |
| 360d | 2025-09-16 | 12 | 364 | 43 | 265 | 17 | 549 |
| last720d | 2024-09-21 | 31 | 642 | 43 | 577 | 25 | 1173 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [nuclei_3.11.1_checksums.txt](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_checksums.txt) | 766 B | `other` |
| [nuclei_3.11.1_linux_386.zip](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_linux_386.zip) | 41.3 MiB | `other` |
| [nuclei_3.11.1_linux_amd64.zip](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_linux_amd64.zip) | 44.0 MiB | `native/linux/x64` |
| [nuclei_3.11.1_linux_arm.zip](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_linux_arm.zip) | 41.8 MiB | `native/linux/arm` |
| [nuclei_3.11.1_linux_arm64.zip](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_linux_arm64.zip) | 39.5 MiB | `native/linux/arm64` |
| [nuclei_3.11.1_macOS_amd64.zip](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_macOS_amd64.zip) | 45.0 MiB | `native/darwin/x64` |
| [nuclei_3.11.1_macOS_arm64.zip](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_macOS_arm64.zip) | 41.6 MiB | `native/darwin/arm64` |
| [nuclei_3.11.1_windows_386.zip](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_windows_386.zip) | 42.0 MiB | `native/win/x64` |
| [nuclei_3.11.1_windows_amd64.zip](https://github.com/projectdiscovery/nuclei/releases/download/v3.11.1/nuclei_3.11.1_windows_amd64.zip) | 43.9 MiB | `native/win/x64` |

## Distribution status

Reported by **43** distros on [repology.org](https://repology.org/project/nuclei). **13** are ✅ on the latest upstream release, **27** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `3.11.1` | ✅ latest |
| Fedora rawhide | `3.11.0` | ⚠️ outdated |
| Nix unstable | `3.11.1` | ✅ latest |
| Alpine edge | `3.11.0` | ⚠️ outdated |

## Improve this data

Install metadata for nuclei lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `nuclei` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/nuclei.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T20:32:03Z._
