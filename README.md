# Dotfiles

![preview](/PREVIEW.png)

## Requirements

This dotfiles was successfully tested using **Arch Linux** with **Openbox** as Window Manager.
But still you can use it to other window manager and Linux Distributions.

Here are the requirements for you to properly use this dotfiles


| Name | Required |Use / Description |
|------|----------|-------------|
| Openbox | No | Window Manager | 
| Nato Sans | Yes | Font |
| Polybar | Yes | Status Bar |
| Rofi | Yes | Use for Alt+Tab Selection and Application luncher |
| dunst | Yes | Use for notification |
| vim | No | Editor |
| urxvt / rxvt-unicode | No | Terminal |
| neofetch | No | use to display info in console |
| slop | Yes | Use to select a screen region, use for screenshot and screen recording |
| ffmpeg | Yes | Use to record screen |
| hsretroot | Yes | Use for wallpaper |
| xclip | No | Use for copying from console commands |
| xsel | No | Manipulate X Selection |
| xdotool | Yes | Use for taskbar for polybar |
| xsettingsd | Yes | use for setting daemon |
| xbacklight | Yes | use for backlight |

For window manager, yes openbox is not required. You can use this dotfiles using other window manager
just make sure that you are using window manager that uses X11.

Right now most of the window manager exists is using X11 instead of wayland, like openbox, and i3. 
https://en.wikipedia.org/wiki/Comparison_of_X_window_managers heres a list of different x window managers.

## Installation

For you to install this dotfile, you only need 4 steps

Just reminder before doing this installations make sure that you will backup your current files 
of your profile folder **~/**, specially those files that has same names in files of this repo.
Or to be safe, you can create a new user.

**Step 1:** 

Clone the repository

```bash
$ cd ~/
$ git clone https://github.com/cydrickn/dotfiles.git
```

**Step2**

Copy the files to ~/

```bash
$ cp -rT ~/dotfiles/ ~/
```

**Step3**

Logout

**Step4**

Login
