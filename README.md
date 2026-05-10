# Jarema's dotfiles
This repository contains configuration files and settings for apps I use.

## Apps

### System
*   **[zsh](./zsh) & [bash](./bash)**: shell configs
*   **[Git](./git)** config
*   **[SSH](./ssh)** configs

### Code editors
*   **[Visual Studio Code](./Code)**: keybinds and QoL settings
*   **[Zed](./zed)** [(website)](https://zed.dev): usability settings

### Browsers
*   **[Firefox](./firefox)**: hardening configs
*   **[uBlock Origin](./ublock-origin)**: custom filters
*   **[Mullvad Browser](./Mullvad)**: extension settings

### Social
*   **[Vesktop](./dev.vencord.Vesktop)** & **[Equibop](./equibop)** : settings for custom Discord clients
*   **[SchildiChat Revenge](./SchildiChatRevenge)** [(website)](https://schildi.chat): preferences for a Matrix client
*   **[Beeper](./BeeperTexts)** [(website)](https://beeper.com): configs for a Matrix chat app

### Media
*   **[Komikku](./info.febvre.Komikku)**\: settings keyfile for a comics reader
*   **[NewsFlash](./io.gitlab.news_flash.NewsFlash)** [(website)](https://gitlab.com/news-flash/news_flash_gtk): preferences for a RSS reader
*   **[Mission Center](./io.missioncenter.MissionCenter)** [(website)](https://gitlab.com/mission-center-devs/mission-center): settings keyfile for a system monitor
*   **[Gear Lever](./it.mijorus.gearlever)** [(website)](https://github.com/mijorus/gearlever): configs for an AppImage manager
*   **[Sober](./org.vinegarhq.Sober)** & **[Lunar Client](./.lunarclient)**: settings for game clients
*   **[YouTube Music](./YouTube%20Music)**: configs for a YouTube Music desktop player

## Usage

I haven't made an installation script yet, but you can symlink or copy these files to your system manually.

### Paths

*   zsh, bash, git: Directly in your home directory (`~/.zshrc`, `~/.bashrc`, `~/.gitconfig`).
*   ssh: The `.ssh` folder directly in your home directory.
*   **Code editors**:
    *   VSCode: `~/.config/Code/User/` (native) or `~/.var/app/com.visualstudio.code/config/Code/User/` (Flatpak).
    *   Zed: `~/.config/zed/`.
*   **Browsers & extensions**:
    *   Firefox: Profile configs are in `~/.mozilla/firefox/<profile>/`. Firefox configs go in `/usr/lib64/firefox/`.
        *   If using Zen Browser, the profile path is `~/.zen/<profile>/`. You only need to extract `user.js`.
    *   uBlock Origin: Restore from the backup file in the extension's settings UI.
    *   Mullvad Browser extension: Import settings directly through the extension's UI.
*   **Other apps**:
    *   Equibop: `~/.config/equibop/`.
    *   SchildiChat Revenge: `~/.config/SchildiChatRevenge/`.
    *   Beeper: `~/.config/BeeperTexts/`.
    *   YouTube Music: `~/.config/YouTube Music/`.
*   **Flatpaks**: For most Flatpak apps (Vesktop, Komikku, NewsFlash, Mission Center, Gear Lever, Sober, etc.), settings go into their respective app data folders: `~/.var/app/<app-id>/`.

## License
This repository is licensed under GPLv3, see [LICENSE](./LICENSE).
