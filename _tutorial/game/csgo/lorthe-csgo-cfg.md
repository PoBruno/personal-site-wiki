# [Lorthe CFG Counter-Strike GO](https://github.com/pobruno/lorthe-cfg/blob/main/csgo/lt.cfg)

###### Crosshair
```
cl_crosshair_drawoutline "1"
cl_crosshair_dynamic_maxdist_splitratio "0.0"
cl_crosshair_dynamic_splitalpha_innermod "1"
cl_crosshair_dynamic_splitalpha_outermod "0.300000"
cl_crosshair_dynamic_splitdist "5"
cl_crosshair_friendly_warning "0"
cl_crosshair_outlinethickness "0.500000"
cl_crosshair_sniper_show_normal_inaccuracy "0"
cl_crosshair_sniper_width "1"
cl_crosshair_t "0"
cl_crosshairalpha "185.000000"
cl_crosshaircolor "5"
cl_crosshaircolor_b "0"
cl_crosshaircolor_g "255"
cl_crosshaircolor_r "255"
cl_crosshairdot "0"
cl_crosshairgap "-2.500000"
cl_crosshairgap_useweaponvalue "0"
cl_crosshairsize "1.000000"
cl_crosshairstyle "4"
cl_crosshairthickness "0.500000"
cl_crosshairusealpha "1"
cl_fixedcrosshairgap "-11.000000"
cl_viewmodel_shift_left_amt "0.500000"
cl_viewmodel_shift_right_amt "0.250000"
```

###### Binds Lorthe
```
bind "W" "+forward"
bind "A" "+moveleft"
bind "S" "+back"
bind "D" "+moveright"
bind "F" "use weapon_flashbang"
bind "4" "use weapon_hegrenade"
bind "Z" "use weapon_incgrenade; use weapon_molotov"
bind "X" "use weapon_decoy"
bind "C" "use weapon_smokegrenade"
bind "5" "slot5"
bind "6" "slot6"
bind "1" "slot1; +lookatweapon"
bind "2" "slot2; +lookatweapon"
bind "3" "slot3; +lookatweapon"
bind "MOUSE1" "+attack"
bind "MOUSE2" "+attack2"
bind "MOUSE3" "player_ping"
bind "MOUSE4" "drop"
bind "MOUSE5" "toggle voice_enable 0 1"
bind "MWHEELUP" "r_cleardecals"
bind "MWHEELDOWN" "+jump"
bind "SHIFT" "+speed"
bind "F1" "use weapon_c4; drop;"
bind "G" "drop"
bind "ALT" "drop"
bind "r" "+reload"
bind "q" "lastinv"
bind "ctrl" "+duck"
bind "TAB" "+showscores"
bind "CAPSLOCK" "+voicerecord"
bind "b" "buymenu"
bind "e" "+use"
bind "m" "teammenu"
bind "t" "+spray_menu"
bind "," "buyammo1"
bind "." "buyammo2"
bind "PAUSE" "pause"
bind "DEL" "mute"
```

###### View Model
```
viewmodel_fov "66.500000"
viewmodel_offset_x "2.500000"
viewmodel_offset_y "1.000000"
viewmodel_offset_z "-2.000000"
viewmodel_presetpos "0"
viewmodel_recoil "0"
cl_bob_lower_amt "5.000000"
cl_bobamt_lat "0.100000"
cl_bobamt_vert "0.100000"
cl_bobcycle "0.980000"
cl_hud_background_alpha "0.150000"
cl_hud_bomb_under_radar "1"
cl_hud_color "4"
cl_hud_healthammo_style "0"
cl_hud_playercount_pos "0"
cl_hud_playercount_showcount "1"
cl_hud_radar_scale "1.100000"
hud_scaling "0.900000"
hud_showtargetid "1"
cl_righthand "1"
cl_color "4"
```

###### Radar Configs
```
cl_radar_always_centered "0"
cl_radar_icon_scale_min "0.6"
cl_radar_rotate "1"
cl_radar_scale "0.400000"
cl_radar_square_with_scoreboard "1"
cl_fixedcrosshairgap "-11.000000"
cl_viewmodel_shift_left_amt "0.500000"
cl_viewmodel_shift_right_amt "0.250000"
cl_teamid_overhead_mode "2"
cl_teammate_colors_show "1"
cl_scoreboard_survivors_always_on "0"
cl_sniper_delay_unscope "0"
ui_steam_overlay_notification_position "topright"
snd_tensecondwarning_volume "0.20"
voice_scale "0.4"
cl_bob_lower_amt "5.000000"
cl_bobamt_lat "0"
cl_bobamt_vert "0"
cl_bobcycle "0.980000"
cl_hud_background_alpha "0.150000"
cl_hud_bomb_under_radar "1"
cl_hud_color "7"
cl_hud_healthammo_style "1"
cl_hud_playercount_pos "0"
cl_hud_playercount_showcount "1"
cl_hud_radar_scale "1.100000"
hud_scaling "0.900000"
hud_showtargetid "1"
cl_righthand "1"
cl_color "4"
cl_radar_always_centered "0"
cl_radar_icon_scale_min "0.6"
cl_radar_rotate "1"
cl_radar_scale "0.400000"
cl_radar_square_with_scoreboard "1"
```

###### Basics Configs Lorthe
```
cl_autohelp "0"
cl_autowepswitch "0"
sv_forcepreload "1"
fps_max "300"
sensitivity "0.675"
zoom_sensitivity_ratio_mouse "0.5"
mat_setvideomode 1152 864 0
cl_showloadout 1

alias -smoke_throw 		"cl_crosshairsize 2.1;" 
alias +smoke_throw 		"cl_crosshairsize 9999;"
bind "V" +smoke_throw
```

###### Show Damage
```
developer "1"
con_filter_text "Damage Given"
con_filter_text_out Player:
con_filter_enable "2"
```

###### Bind Jumpthrow on Space
```
alias "+jumpthrow" "+jump;-attack"
alias "-jumpthrow" "-jump"
bind "SPACE" "+jumpthrow"
bind "SPACE" "+jumpthrow"
```

###### Others
```
cl_use_opens_buy_menu "0"
r_player_visibility_mode "1"
triple_monitor_mode "0"
mat_monitorgamma "0"
mat_setvideomode 1152 864 0
mat_queue_mode "-1"
r_dynamic "0"
r_drawparticles "0"
```