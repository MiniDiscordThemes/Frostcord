[screenshot1]:      https://cdn.discordapp.com/attachments/1142305515439923260/1144660960062214186/frostcord-user.png
[screenshot2]:      https://cdn.discordapp.com/attachments/1142305515439923260/1144660960397770813/frostcord-thread.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-bd-dl]:     https://img.shields.io/github/downloads/MiniDiscordThemes/Frostcord/Frostcord.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/Frostcord/net.saltssaumure.Frostcord.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/Frostcord?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/Frostcord
[issues]:           https://github.com/MiniDiscordThemes/Frostcord/issues
[license]:          https://github.com/MiniDiscordThemes/Frostcord/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/Frostcord/blob/main/Frostcord.theme.css

[frostcord]:        https://github.com/intergrav/frostcord
[author-frostcord]: https://github.com/intergrav
[license-frostcord]:https://github.com/intergrav/frostcord/blob/main/LICENSE

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.Frostcord "Replugged store page"
[release-bd-gh]:    https://github.com/MiniDiscordThemes/Frostcord/releases/latest/download/Frostcord.theme.css "Get latest release"
[release-rp-gh]:    https://github.com/MiniDiscordThemes/Frostcord/releases/latest/download/net.saltssaumure.Frostcord.asar "Get latest release"

# Frostcord Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-bd-dl]][release-bd-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***Translucent blur for overlay backgrounds.***

| User popout                                              | Thread browser                                              |
| -------------------------------------------------------- | ----------------------------------------------------------- |
| ![Screenshot of user popout with Frostcord][screenshot1] | ![Screenshot of thread browser with Frostcord][screenshot2] |

## Installation

### [BetterDiscord][BetterDiscord]
1. Download `Frostcord.theme.css`:
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.

### [Replugged][Replugged]
#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.Frostcord.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.

### [Vencord][Vencord]
#### Local
1. Download `Frostcord.theme.css`:
    - [GitHub][release-bd-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/Frostcord/Frostcord.theme.css`

## Customisation

| Description   | Variable name         | Valid values              | Default value |
| ------------- | --------------------- | ------------------------- | ------------- |
| Blur distance | `--frostcord-blur`    | Any [length][css-length]. | `16px`        |
| Opacity       | `--frostcord-opacity` | Any percentage.           | `80%`         |

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
2. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-19 of [`Frostcord.theme.css`][.theme.css].
4. Edit the variable values and save.

### Vencord
#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `Frostcord.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-19 of [`Frostcord.theme.css`][.theme.css].
3. Edit the variable values.

## License
[MIT License][license]

### Includes
- [Frostcord][frostcord] by [Devin][author-frostcord] - [MIT License][license-frostcord]

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].