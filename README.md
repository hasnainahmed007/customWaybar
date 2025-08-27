//install waybar
sudo dnf install waybar
waybar --version


mkdir -p ~/.config/waybar
~/.config/waybar/myconfig.jsonc
~/.config/waybar/mystyle.css

//You can run Waybar manually using
pkill waybar
waybar -c ~/.config/waybar/myconfig.jsonc -s ~/.config/waybar/mystyle.css &


