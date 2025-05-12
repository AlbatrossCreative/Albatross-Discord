# Albatross 1.0

[![Version](https://img.shields.io/github/manifest-json/v/albatrosscreative/albatross-discord?style=for-the-badge&labelColor=404c5a&color=0a4d41)](.github/docs/changelog.md)
[![License](https://img.shields.io/github/license/albatrosscreative/albatross-discord?style=for-the-badge&labelColor=404c5a&color=0a4d41)](license)
[![Stars](https://img.shields.io/github/stars/albatrosscreative/albatross-discord?style=for-the-badge&labelColor=404c5a&color=0a4d41)](https://github.com/albatrosscreative/albatross-discord/stargazers)
[![vencord](https://img.shields.io/badge/vencord-mod?style=for-the-badge&color=404c5a)](https://vencord.dev)
[![betterdiscord](https://img.shields.io/badge/betterdiscord-mod?style=for-the-badge&color=404c5a)](https://vencord.dev)
[![Sulfide](https://img.shields.io/badge/sulfide-language?style=for-the-badge&color=404c5a)](https://github.com/LeafyLuigi/sulfide)

## Disclaimers

### ⚠️ This current build of Albatross is NOT complete and its official release will be completely different from its current release

### ⚠️Theme Attributes MUST be turned on for Albatross to function properly. Thank you**

Albatross is a fun project to help me understand sass more, alot of unnecessary scss styling throughout the theme, very little optimization, all compiled into one file. Enjoy!

- [Getting started](#getting-started)
- [Installation](#installation)

| Featured Palettes (Many More to Offer..)                                                  |                                                                                             |                                                                                            |
| ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| ![Comet](https://github.com/user-attachments/assets/863e5f6f-6d35-4548-969b-7b1f7c24267c) | ![CreArts](https://github.com/user-attachments/assets/65af82b6-1c47-44a4-b76f-a888ee1e4786) | ![NextUI](https://github.com/user-attachments/assets/f61ae4ba-11e8-4c37-a7c6-0bc6ad5ac79b) |
| **Comet (Default)**                                                                       | **CreArts**                                                                                 | **NextUI**                                                                                 |

## Getting Started

## Installation

Please ensure Discord is installed with your choosing of the client mods below.

| Client Mods |
|-------------|
| ![BetterDiscord](https://discord-extensions.github.io/assets/icons/betterdiscord.png) [Better Discord](https://betterdiscord.app/) |
| ![Vencord](https://discord-extensions.github.io/assets/icons/vencord.gif) [Vencord](https://vencord.dev/) |

| Discord Builds |
|-----------------|
| [Discord Canary](https://discord.com/api/downloads/distributions/app/installers/latest?platform=win&channel=canary&arch=x64) |
| [Discord Stable](https://discord.com/api/downloads/distributions/app/installers/latest?platform=win&channel=canary&arch=x64) |

### CSS Import

- Copy and paste the link in your Quick CSS page.

```css
@import url("https://albatrosscreative.github.io/Albatross-Discord/public/build/albatross.css");
```

## Local Installation & Setup

I recommend doing this until Albatross has a normally functioning CDN to import through Quick CSS.

### 1. Clone Repository

Use this command to clone the repository to your desired directory.

```cmd
git clone https://github.com/AlbatrossCreative/Albatross-Discord.git
```

### 2. Go to project folder

```cmd
cd albatross-discord
```

### 3. Install dependencies

```cmd
pnpm install
```

### 4. Development Scripts

**Use** `pnpm` **to begin using Albatross based on your use choice.**

| Script    | Description                                                 |
| :-------- | :---------------------------------------------------------- |
| `buildVC` | Creates `new albatross.theme.css` to `vencord/themes`       |
| `buildBD` | Creates `new albatross.theme.css` to `betterdiscord/themes` |
| `compile` | Compile the current theme to `public/build/css`             |
| `devBD`   | Begin live development for BetterDiscord.                   |
| `devVC`   | Begin live development for Vencord.                         |
| :-------- | :---------------------------------------------------------- |
| `buildVC` | Creates `new albatross.theme.css` to `vencord/themes`       |
| `buildBD` | Creates `new albatross.theme.css` to `betterdiscord/themes` |
| `compile` | Compile the current theme to `public/build/css`             |
| `devBD`   | Begin live development for BetterDiscord.                   |
| `devVC`   | Begin live development for Vencord.                         |

## [Wiki](https://github.com/albatrosscreative/albatross-discord/wiki)

The wiki contains information regarding Albatross's design system and development process. To contribute to Albatross please read the [contribution](https://github.com/albatrosscreative/albatross-discord/wiki) section of the wiki.

- [Albatross Wiki](https://github.com/albatrosscreative/albatross-discord/wiki)

## Notice For contributors

Before contributing to this project, please look through LeafyLuigi's [Sulfide](https://github.com/LeafyLuigi/sulfide) as this is the backend for how Albatross keeps its classes updated and maintained, and every file uses this system. So it'd be good to get familiar with it.

## Credits

Albatross is greatly inspired by these projects to make Albatross what it is today.

- **[CreArts](https://github.com/CreArts-Community/CreArts-Discord) by The [CreArts-Community](https://github.com/CreArts-Community)**
- **[RadialStatus](https://github.com/DiscordStyles/RadialStatus) by [DiscordStyles](https://github.com/DiscordStyles)**

## License

This project is under the **[GNU General Public License v3.0](https://spdx.org/licenses/GPL-3.0-or-later.html)**. Please refer to the [License](license) for further information regarding the license' permissions, limitations and conditions.

<br>
<br>
<div align="center">

Made with ♥️ by [Albatross Creative](https://github.com/albatrosscreative)

<small>Developed with <a href="https://github.com/LeafyLuigi/sulfide">Sulfide</a> by <a href="https://github.com/leafyluigi">LeafyLuigi</a></small>
</div>
