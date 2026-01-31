
## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/falah-bit/dotfiles.git
    cd dotfiles
    ```

2. Install the required dependencies:
    ```bash
    sudo pacman -S hyprland kitty wofi waybar mako zsh ttf-jetbrains-mono ttf-jetbrains-mono-nerd swww wl-clipboard
    yay -S python-pywal16 wlogout brighnessctl
    ```

3. Copy the configuration files to their respective locations:
    ```bash
    cp -r .config/* ~/.config/
    ```


4. Update the Waybar and Wofi configuration:
    If your Waybar and Wofi configuration references a CSS file like:
    ```
    @import "/home/vally/.cache/wal/colors-waybar.css";
    ``` 
    make sure to replace "vally" with your actual username.

5. Restart your session and enjoy your new setup!

