basically sum config files to set up your sway linux computer!!

# MANDATORY PACKAGES:
- sway (duh)
- waybar
- pamixer
- neofetch
- wofi

# INSTALLATION:
cant find a proper way to install the config files, soo just copy and paste them to ~/.config, by the way the neofetch config file has its ascii set to linuxmint_small since it was made in linux mint, so change it if you are on another distro lol (PLEASE change the wallpaper thing on the sway config file to the directory where your wallpaper is)

# MAKE THE DIRECTORIES:
1. mkdir -p .config/sway && cp /etc/sway/config .config/sway/config
2. mkdir .config/waybar && cp /etc/xdg/waybar/* .config/waybar/
3. mkdir .config/wofi && cd .config/wofi && touch config style.css

# KEYBINDS:
- mod + 1-9 = workspaces
- mod + left, right/up, down = focus on the respective window
- mod + alt + up/down = volume
- mod + d = wofi
- mod + enter = terminal
- mod + q = close focused window

# NOTES:
feel free to change anything from ts, although i made it to archive my config files
