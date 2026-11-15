# nuclei

[中文版本](./README.cn.md)

Nuclei is a fast, customizable vulnerability scanner powered by the global security community and built on a simple YAML-based DSL, enabling collaboration to tackle trending vulnerabilities on the internet. It helps you find vulnerabilities in your applications, APIs, networks, DNS, and cloud configurations.

[![x-cmd/install — nuclei Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/nuclei.svg)](https://x-cmd.com/install/nuclei)

## Install

```sh
x install nuclei
```

## Code insight

Total: **164,835** lines of code across **1404** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 151,040 | 17,471 | 22,448 | 1064 |
| Yaml | 8,205 | 445 | 1,106 | 295 |
| Json | 3,224 | 0 | 1 | 7 |
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
- **Last commit**: 2026-11-14
- **Assets in release**: 9

## Popularity

- **Stars**: 32,927 · **Forks**: 4,005 · **Open issues**: 3,127 · **Contributors**: 290

## Totals (cumulative)

- **Releases**: 147 · **Merged PRs**: 2964 · **Open PRs**: 44 · **Closed issues**: 3066 · **Open issues**: 61 · **Commits**: 7184

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-16 | 0 | 94 | 24 | 97 | 19 | 191 |
| last60d | 2026-09-16 | 0 | 158 | 25 | 145 | 21 | 346 |
| 90d | 2026-08-17 | 0 | 191 | 25 | 165 | 23 | 448 |
| last180d | 2026-05-19 | 4 | 298 | 43 | 239 | 26 | 580 |
| 360d | 2025-11-20 | 10 | 478 | 44 | 380 | 29 | 845 |
| last720d | 2024-11-25 | 27 | 743 | 44 | 666 | 34 | 1717 |

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

Reported by **44** distros on [repology.org](https://repology.org/project/nuclei). **17** are ✅ on the latest upstream release, **23** are ⚠️ on an older version.

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

_Snapshot: `data/card/261115.yml` · 2026-11-15T06:13:09Z._
