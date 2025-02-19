For hyrpland since there aren't much to port just at this line 
      col.active_border = rgb(ff0e82)
      col.inactive_border = rgb(900048)
under general {} in the hyprland.conf file

And for wlogout add this as a bind to launch it 
  bind = $mainMod, ESCAPE, exec, wlogout --protocol layer-shell -b 4
also goes wherever you like on hyprland.conf
