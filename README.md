<div align="center">

## Puppy's Arch Hyprland Install Script

![GitHub Repo stars](https://img.shields.io/github/stars/PuppyAnimations/Arch-Hyprland?style=for-the-badge&color=cba6f7) ![GitHub last commit](https://img.shields.io/github/last-commit/PuppyAnimations/Arch-Hyprland?style=for-the-badge&color=b4befe) ![GitHub repo size](https://img.shields.io/github/repo-size/PuppyAnimations/Arch-Hyprland?style=for-the-badge&color=cba6f7)

<br/>
</div>

#### ✨ Installatation Instructions
> clone this repo (latest commit only) to reduce file size download by using git. Change directory, make executable and run the script:
```bash
git clone --depth=1 https://github.com/JaKooLit/Arch-Hyprland.git ~/Arch-Hyprland
cd ~/Arch-Hyprland
chmod +x install.sh
./install.sh
```

<br/>
</div>

#### Hyprland-Dots-Showcase 
<p align="center">
    <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-ScreenShots/Arch-v2/Arch-Default-Layout.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/dark-theme.png" />   
   <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/Light-theme.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-ScreenShots/Arch-v2/Another-Screenshot.png"" /> 
</p>

<p align="center">
    <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/default-waybar.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/rofi.png" />   
   <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/wlogout-dark.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/showcase2.png"" /> 
   <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/waybar-layout.png" /> <img align="center" width="49%" src="https://raw.githubusercontent.com/JaKooLit/screenshots/main/Hyprland-Dots-Showcase/waybar-style.png"" /> 
</p>

<p align="center">
    <img align="center" width="100%" src="https://raw.githubusercontent.com/JaKooLit/Arch-Hyprland/main/Installer.png" />

### 🪧🪧🪧 ANNOUNCEMENT 🪧🪧🪧
- This Repo does not contain Hyprland Dots or configs! Dotfiles can be checked here [Hyprland-Dots](https://github.com/PuppyAnimations/Hyprland-Dots). During installation, if you opt to copy installation, it will be downloaded from that centralized repo.
- Hyprland-Dots use are constantly evolving / improving. you can check CHANGELOGS here [Hyprland-Dots-Changelogs](https://github.com/PuppyAnimations/Hyprland-Dots/wiki/Changelogs).
- the wallpapers offered to be downloaded towards the end is from this [REPO](https://github.com/PuppyAnimations/Wallpaper-Bank).

> [!WARNING] 
> Download this script on a directory where you have write permissions. ie. HOME. Or any directory within your home directory; else the script will fail.

#### 🆕  Prerequisites
- This install script is intended for atleast Server type / Minimal Arch Linux installed.

#### 🔘 Pipewire and Pipewire audio
- This script will install pipewire and will also disable or will uninstall pulseaudio. If you dont want it, you can simply just delete pipewire.sh in install-scripts folder before installing. 

#### ✨ Costumize the packages to be installed
- Inside the install-scripts folder, you can edit 00-hypr-pkgs.sh. Be careful though as the Hyprland Dots may not work properly!
- Default GTK theme if agreed to be installed is Tokyo Night GTK themes (dark and light) + Tokyo Night SE icons.

#### 💫 SDDM and GTK Themes
- If you opted to install SDDM theme, here's the [SDDM-Theme](https://github.com/PuppyAnimations/SDDM-Theme).
- If you opted to install GTK Themes, Icons and Cursor offered are Tokyo Nights. [GTK-Themes](https://github.com/PuppyAnimations/GTK-Themes) & Bibata Cursor Modern Ice.

#### 👀 NVidia GPU Owners.
- By default, nvidia-dkms will be installed. and only supports GTX 900 and newer. If required to install older driver, edit the nvidia.sh in scripts-folder
> [!IMPORTANT]
> If you want to use nouveau driver, choose N when asked if you have nvidia gpu. This is because the nvidia installer part, it will blacklist nouveau. Hyprland will still be installed but it will skip blacklisting nouveau.

#### ✨ for ZSH and OH-MY-ZSH installation
> installer should auto change your default shell to zsh. However, if it does not, do this:
```bash
chsh -s $(which zsh)
zsh
source ~/.zshrc
```
- Reboot or logout
- By default agnoster theme is installed. You can find more themes from [OH-MY-ZSH-THEMES](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes).
- To change the theme, edit ~/.zshrc . Look for ZSH_THEME="desired theme".

#### ✨ TO DO once installation done and dotfiles copied
- Hyprland-Dots v1.0.0, initial boot file will attempt to apply GTK themes, cursor, and icons. You can tweak more using nwg-look (GTK-Settings) utility.
- SUPER H for HINT or click on the waybar HINT! Button.
- Head over to [FAQ](https://github.com/PuppyAnimations/Hyprland-Dots/wiki/FAQ) and [TIPS](https://github.com/PuppyAnimations/Hyprland-Dots/wiki/TIPS).

#### 🙋 Got a questions regarding the Hyprland Dots or configurations? 🙋
- Head over to the [WIKI](https://github.com/PuppyAnimations/Hyprland-Dots/wiki).

#### 🙋 Having issues or questions? 
- For the installation portion, please open issue on this repo.
- For the Hyprland dots / configuration, submit an issue [here](https://github.com/PuppyAnimations/Hyprland-Dots/issues).

#### 🔧 Proper way to re-installing a particular script from install-scripts folder
- CD into Arch-Hyprland Folder and then ran the below command. 
- I.e. `./install-scripts/gtk-themes` - For reinstall GTK Themes.

#### 🛣️ Roadmap:
- [ ] Possibly adding gruvbox themes, cursors, icons

#### ⚠️ some known issues
- Reports from members of my discord, states that some users of nvidia are getting stuck on sddm login. Credits to @Kenni. Fix stated was:
```  
 while in sddm press ctrl+alt+F2 or F3
log into your account
`lspci -nn`, find the id of your nvidia card
`ls /dev/dri/by-path` find the matching id
`ls -l /dev/dri/by-path` to check where the symlink points to 
)
```
- Add "env = WLR_DRM_DEVICES,/dev/dri/cardX" to the ENVvariables config (.config/hypr/UserConfigs/ENVariables.conf); X being where the symlink of the gpu points to
- More info from the [hyprland wiki](https://wiki.hyprland.org/FAQ/#my-external-monitor-is-blank--doesnt-render--receives-no-signal-laptop).

#### 🫥 Improving performance for Older Nvidia Cards using driver 470
  - ['SEE HERE`](https://github.com/JaKooLit/Hyprland-Dots/discussions/123#discussion-6035205)
  
#### 📒 Final Notes
- Join JaKooLit's discord channel [`Discord`](https://discord.gg/V2SJ92vbEN).
- Feel free to copy, re-distribute, and use this script however you want. Would appreciate if you give JaKooLit some love by crediting their work.

## 💖 Support
- a Star on my Github repos would be nice.
- Subscribe to JaKooLit's Youtube Channel [YouTube](https://www.youtube.com/@Ja.KooLit).
- You can also buy JaKooLit coffee through ko-fi.com or Coffee.com.

<a href='https://ko-fi.com/jakoolit' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy JaKooLit a Coffee at ko-fi.com' />

[!["Buy JaKooLit A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/JaKooLit)
