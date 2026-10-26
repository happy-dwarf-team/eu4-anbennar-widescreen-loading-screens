# Anbennar – Widescreen Loading Screens

[![Steam Workshop](https://img.shields.io/badge/Steam%20Workshop-Widescreen%20Loading%20Screens-1b2838?logo=steam)](https://steamcommunity.com/sharedfiles/filedetails/?id=3686212690)
[![Latest release](https://img.shields.io/github/v/release/happy-dwarf-team/eu4-anbennar-widescreen-loading-screens)](https://github.com/happy-dwarf-team/eu4-anbennar-widescreen-loading-screens/releases/latest)
[![License: MIT](https://img.shields.io/github/license/happy-dwarf-team/eu4-anbennar-widescreen-loading-screens)](LICENSE)

A Europa Universalis IV mod for [Anbennar](https://steamcommunity.com/sharedfiles/filedetails/?id=1385440355)
that makes its loading screens look good on widescreen monitors. It replaces
Anbennar's 32 loading screens in `gfx/loadingscreens` with upscaled versions
(3440 × 2580).

- Needs Anbennar ("Anbennar: A Fantasy Total Conversion" or the
  Anbennar-PublicFork) and EU4 1.37.
- Changes only images in `gfx/loadingscreens`, none of EU4's checksummed files,
  so the mod does not change the game's checksum on its own.

## Install

Subscribe on the
[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3686212690)
and enable it in the Paradox launcher in the same playset as Anbennar. The mod
lists Anbennar as a dependency, so the launcher loads it after Anbennar.

## Development

- [`src/`](src) is the mod folder: `descriptor.mod`, the thumbnail and the
  loading screens.
- Pull requests use [Conventional Commits](https://www.conventionalcommits.org/)
  titles. [release-please](https://github.com/googleapis/release-please) keeps
  a release pull request; merging it bumps `version` in `src/descriptor.mod`,
  updates `CHANGELOG.md` and drafts a GitHub release.
- Every pull request gets a dry-run preview of the Workshop upload
  (`workshop-preview.yml`), and publishing the GitHub release uploads the mod
  with [paradox-workshop-publish](https://github.com/happy-dwarf-team/paradox-workshop-publish)
  (`workshop-publish.yml`, configured in [`workshop.toml`](workshop.toml)) and
  asks [happydwarf.dev](https://happydwarf.dev/) to rebuild (`website.yml`).

## License

MIT, see [LICENSE](LICENSE). The loading screens are upscaled from Anbennar's
own. Unofficial community project, not affiliated with Paradox Interactive or
the Anbennar team.
