

# BSPWM Setup and Theme for EndeavourOS
**Based on BSPWM EndeavorOS Community Edition (https://github.com/EndeavourOS-Community-Editions/bspwm)**

## Iso installation
    At the initial setup, close Calamares Welcome screen, launch a terminal and run this command:

    sudo curl https://raw.githubusercontent.com/AlessandroPerazzetta/endeavouros-bspwm/main/netinstall.yaml --output /etc/calamares/modules/netinstall.yaml

    after the netinstall.yaml is downloaded, restart Calamares with:

    eos-welcome

    Start installer, and complete installation

## To Install manually

    git clone https://github.com/AlessandroPerazzetta/endeavouros-bspwm.git

    cd endeavouros-bspwm

    bash bspwm-install.sh
   
## Contained In The Script
    cp -R .config/* ~/.config/
        
    cp .gtkrc-2.0 ~/.gtkrc-2.0
    
    chmod -R +x ~/.config/bspwm/scripts
        
    yay -Syu --needed --noconfirm - < packages-repository.txt
    
## Get involved at our forum:
https://forum.endeavouros.com/c/desktop-environments/bspwm/75

## Tutorial for bspwm-wm settings:
- Background handled by nitrogen
- Gtk3 theme handled by lxappearance-gtk3
- Filebrowser = Thunar
- Default Terminal-Emulator = xfce4-terminal
- Text-Editor = xed
- Application Launcher = Rofi


![bspwm](https://raw.githubusercontent.com/AlessandroPerazzetta/endeavouros-bspwm/main/bspwm.png)