# Font awesome rofi
bindsym $mod+t exec /home/sam/rofi-fontawesome/fontawesome-menu/fontawesome-menu -f /home/sam/rofi-fontawesome/fontawesome-menu/fa5-icon-list.txt -o '-i -columns 4'


# Focus on click only (to use onscreen keyboard)
focus_follows_mouse no

Requires:
- Panther launcher (dl the pkg and install with pacman -U)
- Onboard
- Font awesome (sudo pacman -S ttf-fontawesome ... or something like that, can tab complete)
- Use rofi-fontawesome for dev
