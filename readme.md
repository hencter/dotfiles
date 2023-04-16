# Dotfiles

## Init

```bash
chezmoi init --apply https://github.com/hencter/dotfiles.git
```

```bash
chezmoi init --apply hencter
```

## 依赖

```
# gnome
sudo pacman -S gnome
# hyprland 
sudo pacman -S hyprland community/hyprland community/xdg-desktop-portal-hyprland community/kitty
# 基本软件
sudo pacman -S thunar gvfs extra/xfce4-settings qt5ct
# fcitx5
sudo pacman -S fcitx5-im community/fcitx5-chinese-addons community/fcitx5-pinyin-zhwiki
```

## Hyprland

In Arch Linux
