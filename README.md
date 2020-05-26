# swapworkspace
Simple script to allow workspace swapping on outputs for i3/sway. This mimics xmonad/spectrwm workspace behavior.

# To use:
Simply drop the script somewhere in your $PATH, make it executable, and bind it in your i3/sway config like so:
    bindsym $mod+1 exec swapworkspace 1
    bindsym $mod+2 exec swapworkspace 2
    bindsym $mod+3 exec swapworkspace 3
    bindsym $mod+4 exec swapworkspace 4
    bindsym $mod+5 exec swapworkspace 5
    bindsym $mod+6 exec swapworkspace 6
    bindsym $mod+7 exec swapworkspace 7
    bindsym $mod+8 exec swapworkspace 8
    bindsym $mod+9 exec swapworkspace 9
    bindsym $mod+0 exec swapworkspace 10
