# Albatross Pre-release 1.0.0

⚠️ This theme is still underdevelopment and bugs **WILL** occur.

[![License](https://img.shields.io/github/license/albatrosscreative/albatross-discord?style=for-the-badge&labelColor=404c5a&color=0a4d41)](license)
[![Stars](https://img.shields.io/github/stars/albatrosscreative/albatross-discord?style=for-the-badge&labelColor=404c5a&color=0a4d41)](https://github.com/albatrosscreative/albatross-discord/stargazers)
[![vencord](https://img.shields.io/badge/vencord-mod?style=for-the-badge&color=404c5a)](https://vencord.dev)
[![betterdiscord](https://img.shields.io/badge/betterdiscord-mod?style=for-the-badge&color=404c5a)](https://vencord.dev)
[![Sulfide](https://img.shields.io/badge/sulfide-language?style=for-the-badge&color=404c5a)](https://github.com/LeafyLuigi/sulfide)
![replugged](https://img.shields.io/badge/replugged%20not%20supported-language?style=for-the-badge&color=404c5a)

- [Albatross Pre-release 1.0.0](#albatross-pre-release-100)
	- [Disclaimers](#disclaimers)
	- [Palettes](#palettes)
	- [Changelog](#changelog)
		- [Pre-release v0.1.0 - 2025-06-11](#pre-release-v010---2025-06-11)
			- [Official Release](#official-release)
	- [Known Bugs](#known-bugs)
		- [Scrolling issues](#scrolling-issues)
	- [Roadmap](#roadmap)
	- [Getting Started](#getting-started)
		- [Installation](#installation)
		- [Option 1 - Download theme.css file](#option-1---download-themecss-file)
		- [Option 2 - CSS Import](#option-2---css-import)
			- [1. Base Import](#1-base-import)
			- [2. Palette](#2-palette)
		- [Option 3 - Local Installation \& Setup](#option-3---local-installation--setup)
			- [1. Clone Repository](#1-clone-repository)
			- [2. Go to project folder](#2-go-to-project-folder)
			- [3. Install dependencies](#3-install-dependencies)
			- [4. Scripts](#4-scripts)
	- [Usage](#usage)
		- [Changing palettes](#changing-palettes)
			- [Quick CSS \& via `albatross.theme.css`](#quick-css--via-albatrossthemecss)
	- [Wiki](#wiki)
	- [Contributors](#contributors)
	- [Credits](#credits)
	- [License](#license)

## Disclaimers

⚠️Theme Attributes MUST be turned on for Albatross to function properly. Thank you**

## Palettes

| ![Image](https://github.com/user-attachments/assets/e604ea2a-f5bf-4c41-abce-85e626018624)  | ![Image](https://github.com/user-attachments/assets/9647a40e-0697-456b-8dc5-e7af5067939b)  | ![Image](https://github.com/user-attachments/assets/a33ad952-ec3d-441f-a975-e20b96f8b684) |
| :---: | :---: | :---: |
|**Nord**| **CreArts** | **HeroUI**  |
| ![Image](https://github.com/user-attachments/assets/a9f1dd72-38c0-46c8-9dbb-531ac87ba2b9) | ![Image](https://github.com/user-attachments/assets/69f1f5a3-f88b-4aba-8f79-101eef4bd2f8) | ![Image](https://github.com/user-attachments/assets/94bbc155-b705-412e-807b-087fb6e3c80f) |
|**Miyu**| **Comet** | **Dracula**  |

## [Changelog](/changelog.md)

All notable changes to this project will be documented in this file. Visit [changelog.md](/changelog.md) to view the full code history.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

### Pre-release [v0.1.0](https://github.com/AlbatrossCreative/Albatross-Discord/releases) - 2025-06-11

[Download alabtross.theme.css](https://github.com/AlbatrossCreative/Albatross-Discord/releases)

#### Official Release

Officially begun tracking changes and fixes within Albatross. Still expect bugs, and unthemed elements

## Known Bugs

### Scrolling issues

Due to Discords lazy loading being programmed with fixed height dimensions for its scrolling elements, it will break while using Albatross when scrolling to the bottom of a scroller, or scrolling to a specific point in the scrollbar. I am currently working on a fix.

Spot a bug? Make an [Issue](https://github.com/AlbatrossCreative/Albatross-Discord/issues)

## Roadmap

Heres a list of features im planning on adding soon.

**🟢 Minor 🟡 Moderate 🔴 Major**

| **Urgency** |    **Feature**     |
| :---------: | :----------------: |
|      🔴      | Light mode support |
|      🟢      | Add more Palettes  |
|      🔴      | Nitro customization support |
|  🟡 | Add more plugin support |

## Getting Started

### Installation

Please ensure Discord is installed with your choosing of the client mods below.

<div class="tg-wrap">
	<table>
		<thead>
			<tr>
				<th>Client Mods</th>
				<th>Discord Builds</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td align=center>
					<a href="https://betterdiscord.app/" target="_blank" rel="noopener noreferrer"
						><img
						src="https://discord-extensions.github.io/assets/icons/betterdiscord.png"
						alt="Image"
						width="15"
						height="15"
					/> <span >Better Discord (Buggy)</span></a
					>
				</td>
				<td align=center>
					<a
						href="https://discord.com/api/downloads/distributions/app/installers/latest?platform=win&channel=canary&arch=x64"
						target="_blank"
						rel="noopener noreferrer"
						>Discord Canary</a
					>
				</td>
			</tr>
			<tr>
				<td align=center>
					<a href="https://vencord.dev/" target="_blank" rel="noopener noreferrer"
						><img
						src="https://discord-extensions.github.io/assets/icons/vencord.gif"
						alt="Image"
						width="14"
						height="14"
					/><span>Vencord</span></a
					><br />
				</td>
				<td align=center>
					<a
						href="https://discord.com/api/downloads/distributions/app/installers/latest?platform=win&channel=canary&arch=x64"
						target="_blank"
						rel="noopener noreferrer"
						>Discord Stable</a
					>
				</td>
			</tr>
			<tr>
				<td colspan="2" align=center>Replugged not supported</td>
			</tr>
		</tbody>
	</table>
</div>

### Option 1 - Download theme.css file

Easiest method to install Alabatross is to download [albatross.theme.css]() from the [releases]() page. Drag and drop it into your client mods theme folder.

 `BetterDiscord/themes` or `vencord/themes`

### Option 2 - CSS Import

#### 1. Base Import

- Copy and paste ALL the following links in your Quick CSS page. These are REQUIRED.

```css
@import url("https://albatrosscreative.github.io/Albatross-Discord/public/build/albatross-minified.css");
@import url('https://albatrosscreative.github.io/Albatross-Backend/theme/backend/albatross-vars.css');
```

#### 2. Palette

- Albatross also requires a palette of your choice to display properly. More palettes will be available in the future
  
```css
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/crearts.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/comet.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/nextui.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/dracula.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/miyu.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/nord.css'); */
```

###  Option 3 - Local Installation & Setup

I recommend doing this until Albatross has a normally functioning CDN to import through Quick CSS.

#### 1. Clone Repository

Use this command to clone the repository to your desired directory.

```cmd
git clone https://github.com/AlbatrossCreative/Albatross-Discord.git
```

#### 2. Go to project folder

```cmd
cd albatross-discord
```

#### 3. Install dependencies

```cmd
pnpm install
```

#### 4. Scripts

**Use** `pnpm` **to begin using Albatross based on your use choice.**

| Script    | Description                                                 |
| :-------- | :---------------------------------------------------------- |
| `buildVC` | Creates `new albatross.theme.css` to `vencord/themes`       |
| `buildBD` | Creates `new albatross.theme.css` to `betterdiscord/themes` |
| `compile` | Compile the current theme to `public/build/css`             |
| `devBD`   | Begin live development for BetterDiscord.                   |
| `devVC`   | Begin live development for Vencord.                         |

## Usage

### Changing palettes

Heres how to swap out your palettes based on which method youve installed Albatross.

#### Quick CSS & via `albatross.theme.css`

1. Open QuickCSS albatross.theme.css in your themes folder. (If you use BetterDiscord you can edit the file within the themes page)
2. Comment out the palettes you don't want.

```css
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/crearts.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/comet.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/nextui.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/dracula.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/miyu.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/nord.css'); */
```

3. Uncomment the palette you'd like. (Only 1 at a time)

```css
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/crearts.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/comet.css'); */
 @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/nextui.css'); 
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/dracula.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/miyu.css'); */
/* @import url('https://albatrosscreative.github.io/Albatross-Backend/theme/palettes/nord.css'); */
```


## [Wiki](https://github.com/albatrosscreative/albatross-discord/wiki)

The wiki contains information regarding Albatross's design system and development process. To contribute to Albatross please read the [contribution](https://github.com/albatrosscreative/albatross-discord/wiki) section of the wiki.

- [Albatross Wiki](https://github.com/albatrosscreative/albatross-discord/wiki)

## Contributors
If your wishing to contribute, it's important to note that this theme is developed using [Sulfide](https://github.com/LeafyLuigi/sulfide), Which is used throughout the theme and must be understood before attempting to deveolop with. Please read Sulfides [README](https://github.com/LeafyLuigi/sulfide/?tab=readme-ov-file#usage) for information on how to use sulfide. 

Please make an issue/pull request, or contact me in our [Discord Server](). Visit [contribution.md](/contribution.md) for more information on how to contribute to Albatross.

## Credits

Alabtross is inspired by and uses designs from the following projects. Albatross wouldnt be what is it without them

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
