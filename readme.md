# Dotfiles

## Init

```bash
chezmoi init --apply https://github.com/hencter/dotfiles.git
chezmoi init --apply hencter

sudo pacman -S lazy
```

## Dependent

```bash
# First install a browse e.g. firefox-developer-edition
sudo pacman -S firefox-developer-edition

# Hyprland「也许可以叫做：梦幻乐园」
sudo pacman -S hyprland community/hyprland community/xdg-desktop-portal-hyprland community/kitty

# 显示管理器，这边建议 gdm 目前，他是 wayland 的支持比较完整的，
# 并且是默认源里面就存在的，不像 SDDM 需要 AUR 里面下载 git 版本
sudo pacman -S gdm # setting

# 系统状态查看器
sudo pacman -S bottom

# 应用启动器
sudo pacman -S wofi # hyprland default

# 通知守护进程
sudo pacman -S mako

# man
sudo pacman -S man

# QT
sudo pacman -S qt5-wayland qt6-wayland qt5ct qt6ct

# 基本软件

```bash
sudo pacman -S thunar gvfs \
thunar-media-tags-plugin thunar-volman tumbler libgsf
```

# 解压缩

```bash
sudo pacman -S file-roller
```

# 输入法：fcitx5

```bash
sudo pacman -S fcitx5-im community/fcitx5-chinese-addons community/fcitx5-pinyin-zhwiki

```

# Config

```environment
# /etc/environment
GTK_IM_MODULE=fcitx
QT_IM_MODULE=fcitx
XMODIFIERS=@im=fcitx
SDL_IM_MODULE=fcitx
GLFW_IM_MODULE=ibus
```

```bash
# 截图
sudo pacman -S grim slurp wl-clipboard # 剪切板是为了方便图片，也是为了方便 neovim
# 录屏，要么就是下面的这个标，要么就是 OBS-Studio
sudo pacman -S obs-studio
# 壁纸
# paru -S swww
```

