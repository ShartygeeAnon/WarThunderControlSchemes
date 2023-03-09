# WarThunderControlSchemes

Several control schemes that make more efficient use of your keyboard and mouse with extensive use of convenient modifier keys, mainly Caps Lock and Tab. The non-crucial scoreboard has been manually moved from the convenient Tab to F1, a key which is normally used for the help menu (still accessible through the Esc menu) and cannot be changed or unbound from within the game, requiring manual editing of an exported controls file.

*Note*: all of the following control schemes assume you're using the weapon selection system and not the legacy weapon controls. Make sure to enable the Automatic activation of aircraft weapon selection at mission start in Air Battle Settings.
#
The control schemes are:

1) **Controls.blk** - default control scheme intended for most aircraft in the game
2) **Controls_VTOL_and_VWS.blk** - same as Controls.blk, but with flap and wing sweep/VTOL buttons swapped, intended for variable wing sweep and VTOL aircraft
3) **Controls_FritzX.blk** - Same as Controls.blk, but with modified guided weapon controls, intended for aircraft carrying the PC 1400 X glide bomb and possibly other similarly controlled guided weapons in the future, not recommended for use with MCLOS missiles such as AA.20s or AGM-12s
4) **Controls_Sim.blk** - same as Controls.blk, but with Full-real controls enabled in all modes, mouse wheel controlling the vertical position of the camera instead of zoom (still available with Tab + mouse wheel) for better control over cockpit visibility, and Y-axes inverted such that moving the mouse up pitches the aircraft up and vice versa with normal, non-inverted free look and gunner camera

*Note*: if you suddenly can no longer change the vertical position of the camera in the cockpit, that's probably due to Opentrack somehow interfering with the game. To fix the issue, rename the Opentrack folder in any way at all. The issue persists between game launches and even Windows restarts until you rename the Opentrack folder and will repeat every time you open opentrack.exe. I have little idea how or why this happens and even less of an idea why it's so persistent.

5) **Controls_Sim_and_VWS.blk** - same as Controls_Sim.blk, but with flap and wing sweep/VTOL buttons swapped