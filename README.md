# assuming your hud DOESNT have a valve.rc file

1. place these files in your hud directory
2. put `#base weapon.res` at the top of your `scripts/hudlayout.res`
3. <b>enable a hud crosshair</b>

to change icon size, go into `cfg/weapon.cfg` and adjust `cl_crosshair_scale` accordingly<br>
to change position, adjust the `xpos` and `ypos` inside `scripts/weapon.res`

# assuming your hud DOES have a valve.rc file

1. place these files in your hud directory, <b>DO NOT REPLACE ANY FILES</b>
2. put `exec weapon.cfg` at the very end of your `cfg/valve.rc`
3. put `#base weapon.res` at the top of your `scripts/hudlayout.res`
4. enable a hud crosshair

to change icon size, go into `cfg/weapon.cfg` and adjust `cl_crosshair_scale` accordingly<br>
to change position, adjust the `xpos` and `ypos` inside `scripts/weapon.res`

# credits
minhud - most files