* Showcase Videos
  * Desktop:
  * Laptop:
* These are my extremely simple dotfiles if forking go to the final line

* Any ways please please please read the README for whatever version of the dotfiles you are downloading so you do not end up with missing packages because that will not be good at all
So there will for now be 2 dotfile configs the Laptop and the one you most likely say the Desktop one for my well Desktop of coarse both will be put up

* Setup (note look at the commands and change things you don't want or have installed if you do change stuff in the command PLEASE look at your dotfiles from me after)
  * Desktop
    * Assuming your running Arch or derivatives that use systemd run these commands
        * sudo pacman -S swappy slurp waybar fastfetch fish mako uwsm cava kitty hyprland hyprlauncher hyprlock hyprpolkitagent figlet grim cmatrix ttf-3270 dolphin firefox blueman bluez pipewire pipewire-pulse pavucontrol
        * yay -S wlogout hyprqt6engine mpvpaper fetch-git pixora-icons-git or paru -S wlogout hyprqt6engine mpvpaper fetch-git pixora-icons-git 
        * systemctl enable --now --user pipewire pipewire-pulse
        * sudo systemctl enable --now bluetooth
        * Download Desktop Dotfiles and put in Your User folder
        * Add any themes possibly (You need to add Cursor and Color Themes for hyprqt6engine)
    * Laptop
      * Assuming your running Arch or derivatives that use systemd run these commands
        * sudo pacman -S swappy slurp waybar fastfetch fish mako uwsm cava kitty hyprland hyprlauncher hyprlock hyprpolkitagent figlet grim cmatrix ttf-3270 dolphin firefox blueman bluez pipewire pipewire-pulse pavucontrol power-profiles-daemon
        * yay -S wlogout hyprqt6engine mpvpaper fetch-git pixora-icons-git or paru -S wlogout hyprqt6engine mpvpaper fetch-git pixora-icons-git 
        * systemctl enable --now --user pipewire pipewire-pulse
        * sudo systemctl enable --now bluetooth
        * Download Laptop Dotfiles and put in Your User folder
        * Add any themes possibly (You need to add Cursor and Color Themes for hyprqt6engine)
* Cool Screenshot Time
  * Universal

    * Notifications
    ![](Notificaton.png)

  * Desktop
      * Blank Desktop
      ![](Desktop-With-Nothing.png)

      * Desktop with all terminal stuff that is custom (except btop since menu config in tui I think)
      ![](All custom terminal scripts with custom dotfiles (except btop since menu config in tui I think).png)

* Credits
  * All credits to dotfiles files go to me since well I made them
  * All (Credits to everything used across all configs)
    * Mako: https://github.com/emersion/mako
    * Waybar: https://github.com/alexays/waybar
    * Emote: https://github.com/tom-james-watson/Emote
    * Cursor: https://store.kde.org/p/2355061/
    * Icons: https://github.com/tsora1603/pixora-icons
    * Color Scheme: https://store.kde.org/p/1903937
    * GTK Theme: https://store.kde.org/p/1357889
    * Hypr: https://hypr.land/
    * Pavucontrol: https://freedesktop.org/software/pulseaudio/pavucontrol/?__goaway_challenge=meta-refresh&__goaway_id=128ae0061403e266fec343f88ab37161&__goaway_referer=https%3A%2F%2Farchlinux.org%2F
    * Fastfetch: https://github.com/fastfetch-cli/fastfetch
    * Font: https://www.nerdfonts.com/
    * Shell: https://fishshell.com/
    * Screenshots: (Slurp: https://github.com/emersion/slurp) (Swappy: https://github.com/jtheoof/swappy) (Grim: https://github.com/emersion/grim)
    * UWSM: https://github.com/Vladimir-csp/uwsm
    * Terminal: https://github.com/kovidgoyal/kitty
    * Figlet: https://www.figlet.org/
    * Cmatrix: https://github.com/abishekvashok/cmatrix
    * Dolphin: https://kde.org/
    *Firefox: https://www.firefox.com/
  * Desktop
    * Wallpaper Renderer: https://github.com/GhostNaN/mpvpaper
    * Wallpaper: https://moewalls.com/anime/miku-error-vocaloid-live-wallpaper/ or https://steamcommunity.com/sharedfiles/filedetails/?id=3729448969
  * Laptop
    * power-profiles-daemon: https://gitlab.freedesktop.org/upower/power-profiles-daemon
    * Wallpaper Renderer: https://hypr.land/
    * Wallpaper: I had some trouble finding it again on the web if anyone is able to source the wallpaper please tell me so I can add it to credits

* If you do not give me any credit though and your dotfiles are a fork of mine and only have minor visual change like changing the roundness or color of something I will take action and take it down just because its under a Public license does not  mean I can not take action
