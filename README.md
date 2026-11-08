# Violet Evergarden Codex Pet

An unofficial, fan-made animated Codex pet inspired by Violet Evergarden. This repository preserves three artwork revisions, with v3 as the latest and default version.

这是一个非官方的薇尔莉特 Codex 动画宠物仓库，收录三个形象迭代版本，其中 v3 是最新默认版本。

![v3 animation contact sheet](docs/contact-sheet.png)

## Versions

The v1/v2/v3 labels describe the artwork revisions. All three packages use Codex sprite format v2.

v1/v2/v3 表示形象迭代版本；三个安装包均使用 Codex v2 图集格式。

| Revision | Design | Package | Preview |
| --- | --- | --- | --- |
| v3 (latest) | Compact proportions with a smaller suitcase and shortened folded parasol | [repository root](.) | [contact sheet](docs/contact-sheet.png) |
| v2 | Traveler design with a larger suitcase and folded parasol | [`versions/v2`](versions/v2) | [contact sheet](versions/v2/docs/contact-sheet.png) |
| v1 | Original chibi design without the travel props | [`versions/v1`](versions/v1) | [contact sheet](versions/v1/docs/contact-sheet.png) |

## Features

- Codex sprite format v2
- 1536 x 2288 transparent WebP atlas
- 9 standard animation states
- 16 clockwise look directions
- Validated 8 x 11 sprite layout

## Install

1. Download this repository with **Code -> Download ZIP** and extract it.
2. Choose the repository root for v3, `versions/v2` for v2, or `versions/v1` for v1.
3. Copy the chosen folder into the Codex pets directory and rename it as shown below.
4. Confirm `pet.json` and `spritesheet.webp` are directly inside the copied folder.
5. Restart Codex and select the pet.

| Revision | Windows destination | macOS/Linux destination |
| --- | --- | --- |
| v3 | `%USERPROFILE%\.codex\pets\violet-evergarden-chibi-prop-v3` | `$HOME/.codex/pets/violet-evergarden-chibi-prop-v3` |
| v2 | `%USERPROFILE%\.codex\pets\violet-evergarden-chibi-prop-v2` | `$HOME/.codex/pets/violet-evergarden-chibi-prop-v2` |
| v1 | `%USERPROFILE%\.codex\pets\violet-evergarden-chibi` | `$HOME/.codex/pets/violet-evergarden-chibi` |

## Preview

![Look directions](docs/look-directions.png)

Individual v3 animation previews are available in [`docs/previews`](docs/previews). The v1 and v2 direction previews are stored with their packages.

## Validation

All three packaged atlases pass the local Codex v2 atlas validator with no errors or warnings:

- [v3 validation](qa/validation.json)
- [v2 validation](versions/v2/qa/validation.json)
- [v1 validation](versions/v1/qa/validation.json)

SHA-256 checksums are listed in [`SHA256SUMS.txt`](SHA256SUMS.txt).

## Notice

This repository is an unofficial fan project and is not affiliated with or endorsed by the creators, publishers, or rights holders of *Violet Evergarden*. See [`NOTICE.md`](NOTICE.md). No open-source license is included.
