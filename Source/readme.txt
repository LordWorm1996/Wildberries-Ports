Hello again Gabo :D
Here you'll find all the source files for the ports and I'll explain some stuff related to them.

Hyprland 
For hyprland the only thing I could do was to change the border colors as you can see on the hyprland.png
you can see the window borders have two different colors based on active and inactive window
just add 
    col.active_border = rgb(ff0e82)
    col.inactive_border = rgb(900048)
under general {}


kityy
For kitty all the colors where ported and you can see them with fastfetch, I also added transparency

swaync
For swaync you can see that the aux colors have been used for importance of the notification

waybar
For waybar also all the colors are ported apart from some aux ones that I couldn't find a reason to have them since
they are primarly used for text highlighting, however battery levels and status use them

wofi
For wofi most of the colors are again ported and I also added transparency