<div align="center">
    <h1>【 end_4's Hyprland dotfiles PR 】</h1>
    <h3>Custom Fork with Community Pull Requests Integration</h3>
</div>

<div align="center"> 

![](https://img.shields.io/github/last-commit/farhhh/dots-hyprland-PR?&style=for-the-badge&color=8ad7eb&logo=git&logoColor=D9E0EE&labelColor=1E202B)
![](https://img.shields.io/github/stars/farhhh/dots-hyprland-PR?style=for-the-badge&logo=andela&color=86dbd7&logoColor=D9E0EE&labelColor=1E202B)
![](https://img.shields.io/github/repo-size/farhhh/dots-hyprland-PR?color=86dbce&label=SIZE&logo=protondrive&style=for-the-badge&logoColor=D9E0EE&labelColor=1E202B)

</div>

<div align="center">
    <h2>• overview •</h2>
    <h3></h3>
</div>

> [!NOTE]  
> Это форк оригинальной сборки [dots-hyprland от end-4](https://github.com/end-4/dots-hyprland).
> Главная цель этого репозитория — внедрение понравившихся мне пулл-реквестов от сообщества.
> Please write your pull requests! I'll review them all, and if I like them and they work well, I'll definitely add them!

<details> 
  <summary>What this is/isn't</summary>

  - Technically, configuration files
  - Realistically, mostly the custom graphical shell
  - NOT a system setup script: no graphic drivers, no zram setup, etc.
  
</details>

<details> 
  <summary>Notable features</summary>
     
  - **Community PRs**: Active integration of fixes and features from community PRs
  - **Overview**: Shows open apps with live previews
  - **AI**: Gemini, Ollama, and more
  - **QoL**: screen translation, anti-flashbang, Google Lens
  - **Material themes**: Choose your wallpaper, done, enjoy
  - **Transparent installation**: Every command is shown before it's run
</details>

<details> 
  <summary>Installation</summary>

   - **IMPORTANT: Hyprland 0.55 Update**: If your distro has not shipped Hyprland 0.55 and/or you're not ready for it, you should switch to the Pre-Hyprland Luaification release. See [the wiki](https://ii.clsty.link/en/ii-qs/01setup/) for more info
   - Clone this repo and run `./setup install`:
     ```bash
     git clone [https://github.com/farhhh/dots-hyprland-PR.git](https://github.com/farhhh/dots-hyprland-PR.git)
     cd dots-hyprland-PR
     ./setup install
     ```
   - **Keybinds**: Should be somewhat familiar to Windows or GNOME users. Important ones:
     - `Super`+`/` = keybind list
     - `Super`+`Enter` = terminal

</details>

<details>
  <summary>Software overview</summary>

  | Software | Purpose |
  | ------------- | ------------- |
  | [Hyprland](https://github.com/hyprwm/hyprland) | The compositor (manages and renders windows) |
  | [Quickshell](https://quickshell.outfoxxed.me/) | A QtQuick-based widget system, used for the status bar, sidebars, etc. |
  | Others | See [deps-info.md](https://github.com/end-4/dots-hyprland/blob/main/sdata/deps-info.md) |

</details>

<div align="center">
    <h2>• screenshots •</h2>
    <h3></h3>
</div>

<div align="center">
    <img src="assets/illogical-impulse.svg" alt="illogical-impulse logo" style="float:left; width:400;">
</div>

Widget system: Quickshell | Support: Yes

[Showcase video](https://www.youtube.com/watch?v=RPwovTInagE)

| AI, settings app | Some widgets |
|:---|:---------------|
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5d4e7d07-d0b4-4406-a4c9-ed7ba90e3fe4" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6a32395f-9437-4192-8faf-2951a9e84cbe" /> |
| Window management | wow look its orange |
| <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c51bed8b-3670-4d4c-9074-873be224fb8e" /> | <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/98703a66-0743-439f-a721-cef7afa6ab95" /> |

<div align="center">
    <h2>• credits & thank you •</h2>
    <h3></h3>
</div>

 - [@end-4](https://github.com/end-4) for creating the amazing original dots-hyprland repository
 - [@clsty](https://github.com/clsty) for making the dotfiles accessible by taking care of the install script and many other things
 - [@midn8hustlr](https://github.com/midn8hustlr) for greatly improving the color generation system
 - [@outfoxxed](https://github.com/outfoxxed/) for being extremely supportive in my Quickshell journey
 - Quickshell: [Soramane](https://github.com/caelestia-dots/shell/), [FridayFaerie](https://github.com/FridayFaerie/quickshell), [nydragon](https://github.com/nydragon/nysh)
 - AGS: [Aylur](https://github.com/Aylur/dotfiles/tree/ags-pre-ts), [kotontrion](https://github.com/kotontrion/dotfiles)
 - EWW: [fufexan](https://github.com/fufexan/dotfiles)

<div align="center">
    <h2>• inspirations/copying •</h2>
    <h3></h3>
</div>

 - Inspiration: Material Design 3
 - Copying: Absolutely, feel free. Just follow the license and it's all good