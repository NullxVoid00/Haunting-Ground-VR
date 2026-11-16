# Haunting Ground VR

**In development · No public mod release yet · PC VR**

Step into Fiona's world with a tracked first-person viewpoint, visible body and hands, physical door handles, and a journal you can hold and touch. The project builds on **OpenHuey**, with a dedicated Windows installer and launcher.

[Future downloads & release notes](https://github.com/NullxVoid00/Haunting-Ground-VR/releases) · [Report an issue](https://github.com/NullxVoid00/Haunting-Ground-VR/issues) · [Abyssal Light Games](https://nullxvoid00.github.io/)

## Release status

This is the public project and future release hub. **There is no downloadable mod build published here yet.** The repository currently contains project information and release documentation; GitHub's **Code → Download ZIP** downloads those documents, not an installable mod.

When a build is ready, its installer or archive, supported game version, controls, installation steps and known issues will be published under [Releases](https://github.com/NullxVoid00/Haunting-Ground-VR/releases). Use **Watch → Custom → Releases** to follow future downloads. No release date is announced.

## What is being developed

| Area | Current development work |
| --- | --- |
| **Presence and movement** | Stereo rendering and head tracking have been confirmed in a Quest session. The development build includes body following, tracked hands, height calibration and smooth/snap turning. |
| **Physical interaction** | Door-handle grips, held-item interactions and contact feedback are implemented in the development build. |
| **Journal and map** | Shoulder retrieval, two-handed holding choices and fingertip selection of printed journal tabs are implemented. |
| **Original adventure** | Native movement, panic/stamina rules, Hewie button commands, dialogue and save systems remain part of the experience. |
| **Setup** | The local installer supports install/repair, headset checks and launching, using the player's own ISO. |

## Target setup

- **Game / platform:** Windows PC and your own Haunting Ground USA disc image (SLUS-21075), used by the OpenHuey-based runtime.
- **VR setup:** An OpenXR-capable PC VR connection and tracked controllers. Quest 3 through Virtual Desktop / VDXR is the documented headset test path; other runtime paths require validation.
- **Game ownership:** Supply your own required game files. No commercial game data, ROM, disc image, BIOS or save data is provided by this repository.

## Development controls

These are the current documented starting mappings, not a finalized release manual. The instructions shipped with a future build take precedence.

| Input | Action |
| --- | --- |
| Left / right stick | Move / turn |
| A / B | Run or confirm / kick or back |
| Right trigger / door-handle grip | Interact / manipulate a supported door |
| Right / left shoulder + grip | Journal / map |
| Right stick click | Recalibrate seated or standing height |
| X / left trigger / left grip | Hewie wait / go-check-attack / come |

## Known limitations and next work

- Recent journal, finger-contact, door and body changes need further headset comfort and alignment testing.
- Runtime/render spikes remain under investigation.
- Complete-game coverage, every bonus mode and all alternate OpenXR runtime paths have not been verified.
- Voice commands and expanded petting/gesture interactions for Hewie are not advertised as completed features.

Builds, automated checks and desktop captures do not by themselves establish headset comfort, full-game compatibility or a release-ready experience. The descriptions above distinguish implemented development work from unfinished work.

## Installing a future release

Installation instructions will accompany each published build. Until then, there is no supported public installation procedure or binary to download from this repository. Game-version and runtime requirements may change as development continues.

## Feedback

Use [Issues](https://github.com/NullxVoid00/Haunting-Ground-VR/issues) for questions or reports. For a future build, include its version, game version, headset/runtime and clear reproduction steps. Remove personal paths and private information from logs, and do not attach game files or saves.

## Credits

VR project by **NullxVoid / Abyssal Light Games**. This is an unofficial fan project and is not affiliated with or endorsed by the original game's creators or publishers.

- [OpenHuey — ArnautDaniel](https://github.com/ArnautDaniel/OpenHuey) — Native Haunting Ground reconstruction used as the foundation.
- [OpenXR SDK](https://github.com/KhronosGroup/OpenXR-SDK) — OpenXR development foundation.

Original games, names and assets belong to their respective owners. Upstream code and dependencies retain their own licenses. Future distributions will include the applicable notices and source obligations; this documentation hub does not relicense upstream or game material.

## Maintaining releases

See the [release guide](docs/RELEASE_GUIDE.md) and [release notes template](docs/RELEASE_TEMPLATE.md).

*Project information reviewed 2026-11-16 against local development documentation. This date is not a release or headset-certification date.*
