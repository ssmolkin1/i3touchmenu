# Font awesome rofi
bindsym $mod+t exec /home/sam/rofi-fontawesome/fontawesome-menu/fontawesome-menu -f /home/sam/rofi-fontawesome/fontawesome-menu/fa5-icon-list.txt -o '-i -columns 4'


# Focus on click only (to use onscreen keyboard)
focus_follows_mouse no
# Floating xlunch
for_window [class="xlunch"] floating enable resize shrink width 300 px or 300 ppt, resize shrink height 300 px or 300 ppt, move position center 

Requires:
- xlunch (aur)
- Onboard
- Font awesome (sudo pacman -S ttf-fontawesome ... or something like that, can tab complete)
- Use rofi-fontawesome (git) for dev
