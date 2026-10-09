![WM](https://img.shields.io/badge/WM-I3-8caaee?style=for-the-badge&labelColor=414559)
![THEME](https://img.shields.io/badge/THEME-CATPPUCCIN%20FRAPP%C3%89-ca9ee6?style=for-the-badge&labelColor=414559)
![STARS](https://img.shields.io/github/stars/6aru/i3-EllenJoe?style=for-the-badge&label=STARS&color=81c8be&labelColor=414559)
![FORKS](https://img.shields.io/github/forks/6aru/i3-EllenJoe?style=for-the-badge&label=FORKS&color=e5c890&labelColor=414559)

> A Catppuccin Frappé–themed i3 setup — polybar, picom (blur + fading), ranger, starship, neofetch, lxterminal.

<div align="center">
    
<a href="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180230.png" target="_blank">
    <img src="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180230.png" width="48%" alt="i3 Tiled Layout" title="Lockscreen">
</a>
<a href="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180211.png" target="_blank">
    <img src="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180211.png" width="48%" alt="Polybar" title="i3wm & i3stastus bar">
</a>

<br>

<a href="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180316.png" target="_blank">
    <img src="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180316.png" width="48%" alt="Dmenu" title="dmenu">
</a>
<a href="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180410.png" target="_blank">
    <img src="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180410.png" width="48%" alt="Terminal" title="Lxterminal, atuin & neofetch">
</a>

<a href="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180916.png" target="_blank">
    <img src="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180916.png" width="48%" alt="File-maneger" title="Superfile">
</a>
<a href="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180949.png" target="_blank">
    <img src="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T180949.png" width="48%" alt="Vim" title="SuperFile & Vim">
</a>

<br>

<a href="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T181110.png" target="_blank">
    <img src="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T181110.png" width="48%" alt="Browser" title="FireFox-esr">
</a>
<a href="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T182207.png" target="_blank">
    <img src="https://github.com/6aru/i3-EllenJoe/blob/main/assets/Shots/Screenshot-20251026T182207.png" width="48%" alt="Power Menu" title="Reboot or Poweroff">
</a>

</div>

---

## Install

```bash
git clone https://github.com/6aru/i3-EllenJoe.git
cp -r i3-EllenJoe/i3 i3-EllenJoe/polybar ~/.config/
cp i3-EllenJoe/picom.conf i3-EllenJoe/starship.toml i3-EllenJoe/lxterminal.conf ~/.config/
cp -r i3-EllenJoe/ranger i3-EllenJoe/neofetch ~/.config/
cp i3-EllenJoe/.bashrc i3-EllenJoe/.vimrc ~/
cp i3-EllenJoe/Wallpaper.jpg ~/Pictures/
chmod +x ~/.config/polybar/launch.sh ~/.config/ranger/scope.sh
```

See the **[wiki](../../wiki/Installation)** for dependencies, **[overview](../../wiki/Overview)** for the full keybind list — copying the files alone isn't enough, a few tools in here aren't widely pre-installed.

## What's in it

i3 · polybar · picom · ranger (Dracula colorscheme) · starship · neofetch · lxterminal · ble.sh · atuin · eza
