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
# gnome，安装 gnome 首先是为了保障你基本的桌面环境，hypr 不一定稳定，但是 gnome 的稳定性应该略高于 hypr
sudo pacman -S gnome
# hyprland 
sudo pacman -S hyprland community/hyprland community/xdg-desktop-portal-hyprland community/kitty
# 基本软件
sudo pacman -S thunar gvfs extra/xfce4-settings qt5ct
# fcitx5
sudo pacman -S fcitx5-im community/fcitx5-chinese-addons community/fcitx5-pinyin-zhwiki
# 文件管理 和 归档管理（压缩）
sudo pamcan -S thunar file-roller

```

## Hyprland

In Arch Linux
