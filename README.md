# nuclei

[中文版本](./README.cn.md)

Nuclei is a fast, customizable vulnerability scanner powered by the global security community and built on a simple YAML-based DSL, enabling collaboration to tackle trending vulnerabilities on the internet. It helps you find vulnerabilities in your applications, APIs, networks, DNS, and cloud configurations.

[![x-cmd/install — nuclei Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/nuclei.svg)](https://x-cmd.com/install/nuclei)

## Install

```sh
x install nuclei
```

## Code insight

Total: **168,382** lines of code across **1419** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 154,582 | 18,097 | 23,142 | 1079 |
| Yaml | 8,205 | 445 | 1,106 | 295 |
| Json | 3,225 | 0 | 1 | 7 |
| TypeScript | 1,616 | 3,095 | 1,350 | 37 |
| Makefile | 252 | 11 | 40 | 1 |

## OpenSSF Scorecard

Overall score: **6.4 / 10**

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
- **Last commit**: 2026-11-20
- **Assets in release**: 9

## Popularity

- **Stars**: 33,161 · **Forks**: 4,048 · **Open issues**: 3,190 · **Contributors**: 296

## Totals (cumulative)

- **Releases**: 147 · **Merged PRs**: 3001 · **Open PRs**: 57 · **Closed issues**: 3104 · **Open issues**: 86 · **Commits**: 7278

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-22 | 0 | 118 | 35 | 122 | 46 | 250 |
| last60d | 2026-09-22 | 0 | 185 | 38 | 174 | 48 | 405 |
| 90d | 2026-08-23 | 0 | 226 | 38 | 197 | 50 | 507 |
| last180d | 2026-05-25 | 4 | 330 | 56 | 273 | 52 | 639 |
| 360d | 2025-11-26 | 10 | 508 | 57 | 412 | 54 | 904 |
| last720d | 2024-12-01 | 27 | 776 | 57 | 695 | 59 | 1799 |

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

Reported by **45** distros on [repology.org](https://repology.org/project/nuclei). **17** are ✅ on the latest upstream release, **24** are ⚠️ on an older version.

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

_Snapshot: `data/card/261121.yml` · 2026-11-21T06:56:20Z._
