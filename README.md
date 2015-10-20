//Enable cheats for demo viewing to be able to disable certain things such as mat_postprocess
sv_cheats 1
cvar_unhide_all (Opening up all command opportunities or atleast more that are available)

//Set video mode (Width, Height, Windowed = 1, Fullscreen = 0)
mat_setvideomode 1920 1080 1

host_sync_fps 1
host_thread_mode 0
mat_queue_mode 0

//Viewmodel settings, i just put these in to max things out - the max is 68, 2.5, 2, -2
viewmodel_fov 90
viewmodel_offset_x 3
viewmodel_offset_y 2
viewmodel_offset_z -2
cl_bob_lower_amt 0

weapon_recoil_model 0

//Remove grey fog/blur around the scope and more things
mat_postprocess_enable 0

cvar_unhide_all 1
sv_disablefreezecam 1
sv_nomvp 1
sv_nostats 1
sv_nonemesis 1
sv_skyname vertigoblue_hdr
fog_enable 0
fog_override 1

mat_dxlevel 90

mat_hdr_enabled	 "1"

//Set the framerate you want to record at
host_framerate 0

sv_showimpacts 0
net_graph 0 (disables net_graph shown in the video)
cl_showfps 0 (disables fps shown in the video)
hud_saytext_time 0
hud_scaling 0.75 (the higher the scaling, the bigger is the HUD shown in the video ultimately)
hud_showtargetid 0
hud_takesshots 0
hud_drawhistory_time 0
hideradar 1

//Crosshairsettings:
cl_crosshairthickness "0"
cl_crosshairstyle 4
cl_crosshairsize 4
cl_crosshaircolor 5; cl_crosshaircolor_r 255;cl_crosshaircolor_g 255;cl_crosshaircolor_b 255
cl_crosshairgap 0.5
cl_crosshairdot 0

//Remove the HUD (1=Removed, 0=Visible) - helpful if you bind 0 and 1 to keys and then switch between them while recording/demoviewing
cl_draw_only_deathnotices 0

//Position of the weapon (cl_righthand 0 puts it lefthanded, cl_righthand 1 puts it righthanded)
cl_righthand 1

//Kill assists (0 = disables Assists in the deathnotice and makes it a lot cleaner looking for videos, 1 = enables Assists and shows them in the deathnotice)
mp_display_kill_assists 0

//For GOTV startmovie recording use 0 = Sound brakes, fixes lagg though (= You need to record sound separately with Fraps/Dxtory); for POV demos put it to 1 again, for some reason startmovie works just fine with POV/Ineye demos
host_timescale 0


//Misc
host_sync_fps 1
host_thread_mode 0
mat_queue_mode 0
cl_interp_ratio 2
bind "space" "demo_togglepause"

//Skin Removal in Demos
cl_custom_material_override 0 (0= Disabled 1=Enabled)

//HLAE CMD

mirv_cvar_unhide_all
mirv_snd_timescale 1
bind pgup "mirv_campath add"
bind pgdn "mirv_campath clear"
bind home "mirv_campath save campath"
bind end "mirv_campath load campath"
bind ins "mirv_campath enable 1"
bind del "mirv_campath enable 0"
mirv_gameoverlay enable 0


