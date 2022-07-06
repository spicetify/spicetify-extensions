# Spicetify Extensions

This repository holds the official list of all [Spicetify](https://github.com/spicetify/spicetify-cli) themes, a command-line tool to customize Spotify. If a theme is present here, then it will be present in Spicetify Marketplace.

> _Note_: Due to the development of Spicetify Marketplace, a game-changing addition to the Spicetify ecosystem, we are now shifting towards a more open-source friendly approach to theme development. This means that theme creators should now have the freedom to build their themes in a repository owned by them, rather than a repository owned by Spicetify.

> _Note_: Although in the past this repository held the whole code for themes, we are now simply holding the list of available themes. Think of it as an index of themes, or a Database _of sorts_.

You can add your own theme simply by opening a Pull Request (more info in [CONTRIBUTING.md](./CONTRIBUTING.md)).

### **You can find a preview of all the themes in [THEMES.md](./THEMES.md).**

## Notes:

- **These themes require that you have the latest version of Spotify and Spicetify.**
- **To install Dribbblish and Turntable themes, follow the instructions in their READMEs**.
- **Spotify ad-blocked version is not supported.**

## Installation and usage

(If you use Arch Linux you can find this project on the [AUR](https://aur.archlinux.org/packages/spicetify-themes-git/))

1.  Clone this repository. Make sure [git](https://git-scm.com/) is installed and run:

    ```bash
    git clone https://github.com/spicetify/spicetify-themes.git
    ```

2.  Copy the files into the [Spicetify Themes folder](https://spicetify.app/docs/development/customization#themes). Run:

    **Linux**

    ```bash
    cd spicetify-themes
    cp -r * ~/.config/spicetify/Themes
    ```

    **MacOS**

    ```bash
    cd spicetify-themes
    cp -r * ~/.config/spicetify/Themes
    ```

    **Windows**

    ```powershell
    cd spicetify-themes
    cp * "$(spicetify -c | Split-Path)\Themes\" -Recurse
    ```

3.  Choose which theme to apply just by running:
    ```bash
    spicetify config current_theme THEME_NAME
    ```
    Some themes have 2 or more different color schemes. After selecting the theme you can switch between them with:
    ```bash
    spicetify config color_scheme SCHEME_NAME
    ```

### Extra

The `_Extra` folder contains additional resources for tweaking the look of
Spotify. More info in its [README](./.Extra/README.md).

## Contributions

We've set up a separate document for our [contribution guidelines](./CONTRIBUTING.md).

## Troubleshooting

Do not open issues for general support questions as we want to keep GitHub issues for bug reports and feature requests. If you find problems when using or installing these themes, or you need help in modifying a theme then ask for suggestions on the [subreddit](https://www.reddit.com/r/spicetify/) or on the [Discord Server](https://discord.com/invite/VnevqPp2Rr).

Use GitHub issues ONLY for bugs and requesting new features.

If you are unsure about which channel to use, go for Reddit or Discord.

## Useful resources

- [Spicetify theme without free version UI elements (e.g. "Upgrade" button)](https://github.com/Daksh777/SpotifyNoPremium)
- [DribbblishDynamic theme for v2](https://github.com/JulienMaille/dribbblish-dynamic-theme)
